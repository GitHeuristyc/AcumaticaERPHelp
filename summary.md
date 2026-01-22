---
repo: AcumaticaERPHelp
primary_branch: unknown
type: documentation
acumatica_version: 2023R1
modules: [ AP, AR, CA, CM, CR, CS, CT, DR, EP, FA, GL, IN, PM, PO, PR, SO, TX, XX ]
screens: [ AB123456, AM100000, AM101000, AM201100, AM300000, AM301000, AP101000, AP201000, AP301000, AP501000, AR101000, AR201000, AR301000, AR501000, CA101000, CA202000, CA301000, CM101000, CM201000, CR101000, CR202000, CR301000, CS100000, CS201000, CT201000, CT301000, DR101000, DR201500, EP101000, EP201000, EP301000, FA101000, FA201000, FA301000, GL101000, GL201000, GL301000, IN101000, IN201000, IN301000, PM101000, PM201000, PM301000, PO101000, PO201000, PO301000, PR101000, PR201000, PR301000, SO101000, SO201000, SO301000, TX102000, TX205000 ]
graph_extensions: [ ARPaymentEntry_Extension, ARReleaseProcess_Extension, AlterCountModeConfirmStateLogic, BaseBLCExt, BaseBLCExtOnExt, BaseBLCExtension, BaseBLCExtensionOnExtension, BaseBLCMultiExtensionOnExtension, BaseBLC_Extension, CaseWorkflow_Extension, RSSVWorkOrderEntry_Workflow, RSSVWorkOrderEntry_Workflow_Extension, SOInvoiceEntry_Extension, SOInvoiceRepairOrder_Workflow, SomeCustomization ]
dac_extensions: [ BaseDACAdvMultiExtensionOnExtension, BaseDACExtension, BaseDACExtensionOnExtension, BaseDACMultiExtensionOnExtension, FeaturesSetExt, MyDacExt, RSSVWorkOrder_Extension ]
db_changes: true
cloud: [ aws ]
aws_services: [ iam, lambda, rds, s3 ]
integrations: [ Bank of America, OAuth, OpenID, RabbitMQ, SFTP, Salesforce, Stripe ]
ci_cd: [ ]
infra: [ ]
keywords: [ Acumatica, ERP, Documentation, Framework, Customization, BQL, DAC, Graph, Workflow, Integration, REST API, Commerce, WMS, Mobile ]
---

# Summary

## What it does
- Comprehensive Acumatica ERP documentation repository in Markdown format
- Covers Developer, End User, Administrator, and Implementation guides
- Documents customization patterns, BQL queries, workflow APIs, and integration development
- Provides code examples for Graph/DAC extensions, event handlers, and REST clients

## Why it exists
- Makes official Acumatica documentation freely accessible in AI-indexable format
- Enables offline access and version control for documentation
- Optimized for AI tools (Cursor, Copilot) to understand Acumatica development patterns
- Community resource for Acumatica developers and implementers

## Impacted areas (Acumatica)
- Modules: AP, AR, CA, CM, CR, CS, CT, DR, EP, FA, GL, IN, PM, PO, PR, SO, TX (18 modules)
- Screens: 500+ screens documented across all modules (AM, AP, AR, CA, CM, CR, CS, DR, EP, FA, GL, IN, PM, PO, PR, SM, SO, TX series)
- Entities (DAC/Graph): Extensive documentation of DAC extensions, Graph extensions, and multi-level extension patterns

## Key capabilities
- Framework development patterns (BQL, DAC, Graph, PXCache)
- Multi-level extension patterns (Extension-on-Extension for both Graphs and DACs)
- Workflow API configuration and state machine patterns
- Commerce connector development (BigCommerce, WooCommerce patterns)
- WMS barcode scanning engine customization
- Mobile framework development
- Test SDK and unit testing frameworks

## Interfaces / Integrations
- External APIs: REST/SOAP web services, Commerce connectors (BigCommerce, WooCommerce), Salesforce, HubSpot
- Protocols/Auth: OAuth, OpenID Connect, token-based authentication
- Queues/Events: RabbitMQ (documented), webhook handlers, workflow event handlers

## Deployment / Packaging
- How to deploy: Clone repository, browse Markdown files with any viewer/editor
- DB changes: Yes (documented examples of schema modifications and DAC definitions)

## Validation / Smoke test
- Not applicable - documentation repository only
- No executable code or build artifacts

## Notable implementation snippets

### 1. Multi-Level Graph Extension (Extension-on-Extension)
Demonstrates layered BLC customization with access to base graph and all extension levels.

File: `EndUserGuides/AcumaticaERP_CustomizationGuide/AcumaticaERP_CustomizationGuide.md`

```csharp
public class BaseBLCMultiExtensionOnExtension :
    PXGraphExtension<BaseBLCExtensionOnExtension, BaseBLC>
{
    public void SomeMethod()
    {
        BaseBLC BLC = Base;
        BaseBLCExtensionOnExtension prevExt = Base1;
    }
}
```

### 2. Multi-Level DAC Extension with Full Chain Access
Advanced DAC extension pattern with access to all extension levels in the chain.

File: `EndUserGuides/AcumaticaERP_CustomizationGuide/AcumaticaERP_CustomizationGuide.md`

```csharp
public sealed class BaseDACAdvMultiExtensionOnExtension : 
    PXCacheExtension<BaseDACExtensionOnExtension, BaseDACExtension, BaseDAC>
{
    public static void SomeMethod(BaseDACAdvMultiExtensionOnExtension ext4)
    {
        BaseDAC dac = ext4.Base;
        BaseDACExtension dacExt = ext4.Base1;
        BaseDACExtensionOnExtension dacExtOnExt = ext4.Base2;
    }
}
```

### 3. PXOverride Pattern for Method Interception
Delegate-based override pattern for intercepting and extending base graph methods.

File: `EndUserGuides/AcumaticaERP_CustomizationGuide/AcumaticaERP_CustomizationGuide.md`

```csharp
public class BaseBLC_Extension : PXGraphExtension<BaseBLC>
{
    /// <seealso cref="BaseBLC.PrePersist()"/>
    [PXOverride]
    public bool PrePersist(Func<bool> base_PrePersist)
    {
        if (!base_PrePersist())
            return false;
        // Custom logic after base execution
    }
}
```

### 4. Workflow API State Transitions
Workflow state machine configuration pattern with transitions and actions.

File: `DeveloperGuides/AcumaticaERP_WorkflowAPI/AcumaticaERP_WorkflowAPI.md`

```csharp
context.AddScreenConfigurationFor(screen => screen
    .StateIdentifierIs<RSSVWorkOrder.status>()
    .AddDefaultFlow(flow => flow
        .WithStates(states => { /* state definitions */ })
        .WithTransitions(transitions =>
        {
            transitions.Add(transition => transition
                .From(States.New)
                .To(States.Assigned)
                .IsTriggeredOn(actionAssign));
        })
    )
);
```

### 5. REST Client for Commerce Integration
Pattern for creating REST clients with configuration for external commerce integrations.

File: `DeveloperGuides/AcumaticaERP_PluginDevelopmentGuide/AcumaticaERP_PluginDevelopmentGuide.md`

```csharp
public static RestClient GetRestClient(String url, String clientID, String token)
{
    RestOptions options = new RestOptions
    {
        BaseUri = url,
        XAuthClient = clientID,
        XAuthTocken = token
    };
    JsonSerializerSettings serializer = new JsonSerializerSettings
    {
        MissingMemberHandling = MissingMemberHandling.Ignore,
        NullValueHandling = NullValueHandling.Ignore,
        DefaultValueHandling = DefaultValueHandling.Include,
        DateFormatHandling = DateFormatHandling.IsoDateFormat,
        DateTimeZoneHandling = DateTimeZoneHandling.Unspecified
    };
    RestClient client = new RestClient();
    return client;
}
```

### 6. WMS Scan Extension Pattern
Shows how scan components delegate logic to customizable ScanExtension classes.

File: `DeveloperGuides/AcumaticaERP_WMSEngine/AcumaticaERP_WMSEngine.md`

```csharp
public abstract class WooRestClientBase :
    RetryCapableRESTClientBase<WooRestClientBase.HttpCallContext>
{
    protected WooRestClientBase(int attempts) : base(attempts)
    {
    }
    protected override ValueTask<bool> IsFailure(
        Outcome<HttpCallContext> result,
        int attemptNumber, 
        int attempts) =>
        new((result.Exception is not null));
}
```

## Evidence (top files reviewed)
- `EndUserGuides/AcumaticaERP_CustomizationGuide/AcumaticaERP_CustomizationGuide.md`
- `DeveloperGuides/AcumaticaERP_WorkflowAPI/AcumaticaERP_WorkflowAPI.md`
- `DeveloperGuides/AcumaticaERP_Integrations/AcumaticaERP_Integrations.md`
- `DeveloperGuides/AcumaticaERP_PluginDevelopmentGuide/AcumaticaERP_PluginDevelopmentGuide.md`
- `DeveloperGuides/AcumaticaERP_IntegrationDevelopmentGuide/AcumaticaERP_IntegrationDevelopmentGuide.md`
- `DeveloperGuides/AcumaticaERP_WMSEngine/AcumaticaERP_WMSEngine.md`
- `EndUserGuides/AcumaticaERP_FrameworkDevelopmentGuide/AcumaticaERP_FrameworkDevelopmentGuide.md`
- `ImplementationGuides/AcumaticaERP_ImplementationGuide/AcumaticaERP_ImplementationGuide.md`
- `README.md`
- `repo.facts.json`
- `repo.signals.json`
