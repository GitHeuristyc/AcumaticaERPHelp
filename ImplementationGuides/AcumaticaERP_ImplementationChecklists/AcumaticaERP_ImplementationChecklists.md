**Consultant Guide**

# **System Implementation 2025 R1**

![](_page_0_Picture_2.jpeg)

## **Contents**

| Copyright7                                                                      |  |  |
|---------------------------------------------------------------------------------|--|--|
| Acumatica ERP Implementation Checklists8                                        |  |  |
| Accounts Payable9                                                               |  |  |
| AP Bills: Implementation Checklist 9                                            |  |  |
| AP Bill Payments: Implementation Checklist10                                    |  |  |
| AP Documents from PDFs: Implementation Checklist 11                             |  |  |
| Bill Prepayments: Implementation Checklist12                                    |  |  |
| Debit and Credit Adjustments: Implementation Checklist13                        |  |  |
| Interbranch Bills Without Balancing: Implementation Checklist14                 |  |  |
| Interbranch Bills with Balancing: Implementation Checklist15                    |  |  |
| Check Reprinting: Implementation Checklist 17                                   |  |  |
| Multiple Bill Payments: Implementation Checklist18                              |  |  |
| Payments for a Shared Vendor: Implementation Checklist 19                       |  |  |
| Partial Payments: Implementation Checklist20                                    |  |  |
| Voiding Payments: Implementation Checklist 21                                   |  |  |
| Payments with a Corporate Card: Implementation Checklist22                      |  |  |
| Accounts Receivable23                                                           |  |  |
| AR Invoices: Implementation Checklist23                                         |  |  |
| AR Invoice Correction: Implementation Checklist 24                              |  |  |
| Auto-Applying Payments: Implementation Checklist25                              |  |  |
| Refunds: Implementation Checklist 26                                            |  |  |
| Interbranch Invoices with Balancing: Implementation Checklist26                 |  |  |
| Interbranch Invoices Without Balancing: Implementation Checklist 28             |  |  |
| Intercompany Sales: Implementation Checklist29                                  |  |  |
| Invoice Payments: Implementation Checklist31                                    |  |  |
| Invoice Prepayments: Implementation Checklist32                                 |  |  |
| Invoice with Combined Subaccounts: Implementation Checklist 32                  |  |  |
| Payments with Write-Offs: Implementation Checklist34                            |  |  |
| Basic Company Configuration36                                                   |  |  |
| Preparing an Instance: Implementation Checklist 36                              |  |  |
| Company Without Branches: Implementation Checklist 36                           |  |  |
| Company with Branches that Do Not Require Balancing: Implementation Checklist39 |  |  |
| Company with Branches that Require Balancing: Implementation Checklist 42       |  |  |
| Budget Management 46                                                            |  |  |

#### Contents | **3**

| Access to Budget Nodes: Implementation Checklist 46                              |  |
|----------------------------------------------------------------------------------|--|
| Budget Based on an Existing Budget: Implementation Checklist47                   |  |
| Budget vs Actual ARM Report: Implementation Checklist 48                         |  |
| Converting a Simple Budget to a Hierarchical Budget: Implementation Checklist 49 |  |
| Hierarchical Budget: Implementation Checklist50                                  |  |
| Modifying a Hierarchical Budget: Implementation Checklist51                      |  |
| Revising a Budget: Implementation Checklist 52                                   |  |
| Simple Budget: Implementation Checklist 53                                       |  |
| Cash Management 55                                                               |  |
| Bank Reconciliation: Implementation Checklist55                                  |  |
| Cash Entries: Implementation Checklist 56                                        |  |
| Funds Transfers: Implementation Checklist57                                      |  |
| Intercompany Funds Transfers: Implementation Checklist 58                        |  |
| Customer Relationship Management60                                               |  |
| Case Assignment to Owners and Workgroups: Implementation Checklist 60            |  |
| Lead Assignment to Owners and Workgroups: Implementation Checklist61             |  |
| Opportunity Assignment to Owners and Workgroups: Implementation Checklist62      |  |
| Configuring CRM Functionality: Implementation Checklist 63                       |  |
| Duplicate Validation: Implementation Checklist 65                                |  |
| Emails and Activities: Implementation Checklist 66                               |  |
| Case Management: Implementation Checklist 67                                     |  |
| Opportunity Management: Implementation Checklist 70                              |  |
| Marketing Lists: Implementation Checklist73                                      |  |
| Marketing Campaigns: Implementation Checklist74                                  |  |
| Mass Emails: Implementation Checklist75                                          |  |
| Lead Qualification by Marketing Teams: Implementation Checklist 76               |  |
| Lead Qualification by Sales Teams: Implementation Checklist 77                   |  |
| Record Validation for Duplicates: Implementation Checklist 78                    |  |
| Customers and Vendors79                                                          |  |
| Customer Statements: Implementation Checklist79                                  |  |
| Customer Visibility: Implementation Checklist80                                  |  |
| On-Demand Statements: Implementation Checklist81                                 |  |
| Regenerating Statements: Implementation Checklist82                              |  |
| Vendor Visibility: Implementation Checklist83                                    |  |
| Equipment Management 85                                                          |  |
| Equipment Management: Implementation Checklist85                                 |  |

| General Ledger 86                                                   |  |
|---------------------------------------------------------------------|--|
| Adjusting Transactions: Implementation Checklist 86                 |  |
| Allocation Rules: Implementation Checklist 86                       |  |
| GL Transactions: Implementation Checklist 87                        |  |
| Interbranch Account Mapping: Implementation Checklist 88            |  |
| Recurring Transactions: Implementation Checklist88                  |  |
| Reversing Transactions: Implementation Checklist 89                 |  |
| Running of Allocations: Implementation Checklist 90                 |  |
| Splitting Transactions: Implementation Checklist91                  |  |
| Transactions with Subaccounts: Implementation Checklist92           |  |
| Financial Periods 93                                                |  |
| Financial Calendar Generation: Implementation Checklist 93          |  |
| Financial Periods: Implementation Checklist 93                      |  |
| Opening Financial Periods: Implementation Checklist 94              |  |
| Closing Financial Periods: Implementation Checklist94               |  |
| Multicurrency Management96                                          |  |
| AP Bills in Foreign Currencies: Implementation Checklist 96         |  |
| AR Invoices in Foreign Currencies: Implementation Checklist97       |  |
| Credit Memos in Foreign Currencies: Implementation Checklist98      |  |
| Debit Adjustments in Foreign Currencies: Implementation Checklist99 |  |
| Multicurrency Cash Account: Implementation Checklist 100            |  |
| Multicurrency Funds Transfers: Implementation Checklist101          |  |
| Multicurrency Payment of Invoices: Implementation Checklist 103     |  |
| Multicurrency Payment of Bills: Implementation Checklist104         |  |
| Documents in Different Base Currencies: Implementation Checklist105 |  |
| Revaluation of AP Documents: Implementation Checklist 106           |  |
| Revaluation of AR Documents: Implementation Checklist 107           |  |
| Revaluation of Bank Accounts: Implementation Checklist 109          |  |
| Translation of Financial Statements: Implementation Checklist110    |  |
| Consolidated Financial Statement: Implementation Checklist 111      |  |
| Payroll Management 113                                              |  |
| Payroll Basic Configuration: Implementation Checklist113            |  |
| Prices and Discounts 115                                            |  |
| Sales Prices: Implementation Checklist 115                          |  |
| Prices in Base Currencies: Implementation Checklist 116             |  |
| Project Accounting118                                               |  |

#### Contents | **5**

| Committed Costs: Implementation Checklist 118                                  |  |
|--------------------------------------------------------------------------------|--|
| Change Requests: Implementation Checklist 120                                  |  |
| Employee Time Billing: Implementation Checklist 122                            |  |
| Expense Receipts with Corporate Cards: Implementation Checklist123             |  |
| Expense Returns to Corporate Cards: Implementation Checklist124                |  |
| Overhead in the Project Budget: Implementation Checklist 125                   |  |
| Pro Forma Invoices: Implementation Checklist126                                |  |
| Project Quotes: Implementation Checklist 128                                   |  |
| Project Budget: Implementation Checklist 129                                   |  |
| Project Budget Forecasts: Implementation Checklist 131                         |  |
| Project Templates and Common Tasks: Implementation Checklist 132               |  |
| Project Transactions: Implementation Checklist132                              |  |
| Project Inventory Tracking by Warehouse Location: Implementation Checklist 134 |  |
| Purchasing Services for Projects: Implementation Checklist 136                 |  |
| Single-Tier Change Management: Implementation Checklist 138                    |  |
| Taxes in Projects: Implementation Checklist 139                                |  |
| Time Tracking Configuration: Implementation Checklist 142                      |  |
| Vendor Payments for a Project: Implementation Checklist 144                    |  |
| WIP Labor Costs in Cost-Plus Projects: Implementation Checklist146             |  |
| WIP Labor Costs in Fixed-Price Projects: Implementation Checklist 147          |  |
| Route Management 149                                                           |  |
| Route Management: Implementation Checklist 149                                 |  |
| Service Management151                                                          |  |
| Service Order Types: Implementation Checklist151                               |  |
| Taxes153                                                                       |  |
| Cash Entries with Taxes: Implementation Checklist153                           |  |
| Credit Memos with Sales Taxes: Implementation Checklist154                     |  |
| Funds Transfers with Taxable Fees: Implementation Checklist 155                |  |
| Invoices with Inclusive Sales Taxes: Implementation Checklist 156              |  |
| Invoices with Sales Taxes: Implementation Checklist 158                        |  |
| Purchases with Inclusive Sales Taxes: Implementation Checklist 160             |  |
| Purchases with Sales Taxes: Implementation Checklist161                        |  |
| Purchases with Use Taxes: Implementation Checklist 162                         |  |
| Sales Tax Adjustments: Implementation Checklist164                             |  |
| Tax Report Preparation: Implementation Checklist 164                           |  |
| Release of Sales Tax Report: Implementation Checklist 165                      |  |
|                                                                                |  |

| Taxes Included in the Cost of Items: Implementation Checklist165 |  |
|------------------------------------------------------------------|--|
| Voiding of a Sales Tax Report: Implementation Checklist166       |  |

## <span id="page-6-0"></span>**Copyright**

#### **© 2025 Acumatica, Inc.**

#### **ALL RIGHTS RESERVED.**

No part of this document may be reproduced, copied, or transmitted without the express prior consent of Acumatica, Inc.

3075 112th Avenue NE, Suite 200, Bellevue, WA 98004, USA

## **Restricted Rights**

The product is provided with restricted rights. Use, duplication, or disclosure by the United States Government is subject to restrictions as set forth in the applicable License and Services Agreement and in subparagraph (c)(1)(ii) of the Rights in Technical Data and Computer Soware clause at DFARS 252.227-7013 or subparagraphs (c)(1) and (c)(2) of the Commercial Computer Soware-Restricted Rights at 48 CFR 52.227-19, as applicable.

#### **Disclaimer**

Acumatica, Inc. makes no representations or warranties with respect to the contents or use of this document, and specifically disclaims any express or implied warranties of merchantability or fitness for any particular purpose. Further, Acumatica, Inc. reserves the right to revise this document and make changes in its content at any time, without obligation to notify any person or entity of such revisions or changes.

#### **Trademarks**

Acumatica is a registered trademark of Acumatica, Inc. HubSpot is a registered trademark of HubSpot, Inc. Microso Exchange and Microso Exchange Server are registered trademarks of Microso Corporation. All other product names and services herein are trademarks or service marks of their respective companies.

Soware Version: 2025 R1 Last Updated: 06/01/2025

## <span id="page-7-0"></span>**Acumatica ERP Implementation Checklists**

You can follow this guide when configuring Acumatica ERP functional areas. Each chapter of this guide is focused on the implementation of a particular functional area, and includes the implementation checklists that you use to make sure that the system is configured properly for performing particular business processes.

The checklists within each part of the guide are grouped by functional areas and are sorted in an alphabetical order.

## **Functional Areas**

- *[Basic Company Configuration](#page-35-3)*
- *[Accounts Payable](#page-8-2)*
- *[Accounts Receivable](#page-22-2)*
- *[Cash Management](#page-54-2)*
- *[Customers](#page-78-2) and Vendors*
- *[General Ledger](#page-85-3)*
- *[Financial Periods](#page-92-3)*
- *[Order Management](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=59d8b6a4-fc87-44e8-a3a6-d971eef04210)*
- *[Prices and Discounts](#page-114-2)*
- *[BigCommerce Integration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=59d8b6a4-fc87-44e8-a3a6-d971eef04214)*
- *[Shopify Integration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=59d8b6a4-fc87-44e8-a3a6-d971eef04215)*

## <span id="page-8-2"></span><span id="page-8-0"></span>**Accounts Payable**

## <span id="page-8-1"></span>**AP Bills: Implementation Checklist**

To ensure that the system is configured properly for processing AP bills, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                   |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimum set of features has been enabled as<br>described in Company Without Branches: General Information,<br>Company with Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches that Require Bal<br>ancing: General Information |
| Vendors (AP303000)                 | Verify the existence of the vendor accounts for the vendors<br>for which you will create AP bills. For details, see Vendors: Im<br>plementation Activity.                                                                                                                           |
| Non-Stock Items (IN202000)         | Verify the existence of non-stock items that can be used when<br>creating AP bills. For details, see Non-Stock Item: Implementa<br>tion Activity.                                                                                                                                   |

## **Settings That Affect the Workflow**

You use accounts payable forms to record purchases you make on credit. The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AP bills the *On Hold* status.
  - Clear the **RequireVendor Reference** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a vendor reference number in the**Vendor Ref.** box when creating an AP bill on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AP bills will be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-9-0"></span>**AP Bill Payments: Implementation Checklist**

To ensure that the system is configured properly for paying AP bills, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                               | Notes |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, or Company with Branches<br>that Require Balancing: General Information. |       |
| Vendors (AR303000)                 | Verify the existence of the vendor accounts<br>for the vendors whose bills you will pay. For<br>details, see Vendors: Implementation Activity.                                                                                                                                  |       |
| Payment Methods (CA204000)         | Make sure that the CHECK payment method<br>has been specified when creating a payment.                                                                                                                                                                                          |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created checks the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that checks will be automatically posted to the general ledger once they are released.
- The following payment method settings should be specified for the payment method on the *[Payment](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6) [Methods](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6)* (CA204000) form:
  - Select the **Print Checks** option in the **Additional Processing** section on the**Settings for Use in AP** tab.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-10-0"></span>**AP Documents from PDFs: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for recognizing AP documents from PDF files, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you start recognizing AP documents from PDF files, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                              | Criteria to Check                                                                                                                                                                           |  |
|---------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Enable/Disable Features (CS100000)<br>form        | Make sure that the AP Document Recognition Service feature has been<br>enabled.                                                                                                             |  |
|                                                   | The feature is not available in trial mode and can be en<br>abled only if it is included in the license that is applied to<br>the Acumatica ERP instance.                                   |  |
| Email Accounts (SM204002) form                    | Make sure that a system email account is created with incoming mail<br>processing activated and the Submit to Incoming Documents check<br>box selected on the Incoming Mail Processing tab. |  |
|                                                   | This configuration is needed only if you want automatical<br>ly submit PDF attachments of incoming emails for recogni<br>tion.                                                              |  |
| Rebuild Full-Text Entity Index<br>(SM209500) form | Rebuild search indexes before you start using the AP Document Recogni<br>tion Service feature. For details, see Building Search Indexes.                                                    |  |

## **Project-Related Recognition Checklist**

If you are planning to recognize project-related AP documents from PDF files, you make sure that the following additional configuration steps have been performed, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                                                                      |  |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Enable/Disable Features (CS100000)<br>form | Make sure that the following features are enabled:<br>•<br>Recognition of Project-Related Documents<br>The feature is not available in trial mode and can be en<br>abled only if it is included in the license that is applied<br>to the Acumatica ERP instance.<br>•<br>Projects<br>•<br>Construction |  |

| Form                                                 | Criteria to Check                                                                                                                                                                                               |
|------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Projects Preferences (PM101000)<br>form, General tab | Make sure that the integration of project accounting and accounts<br>payable is enabled—that is, the AP check box is selected in theVisibility<br>Settings section on the Projects Preferences (PM101000) form. |
| Projects (PM101000) form,Summary<br>tab              | Make sure that for each project for which you plan to recognize AP docu<br>ments, the AP check box is selected in theVisibility Settings section on<br>the Projects Preferences (PM101000) form.                |

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *[AP Documents from PDFs: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f229cd53-b896-41c9-a2d8-f6aadd4bc8f5)*.

## <span id="page-11-0"></span>**Bill Prepayments: Implementation Checklist**

To ensure that the system is configured properly for processing prepayments, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Vendors (AR303000)                 | Verify the existence of the vendor accounts<br>for the vendors for which you will create and<br>process prepayments. For details, see Ven<br>dors: Implementation Activity.                                                                                                      |       |
| Non-Stock Items (IN202000)         | Verify the existence of non-stock items that<br>can be used when creating prepayment re<br>quests. For details, see Non-Stock Item: Imple<br>mentation Activity.                                                                                                                 |       |
| Payment Methods (CA204000)         | Make sure the CHECK payment method has<br>been selected when paying a prepayment re<br>quest.                                                                                                                                                                                    |       |

#### **Implementation Notes**

When deciding how many and which prepayment accounts to use to make it easier to track them in the system, you can select one or any of the following options:

- To use a single prepayment account for all prepayments (to all vendors)
- To specify the prepayment accounts for particular vendor classes
- To specify separate prepayment accounts for specific vendors

If you do not specify a separate account for prepayments, the vendor prepayments will be debited to the vendor AP account.

To assign the prepayment accounts, do the following:

- 1. On the *Vendor [Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=20dc8b93-d83a-49cf-8cfb-d2ffd2f0db87)* (AP201000) form, specify the prepayment account and subaccount for the default vendor class and for each of the other vendor classes. This will make it easy to create new vendor classes and new vendors with the proper prepayment account specified.
- 2. Use the *[Vendors](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a9584be3-f2bd-4d67-80d4-8041d809df56)* (AP303000) form to specify the prepayment account and subaccount for each vendor.

### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created checks the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that checks will be automatically posted to the general ledger once they are released.
- The following payment method settings should be specified for the payment method on the *[Payment](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6) [Methods](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6)* (CA204000) form:
  - Select the **Print Checks** option in the **Additional Processing** section on the**Settings for Use in AP** tab.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-12-0"></span>**Debit and Credit Adjustments: Implementation Checklist**

To ensure that the system is configured properly for processing debit and credit adjustments, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |

| Form               | Criteria to Check                                                                                                                                                                | Notes |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Vendors (AP303000) | Verify the existence of the vendor accounts<br>for the vendors for which you will create debit<br>and credit adjustments. For details, see Ven<br>dors: Implementation Activity. |       |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created debit and credit adjustments the *On Hold* status.
  - Clear the **RequireVendor Reference** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a vendor reference number in the**Vendor Ref.** box when creating a debit or credit adjustment on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that debit and credit adjustments will be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-13-0"></span>**Interbranch Bills Without Balancing: Implementation Checklist**

Before users begin processing AP bills between branches that do not require balancing, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table

| Form                                       | Settings to Check                                            | Notes |
|--------------------------------------------|--------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the following fea<br>tures have been enabled: |       |
|                                            | •<br>Standard Financials                                     |       |
|                                            | •<br>Multibranch Support                                     |       |
|                                            | •<br>Multicompany Support                                    |       |
|                                            | •<br>Advanced Financials                                     |       |
|                                            | •<br>Inter-Branch Transactions                               |       |

| Form                                          | Settings to Check                                                                                                                                                              | Notes                                                                                            |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Multiple forms                                | Make sure that the minimum con<br>figuration of the company has been<br>performed.                                                                                             |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                                                    |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which bills will be defined have<br>a status of Open.                                                                                | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Vendors (AP303000) form                       | Ensure that all needed vendors—<br>that is, all vendors for which AP<br>bills between branches not requir<br>ing balancing may be created—<br>have been defined in the system. |                                                                                                  |

## **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts the appropriate transactions to the general ledger when AP documents are released. If this check box is cleared, you have to post the batch aer you release the AP document.
- If the **PostSummary on Updating GL** check box is selected, AP documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AP document specify the same account and branch, then in the GL batch, these rows are combined into one row (that is, one journal entry) with the summarized amount. If this check box is cleared, the lines of the AP document are not combined into one journal entry in the GL batch.
- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **RequireVendor Reference** check box is selected, you must fill in the**Vendor Ref.** box on the *[Bills and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234) [Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* form. If this check box is cleared, you can leave the**Vendor Ref.** box blank.

## <span id="page-14-0"></span>**Interbranch Bills with Balancing: Implementation Checklist**

Before users begin processing AP bills between branches that require balancing, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                            | Settings to Check                                                                                                                  | Notes                                                                                            |
|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form      | Make sure that the following fea<br>tures have been enabled:                                                                       |                                                                                                  |
|                                                 | •<br>Standard Financials                                                                                                           |                                                                                                  |
|                                                 | •<br>Multibranch Support<br>•<br>Multicompany Support                                                                              |                                                                                                  |
|                                                 | •<br>Advanced Financials                                                                                                           |                                                                                                  |
|                                                 | •<br>Inter-Branch Transactions                                                                                                     |                                                                                                  |
| Multiple forms                                  | Make sure that the minimum con<br>figuration of the company has been<br>performed.                                                 |                                                                                                  |
| Chart of Accounts (GL202500) form               | Check whether the necessary ac<br>counts have been created.                                                                        |                                                                                                  |
| Inter-Branch Account Mapping<br>(GL101010) form | Be sure that the account mapping<br>rules have been specified for the<br>branches.                                                 | For details on defining these rules,<br>see Interbranch Account Mapping:<br>General Information. |
| Company Financial Calendar<br>(GL201100) form   | Be sure that all financial periods for<br>which AP bills for branches requir<br>ing balancing may occur have a sta<br>tus of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Vendors (AP303000) form                         | Ensure that all vendors that may<br>be specified in these AP bills are de<br>fined in the system.                                  |                                                                                                  |

## **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts the appropriate transactions to the general ledger when AP documents are released. If this check box is cleared, you have to post the batch aer you release the AP document.
- If the **PostSummary on Updating GL** check box is selected, AP documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AP document specify the same account and branch, then in the GL batch, these rows are combined into one row (that is, one journal entry) with the summarized amount. If this check box is cleared, the lines of the AP document are not combined into one journal entry in the GL batch.
- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **RequireVendor Reference** check box is selected, you must fill in the**Vendor Ref.** box on the *[Bills and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234) [Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* form. If this check box is cleared, you can leave the**Vendor Ref.** box blank.

## <span id="page-16-0"></span>**Check Reprinting: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing check reprinting, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially print and reprint checks, you make sure the settings have been specified and entities created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                             |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been enabled<br>as described in Company Without Branches: General<br>Information, Company with Branches that Do Not Re<br>quire Balancing: General Information, and Company with<br>Branches that Require Balancing: General Information. |
| Payment Methods (CA204000)         | Make sure that the CHECK payment method has been<br>specified when creating a payment.                                                                                                                                                                                        |

## **Settings That Affect the Workflow**

You can affect the workflow of reprinting checks by specifying additional settings as follows:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created checks the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that checks will be automatically posted to the general ledger once they are released.
- The following payment method settings should be specified for the payment method on the *[Payment](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6) [Methods](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6)* (CA204000) form:
  - Select the **Print Checks** option in the **Additional Processing** section on the**Settings for Use in AP** tab.

## **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you reprint checks as described in *[Check Reprinting: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=abdf6b04-5556-4cab-9cf2-1b0a7c492886)*.

## <span id="page-17-0"></span>**Multiple Bill Payments: Implementation Checklist**

To ensure that the system is configured properly for processing a payment of multiple bills, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Vendors (AP303000)                 | Verify the existence of the vendor accounts<br>for the vendors whose bills you want to pay<br>with one payment. For details, see Vendors:<br>Implementation Activity.                                                                                                            |       |
| Payment Methods (CA204000)         | Make sure the CHECK payment method has<br>been selected when creating a payment.                                                                                                                                                                                                 |       |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created payments the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that payments will be automatically posted to the general ledger once they are released.
- The following payment method settings should be specified for the payment method on the *[Payment](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6) [Methods](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6)* (CA204000) form:
  - Select the **Print Checks** option in the **Additional Processing** section on the**Settings for Use in AP** tab.
- The following vendor settings should be specified on the *[Vendors](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a9584be3-f2bd-4d67-80d4-8041d809df56)* (AP303000) form:
  - For the vendor whose bills should be paid by separate payments, select the **PaySeparately** check box in the **Default PaymentSettings** section of the **Payment** tab.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-18-0"></span>**Payments for a Shared Vendor: Implementation Checklist**

Before users begin processing payments for a vendor shared between different companies, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                          | Settings to Check                                                                                                                                                                                                                                           | Notes                                                                                            |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure that the following fea<br>tures have been enabled:                                                                                                                                                                                                |                                                                                                  |
|                                               | •<br>Standard Financials                                                                                                                                                                                                                                    |                                                                                                  |
|                                               | •<br>Multibranch Support<br>•<br>Multicompany Support                                                                                                                                                                                                       |                                                                                                  |
| Multiple forms                                | Make sure that the minimum con<br>figuration of the companies has<br>been performed.                                                                                                                                                                        |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                                                                                                                                 |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Make sure that all periods for which<br>users may process payments for<br>a shared vendor have a status of<br>Open.                                                                                                                                         | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Vendors (AP303000) form                       | Ensure that all vendors for which<br>shared payments from different<br>companies may be processed are<br>defined in the system. For these<br>vendors, also be sure that no ac<br>count has been specified in the<br>Cash Account box of the Payment<br>tab. |                                                                                                  |
| Payment Methods (CA204000) form               | Be sure that the necessary cash ac<br>counts have been defined as the<br>default accounts for the branches<br>in the payment methods of the ven<br>dor.                                                                                                     |                                                                                                  |

## **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts the appropriate transactions to the general ledger when AP documents are released. If this check box is cleared, you have to post the batch aer you release the AP document.
- If the **PostSummary on Updating GL** check box is selected, AP documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AP document specify the same account and branch, then in the GL batch, these rows are combined into one row (that is,

one journal entry) with the summarized amount. If this check box is cleared, the lines of the AP document are not combined into one journal entry in the GL batch.

- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **RequireVendor Reference** check box is selected, you must fill in the**Vendor Ref.** box on the *[Bills and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234) [Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* form. If this check box is cleared, you can leave the**Vendor Ref.** box blank.

## <span id="page-19-0"></span>**Partial Payments: Implementation Checklist**

To ensure that the system is configured properly for paying AP bills, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                               | Notes |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, or Company with Branches<br>that Require Balancing: General Information. |       |
| Vendors (AR303000)                 | Verify the existence of the vendor accounts<br>for the vendors whose bills you will pay. For<br>details, see Vendors: Implementation Activity.                                                                                                                                  |       |
| Payment Methods (CA204000)         | Make sure that the CHECK payment method<br>has been specified when creating a payment.                                                                                                                                                                                          |       |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created checks the *On Hold* status.

- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that checks will be automatically posted to the general ledger once they are released.
- The following payment method settings should be specified for the payment method on the *[Payment](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6) [Methods](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6)* (CA204000) form:
  - Select the **Print Checks** option in the **Additional Processing** section on the**Settings for Use in AP** tab.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-20-0"></span>**Voiding Payments: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for voiding payments, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you void payments, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                               |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been enabled as de<br>scribed in Company Without Branches: General Information,<br>Company with Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches that Require Bal<br>ancing: General Information. |
| Vendors (AR303000)                 | Verify the existence of the vendor accounts for the vendors<br>whose payments you want to void. For details, see Vendors:<br>Implementation Activity.                                                                                                                           |
| Payment Methods (CA204000)         | Make sure that the CHECK payment method has been speci<br>fied when creating a payment.                                                                                                                                                                                         |

## **Other Settings That Affect the Workflow**

You can affect the workflow of payment voiding by specifying additional settings as follows:

- To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form.
- To cause every AP transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* form. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- To give the created payments the *On Hold* status, select the **Hold Documents on Entry** check box in the **Data EntrySettings** section on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* form. This setting indicates that payments will be automatically posted to the general ledger once they are released.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you void a payment as described in *Voiding [Payments:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=238e778f-8c0b-45e4-891e-48067c018943) Process Activity*.

## <span id="page-21-0"></span>**Payments with a Corporate Card: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing expenses with corporate cards, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially process expenses with the corporate cards, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                       | Criteria to Check                                                                                                                                                                                 |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Corporate Cards (CA202500) | Make sure that the corporate card has been config<br>ured. For more information, see Corporate Cards: Gen<br>eral Information.                                                                    |
| Vendors (AP303000)         | Make sure that a vendor that represents the bank that<br>issued the corporate credit card have been created.<br>For this vendor, specify the accrued liability account as<br>the Expense Account. |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing expenses with corporate credit cards by specifying additional settings as follows:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created payments the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that payments will be automatically posted to the general ledger once they are released.

## <span id="page-22-2"></span><span id="page-22-0"></span>**Accounts Receivable**

## <span id="page-22-1"></span>**AR Invoices: Implementation Checklist**

To ensure that the system has been configured properly for the processing of AR invoices, make sure that the criteria listed in the table have been met in the system as described.

## **Implementation Checklist**

We recommend that before you initially process AR invoices, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                                  | Criteria to Check                                                                                                                                                                                                                                                                 | Notes |
|-------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)                    | Make sure the minimal features have been<br>enabled, as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)                                  | Be sure that the customer accounts for the<br>customers for which you will create AR invoic<br>es have been defined.                                                                                                                                                              |       |
| Non-Stock Items (IN202000), Stock<br>Items (IN202500) | Verify the existence of non-stock items or<br>stock items that can be used when you are<br>creating AR invoices. For details, see Non<br>Stock Item: Implementation Activity.                                                                                                     |       |

#### **Settings That Affect the Workflow**

In general, you use accounts receivable forms specifically for sales made on credit. The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **General** tab (**PostingSettings** section) of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **General** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices the *On Hold* status.

- Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a payment reference number in the **Payment Ref.** box when creating a payment on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AR invoices to be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-23-0"></span>**AR Invoice Correction: Implementation Checklist**

To ensure that the system is configured properly for creating and releasing credit and debit memos, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers for which you will correct<br>AR invoices by creating credit and debit mem<br>os. For details, see Customers: Implementation<br>Activity.                                                                     |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable preferences settings should be specified on the **General** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.
  - Make sure that the **Use CreditTerms in Credit Memos** check box is cleared in the **Data EntrySettings** section. This setting indicates that credit memos cannot have credit terms and cash discounts applied to them.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-24-0"></span>**Auto-Applying Payments: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing auto-application of payments, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially auto-apply payments or prepayments to customer documents, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                             |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been enabled<br>as described in Company Without Branches: General<br>Information, Company with Branches that Do Not Re<br>quire Balancing: General Information, and Company with<br>Branches that Require Balancing: General Information. |
| Statement Cycles (AR202800)        | Make sure that the End of Month statement cycle has<br>been configured.                                                                                                                                                                                                       |
| Customers (AR303000)               | Verify the existence of the customer accounts for the<br>customers whose payments or prepayments you will<br>auto-apply to documents. For details, see Customers:<br>Implementation Activity.<br>Make sure that the EOM statement cycle has been se                           |
|                                    | lected for the customer accounts in theStatement Cy<br>cle ID box in the Financial Settings section on the Fi<br>nancial tab of the current form.                                                                                                                             |

## **Other Settings That Affect the Workflow**

You can affect the workflow of the auto-application process by specifying additional settings on the **General Settings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form as follows:

- Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.

## **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you perform the auto-application process as described in *[Auto-Applying Payments: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=648d7f92-c928-4499-bd82-6acc2f3f2a3a)*.

## <span id="page-25-0"></span>**Refunds: Implementation Checklist**

To ensure that the system is configured properly for creating a refund, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers whose refunds you will<br>process. For details, see Customers: Imple<br>mentation Activity.                                                                                                                   |       |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **General** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. With this check box cleared, you do not have to fill in payment reference information in the **Payment Ref.** box on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-25-1"></span>**Interbranch Invoices with Balancing: Implementation Checklist**

Before users begin processing invoices between branches that require balancing, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                            | Settings to Check                                                                         | Notes                                                                                            |
|-------------------------------------------------|-------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form      | Make sure that the following fea<br>tures have been enabled:                              |                                                                                                  |
|                                                 | •<br>Standard Financials                                                                  |                                                                                                  |
|                                                 | •<br>Multi-Branch Support                                                                 |                                                                                                  |
|                                                 | •<br>Advanced Financials                                                                  |                                                                                                  |
|                                                 | Inter-Branch Transactions<br>•                                                            |                                                                                                  |
|                                                 | Make sure that the minimum con<br>figuration of the company has been<br>performed.        |                                                                                                  |
| Chart of Accounts (GL202500) form               | Check whether the necessary ac<br>counts have been created.                               |                                                                                                  |
| Inter-Branch Account Mapping<br>(GL101010) form | Be sure that the account mapping<br>rules have been specified for the<br>branches.        | For details on defining these rules,<br>see Interbranch Account Mapping:<br>General Information. |
| Company Financial Calendar<br>(GL201100) form   | Be sure that the periods for which<br>invoices will be defined have a sta<br>tus of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Customers (AR303000) form                       | Be sure that the periods for which<br>invoices will be defined have a sta<br>tus of Open. |                                                                                                  |

## **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts transactions to the general ledger when AR documents are released. If this check box is cleared, you have to post the batch aer you release the AR document.
- If the **PostSummary on Updating GL** check box is selected, AR documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AR document specify the same account and branch, then in the GL batch, these rows will be combined into one entry with the summarized amount. If this check box is cleared, the lines of the AR document will not be combined into one journal entry in the GL batch.
- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* (AR301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **Require Payment Reference on Entry** check box is selected, you must fill in the **Payment Ref.** box on the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* form. If this check box is cleared, you can leave the **Payment Ref.** box blank.
- If the **Require Invoice/Memo Printing Before Release** check box is selected, you must print an AR invoice or memo before release for those customers who prefer to receive printed copies of the documents. That is, if the **Print Invoices** check box is selected on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* (AR303000) form for a customer account,

each invoice is created with the *Pending Print* status. If this check box is cleared, you can release the invoice without printing.

• If the **Require Invoice/Memo Emailing Before Release** check box is selected, you must send an email with an AR invoice or memo before release for those customers who prefer to receive copies of the documents by email. That is, if the**Send Invoices by Email** check box is selected on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* form for a customer account, each invoice is created with the *Pending Email* status. If this check box is cleared, you can release the invoice without sending an email.

## <span id="page-27-0"></span>**Interbranch Invoices Without Balancing: Implementation Checklist**

Before users begin processing invoices between branches that do not require balancing,you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                          | Settings to Check                                                                                                                                                                   | Notes                                                                                            |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure that the following fea<br>tures have been enabled:                                                                                                                        |                                                                                                  |
|                                               | Standard Financials<br>•                                                                                                                                                            |                                                                                                  |
|                                               | •<br>Multibranch Support                                                                                                                                                            |                                                                                                  |
|                                               | •<br>Multicompany Support                                                                                                                                                           |                                                                                                  |
|                                               | •<br>Advanced Financials                                                                                                                                                            |                                                                                                  |
|                                               | •<br>Inter-Branch Transactions                                                                                                                                                      |                                                                                                  |
|                                               | Make sure that the minimum con<br>figuration of the company has been<br>performed.                                                                                                  |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                                                         |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the periods for which<br>invoices will be defined have a sta<br>tus of Open.                                                                                           | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Customers (AR303000) form                     | Ensure that all needed customers—<br>that is, all customers for which in<br>voices between branches not re<br>quiring balancing may be created—<br>have been defined in the system. |                                                                                                  |

#### **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts transactions to the general ledger when AR documents are released. If this check box is cleared, you have to post the batch aer you release the AR document.
- If the **PostSummary on Updating GL** check box is selected, AR documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AR document specify the same account and branch, then in the GL batch, these rows will be combined into one entry with

the summarized amount. If this check box is cleared, the lines of the AR document will not be combined into one journal entry in the GL batch.

- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* (AR301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **Require Payment Reference on Entry** check box is selected, you must fill in the **Payment Ref.** box on the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* form. If this check box is cleared, you can leave the **Payment Ref.** box blank.
- If the **Require Invoice/Memo Printing Before Release** check box is selected, you must print an AR invoice or memo before release for those customers who prefer to receive printed copies of the documents. That is, if the **Print Invoices** check box is selected on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* (AR303000) form for a customer account, each invoice is created with the *Pending Print* status. If this check box is cleared, you can release the invoice without printing.
- If the **Require Invoice/Memo Emailing Before Release** check box is selected, you must send an email with an AR invoice or memo before release for those customers who prefer to receive copies of the documents by email. That is, if the**Send Invoices by Email** check box is selected on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* form for a customer account, each invoice is created with the *Pending Email* status. If this check box is cleared, you can release the invoice without sending an email.

## <span id="page-28-0"></span>**Intercompany Sales: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing intercompany sales, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially perform intercompany sales, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                        |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the following features have been enabled:<br>•<br>Standard Financials<br>•<br>Multibranch Support<br>Multicompany Support<br>•<br>Advanced Financials<br>•<br>•<br>Inter-Branch Transactions                                              |
| Companies (CS101500)               | If you are going to extend as a customer or vendor any company that has<br>the Without Branches company type, make sure that the company has<br>been configured. For details, see Company Without Branches: To Config<br>ure a Company Without Branches. |

| Form                        | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                           |
|-----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Branches (CS102000)         | If you are going to extend as a customer or vendor any branches of com<br>panies with the With Branches Not Requiring Balancing or With Branches<br>Requiring Balancing company type, make sure that the companies have<br>been configured. For details, see Company with Branches that Do Not Re<br>quire Balancing: Implementation Activity and Company with Branches that<br>Require Balancing: Implementation Activity. |
| Customer Classes (AR201000) | Make sure that the customer class to be used for a customer extended<br>from a company or branch has been defined. For details, see Accounts<br>Receivable: To Create a Customer Class.                                                                                                                                                                                                                                     |
| Vendor Classes (AP201000)   | Make sure that the vendor class to be used for a vendor extended from a<br>company or branch has been defined. For details, see Accounts Payable:<br>To Create a Vendor Class.                                                                                                                                                                                                                                              |

## **Other Settings That Affect the Workflow**

You can affect the workflow of intercompany sales by specifying additional settings as follows:

- To cause AR documents to be posted automatically, select the **Automatically Post on Release** check box on the **GeneralSettings** tab (**PostingSettings** section) of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form.
- To cause the ID of the default customer class to be inserted automatically when a company or branch has been extended to be a customer, select a customer class ID in the **Default Customer Class ID** box on the **GeneralSettings** tab (**Data EntrySettings** section) of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* form. If this box is empty, you will have to specify a customer class for the new customer on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* (AR303000) form.
- To cause the system to insert a sales account from the customer location to an AR invoice, in the **Use IntercompanySales Account From** box, select *Customer Location*. If *Inventory Item* is selected in this box, the system will insert the sales account specified in the**Sales Account** box on the **GL Accounts** tab of the *[Non-Stock Items](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=bf68dd4f-63d4-460d-8dc0-9152f2bd6bf1)* (IN202000) form for non-stock items.
- To cause new documents to be assigned the *On Hold* status when they are created, select the **Hold Documents on Entry** check box on the **GeneralSettings** tab (**Data EntrySettings** section) of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* form. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- To cause AP documents to be posted automatically, select the **Automatically Post on Release** check box on the **GeneralSettings** tab (**PostingSettings** section) of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form.
- To cause the ID of the default vendor class to be inserted automatically when a company or branch has been extended to be a vendor, select a vendor class ID in the **DefaultVendor Class ID** box on the **General Settings** tab (**Data EntrySettings** section) of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* form. If this box is empty, you will have to specify a vendor class for the new vendor on the *[Vendors](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a9584be3-f2bd-4d67-80d4-8041d809df56)* (AP303000) form.
- To cause the system to insert an expense account from the vendor location to an AP bill created from an AR invoice, in the **Use Intercompany Expense Account From** box, select *Vendor Location*. If *Inventory Item* is selected in this box, the system will insert the expense account specified in the **Expense Account** box on the **GL Accounts** tab of the *[Non-Stock Items](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=bf68dd4f-63d4-460d-8dc0-9152f2bd6bf1)* (IN202000) form for non-stock items.
- To cause new documents to be assigned the *On Hold* status when they are created, select the **Hold Documents on Entry** check box on the **GeneralSettings** tab (**Data EntrySettings** section) of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* form. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process intercompany sales by performing instructions similar to those described in *[Intercompany](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0db4c77c-f877-471a-b025-db9fc303cb15) Sales: To Process [an Intercompany Invoice](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0db4c77c-f877-471a-b025-db9fc303cb15)*, *[Intercompany](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=eb80dc35-c7a9-4a2a-bd9b-1f59f1c966a0) Sales: To Pay an Intercompany Bill*, and *[Intercompany](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8e65e73c-8eb5-4a97-bab2-ccc158799bd4) Sales: To Pay an [Intercompany Invoice](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8e65e73c-8eb5-4a97-bab2-ccc158799bd4)*.

## <span id="page-30-0"></span>**Invoice Payments: Implementation Checklist**

To ensure that the system is configured properly for creating a payment and applying it to an invoice, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers whose invoices you will<br>pay. For details, see Customers: Implementa<br>tion Activity.                                                                                                                      |       |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **GeneralSettings** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. With this check box cleared, you do not have to fill in payment reference information in the **Payment Ref.** box on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-31-0"></span>**Invoice Prepayments: Implementation Checklist**

To ensure that the system has been configured properly for the processing of prepayments, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                 | Notes |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled, as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)               | Be sure that the customer accounts for the<br>customers for which you will create and<br>process prepayments have been defined.                                                                                                                                                   |       |

## **Settings That Affect the Workflow**

In general, you use accounts receivable forms specifically for sales made on credit. The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **GeneralSettings** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created prepayments the *On Hold* status.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a payment reference number in the **Payment Ref.** box when creating a prepayment on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes prepayments to be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-31-1"></span>**Invoice with Combined Subaccounts: Implementation Checklist**

To ensure that the system has been configured properly for the processing of AR invoices, make sure that the criteria listed in the table have been met in the system as described.

| Form                                                              | Criteria to Check                                                                                                                                                                                                                                                                                                | Notes |
|-------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form                        | Make sure the Standard Financials and Subac<br>counts(under Advanced Financials) features<br>have been enabled.                                                                                                                                                                                                  |       |
| Multiple forms                                                    | Make sure that the minimum configuration<br>of the company has been performed, as de<br>scribed in Company Without Branches: Gen<br>eral Information, Company with Branches that<br>Do Not Require Balancing: General Information,<br>and Company with Branches that Require Bal<br>ancing: General Information. |       |
| Segmented Keys (CS202000) form,<br>Segment Values (CS203000) form | Be sure that the SUBACCOUNTS segmented<br>key has been configured to meet the compa<br>ny's business needs, as described in Subac<br>counts: General Information.                                                                                                                                                |       |
| Accounts Receivable Preferences<br>(AR101000) form                | Make sure that a proper subaccount mask<br>has been specified for AR documents, as de<br>scribed in Combined Subaccounts: To Define a<br>Subaccount Mask for AR Documents.                                                                                                                                       |       |
| Customers (AR303000)                                              | Be sure that the customer accounts have<br>been defined for the customers for which you<br>will create AR invoices.                                                                                                                                                                                              |       |
| Non-Stock Items (IN202000), Stock<br>Items (IN202500)             | Verify the existence of the non-stock items or<br>stock items (or both) that will be used when<br>you are creating AR invoices. For details, see<br>Non-Stock Item: Implementation Activity.                                                                                                                     |       |

## **Settings That Affect the Workflow**

For a streamlined workflow of processing AR invoices, we recommend that you specify various settings related to the general ledger and to accounts receivable.

Do the following on the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:

- Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
- Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)

Do the following on the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:

- Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting causes the system to assign the *On Hold* status to the created AR invoices.
- Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. With this setting, users do not have to enter a payment reference number in the **Payment Ref.** box when creating an AR invoice on the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* (AR301000) form.

• Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AR invoices to be automatically posted to the general ledger once they are released.

With these settings specified, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-33-0"></span>**Payments with Write-Offs: Implementation Checklist**

To ensure that the system is configured properly for creating a credit write-off when you process a payment, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes                                                                                                                                                                                      |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the basic features have been en<br>abled, as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |                                                                                                                                                                                            |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers whose payments you want<br>to process. For details, see Customers: Imple<br>mentation Activity.                                                                                                               |                                                                                                                                                                                            |
|                                    | The needed customer accounts must be spec<br>ified for write-offs in the Financial Settings<br>section on the Financial tab as follows:                                                                                                                                          |                                                                                                                                                                                            |
|                                    | •<br>The Enable Write-Offs check box must be<br>selected.<br>•<br>A Write-Off Limit value must be specified.                                                                                                                                                                     |                                                                                                                                                                                            |
| Chart of Accounts (GL202500)       | Verify the existence of the GL accounts to<br>which the write-off amounts will be posted.                                                                                                                                                                                        | The account you use<br>to post credit write<br>off amounts should be<br>an Income account;<br>the account you use to<br>post balance write-off<br>amounts should be an<br>Expense account. |
| Reason Codes (CS211000)            | Verify the existence of the reason codes to be<br>used for write offs.                                                                                                                                                                                                           |                                                                                                                                                                                            |

## **Settings That Affect the Workflow**

Be sure that the appropriate settings have been defined as follows:

- Do the following on the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR document you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system

consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)

- On the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form, do the following:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. With this check box cleared, you do not have to fill in payment reference information in the **Payment Ref.** box on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.

With these settings specified, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-35-3"></span><span id="page-35-0"></span>**Basic Company Configuration**

## <span id="page-35-1"></span>**Preparing an Instance: Implementation Checklist**

You can use the tables in this topic to quickly check whether the preparation steps are being performed in Acumatica ERP. The following tables cover both mandatory and recommended preparation steps.

The person who performs the initial configuration uses the *admin* username and the initial password only until the accounts for the persons participating in implementation are created (in the last task of initial configuration). We recommend that aer initial configuration, the users use their personal usernames and passwords to access the system.

#### *Table: Mandatory Configuration*

To ensure that the instance has been implemented properly, make sure that the necessary features have been enabled and the needed entities have been created, as listed in the following table.

| Form                               | Criteria to Check                                                                 |
|------------------------------------|-----------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The default set of features has been enabled for the instance.                    |
| Activate License (SM201510)        | A license key has been entered and activated. The license details are<br>correct. |

#### *Table: Recommended Configuration*

The settings listed in the following table can be specified to secure the process of implementation.

| Form                            | Criteria to Check                                                                                                                                                                                              |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Security Preferences (SM201060) | The system-wide security policy has been configured to ensure that<br>access to the tenant in implementation is secure and to track activities<br>performed with the tenant by people involved in the process. |
| Users (SM201010)                | User accounts for people involved in the implementation have been<br>created, by using the Users (SM201010) form.                                                                                              |
|                                 | For each user, at least the following settings have been specified:                                                                                                                                            |
|                                 | •<br>Username (login)                                                                                                                                                                                          |
|                                 | •<br>Initial password to be changed on the first sign-in                                                                                                                                                       |
|                                 | •<br>Email address                                                                                                                                                                                             |
|                                 | •<br>Set of predefined roles that allow access to all system resources                                                                                                                                         |

## <span id="page-35-2"></span>**Company Without Branches: Implementation Checklist**

You can use the tables in this topic to quickly check whether the basic company configuration steps are being performed in Acumatica ERP. The following tables cover both mandatory configuration steps and recommended configuration steps.

#### *Table: Mandatory Configuration*

To ensure that the basic configuration of a company has been implemented properly, make sure that the necessary features have been enabled and the needed entities have been created, as listed in the following table.

| Form                                         | Criteria to Check                                                                                                                                                                                                             |
|----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form      | Make sure that the Standard Financials group of fea<br>tures has been enabled.                                                                                                                                                |
| Companies (CS101500) form                    | Make sure that the necessary company has been creat<br>ed and that the necessary ledger has been created and<br>assigned to it.                                                                                               |
| Chart of Accounts (GL202500) form            | Make sure that the necessary accounts for performing<br>financial operations have been added.                                                                                                                                 |
| General Ledger Preferences (GL102000) form   | Make sure that all necessary settings to use the gener<br>al ledger functionality have been specified, including<br>the YTD Net Income and Retained Earnings accounts.                                                        |
| Financial Year (GL101000) form               | Make sure that the first financial year in which the<br>company will operate has been added and the periods<br>have been generated.                                                                                           |
| Company Financial Calendar (GL201100) form   | Make sure that the periods in which the company will<br>operate are open.                                                                                                                                                     |
| Cash Management Preferences (CA102000) form  | Make sure that all necessary settings to use the cash<br>management functionality have been specified, in<br>cluding the Cash-in-Transit account.                                                                             |
| Cash Accounts (CA202000) form                | Make sure that the necessary cash accounts to record<br>cash entries and funds transfers have been created,<br>and that the necessary entry types have been assigned<br>to them.                                              |
| Payment Methods (CA204000) form              | Make sure that the payment methods to be used have<br>been created and defined to use the proper accounts.                                                                                                                    |
| Entry Types (CA203000) form                  | Make sure that the necessary entry types for process<br>ing cash payments have been created and assigned to<br>the related cash accounts.                                                                                     |
| Credit Terms (CS206500) form                 | Make sure that the needed credit terms—those that<br>are commonly used by vendors in their relations with<br>your company, and those that are used by your com<br>pany in its relations with customers—have been creat<br>ed. |
| Vendor Classes (AP201000) form               | Make sure that the default vendor class, which pro<br>vides the default values for vendor accounts and for<br>other vendor classes, has been created.                                                                         |
| Accounts Payable Preferences (AP101000) form | Make sure that all necessary settings to use the ac<br>counts payable functionality have been specified.                                                                                                                      |

| Form                                            | Criteria to Check                                                                                                                                                                                         |
|-------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Statement Cycles (AR202800) form                | Make sure that the necessary statement cycles, which<br>will later be used to track customers' outstanding bal<br>ances and send electronic or printed statements to the<br>customers, have been created. |
| Customer Classes (AR201000) form                | Make sure that the default customer class, which pro<br>vides the default values for customer accounts and for<br>other customer classes, has been created.                                               |
| Accounts Receivable Preferences (AR101000) form | Make sure that all necessary settings to use the ac<br>counts receivable functionality have been specified.                                                                                               |

#### *Table: Recommended Configuration*

The settings listed in the following table can be specified to simplify the process of creating entities in the system.

| Form                                         | Criteria to Check                                                                                                                             |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| General Ledger Preferences (GL102000) form   | Make sure that the following settings have been speci<br>fied:                                                                                |
|                                              | •<br>The Automatically Post on Release check box is<br>selected.                                                                              |
|                                              | •<br>The Hold Batches on Entry check box is cleared.                                                                                          |
| Cash Management Preferences (CA102000) form  | Make sure that the following settings have been speci<br>fied:                                                                                |
|                                              | •<br>The Automatically Post to GL on Release check<br>box is selected.                                                                        |
|                                              | •<br>The Hold Transactions on Entry check box is<br>cleared.                                                                                  |
|                                              | •<br>The Require Document Ref. Nbr. on Entry check<br>box is cleared.                                                                         |
| Accounts Payable Preferences (AP101000) form | Make sure that the following settings have been speci<br>fied:                                                                                |
|                                              | •<br>The Automatically Post on Release check box is<br>selected.                                                                              |
|                                              | •<br>A vendor class, which will be used to provide de<br>fault values for vendor accounts, is selected in the<br>Default Vendor Class ID box. |
|                                              | •<br>The Hold Documents on Entry check box is<br>cleared.                                                                                     |
|                                              | •<br>The Require Approval of Bills Prior to Payment<br>check box is cleared.                                                                  |
|                                              | •<br>The Validate Document Totals on Entry check box<br>is cleared.                                                                           |
|                                              | •<br>The Require Vendor Reference check box is<br>cleared.                                                                                    |

| Form                                            | Criteria to Check                                                                                                                                          |  |
|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Accounts Receivable Preferences (AR101000) form | Make sure that the following settings have been speci<br>fied:                                                                                             |  |
|                                                 | •<br>The Automatically Post on Release check box is<br>selected.                                                                                           |  |
|                                                 | •<br>A customer class, which will be used to provide de<br>fault values for customer accounts, has been se<br>lected in the Default Customer Class ID box. |  |
|                                                 | •<br>The Hold Documents on Entry check box is<br>cleared.                                                                                                  |  |
|                                                 | •<br>The Validate Document Totals on Entry check box<br>is cleared.                                                                                        |  |
|                                                 | •<br>The Require Payment Reference on Entry check<br>box is cleared.                                                                                       |  |

## <span id="page-38-0"></span>**Company with Branches that Do Not Require Balancing: Implementation Checklist**

You can use the tables in this topic to quickly check whether the configuration steps for a company with branches that do not require balancing are being performed in Acumatica ERP. The following tables cover both the mandatory configuration steps and the recommended configuration steps.

#### *Table: Mandatory Configuration*

To ensure that the basic configuration of a company has been implemented properly, make sure that the necessary features have been enabled and the needed entities have been created, as listed in the following table.

| Form                                       | Things to Check                                                                                                                                                                                | Notes |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the Standard Fi<br>nancials group of features and the<br>Multibranch Support and Multicom<br>pany Support features have been<br>enabled.                                        |       |
| Companies (CS101500) form                  | Make sure that the necessary com<br>pany has been created with the<br>With Branches Not Requiring Bal<br>ancing type and that the necessary<br>ledger has been created and as<br>signed to it. |       |
| Branches (CS102000) form                   | Make sure that the branches of the<br>company have been created.                                                                                                                               |       |
| Chart of Accounts (GL202500) form          | Make sure that the necessary ac<br>counts for performing financial op<br>erations have been added.                                                                                             |       |

| Form                                            | Things to Check                                                                                                                                                                                                                    | Notes |
|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| General Ledger Preferences<br>(GL102000) form   | Make sure that all necessary set<br>tings to use the general ledger<br>functionality have been specified,<br>including the YTD Net Income and<br>Retained Earnings accounts.                                                       |       |
| Financial Year (GL101000) form                  | Make sure that the first financial<br>year in which the company will op<br>erate has been added and the peri<br>ods have been generated.                                                                                           |       |
| Company Financial Calendar<br>(GL201100) form   | Make sure that the periods in which<br>the company will operate are open.                                                                                                                                                          |       |
| Cash Management Preferences<br>(CA102000) form  | Make sure that all necessary set<br>tings to use the cash management<br>functionality have been specified,<br>including the Cash-in-Transit ac<br>count.                                                                           |       |
| Cash Accounts (CA202000) form                   | Make sure that the necessary cash<br>accounts to record cash entries and<br>funds transfers have been created,<br>and that the necessary entry types<br>have been assigned to them.                                                |       |
| Payment Methods (CA204000) form                 | Make sure that the payment meth<br>ods to be used have been created<br>and have been defined to use the<br>proper accounts.                                                                                                        |       |
| Entry Types (CA203000) form                     | Make sure that the necessary entry<br>types for processing cash payments<br>have been created and assigned to<br>the related cash accounts.                                                                                        |       |
| Credit Terms (CS206500) form                    | Make sure that the needed credit<br>terms—those that are commonly<br>used by vendors in their relations<br>with your company, and those that<br>are used by your company in its re<br>lations with customers—have been<br>created. |       |
| Vendor Classes (AP201000) form                  | Make sure that the default vendor<br>class, which provides the default<br>values for vendor accounts and for<br>other vendor classes, has been cre<br>ated.                                                                        |       |
| Accounts Payable Preferences<br>(AP101000) form | Make sure that all necessary set<br>tings to use the accounts payable<br>functionality have been specified.                                                                                                                        |       |

| Form                                               | Things to Check                                                                                                                                                                                                   | Notes |
|----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Statement Cycles (AR202800) form                   | Make sure that the necessary state<br>ment cycles, which will later be<br>used to track customers' outstand<br>ing balances and send electronic<br>or printed statements to the cus<br>tomers, have been created. |       |
| Customer Classes (AR201000) form                   | Make sure that the default cus<br>tomer class, which provides the de<br>fault values for customer accounts<br>and for other customer classes, has<br>been created.                                                |       |
| Accounts Receivable Preferences<br>(AR101000) form | Make sure that all necessary set<br>tings to use the accounts receiv<br>able functionality have been speci<br>fied.                                                                                               |       |

#### *Table: Recommended Configuration*

The settings listed in the following table can be specified to simplify the process of creating entities in the system.

| Form                                           | Things to Check                                                            | Notes |
|------------------------------------------------|----------------------------------------------------------------------------|-------|
| General Ledger Preferences<br>(GL102000) form  | Make sure that the following set<br>tings have been specified:             |       |
|                                                | •<br>The Automatically Post on Re<br>lease check box is selected.          |       |
|                                                | •<br>The Hold Batches on Entry<br>check box is cleared.                    |       |
| Cash Management Preferences<br>(CA102000) form | Make sure that the following set<br>tings have been specified:             |       |
|                                                | •<br>The Automatically Post to GL<br>on Release check box is select<br>ed. |       |
|                                                | •<br>The Hold Transactions on En<br>try check box is cleared.              |       |
|                                                | •<br>The Require Document Ref.<br>Nbr. on Entry check box is<br>cleared.   |       |

| Form                                               | Things to Check                                                                                                                                                                                    | Notes |
|----------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Accounts Payable Preferences<br>(AP101000) form    | Make sure that the following set<br>tings have been specified:                                                                                                                                     |       |
|                                                    | •<br>The Automatically Post on Re<br>lease check box is selected.                                                                                                                                  |       |
|                                                    | •<br>A vendor class, which will be<br>used to provide default values<br>for vendor accounts (and for<br>other vendor classes), is select<br>ed in the Default Vendor Class<br>ID box.              |       |
|                                                    | •<br>The Hold Documents on Entry<br>check box is cleared.                                                                                                                                          |       |
|                                                    | •<br>The Require Approval of Bills<br>Prior to Payment check box is<br>cleared.                                                                                                                    |       |
|                                                    | •<br>The Validate Document Totals<br>on Entry check box is cleared.                                                                                                                                |       |
|                                                    | •<br>The Require Vendor Reference<br>check box is cleared.                                                                                                                                         |       |
| Accounts Receivable Preferences<br>(AR101000) form | Make sure that the following set<br>tings have been specified:                                                                                                                                     |       |
|                                                    | •<br>The Automatically Post on Re<br>lease check box is selected.                                                                                                                                  |       |
|                                                    | •<br>A customer class, which will be<br>used to provide default values<br>for customer accounts (and for<br>other customer classes), has<br>been selected in the Default<br>Customer Class ID box. |       |
|                                                    | •<br>The Hold Documents on Entry<br>check box is cleared.                                                                                                                                          |       |
|                                                    | •<br>The Validate Document Totals<br>on Entry check box is cleared.                                                                                                                                |       |
|                                                    | •<br>The Require Payment Ref<br>erence on Entry check box is<br>cleared.                                                                                                                           |       |

## <span id="page-41-0"></span>**Company with Branches that Require Balancing: Implementation Checklist**

You can use the tables in this topic to quickly check whether the configuration steps for a company with branches that require balancing are being performed in Acumatica ERP. The following tables cover both the mandatory configuration steps and the recommended configuration steps.

#### *Table: Mandatory Configuration*

To ensure that the basic configuration of a company has been implemented properly, make sure that the necessary features have been enabled and the needed entities have been created, as listed in the following table.

| Form                                           | Things to Check                                                                                                                                                                          | Notes |
|------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form     | Make sure that the Standard Fi<br>nancials group of features and the<br>Multibranch Support and Multicom<br>pany Support features have been<br>enabled.                                  |       |
| Companies (CS101500) form                      | Make sure that the necessary com<br>pany has been created with the<br>With Branches Requiring Balancing<br>type and that the necessary ledger<br>has been created and assigned to<br>it. |       |
| Branches (CS102000) form                       | Make sure that the branches of the<br>company have been created.                                                                                                                         |       |
| Chart of Accounts (GL202500) form              | Make sure that the necessary ac<br>counts for performing financial op<br>erations have been added.                                                                                       |       |
| General Ledger Preferences<br>(GL102000) form  | Make sure that all necessary set<br>tings to use the general ledger<br>functionality have been specified,<br>including the YTD Net Income and<br>Retained Earnings accounts.             |       |
| Financial Year (GL101000) form                 | Make sure that the first financial<br>year in which the company will op<br>erate has been added and the peri<br>ods have been generated.                                                 |       |
| Company Financial Calendar<br>(GL201100) form  | Make sure that the periods in which<br>the company will operate are open.                                                                                                                |       |
| Cash Management Preferences<br>(CA102000) form | Make sure that all necessary set<br>tings to use the cash management<br>functionality have been specified,<br>including the Cash-in-Transit ac<br>count.                                 |       |
| Cash Accounts (CA202000) form                  | Make sure that the necessary cash<br>accounts to record cash entries and<br>funds transfers have been created,<br>and that the necessary entry types<br>have been assigned to them.      |       |
| Payment Methods (CA204000) form                | Make sure that the payment meth<br>ods to be used have been created<br>and have been defined to use the<br>proper accounts.                                                              |       |

| Form                                               | Things to Check                                                                                                                                                                                                                    | Notes |
|----------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Entry Types (CA203000) form                        | Make sure that the necessary entry<br>types for processing cash payments<br>have been created and assigned to<br>the related cash accounts.                                                                                        |       |
| Credit Terms (CS206500) form                       | Make sure that the needed credit<br>terms—those that are commonly<br>used by vendors in their relations<br>with your company, and those that<br>are used by your company in its re<br>lations with customers—have been<br>created. |       |
| Vendor Classes (AP201000) form                     | Make sure that the default vendor<br>class, which provides the default<br>values for vendor accounts and for<br>other vendor classes, has been cre<br>ated.                                                                        |       |
| Accounts Payable Preferences<br>(AP101000) form    | Make sure that all necessary set<br>tings to use the accounts payable<br>functionality have been specified.                                                                                                                        |       |
| Statement Cycles (AR202800) form                   | Make sure that the necessary state<br>ment cycles, which will later be<br>used to track customers' outstand<br>ing balances and send electronic<br>or printed statements to the cus<br>tomers, have been created.                  |       |
| Customer Classes (AR201000) form                   | Make sure that the default cus<br>tomer class, which provides the de<br>fault values for customer accounts<br>and for other customer classes, has<br>been created.                                                                 |       |
| Accounts Receivable Preferences<br>(AR101000) form | Make sure that all necessary set<br>tings to use the accounts receiv<br>able functionality have been speci<br>fied.                                                                                                                |       |

#### *Table: Recommended Configuration*

The settings listed in the following table can be specified to simplify the process of creating entities in the system.

| Form                                          | Things to Check                                                                                                              | Notes |
|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|-------|
| General Ledger Preferences<br>(GL102000) form | Make sure that the following set<br>tings have been specified:                                                               |       |
|                                               | •<br>The Automatically Post on Re<br>lease check box is selected.<br>•<br>The Hold Batches on Entry<br>check box is cleared. |       |

| Form                                               | Things to Check                                                                                                                                                                                    | Notes |
|----------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Cash Management Preferences<br>(CA102000) form     | Make sure that the following set<br>tings have been specified:                                                                                                                                     |       |
|                                                    | •<br>The Automatically Post to GL<br>on Release check box is select<br>ed.                                                                                                                         |       |
|                                                    | •<br>The Hold Transactions on En<br>try check box is cleared.                                                                                                                                      |       |
|                                                    | •<br>The Require Document Ref.<br>Nbr. on Entry check box is<br>cleared.                                                                                                                           |       |
| Accounts Payable Preferences<br>(AP101000) form    | Make sure that the following set<br>tings have been specified:                                                                                                                                     |       |
|                                                    | •<br>The Automatically Post on Re<br>lease check box is selected.                                                                                                                                  |       |
|                                                    | •<br>A vendor class, which will be<br>used to provide default values<br>for vendor accounts (and for<br>other vendor classes), is select<br>ed in the Default Vendor Class<br>ID box.              |       |
|                                                    | •<br>The Hold Documents on Entry<br>check box is cleared.                                                                                                                                          |       |
|                                                    | •<br>The Require Approval of Bills<br>Prior to Payment check box is<br>cleared.                                                                                                                    |       |
|                                                    | •<br>The Validate Document Totals<br>on Entry check box is cleared.                                                                                                                                |       |
|                                                    | •<br>The Require Vendor Reference<br>check box is cleared.                                                                                                                                         |       |
| Accounts Receivable Preferences<br>(AR101000) form | Make sure that the following set<br>tings have been specified:                                                                                                                                     |       |
|                                                    | •<br>The Automatically Post on Re<br>lease check box is selected.                                                                                                                                  |       |
|                                                    | •<br>A customer class, which will be<br>used to provide default values<br>for customer accounts (and for<br>other customer classes), has<br>been selected in the Default<br>Customer Class ID box. |       |
|                                                    | •<br>The Hold Documents on Entry<br>check box is cleared.                                                                                                                                          |       |
|                                                    | •<br>The Validate Document Totals<br>on Entry check box is cleared.                                                                                                                                |       |
|                                                    | •<br>The Require Payment Ref<br>erence on Entry check box is<br>cleared.                                                                                                                           |       |

## <span id="page-45-0"></span>**Budget Management**

## <span id="page-45-1"></span>**Access to Budget Nodes: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for assigning access to budget nodes, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially assign access to budget nodes, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                 | Criteria to Check                                                                                                                                                                                                                                                                                             |
|--------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)   | Make sure that the Standard Financials and Row-Level<br>Security features have been enabled.                                                                                                                                                                                                                  |
| Multiple forms                       | Make sure that the minimum configuration of the com<br>pany has been performed, as described in Company<br>Without Branches: General Information, Company with<br>Branches that Do Not Require Balancing: General Infor<br>mation, and Company with Branches that Require Bal<br>ancing: General Information. |
| GL functionality                     | Make sure that the general ledger functionality has<br>been implemented, as described in General Ledger:<br>General Information.                                                                                                                                                                              |
| Ledgers (GL201500)                   | Make sure that the ledger to which the budget should<br>be posted has been created, as described in Budget<br>Ledger: General Information.                                                                                                                                                                    |
| Chart of Accounts (GL202500)         | Check whether the necessary accounts have been cre<br>ated.                                                                                                                                                                                                                                                   |
| Master Financial Calendar (GL201000) | Be sure that calendars for the financial years for which<br>budgets will be created have been generated.                                                                                                                                                                                                      |
| Budget Configuration (GL205000)      | Make sure that a budget tree has been created and re<br>leased as described in Budget Tree: Implementation Ac<br>tivity.                                                                                                                                                                                      |

#### **Additional Configuration**

The following table provides details of additional configuration needed for the preparation of a simple budget.

| Form           | Settings to Check                                                                                                                        | Notes |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Multiple forms | If your company uses subaccounts,<br>the subaccounts have to be config<br>ured, as described in Subaccounts:<br>Implementation Activity. |       |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you assign access to budget nodes by performing instructions similar to those described in *[Access to Budget Nodes:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5f2f3a4a-8200-4eb1-a137-5f462fac9d05) [Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5f2f3a4a-8200-4eb1-a137-5f462fac9d05)*.

## <span id="page-46-0"></span>**Budget Based on an Existing Budget: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for preparing a budget based on an uploaded budget, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially prepare a budget, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                 | Criteria to Check                                                                                                                                                                                                                                                                                             |
|--------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)   | Make sure that the Standard Financials feature has<br>been enabled.                                                                                                                                                                                                                                           |
| Multiple forms                       | Make sure that the minimum configuration of the com<br>pany has been performed, as described in Company<br>Without Branches: General Information, Company with<br>Branches that Do Not Require Balancing: General Infor<br>mation, and Company with Branches that Require Bal<br>ancing: General Information. |
| GL functionality                     | Make sure that the general ledger functionality has<br>been implemented, as described in General Ledger:<br>General Information.                                                                                                                                                                              |
| Ledgers (GL201500)                   | Make sure that the ledger to which the budget should<br>be posted has been created, as described in Budget<br>Ledger: General Information.                                                                                                                                                                    |
| Chart of Accounts (GL202500)         | Check whether the necessary accounts have been cre<br>ated.                                                                                                                                                                                                                                                   |
| Master Financial Calendar (GL201000) | Be sure that calendars for the financial years for which<br>budgets will be created have been generated.                                                                                                                                                                                                      |

| Form               | Criteria to Check                                                                                                    |
|--------------------|----------------------------------------------------------------------------------------------------------------------|
| Budgets (GL302010) | Make sure that a simple budget has been created and<br>released as described in Simple Budget: Process Activi<br>ty. |

#### **Additional Configuration**

The following table provides details of additional configuration needed for the preparation of a simple budget.

| Form           | Settings to Check                                                                                                                        | Notes |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Multiple forms | If your company uses subaccounts,<br>the subaccounts have to be config<br>ured, as described in Subaccounts:<br>Implementation Activity. |       |

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you prepare a budget based on an uploaded budget by performing instructions similar to those described in *[Budget Based on](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b2f38dbf-11b3-44b0-b0ae-f95231f04ee0) [an Existing Budget: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b2f38dbf-11b3-44b0-b0ae-f95231f04ee0)*.

## <span id="page-47-0"></span>**Budget vs Actual ARM Report: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for preparing and running an ARM report, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially prepare and run an ARM report, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Things to Check                                                                                                                                                                                                                                                                                                         | Notes |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Finan<br>cials feature has been enabled.                                                                                                                                                                                                                                                    |       |
| Multiple forms                     | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Com<br>pany Without Branches: General In<br>formation, Company with Branches<br>that Do Not Require Balancing: Gen<br>eral Information, and Company with<br>Branches that Require Balancing:<br>General Information. |       |

| Form                                    | Things to Check                                                                                                                                                                                            | Notes |
|-----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Ledgers (GL201500)                      | Make sure that the budget ledger<br>that will be used for the report con<br>figuration has been created, as de<br>scribed in Budget Ledger: General<br>Information.                                        |       |
| Master Financial Calendar<br>(GL201000) | Be sure that calendars for the fi<br>nancial years for which budgets will<br>be created have been generated.                                                                                               |       |
| Budget Configuration (GL205000)         | Make sure that the relevant bud<br>get structure has been configured,<br>as described in Budget Tree: Imple<br>mentation Activity.                                                                         |       |
| Budgets (GL302010)                      | Make sure that a hierarchical bud<br>get has been created, as described<br>in Conversion of a Simple Budget to<br>a Hierarchical Budget: Process Ac<br>tivity or Hierarchical Budget: Process<br>Activity. |       |

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you prepare and run an ARM report by performing instructions similar to those described in *[Budget vs. Actual ARM Report:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=75f7ba19-2c0b-47b1-81e7-4a9f6e10da01) [Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=75f7ba19-2c0b-47b1-81e7-4a9f6e10da01)*.

## <span id="page-48-0"></span>**Converting a Simple Budget to a Hierarchical Budget: Implementation Checklist**

The following table provides details you can use to ensure that the system is configured properly for the conversion of a simple budget to a hierarchical budget, and to understand (and change, if needed) the settings that affect the processing workflow.

| Form                               | Things to Check                                                                                                                                                                                                                                                                                                         | Notes |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Finan<br>cials feature has been enabled.                                                                                                                                                                                                                                                    |       |
| Multiple forms                     | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Com<br>pany Without Branches: General In<br>formation, Company with Branches<br>that Do Not Require Balancing: Gen<br>eral Information, and Company with<br>Branches that Require Balancing:<br>General Information. |       |

| Form                            | Things to Check                                                                                                                                | Notes                                                                                                                                                                                                                                       |
|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ledgers (GL201500)              | Make sure that the ledger to which<br>the budget should be posted has<br>been created, as described in Bud<br>get Ledger: General Information. |                                                                                                                                                                                                                                             |
| Budget Configuration (GL205000) | Make sure that the budget struc<br>ture has been configured, as de<br>scribed in Budget Tree: Implementa<br>tion Activity.                     |                                                                                                                                                                                                                                             |
| Budgets (GL302010)              | Make sure that in the budget that<br>you are going to convert,the masks<br>that are used are the same as in the<br>configured tree.            | If any mask for a single-level bud<br>get is split into multiple masks on<br>a tree or if multiple masks used<br>somewhere in the single-level bud<br>get are merged into a single mask<br>for the tree, the budget cannot be<br>converted. |

## **Other Settings That Affect the Workflow**

To cause some users to view only the budget nodes to which they are assigned access rights based on their roles, you perform the configuration described in *[Access to Budget Nodes: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5f2f3a4a-8200-4eb1-a137-5f462fac9d05)*.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you convert a simple budget to a hierarchical budget by performing instructions similar to those described in *[Conversion of a](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=33efb49a-6f55-464d-9376-a06012943ae8) [Simple Budget to a Hierarchical Budget: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=33efb49a-6f55-464d-9376-a06012943ae8)*.

## <span id="page-49-0"></span>**Hierarchical Budget: Implementation Checklist**

The following table provides details you can use to ensure that the system is configured properly for the preparation of a hierarchical budget, and to understand an additional configuration task that can affect the processing workflow.

| Form                                       | Things to Check                                                                                                                                                                                                                                                                                                         | Notes |
|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the Standard Finan<br>cials feature has been enabled.                                                                                                                                                                                                                                                    |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Com<br>pany Without Branches: General In<br>formation, Company with Branches<br>that Do Not Require Balancing: Gen<br>eral Information, and Company with<br>Branches that Require Balancing:<br>General Information. |       |

| Form                                         | Things to Check                                                                                                                                | Notes |
|----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Ledgers (GL201500) form                      | Make sure that the ledger to which<br>the budget should be posted has<br>been created, as described in Bud<br>get Ledger: General Information. |       |
| Chart of Accounts (GL202500) form            | Check whether the necessary ac<br>counts have been created.                                                                                    |       |
| Master Financial Calendar<br>(GL201000) form | Be sure that calendars for the fi<br>nancial years for which budgets will<br>be created have been generated.                                   |       |
| Budget Configuration (GL205000)<br>form      | Make sure that the relevant bud<br>get structure has been configured,<br>as described in Budget Tree: Imple<br>mentation Activity.             |       |

## **Configuration Tasks That Can Affect the Processing Workflow**

If your company uses subaccounts, the *Subaccounts* feature has to be enabled on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form. In this case, make sure that the budget structure has all account-subaccount pairs that are used for budgeting on the *[Budget Configuration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=9f69e979-e7fd-4c8d-964f-3a75e86e4e43)* (GL205000) form.

## <span id="page-50-0"></span>**Modifying a Hierarchical Budget: Implementation Checklist**

The following table provides details you can use to ensure that the system is configured properly for the modification of a hierarchical budget, and to understand an additional configuration task that can affect the processing workflow.

| Form                               | Things to Check                                                                                                                                                                                                                                                                                                         | Notes |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Finan<br>cials feature has been enabled.                                                                                                                                                                                                                                                    |       |
| Multiple forms                     | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Com<br>pany Without Branches: General In<br>formation, Company with Branches<br>that Do Not Require Balancing: Gen<br>eral Information, and Company with<br>Branches that Require Balancing:<br>General Information. |       |
| Ledgers (GL201500)                 | Make sure that the ledger to which<br>the budget should be posted has<br>been created, as described in Bud<br>get Ledger: General Information.                                                                                                                                                                          |       |

| Form                                    | Things to Check                                                                                                                                                                                            | Notes |
|-----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Chart of Accounts (GL202500)            | Check whether the necessary ac<br>counts have been created.                                                                                                                                                |       |
| Master Financial Calendar<br>(GL201000) | Be sure that calendars for the fi<br>nancial years for which budgets will<br>be created have been generated.                                                                                               |       |
| Budget Configuration (GL205000)         | Make sure that the relevant bud<br>get structure has been configured,<br>as described in Budget Tree: Imple<br>mentation Activity.                                                                         |       |
| Budgets (GL302010)                      | Make sure that a hierarchical bud<br>get has been created, as described<br>in Conversion of a Simple Budget to<br>a Hierarchical Budget: Process Ac<br>tivity or Hierarchical Budget: Process<br>Activity. |       |

#### **Configuration Tasks That Can Affect the Processing Workflow**

If your company uses subaccounts, the *Subaccounts* feature has to be enabled on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form. In this case, make sure that the budget structure has all account-subaccount pairs that are used for budgeting on the *[Budget Configuration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=9f69e979-e7fd-4c8d-964f-3a75e86e4e43)* (GL205000) form.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you modify a hierarchical budget by performing instructions similar to those described in *[Modification of a Hierarchical Budget:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=67a922e9-3756-4854-bf0d-429ac1a620dc) [Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=67a922e9-3756-4854-bf0d-429ac1a620dc)*.

## <span id="page-51-0"></span>**Revising a Budget: Implementation Checklist**

The following table provides details you can use to ensure that the system is configured properly for the revising of a budget.

| Form                                       | Things to Check                                                                                                                                           | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the Standard Finan<br>cials feature has been enabled.                                                                                      |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |

| Form                    | Things to Check                                                                                                                                                                                       | Notes |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Budgets (GL302010) form | Make sure the budgets whose data<br>is going to be modified have been<br>uploaded to the system. For de<br>tails, see Simple Budget: Process<br>Activity or Hierarchical Budget:<br>Process Activity. |       |

## <span id="page-52-0"></span>**Simple Budget: Implementation Checklist**

The following tables provide details you can use to ensure that the system is configured properly for the preparation of a simple budget.

| Form                                    | Things to Check                                                                                                                                                                                                                                                                                                         | Notes |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)      | Make sure that the Standard Finan<br>cials feature has been enabled.                                                                                                                                                                                                                                                    |       |
| Multiple forms                          | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Com<br>pany Without Branches: General In<br>formation, Company with Branches<br>that Do Not Require Balancing: Gen<br>eral Information, and Company with<br>Branches that Require Balancing:<br>General Information. |       |
| GL functionality                        | Make sure that the general ledger<br>functionality has been implement<br>ed, as described in General Ledger:<br>General Information.                                                                                                                                                                                    |       |
| Ledgers (GL201500)                      | Make sure that the ledger to which<br>the budget should be posted has<br>been created, as described in Bud<br>get Ledger: General Information.                                                                                                                                                                          |       |
| Chart of Accounts (GL202500)            | Check whether the necessary ac<br>counts have been created.                                                                                                                                                                                                                                                             |       |
| Master Financial Calendar<br>(GL201000) | Be sure that calendars for the fi<br>nancial years for which budgets will<br>be created have been generated.                                                                                                                                                                                                            |       |

## **Additional Configuration**

The following table provides details of additional configuration needed for the preparation of a simple budget.

| Form           | Settings to Check                                                                                                                        | Notes |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Multiple forms | If your company uses subaccounts,<br>the subaccounts have to be config<br>ured, as described in Subaccounts:<br>Implementation Activity. |       |

## <span id="page-54-2"></span><span id="page-54-0"></span>**Cash Management**

## <span id="page-54-1"></span>**Bank Reconciliation: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for reconciling cash accounts with bank statements, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially perform bank reconciliation, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Tasks to Perform                                                                                                                                                                 | Note                                                                                                                                                                                                              |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features<br>(CS100000) form | Make sure that the following feature has<br>been enabled: Standard Financials.                                                                                                   |                                                                                                                                                                                                                   |
| Chart of Accounts (GL202500)<br>form       | Check whether the necessary accounts<br>have been created. For details, see Gener<br>al Ledger: Chart of Accounts.                                                               |                                                                                                                                                                                                                   |
| Cash Accounts (CA202000) form              | Check whether the necessary cash ac<br>counts have been configured.                                                                                                              | You need to configure a cash<br>account only when you perform<br>the reconciliation for the first<br>time.                                                                                                        |
| Cash Management Preferences<br>(CA101000)  | On the Bank Statement Settings tab in<br>the Import Settings section, make sure<br>that PX.Objects.CA.OFXStatementReader<br>is selected in the Statement Import Ser<br>vice box. | This setting is required for pro<br>cessing a bank statement in<br>Open Financial Exchange (OFX)<br>format, which you can do in<br>Bank Reconciliation: To Process<br>a Bank Statement in OFX Format<br>(Part 1). |

## **Other Settings That Affect the Workflow**

You can affect the workflow of bank reconciliation by specifying additional settings on the *[Cash Management](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b)* (CA101000) form as follows:

- To cause cash transactions to be automatically posted to the general ledger once they are released, make sure that the **Automatically Post to GL on Release** check box is selected in the **Posting and Release Settings** section on the **General** tab.
- To cause the system to assign the *On Hold* status to the created cash transactions, make sure that the **Hold Transactions on Entry** check box in the **Data EntrySettings** section on the **General** tab is selected.

If you want data to be imported on the *Import Bank [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=107c97e9-476d-403e-9a9e-8a2716855d14)* (CA306500) form only aer a user selects the applicable cash account, on the **BankStatements** tab of the *[Cash Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b)* form, you should also select the **Import BankStatement toSingle Cash Account** check box.

If you want the system to automatically update the date of an unreleased AR or AP payment document to the bank transaction date when bank transactions are processed on the *Process Bank [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5266e9a7-81af-4153-9907-3881fc710792)* (CA306000) form, you

should select the**Set Payment Date to BankTransaction Date** check box on the *[Payment Methods](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6)* (CA204000) form for the payment method that is specified for the document. You should clear this check box if for this payment method, the **Integrated Processing** check box is selected on the**Settings to Use in AR** tab of the form.

#### **Testing of Settings**

To make sure that all configuration has been performed correctly, we recommend that you test the performing of bank reconciliations by performing similar steps to those described in *Bank [Reconciliation:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c5e018e0-46db-4f21-802d-5ce13b5c5ded) To Reconcile a Cash [Account](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c5e018e0-46db-4f21-802d-5ce13b5c5ded)* and *Bank [Reconciliation:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=61c25905-e211-4bfa-b4b3-0751c1428712) To Process a Bank Statement in OFX Format (Part 1)*.

## <span id="page-55-0"></span>**Cash Entries: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for creating cash entries, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially create cash entries, you make sure the needed features have been enabled, settings have been specified, and entities have been created as summarized in the following checklist.

| Form                               | Tasks to Perform                                                                                                                                                                                                                                                                 | Note |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |      |
| Cash Accounts (CA202000)           | Make sure the cash accounts used to record<br>cash entries and funds transfers have been<br>created as described in Cash Management:<br>Cash Accounts.                                                                                                                           |      |
| Entry Types (CA203000)             | Make sure that the necessary entry types have<br>been defined as described in Cash Manage<br>ment: Entry Types.                                                                                                                                                                  |      |

## **Settings That Affect the Workflow**

If the following settings are specified on the *[Cash Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b)* (CA101000) form, they can affect the workflow of creating and processing a cash entry as follows:

- You can select the **Hold Transactions on Entry** check box in the **Data EntrySettings** section to create cash transactions with the *On Hold* status by default. If this check box is selected, you can remove a cash entry from hold by clicking **Remove Hold** for the cash entry on the relevant form.
- You can select the **Automatically Post to GL on Release** check box in the **Posting and ReleaseSettings** section. If this check box is selected, when you release a cash entry, the system generates a batch and automatically posts it to the general ledger. If the check box is cleared, on release of a cash entry, the system generates a batch, but instead of immediately posting it to the general ledger, it saves the batch with *Unposted* status. You can post the batch with the *Unposted* status manually on the *Post [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dce8c656-0c7f-4bb9-af68-e9432317964c)* (GL502000) form.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you create a cash entry by performing similar steps to those described in *Cash Entries: To Create a [Disbursement](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=3dfdf2a0-df63-4df4-b044-bad499c64e90) Cash Entry* and *Cash [Entries:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f5bc12-e916-432a-8624-408b5ff3739a) To Create a [Receipt Cash Entry](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f5bc12-e916-432a-8624-408b5ff3739a)*.

## <span id="page-56-0"></span>**Funds Transfers: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing funds transfers, and to understand (and change, if needed) the settings that affect the workflow of funds transfers processing.

## **Implementation Checklist**

We recommend that before you initially perform funds transfers, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                     | Tasks to Perform                                                                               | Note                                                                                               |
|------------------------------------------|------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)       | Make sure that the Standard Finan<br>cials feature has been enabled                            |                                                                                                    |
| Chart of Accounts (GL202500)             | Check whether the necessary ac<br>counts have been created.                                    |                                                                                                    |
| Cash Accounts (CA202000)                 | Check whether the necessary cash<br>accounts have been configured.                             |                                                                                                    |
| Company Financial Calendar<br>(GL201100) | Make sure that the periods during<br>which funds transfers may occur<br>have a status of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form.   |
|                                          |                                                                                                | For details on opening financial pe<br>riods, see Opening Financial Peri<br>ods: Process Activity. |

#### **Other Settings That Affect the Workflow**

The following settings on the *[Cash Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b)* (CA101000) form can affect the processing workflow:

- If the **Automatically Post to GL on Release** check box is selected, the system posts transactions to the general ledger when cash management documents are released. If this check box is cleared, you have to post the batch aer you release the document.
- If the **Hold Transactions on Entry** check box is selected in the **Data EntrySettings** section, when new transactions and funds transfers are entered, they are assigned the *On Hold* status. If the **Hold Transactions on Entry** check box is cleared, the transactions and funds transfers are assigned the *Balanced* status.
- If the **Require Document Ref. Nbr. on Entry** check box is selected, you must fill in the **Document Ref.** box on the *Funds [Transfers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=814c5c8d-45bc-4e4d-98df-1b6785defc6c)* (CA301000) form for new funds transfers. If this check box is cleared, you can decide whether to leave the **Document Ref.** box blank or fill it in.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you perform funds transfers by performing similar steps to those described in *Funds [Transfers:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0ceddeea-ec98-4631-9e45-4851b0ae47a5) Process Activity*.

## <span id="page-57-0"></span>**Intercompany Funds Transfers: Implementation Checklist**

Before users begin processing funds transfers between companies, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                            | Settings to Check                                                                                                                                          | Notes                                                                                            |
|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form      | Make sure that the following fea<br>tures have been enabled:                                                                                               |                                                                                                  |
|                                                 | •<br>Standard Financials<br>•<br>Multibranch Support<br>•<br>Multicompany Support<br>•<br>Advanced Financials<br>•<br>Inter-Branch Transactions            |                                                                                                  |
| Multiple forms                                  | Make sure that the minimum con<br>figuration of the companies has<br>been performed.                                                                       |                                                                                                  |
| Cash Accounts(CA202000) form                    | Check whether the necessary cash<br>accounts have been created, as de<br>scribed in Cash Management: To<br>Create Cash Accounts.                           |                                                                                                  |
| Inter-Branch Account Mapping<br>(GL101010) form | Be sure that the account mapping<br>rules have been defined for the<br>companies, as described in Inter<br>branch Account Mapping: General<br>Information. |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form   | Make sure that the periods during<br>which funds transfers may occur<br>have a status of Open.                                                             | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

#### **Settings That Can Affect the Processing Workflow**

The following settings on the *[Cash Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b)* (CA101000) form can affect the processing workflow:

- If the **Automatically Post to GL on Release** check box is selected, the system posts transactions to the general ledger when cash management documents are released. If this check box is cleared, you have to post the batch aer you release the document.
- If the **Hold Transactions on Entry** check box is selected in the **Data EntrySettings** section, when new transactions and funds transfers are entered, they are assigned the *On Hold* status. If the **Hold Transactions on Entry** check box is cleared, the transactions and funds transfers are assigned the *Balanced* status.

• If the **Require Document Ref. Nbr. on Entry** check box is selected, you must fill in the **Document Ref.** box on the *Funds [Transfers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=814c5c8d-45bc-4e4d-98df-1b6785defc6c)* (CA301000) form for new funds transfers. If this check box is cleared, you can leave the **Document Ref.** box blank.

## <span id="page-59-0"></span>**Customer Relationship Management**

## <span id="page-59-1"></span>**Case Assignment to Owners and Workgroups: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for assigning cases to owners and workgroups, and to understand (and change, if needed) the settings that affect the case assignment workflow.

## **Mandatory Configuration**

We recommend that before you start assigning cases to owners, you make sure that the needed features have been enabled and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:<br>•<br>Customer Management: This feature provides the customer<br>relationship management (CRM) functionality.<br>•<br>Case Management in the Customer Management group of<br>features: This feature gives customer support personnel the<br>ability to create support cases, assign cases to owners, and<br>process cases. |
| Case Classes (CR206000)            | Case classes have been created with the necessary settings and<br>attributes, as described in Defining Case Classes.                                                                                                                                                                                                                                                   |

#### *Table: Configuration of a Case Assignment Map*

If users will be assigning cases to owners and workgroups by using assignment maps, you should configure a case assignment map, which involves the required tasks listed below (which should be performed in the listed order).

| Form                                          | Required Task                                                                                                                     |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Employees (EP203000)                          | Employee records have been created in the system.                                                                                 |
| Company Tree (EP204061)                       | The needed departments, workgroups, and employees have<br>been added to the company tree.                                         |
| Assignment Maps (EP205010)                    | A case assignment map has been created and it is properly con<br>figured.                                                         |
| Customer Management Preferences<br>(CR101000) | A case assignment map has been specified in the Case Assign<br>ment Map box on the General tab (Assignment Settings sec<br>tion). |

## **Other Settings That Affect the Workflow**

You can include the sending of email notifications in the case assignment workflow. If you want email notifications to be sent to the responsible employees when a case is assigned to an employee or when the status of the case is changed, an administrator can set up email or push notifications on the *[Business Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d83a15de-e962-4b94-9f5f-51f501a96b47)* (SM302050) form so that

the employee receives a notification by email, by SMS, or in the Acumatica mobile app. For details, see *[Business](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=920e13d8-387c-404f-8b33-c200ac66df98) [Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=920e13d8-387c-404f-8b33-c200ac66df98)*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you practice assigning cases to owners by performing instructions similar to those described in *[Case Assignment to Owners and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f6c9aa73-8216-4946-9245-0dc7af0cbcda) [Workgroups: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f6c9aa73-8216-4946-9245-0dc7af0cbcda)*.

## <span id="page-60-0"></span>**Lead Assignment to Owners and Workgroups: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for assigning leads to owners, and to understand (and change, if needed) the settings that affect the lead assignment workflow.

## **Implementation Checklist**

We recommend that before you start assigning leads to owners, you make sure that the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                                                                             |
|--------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | The Customer Management feature has been enabled:<br>This feature provides the customer relationship man<br>agement (CRM) functionality, including lead and cus<br>tomer tracking, and also gives users the ability to man<br>age sales opportunities, contacts, marketing lists, and<br>marketing campaigns. |
| Assignment Maps (EP205010)                 | If you will be assigning leads to owners by using as<br>signment maps, a lead assignment map has been cre<br>ated and it is properly configured.                                                                                                                                                              |
| Customer Management Preferences (CR101000) | An assignment map is specified in the Lead Assign<br>ment Map box on the General tab.                                                                                                                                                                                                                         |
| Company Tree (EP204061)                    | The needed departments or workgroups have been<br>added to the company tree.                                                                                                                                                                                                                                  |
| Employees (EP203000)                       | Employee records have been created in the system.                                                                                                                                                                                                                                                             |
| Users (SM201010)                           | User profiles have been created for employees.                                                                                                                                                                                                                                                                |
| Lead Classes (CR207000)                    | Lead classes have been created with the necessary set<br>tings and attributes, including Default Owner on the<br>Details tab (Data Entry Settings section).                                                                                                                                                   |

## **Other Settings That Affect the Lead Assignment Workflow**

You can affect the lead assignment workflow by specifying additional settings in the system, as follows. If you want email notifications to be sent to the responsible employees when a lead is assigned to an employee or when the status of the lead is changed, an administrator can set up email or push notifications on the *[Business Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d83a15de-e962-4b94-9f5f-51f501a96b47)*

(SM302050) form so that the employee receives a notification by email, by SMS, or in Acumatica mobile app. For details, see *[Business Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=920e13d8-387c-404f-8b33-c200ac66df98)*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you practice assigning leads to owners by performing instructions similar to those described in *[Lead Assignment to Owners and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4fed4813-66a9-41e6-b1e1-3af746d7ca61) [Workgroups: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4fed4813-66a9-41e6-b1e1-3af746d7ca61)*.

## <span id="page-61-0"></span>**Opportunity Assignment to Owners and Workgroups: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for assigning opportunities to owners, and to understand (and change, if needed) the settings that affect the opportunity assignment workflow.

#### **Implementation Checklist**

We recommend that before you start assigning opportunities to owners, you make sure that the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                          |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | The Customer Management feature has been enabled:<br>This feature provides the customer relationship man<br>agement (CRM) functionality, including lead and cus<br>tomer tracking, and gives users the ability to man<br>age sales opportunities, contacts, marketing lists, and<br>marketing campaigns.                                                                                   |
| Assignment Maps (EP205010)                 | If you will be assigning opportunities to owners by us<br>ing assignment maps, an opportunity assignment map<br>has been created and properly configured.                                                                                                                                                                                                                                  |
| Customer Management Preferences (CR101000) | If you will be assigning opportunities to owners by us<br>ing assignment maps and you will be using the Assign<br>Opportunities (CR503110) mass-processing form to as<br>sign owners to existing opportunities without owners<br>according to this map, an assignment map has been<br>specified in the Opportunity Assignment Map box on<br>the General tab (Assignment Settings section). |
| Company Tree (EP204061)                    | The needed departments or workgroups have been<br>added to the company tree.                                                                                                                                                                                                                                                                                                               |
| Employees (EP203000)                       | Employee records have been created in the system.                                                                                                                                                                                                                                                                                                                                          |
| Opportunity Classes (CR209000)             | Opportunity classes have been created with the neces<br>sary settings and attributes, including Default Owner<br>on the Details tab (Data Entry Settings section).                                                                                                                                                                                                                         |

#### **Other Settings That Affect the Workflow**

You can affect the opportunity assignment workflow by including the sending of email notifications. If you want email notifications to be sent to the responsible employees when an opportunity is assigned to an employee or when the status of the opportunity is changed, an administrator can set up email or push notifications on the *[Business Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d83a15de-e962-4b94-9f5f-51f501a96b47)* (SM302050) form so that the employee receives a notification by email, by SMS, or in Acumatica mobile app. For details, see *[Business Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=920e13d8-387c-404f-8b33-c200ac66df98)*.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you practice assigning opportunities to owners by performing instructions similar to those described in *[Opportunity Assignment](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2b5ff479-b8f1-4a60-8273-0a838e6df7fe) [to Owners and Workgroups: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2b5ff479-b8f1-4a60-8273-0a838e6df7fe)*.

## <span id="page-62-0"></span>**Configuring CRM Functionality: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the customer relationship management (CRM) functionality in Acumatica ERP, and to specify settings that affect the CRM workflows.

## **Mandatory Configuration**

To ensure that the basic CRM configuration has been implemented properly, make sure that the necessary features have been enabled and settings have been specified, as described in the following checklist.

| Form                                          | Criteria to Check                                                                                                                                                                                                                                                                                                                           |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Multiple forms                                | The following tasks have been performed:                                                                                                                                                                                                                                                                                                    |
|                                               | 1. The initial configuration of the instance has been performed,<br>as described in Preparing an Instance for Implementation                                                                                                                                                                                                                |
|                                               | 2. The minimum company settings have been specified and<br>at least the minimum required functionality has been im<br>plemented for all other functional areas to be integrated<br>with the CRM functionality as described in Company Without<br>Branches: General Information<br>3. The system email accounts to be used for CRM have been |
|                                               | configured, as described in System Email Accounts.                                                                                                                                                                                                                                                                                          |
| Enable/Disable Features (CS100000)            | The Customer Management feature has been enabled. This fea<br>ture provides the customer relationship management function<br>ality, including lead and customer tracking, as well as the han<br>dling of sales opportunities, contacts, marketing lists, and mar<br>keting campaigns.                                                       |
| Customer Management Preferences<br>(CR101000) | The predefined settings in the Numbering Sequences section<br>of the General tab have been saved.                                                                                                                                                                                                                                           |

#### *Table: Recommended Configuration*

To give users the abilities to validate leads, contacts, and business accounts for duplicates, use the automatic processing of documents, use the integration with web map services, and group records that share common characteristics, you should specify and save the recommended settings listed in the following table.

| Form                                          | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)            | The following features have been enabled:                                                                                                                                                                                                                                                                                                                                                                                                                                |
|                                               | •<br>Duplicate Validation in the Customer Management group of<br>features: Provides the duplicate validation functionality,<br>which you can use to set up and perform automatic validation<br>of lead and contact records for duplicates. For an example of<br>configuration, see Duplicate Validation.                                                                                                                                                                 |
|                                               | •<br>Sales Quotes in the Customer Management group of features:<br>Gives you the ability to create opportunity-based sales quotes,<br>send them to customers for review, and create sales orders<br>and invoices based on these quotes.                                                                                                                                                                                                                                  |
|                                               | •<br>Address Lookup Integration in the Customer Management<br>group of features: Gives you the ability to use the address en<br>richment functionality. With this feature enabled, integration<br>with a web map service can be set up, and you can add new<br>addresses, update existing addresses, and fill in the missing<br>address information on the forms that have address informa<br>tion. For details, see Integrating Acumatica ERP with Web Map<br>Services. |
|                                               | •<br>Scheduled Processing in the Monitoring & Automation group of<br>features: Gives you the ability to create schedules for the au<br>tomatic processing of documents. For details, see Scheduling<br>Automated Processing.                                                                                                                                                                                                                                             |
| Lead Classes (CR207000)                       | Lead classes with the necessary details and attributes have been<br>created.                                                                                                                                                                                                                                                                                                                                                                                             |
| Contact Classes (CR205000)                    | Contact classes with the necessary details and attributes have<br>been created.                                                                                                                                                                                                                                                                                                                                                                                          |
| Business Account Classes (CR208000)           | Business account classes with the necessary details and attrib<br>utes have been created.                                                                                                                                                                                                                                                                                                                                                                                |
| Campaign Classes (CR202500)                   | Campaign classes with the necessary details and attributes have<br>been created.                                                                                                                                                                                                                                                                                                                                                                                         |
| Opportunity Classes (CR209000)                | Opportunity classes with the necessary details and attributes<br>have been created.                                                                                                                                                                                                                                                                                                                                                                                      |
| Customer Management Preferences<br>(CR101000) | On the General tab (Data Entry Settings) section, numbering<br>sequences have been saved and classes with the necessary set<br>tings have been specified.                                                                                                                                                                                                                                                                                                                |

## <span id="page-64-0"></span>**Duplicate Validation: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for duplicate validation in Acumatica ERP, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Mandatory Configuration**

We recommend that before you start validating records for duplicates, you make sure that the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                                                                                                                                    |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | The following features have been enabled:                                                                                                                                                                                                                                                                                                                            |
|                                            | •<br>Customer Management: Provides the customer relationship<br>management (CRM) functionality, including lead and cus<br>tomer tracking, as well as the handling of sales opportuni<br>ties, contacts, marketing lists, and campaigns<br>•<br>Duplicate Validation in the Customer Management group of<br>features: Provides the duplicate validation functionality |
| Customer Management Preferences (CR101000) | The numbering sequence settings have been specified and<br>saved to the system, as described in Basic Customer Relation<br>ship Management.                                                                                                                                                                                                                          |
| Duplicate Validation (CR103000)            | The duplicate validation settings have been specified.                                                                                                                                                                                                                                                                                                               |

#### **Recommended Configuration**

To speed duplicate validation and minimize errors, you should specify and save the recommended settings listed in the following table.

| Form                            | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Duplicate Validation (CR103000) | The Validate on Entry check box is selected for each com<br>bination of record types on the Comparison pane. With this<br>check box selected, the system will validate each new lead,<br>contact, or business account when a new record is being cre<br>ated and saved for the first time on the Leads (CR301000),<br>Contacts (CR302000), or Business Accounts (CR303000) form. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of duplicate validation by specifying additional settings:

• To cause the system to perform duplicate validation processing more quickly—validating records and calculating grams is handled in parallel mode and may be a time-consuming process—add the following key to the web.config file located in the website folder.

```
<add key="ParallelProcessingDisabled" value="False" />
```

- To cause the system to validate the field values of each new lead, contact, or business account—such as an email address or phone number—for duplication as soon as a user specifies these settings on the *[Leads](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ce564fa0-baca-4d9b-97a8-ec69910de4c2)* (CR301000), *[Contacts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=75a5dea9-d640-4b71-95b1-88534c4afad7)* (CR302000), or *[Business Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=823f9e2c-d352-4cf4-bbb9-ce6464fecc75)* (CR303000) form and tries to save the record for the first time, select the *Warn* option for these fields in the **Create on Entry** column of the *Duplicate [Validation](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=aa7a410b-514b-41ed-9694-e961a9277368)* (CR103000) form.
- To cause the system to prevent the creation of duplicate leads on the *[Leads](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ce564fa0-baca-4d9b-97a8-ec69910de4c2)* form, duplicate contacts on the *[Contacts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=75a5dea9-d640-4b71-95b1-88534c4afad7)* form, or duplicate business accounts on the *[Business Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=823f9e2c-d352-4cf4-bbb9-ce6464fecc75)* form, select the *Block* option for each needed field in the **Create on Entry** column of the corresponding table on the *Duplicate [Validation](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=aa7a410b-514b-41ed-9694-e961a9277368)* form.
- To cause the system to calculate validation scores according to the duplicate validation rules specified for the pairs of records on the *Duplicate [Validation](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=aa7a410b-514b-41ed-9694-e961a9277368)* form and to keep the missing scores for empty fields, clear the **NormalizeValidation Scores** check box on the **General** tab (**MiscellaneousSettings** section) of the *[Customer Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=63aa74fa-81fd-4d62-85ac-c6b845ab1ac0)* (CR101000) form.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you configure duplicate validation by performing instructions similar to those described in *Duplicate [Validation:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=78e7ee6f-6947-4ac7-8147-50fd8ba1b632) [Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=78e7ee6f-6947-4ac7-8147-50fd8ba1b632)*.

## <span id="page-65-0"></span>**Emails and Activities: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for tracking communication with your potential and existing customers, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you start tracking communication with your potential and existing customers, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                                                               |
|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | The Customer Management has been enabled. This<br>feature provides the customer relationship manage<br>ment (CRM) functionality, including lead and customer<br>tracking, and gives users the ability to manage sales<br>opportunities, contacts, marketing lists, and market<br>ing campaigns. |
| Customer Management Preferences (CR101000) | All the necessary settings have been specified.                                                                                                                                                                                                                                                 |
| Lead Classes (CR207000)                    | Lead classes with the necessary details and attributes<br>have been created.                                                                                                                                                                                                                    |
| Leads (CR301000)                           | Leads that belong to the necessary classes have been<br>added to the system.                                                                                                                                                                                                                    |
| Employees (EP203000)                       | Employee records have been created in the system.                                                                                                                                                                                                                                               |

| Form                      | Criteria to Check                                                                                                                                          |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Users (SM201010)          | Users have been created for employees.                                                                                                                     |
| Email Accounts (SM204002) | A system email account has been configured.                                                                                                                |
| Event Setup (EP204070)    | The system-wide settings have been specified to pre<br>pare the system to send automatic notifications by us<br>ing the built-in notification capabilities |

## **Assignment Notification Settings**

You may want to activate the notification of activity and task assignment by sending email notifications to the responsible employees, which are defined depending on what specific event has happened. These notification capabilities include the following scenarios:

- You can send a notification to the owner of a new activity or task when a creator of the new activity or task is not the owner.
- You can send a notification to the owner of a related entity when one of the following events for which the owner is not the creator has happened:
  - An activity or task has been created for the related entity and assigned to another user.
  - An existing activity or task associated with the related entity has been reassigned to another user.
  - An existing activity or task has been recently associated with the related entity for which the employee is the owner, and assigned to another user.

An administrator can set up the email notifications on the *[Business Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d83a15de-e962-4b94-9f5f-51f501a96b47)* (SM302050) form. For details, see *[Business Events](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=920e13d8-387c-404f-8b33-c200ac66df98)*.

## **Validation of Configuration**

To make sure that all settings are configured correctly, we recommend that you practice communicating with the leads by performing instructions similar to those described in the following topics:

- *Emails and [Activities:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=28e5d1a5-065c-482f-ae9a-db31fd963c4a) To Create an Email*
- *Emails and [Activities:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=3b77010b-7dc2-4b97-9ef3-5c4bcf41f461) To Create an Event*
- *Emails and [Activities:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d7d48c72-60e2-4a9a-9167-4c7de00bae11) To Track a Phone Call*
- *Emails and [Activities:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b4040799-f2e5-402d-98b2-c22376163699) To Create a Task*

## <span id="page-66-0"></span>**Case Management: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for managing cases, and to understand (and change, if needed) the settings that affect the workflow of case management.

## **Mandatory Configuration**

To ensure that the basic CRM configuration for managing cases has been implemented properly, make sure that the necessary features have been enabled, entities have been created, and settings have been specified, as described in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                          |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | The following features have been enabled:                                                                                                                                                                  |
|                                            | •<br>Customer Management: This feature provides the<br>customer relationship management (CRM) func<br>tionality.                                                                                           |
|                                            | •<br>Case Management in the Customer Management<br>group of features: This feature gives customer sup<br>port personnel the ability to create support cases,<br>assign cases to owners, and process cases. |
| Case Classes (CR206000)                    | The needed case classes have been created with the<br>necessary settings and attributes, as described in<br>Defining Case Classes.                                                                         |
| Customer Management Preferences (CR101000) | On the General tab (Data Entry Settings section), in<br>the Default Case Class box, the default case class, that<br>is, the case class that will be used for most cases.                                   |
| Employee Classes (EP202000)                | The needed employee classes have been created with<br>the necessary settings and attributes.                                                                                                               |
| Employees (EP203000)                       | Employee records have been created in the system.                                                                                                                                                          |
| Users (SM201010)                           | User profiles have been created for employees.                                                                                                                                                             |

## **Recommended Configuration**

You should specify and save the recommended settings, which are listed in the following table, to give users the ability to bill customers for cases and for the time that the support team has spent on processing the case, based on the released activities, and to send emails to customers and the support team.

| Form                               | Criteria to Check                                                                                                                                                                                                              |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:                                                                                                                                                                                      |
|                                    | •<br>Scheduled Processing (under the Monitoring & Automation<br>group of features): This feature gives you the ability to cre<br>ate schedules for the automatic processing of documents, in<br>cluding the sending of emails. |
|                                    | •<br>Time Management: This feature gives you the ability to track<br>the time your organization's employees spend on activities<br>that can be included in time cards.                                                         |
| Email Accounts (SM204002)          | A system email account has been configured, as described in<br>Configuring Email Accounts.                                                                                                                                     |
| Business Events (SM302050)         | A business event that causes the system to send emails to cus<br>tomers has been created.                                                                                                                                      |
| Email Templates (SM204003)         | A notification template that is a subscriber for the business<br>event has been created.                                                                                                                                       |

| Form                            | Criteria to Check                                                                                                                |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| Automation Schedules (SM205020) | A schedule for the sending of emails has been created, as de<br>scribed in Managing Emails.                                      |
| Non-Stock Items (IN202000)      | The required non-stock items of the Labor type with needed set<br>tings have been created, as described in Creating Labor Items. |
| Labor Rates (PM209900)          | The cost rates that are specific to particular labor items have<br>been created, as described in Creating Labor Items.           |
| Attributes (CS205000)           | Attributes have been created with the necessary settings.                                                                        |
| Cases (CR306000)                | The User-Defined Fields tab, which holds the values of attribut<br>es required by your company for cases, has been added.        |
| Earning Types (EP102000)        | If you will be using the Per Activity billing mode, the needed<br>earning types that are used in activities have been created.   |
|                                 | A predefined set of earning types has been created<br>in the system. You can modify this set as needed.                          |
| Activity Types (CR102000)       | The activity types that you plan to use are defined and have the<br>Active check box selected.                                   |

## **Other Settings That Affect the Workflow**

You can affect the workflow of case management by specifying additional settings as follows:

- To cause the system to associate a case with a contract, do the following:
  - On the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form, enable the *Contract Management* feature in the *Advanced Financials* group of features: This feature provides the support of contracts, including case processing and contract billing. It makes available all forms related to contract processing and provides integration with accounts receivable and tracking of time and expenses.
  - On the *Contract [Templates](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1d443263-e802-4d25-a166-d08fb31fea9b)* (CT202000) form, activate case counting by specifying a case count item (in the **Case BillingSettings** section of the**Summary** tab).
- If your company's customer support processes include the approval of cases, configure an approval map, as described in *[Approval Configuration: Approval Maps](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d2db53f8-d3ed-47fd-b34e-c743a59a4b83)*.
- If you want to associate activities with projects and project tasks, enable the *Project Accounting* feature on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form and configure the project accounting functionality, as described in *[Basic Project Accounting](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d5f6d500-6ef6-4112-a745-f10ff7b7d3ec)*.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in the following topics:

- *Case [Management:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=175ed18f-9748-4683-a931-25654bc96c24) To Process a Non-Billable Case*
- *Case [Management:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ce913b7d-0788-465e-abe6-96947096eb7b) To Process a Billable Case*

## <span id="page-69-0"></span>**Opportunity Management: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for managing opportunities, and to understand (and change, if needed) the settings that affect the workflow of opportunity management.

## **Mandatory Configuration**

We recommend that before you start managing opportunities, you make sure the needed CRM features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                                          |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | The following features have been enabled:                                                                                                                                                                                                                                  |
|                                            | •<br>Customer Management: This feature provides the customer<br>relationship management (CRM) functionality, including<br>lead and customer tracking, and gives users the ability to<br>manage sales opportunities, contacts, marketing lists, and<br>marketing campaigns. |
|                                            | •<br>Sales Quotes in the Customer Management group of fea<br>tures: This feature gives you the ability to create opportuni<br>ty-based sales quotes, send them to customers for review,<br>and create sales orders and invoices based on these quotes.                     |
| Customer Management Preferences (CR101000) | The predefined settings in the Numbering Sequences section<br>of the General tab have been saved, as described in Basic Cus<br>tomer Relationship Management.                                                                                                              |
| Opportunity Classes (CR209000)             | Opportunity classes with the necessary settings, attributes,<br>and stages have been created, as described in Defining Oppor<br>tunity Classes.                                                                                                                            |
| Business Account Classes (CR208000)        | Business account classes with the necessary settings and at<br>tributes have been created, as described in Defining Business<br>Account Classes.                                                                                                                           |
| Business Accounts (CR303000)               | Business accounts with the necessary settings and attributes<br>have been created, as described in Creating Business Accounts.                                                                                                                                             |
| Customer Classes (AR201000)                | Customer classes with the necessary settings and attributes<br>have been created, as described in Creating a Customer.                                                                                                                                                     |
| Contacts (CR302000)                        | Contacts with the necessary settings and attributes have been<br>created, as described in Creating Contacts.                                                                                                                                                               |

## **Recommended Configuration**

You should specify and save the recommended settings, which are listed in the following table, to give users the ability to time that the sales team has spent on processing the opportunity, based on the released activities, and to send emails to customers and the sales team.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:<br>•<br>Scheduled Processing (under the Monitoring & Automation<br>group of features): This feature gives you the ability to cre<br>ate schedules for the automatic processing of documents, in<br>cluding the sending of emails.<br>•<br>Time Management: This feature gives you the ability to track<br>the time your organization's employees spend on activities<br>that can be included in time cards. |
| Email Accounts (SM204002)          | A system email account has been configured, as described in<br>Configuring Email Accounts.                                                                                                                                                                                                                                                                                                                                                            |
| Business Events (SM302050)         | A business event that causes the system to send emails to cus<br>tomers has been created.                                                                                                                                                                                                                                                                                                                                                             |
| Email Templates (SM204003)         | A notification template that is a subscriber for the business<br>event has been created.                                                                                                                                                                                                                                                                                                                                                              |
| Automation Schedules (SM205020)    | A schedule for the sending of emails has been created, as de<br>scribed in Managing Emails.                                                                                                                                                                                                                                                                                                                                                           |
| Non-Stock Items (IN202000)         | The required non-stock items of the Labor type with needed set<br>tings have been created, as described in Creating Labor Items.                                                                                                                                                                                                                                                                                                                      |
| Labor Rates (PM209900)             | The cost rates that are specific to particular labor items have<br>been created, as described in Creating Labor Items.                                                                                                                                                                                                                                                                                                                                |
| Attributes (CS205000)              | Attributes have been created with the necessary settings.                                                                                                                                                                                                                                                                                                                                                                                             |
| Earning Types (EP102000)           | If you will be using the Per Activity billing mode, the needed<br>earning types that are used in activities have been created.<br>A predefined set of earning types has been created<br>in the system. You can modify this set as needed.                                                                                                                                                                                                             |
| Activity Types (CR102000)          | The activity types that you plan to use are defined and have the<br>Active check box selected.                                                                                                                                                                                                                                                                                                                                                        |

## **Opportunity-Based Documents Checklist**

We recommend that before you start creating opportunity-based sales orders or invoices, you make sure the needed settings have been specified and entities have been created, as summarized in the following checklist.

| Form           | Criteria to Check                                                                                                                                                                                                |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Multiple forms | Order and inventory management functionality has been con<br>figured as described in Order Management Basic Configuration:<br>General Information and Configuration of Order Management:<br>General Information. |

| Form                       | Criteria to Check                                                                                                                                                                                                                 |  |
|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Stock Items (IN202500)     | Stock items with the necessary settings have been added, as<br>described in Stock Items: General Information.                                                                                                                     |  |
| Non-Stock Items (IN202000) | Non-stock items with the necessary settings have been added,<br>as described in Non-Stock Items: General Information and Ser<br>vice Items: General Information.                                                                  |  |
| Opportunities (CR304000)   | The following tasks have been performed:                                                                                                                                                                                          |  |
|                            | •<br>An opportunity has been created and at least one inventory<br>item, stock or non-stock, has been specified on the Details<br>tab.                                                                                            |  |
|                            | A business account of the Customer type has been selected<br>•<br>for the opportunity.                                                                                                                                            |  |
|                            | •<br>If the Sales Quotes feature is enabled on the Enable/Disable<br>Features (CS100000) form, a primary quote has been created<br>for the opportunity.                                                                           |  |
|                            | If the Service Management feature is enabled on the En<br>•<br>able/Disable Features form, the opportunity does not have<br>any service orders associated with this opportunity.                                                  |  |
|                            | If an opportunity includes detail lines with inven<br>tory items and detail lines with the Inventory ID<br>column le blank, a sales order created from that<br>opportunity will include only the lines with inven<br>tory items. |  |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of opportunity management by specifying additional settings as follows:

- To cause the system use opportunity classes during lead conversion, create the needed classes on the *[Lead](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=620bfe02-e8d0-465c-8469-8d72f29e354c) [Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=620bfe02-e8d0-465c-8469-8d72f29e354c)* (CR207000) form.
- To give users the ability to specify discounts for an opportunity, enable the *Customer Discounts* feature on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form and configure discounts. For details, see *[Customer Discounts:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fcb8c6cc-1b39-4f5b-9742-ddf86a477710) [General Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fcb8c6cc-1b39-4f5b-9742-ddf86a477710)*.
- To provide the ability to include taxes in an opportunity, configure taxes, as described in *Sales [Taxes:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fde1a926-8a0f-4b9a-858e-2587345b2111) [General Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fde1a926-8a0f-4b9a-858e-2587345b2111)*.
- To set up required approvals for sales quotes, sales orders, or invoices, enable the *Approval Workflow* feature on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* form (in the *Monitoring & Automation* group of features) and configure an approval map.
- To give users the ability to create service orders, enable the *Service Management* feature on the *[Enable/](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b) [Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* form and configure the field services functionality, as described in *[Field Services Guide](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2843468d-1638-47d7-bb13-e3d3a016945a)*.

### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in the following topics:

- *Opportunity [Management:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4841d86c-c7f9-4c01-b4cf-fcedc0188804) To Add Products to an Opportunity*
- *Opportunity [Management:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b235c9bd-d096-459f-a31c-8af8f5fccac5) To Create a Sales Quote*

• *Opportunity Management: To Create an [Opportunity-Based](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c55b3631-dc4f-4e98-acbe-abec5f3a1109) Sales Order*

## <span id="page-72-0"></span>**Marketing Lists: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for managing marketing lists, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you start working with marketing lists, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                 |
|--------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | The following features have been enabled:                                                                                                                                                                                                         |
|                                            | •<br>Customer Management: This feature provides the<br>customer relationship management (CRM) func<br>tionality, including lead and customer tracking, as<br>well as handling of sales opportunities, contacts,<br>marketing lists, and campaigns |
|                                            | •<br>Scheduled Processing in the Monitoring & Automa<br>tion group of features: Gives you the ability to cre<br>ate schedules for the automatic processing of doc<br>uments                                                                       |
| Customer Management Preferences (CR101000) | All the necessary settings have been specified and<br>saved to the system.                                                                                                                                                                        |
| Leads (CR301000)                           | All the leads you want to add to a marketing list have<br>been created.                                                                                                                                                                           |
| Contacts (CR302000)                        | All the contacts you want to add to a marketing list<br>have been created.                                                                                                                                                                        |
| Email Accounts (SM204002)                  | A system email account has been created.                                                                                                                                                                                                          |
| Email Preferences (SM204001)               | The system email account has been specified as the<br>default system account.                                                                                                                                                                     |
| Automation Schedules (SM205020)            | A schedule for regular runs of the Send and Receive<br>Email process has been created.                                                                                                                                                            |

#### **Validation of Configuration**

To make sure that all settings are configured correctly, we recommend that you practice working with marketing lists by performing instructions similar to those described in the following topics:

- *Marketing Lists: To Create a Static [Marketing](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0591adb9-7609-47d2-aa51-b29da69e3e50) List*
- *Marketing Lists: To Create a Dynamic [Marketing](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6917bf46-70be-439e-9bfe-99f8c2c84718) List*

## <span id="page-73-0"></span>**Marketing Campaigns: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for creating and managing a marketing campaign, and to understand (and change, if needed) the settings that affect the workflow of campaign management.

## **Implementation Checklist**

We recommend that before you start creating and managing a marketing campaign, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                            |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | Make sure that the following features have been en<br>abled:                                                                                                                                                                                                 |
|                                            | •<br>Customer Management: This feature provides the<br>customer relationship management (CRM) func<br>tionality, including lead and customer tracking, as<br>well as handling of sales opportunities, contacts,<br>marketing lists, and marketing campaigns. |
|                                            | •<br>Scheduled Processing in the Monitoring & Automa<br>tion group of features: This feature gives you the<br>ability to create schedules for the automatic pro<br>cessing of documents                                                                      |
| Customer Management Preferences (CR101000) | All the necessary settings have been specified and<br>saved to the system.                                                                                                                                                                                   |
| Lead Classes (CR207000)                    | All the needed lead classes with the necessary settings<br>and attributes have been created.                                                                                                                                                                 |
| Contact Classes (CR205000)                 | All needed contact classes with the necessary settings<br>and attributes have been created.                                                                                                                                                                  |
| Business Account Classes (CR208000)        | All needed business account classes with the neces<br>sary settings and attributes have been created.                                                                                                                                                        |
| Campaign Classes (CR202500)                | The needed campaign classes with the necessary set<br>tings and attributes have been created.                                                                                                                                                                |

#### **Other Settings That Affect the Workflow of Campaign Management**

You can affect the workflow of campaign management by specifying additional settings as follows: If the *Project Accounting* feature is enabled on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form, you can use the project accounting functionality to track expenses and revenue related to a marketing campaign. The system can regard a marketing campaign as a project and use the project budget tracking mechanism for tracking the campaign budget. For more information about project budgets, see *[Managing the Project Budget](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c7127529-f542-1488-99de-b944cb120a85)*. A project can be associated with a marketing campaign through the **Project Accounting Integration** section on the **Campaign Details** tab of the *[Marketing](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=183be654-0b0a-446d-8bec-a6d478ce6620) [Campaigns](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=183be654-0b0a-446d-8bec-a6d478ce6620)* (CR202000) form. If needed, multiple campaigns may be associated with a single project. (For details, see *[Marketing Campaigns: Project Accounting for Campaigns](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b4d7eebb-99b1-458a-9427-be13602a8299)*.)

### **Validation of Configuration**

To make sure that all settings are configured correctly, we recommend that in your system, you create and work with marketing campaigns by performing instructions similar to those described in *[Marketing Campaigns: Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8539f3c5-4479-44e1-9c00-6e45c9c5c49a) [Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8539f3c5-4479-44e1-9c00-6e45c9c5c49a)*.

## <span id="page-74-0"></span>**Mass Emails: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for creating and sending mass emails, and to understand (and change, if needed) the settings that affect the workflow of managing mass emails.

## **Implementation Checklist**

We recommend that before you start creating and sending mass emails, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                            |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | Make sure that the following features have been en<br>abled:                                                                                                                                                                                                 |
|                                            | •<br>Customer Management: This feature provides the<br>customer relationship management (CRM) func<br>tionality, including lead and customer tracking, as<br>well as handling of sales opportunities, contacts,<br>marketing lists, and marketing campaigns. |
|                                            | Scheduled Processing in the Monitoring & Automa<br>•<br>tion group of features: Gives you the ability to cre<br>ate schedules for the automatic processing of doc<br>uments                                                                                  |
| Customer Management Preferences (CR101000) | All the necessary settings have been specified and<br>saved to the system.                                                                                                                                                                                   |
| Email Accounts (SM204002)                  | A system email account has been created.                                                                                                                                                                                                                     |
| Email Preferences (SM204001)               | The system email account has been specified as the<br>default system account.                                                                                                                                                                                |
| Automation Schedules (SM205020)            | A schedule for regular runs of the Send and Receive<br>Email process has been created.                                                                                                                                                                       |

## **Validation of Configuration**

To make sure that all settings are configured correctly, we recommend that in your system, you practice creating and working with mass emails by performing instructions similar to those described in the following topics:

- *Mass [Emails:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=be2b3603-f714-4056-ab36-a7cc8ee41f15) To Create and Send a Mass Email*
- *Mass Emails: To Email from a [Marketing](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=bb12c0b3-0f4b-4da7-b272-06ac7eb24877) List*

• *Mass Emails: To Email from a Marketing [Campaign](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1f94dfae-b881-4306-aa11-f0a23cdf095a)*

## <span id="page-75-0"></span>**Lead Qualification by Marketing Teams: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for qualifying leads by a marketing team, and to understand (and change, if needed) the settings that affect the workflow of qualifying leads.

#### **Implementation Checklist**

We recommend that before you start qualifying leads, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                            |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Customer Management has been enabled. This<br>feature provides the customer relationship manage<br>ment (CRM) functionality, including lead and customer<br>tracking. This feature also gives users the ability to<br>manage sales opportunities, contacts, marketing lists,<br>and marketing campaigns. |
| Leads (CR301000)                   | Leads with the necessary settings and attributes have<br>been created.                                                                                                                                                                                                                                       |
| Lead Classes (CR207000)            | Lead classes with the necessary settings and attributes<br>have been created.                                                                                                                                                                                                                                |
| Opportunity Classes (CR209000)     | Opportunity classes with the necessary settings and<br>attributes have been created.                                                                                                                                                                                                                         |

#### **Other Settings That Affect the Lead Qualification Workflow**

You can affect the lead qualification workflow by specifying additional settings as follows:

- On the *[Contact Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2f95716d-2004-434d-bab8-45be518b7913)* (CR205000) form (**Conversion Settings** section of the **Details** tab), define classes with the necessary settings and attributes. When a user creates a contact—which can be done directly on the *[Contacts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=75a5dea9-d640-4b71-95b1-88534c4afad7)* (CR302000) form or for a particular lead or business account in the **Create Contact** dialog box of the *[Leads](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ce564fa0-baca-4d9b-97a8-ec69910de4c2)* (CR301000) or *[Business Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=823f9e2c-d352-4cf4-bbb9-ce6464fecc75)* (CR303000) form, respectively—the user selects a class, and the system fills in the default settings of the contact based on the settings of the class.
- On the *[Business Account Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7e56b062-9b9a-4628-8853-9532ae7fe1f4)* (CR208000) form (**Conversion Settings** section of the **Details** tab), specify classes with the necessary settings and attributes. When a user creates a business account—which can be done directly on the *[Business Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=823f9e2c-d352-4cf4-bbb9-ce6464fecc75)* form or for a particular lead or contact in the **Create Account** dialog box of the *[Leads](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ce564fa0-baca-4d9b-97a8-ec69910de4c2)* or *[Contacts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=75a5dea9-d640-4b71-95b1-88534c4afad7)* form, respectively—the user selects a class, and the system fills in the default settings of the contact based on the settings of the class.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *Lead [Qualification](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=bed743a6-371b-4a69-9b66-9b5b3cd090bd) by Marketing Teams: To Disqualify a Lead*.

## <span id="page-76-0"></span>**Lead Qualification by Sales Teams: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for qualifying leads by a sales team, and to understand (and change, if needed) the settings that affect the workflow of qualifying leads.

## **Implementation Checklist**

We recommend that before you start qualifying leads, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                            |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Customer Management has been enabled. This<br>feature provides the customer relationship manage<br>ment (CRM) functionality, including lead and customer<br>tracking. This feature also gives users the ability to<br>manage sales opportunities, contacts, marketing lists,<br>and marketing campaigns. |
| Leads (CR301000)                   | Leads with the necessary settings and attributes have<br>been created.                                                                                                                                                                                                                                       |
| Lead Classes (CR207000)            | Lead classes with the necessary settings and attributes<br>have been created.                                                                                                                                                                                                                                |
| Opportunity Classes (CR209000)     | Opportunity classes with the necessary settings and<br>attributes have been created.                                                                                                                                                                                                                         |

## **Other Settings That Affect the Lead Qualification Workflow**

You can affect the lead qualification workflow by specifying additional settings as follows:

- On the *[Contact Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2f95716d-2004-434d-bab8-45be518b7913)* (CR205000) form (**Conversion Settings** section of the **Details** tab), define classes with the necessary settings and attributes. When a user creates a lead, contact, or business account on the *[Contacts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=75a5dea9-d640-4b71-95b1-88534c4afad7)* (CR302000) form, the system will use classes specified on the *[Contact Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2f95716d-2004-434d-bab8-45be518b7913)* form.
- On the *[Business Account Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7e56b062-9b9a-4628-8853-9532ae7fe1f4)* (CR208000) form (**Conversion Settings** section of the **Details** tab), specify classes with the necessary settings and attributes. When a user creates a lead, contact, or business account on the *[Business Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=823f9e2c-d352-4cf4-bbb9-ce6464fecc75)* (CR303000) form, the system will use classes specified on the *[Business Account](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7e56b062-9b9a-4628-8853-9532ae7fe1f4) [Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7e56b062-9b9a-4628-8853-9532ae7fe1f4)* form.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in the following topics:

- *Lead [Qualification](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e0a41c8b-e20a-411f-b382-815bf4f72399) by Sales Teams: To Convert a Lead to an Opportunity*
- *Lead [Qualification](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7e307e86-2f3f-4ff8-bffa-36038578fe4b) by Sales Teams: To Disqualify a Lead*

## <span id="page-77-0"></span>**Record Validation for Duplicates: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for validating lead, contact, and business account records for duplicates. This information will also help you understand (and change, if needed) the settings that affect the workflow of validating duplicate records.

## **Implementation Checklist**

We recommend that before you start validating records for duplicates, you make sure that the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                   |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:<br>•<br>Customer Management: This feature provides the customer<br>relationship management (CRM) functionality, including<br>lead and customer tracking, as well as the handling of sales                                                                                 |
|                                    | opportunities, contacts, marketing lists, and campaigns<br>Duplicate Validation in the Customer Management group of<br>•<br>features: This feature provides the duplicate validation func<br>tionality, which you can use to set up and perform automat<br>ic validation of lead and contact records for duplicates |
| Duplicate Validation (CR103000)    | All necessary settings have been specified and saved to the sys<br>tem, as described in Duplicate Validation.                                                                                                                                                                                                       |

### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that you test the validation of one record and the validation of multiple records by following instructions similar to those described in the following topics:

- *Record Validation for [Duplicates:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8154b2c7-c5bc-4690-87ff-0dca11f29d82) To Validate a Lead for Duplicates*
- *Record Validation for [Duplicates:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c674b31f-65a9-43c0-a7d0-30939e7fe04f) To Validate Multiple Leads for Duplicates*

## <span id="page-78-2"></span><span id="page-78-0"></span>**Customers and Vendors**

## <span id="page-78-1"></span>**Customer Statements: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for preparing customer statements.

## **Implementation Checklist**

We recommend that before you initially prepare customer statements, you make sure settings have been specified and entities have been created, as summarized in the following checklist.

| Form                                           | Criteria to Check                                                                                                                                                                                                                                                                                           |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Customer Classes (AR201000)                    | In the StatementType box in the Default Print and Email Settings section<br>on the General Settings tab, you specify what type of statement the cus<br>tomers assigned to this customer class prefer—balance-forward or open-item.                                                                          |
|                                                | You select the Print Statements check box if you want to make this cus<br>tomer's statements available for mass-printing on the Print Statements<br>(AR503500) form.                                                                                                                                        |
|                                                | You select theSend Statements By Email check box if you want to make this<br>customer's statements available for mass-emailing on the Print Statements<br>form.                                                                                                                                             |
|                                                | You select the Multi-Currency Statements check box if you want this cus<br>tomer's statements to be created in multicurrency format. Such statements<br>are displayed for mass-processing (printing or emailing) if the Foreign Curren<br>cy Statements check box is selected on the Print Statements form. |
|                                                | This check box becomes available if the Multicurrency Accounting feature has<br>been enabled on the Enable/Disable Features (CS100000) form.                                                                                                                                                                |
| Statement Cycles (AR202800)                    | Make sure that the End of Month statement cycle that you want to use for<br>preparing customer statements has been configured.                                                                                                                                                                              |
| Customers (AR303000)                           | Make sure that the EOM statement cycle has been selected for the customer<br>accounts in the Statement Cycle ID box in the Financial Settings section on<br>the Financial tab of the current form.                                                                                                          |
| Accounts Receivable Prefer<br>ences (AR101000) | Make sure that on the General tab (Consolidation Settings section), the For<br>Each Branch option is selected in the Prepare Statements box.                                                                                                                                                                |

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you prepare customer statements as described in *[Customer Statements: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ee3b7697-9d47-4467-a6b7-7938d136aa11)*.

## <span id="page-79-0"></span>**Customer Visibility: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for restricting the visibility of customer records, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially restrict visibility of customer records, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                      | Criteria to Check                                                                                                                                                                                                                                                              |
|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)        | Make sure the minimal features have been enabled, as described<br>in Company Without Branches: General Information, Company with<br>Branches that Do Not Require Balancing: General Information, and<br>Company with Branches that Require Balancing: General Informa<br>tion. |
|                                           | Make sure that the Multibranch Support feature has been en<br>abled, if you need to restrict the visibility of customer records for<br>particular branches.                                                                                                                    |
|                                           | Enable the Customer and Vendor Visibility Restriction feature to<br>perform Customer Visibility: To Restrict Visibility to a Company.                                                                                                                                          |
|                                           | Enable the Multicurrency Accounting and Multiple Base Currencies<br>features to perform Customer Visibility: To Restrict Visibility to a<br>New Company.                                                                                                                       |
| Customer Classes (AR201000)               | Be sure that the customer classes whose visibility you want to re<br>strict have been defined.                                                                                                                                                                                 |
| Customers (AR303000)                      | Be sure that the customer accounts have been defined for the<br>customers whose visibility you want to restrict.                                                                                                                                                               |
| Branches (CS102000)                       | Make sure that for each branch to which the visibility of any cus<br>tomers should be limited, the appropriate role associated with<br>the branch is specified in the Access Role box (Configuration<br>Settings section) on the Branch Details tab.                           |
| Companies (CS101500)                      | Make sure that for each company to which the visibility of any<br>customers should be limited, the appropriate role associated<br>with the company is specified in the Access Role box (Configura<br>tion Settings section) on the Company Details tab.                        |
| Users (SM201010) or User Roles (SM201005) | Make sure that the needed users have been assigned to the roles<br>specified for branches and companies. For details, see User<br>Roles: General Information.                                                                                                                  |

### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *[Customer](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=90609745-18fd-4154-83f6-1d9b23c2f7a3) Visibility: To Restrict Visibility to a Company* and *[Customer](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=786a44af-4e53-4918-a57d-31b2458747d2) Visibility: To Restrict Visibility to a New [Company](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=786a44af-4e53-4918-a57d-31b2458747d2)*.

## <span id="page-80-0"></span>**On-Demand Statements: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for preparing on-demand customer statements.

## **Implementation Checklist**

We recommend that before you initially prepare customer statements, you make sure settings have been specified and entities have been created, as summarized in the following checklist.

| Form                                          | Criteria to Check                                                                                                                                                                                                                                                                                             |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Customer Classes (AR201000)                   | In the StatementType box in the Default Print and Email Set<br>tings section on the General Settings tab, you specify what type of<br>statement the customers assigned to this customer class prefer—<br>balance-forward or open-item.                                                                        |
|                                               | You select the Print Statements check box if you want to make<br>this customer's statements available for mass-printing on the Print<br>Statements (AR503500) form.                                                                                                                                           |
|                                               | You select theSend Statements By Email check box if you want to<br>make this customer's statements available for mass-emailing on<br>the Print Statements form.                                                                                                                                               |
|                                               | You select the Multi-Currency Statements check box if you want<br>this customer's statements to be created in multicurrency format.<br>Such statements are displayed for mass-processing (printing or<br>emailing) if the Foreign Currency Statements check box is select<br>ed on the Print Statements form. |
|                                               | This check box becomes available if the Multicurrency Account<br>ing feature has been enabled on the Enable/Disable Features<br>(CS100000) form.                                                                                                                                                              |
| Statement Cycles (AR202800)                   | Make sure that the End of Month statement cycle that you want to<br>use for preparing customer statements has been configured.                                                                                                                                                                                |
| Customers (AR303000)                          | Make sure that the EOM statement cycle has been selected for the<br>customer accounts in the Statement Cycle ID box in the Finan<br>cial Settings section on the Financial tab of the current form. The<br>statement type should be Open Item.                                                                |
| Accounts Receivable Preferences<br>(AR101000) | Make sure that on the General tab (Consolidation Settings sec<br>tion), the For Each Branch option is selected in the Prepare State<br>ments box.                                                                                                                                                             |

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you prepare on-demand statements as described in *[On-Demand Statements: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=64b78dc9-bb2d-4fd2-86bb-57f4be701af8)*.

## <span id="page-81-0"></span>**Regenerating Statements: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for regenerating customer statements and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you regenerate customer statements, you make sure settings have been specified and entities have been created, as summarized in the following checklist.

| Form                                          | Criteria to Check                                                                                                                                                                                                                                                                                             |  |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Customer Classes (AR201000)                   | In the StatementType box in the Default Print and Email Set<br>tings section on the General Settings tab, you specify what type of<br>statement the customers assigned to this customer class prefer—<br>balance-forward or open-item.                                                                        |  |
|                                               | You select the Print Statements check box if you want to make<br>this customer's statements available for mass-printing on the Print<br>Statements (AR503500) form.                                                                                                                                           |  |
|                                               | You select theSend Statements By Email check box if you want to<br>make this customer's statements available for mass-emailing on<br>the Print Statements form.                                                                                                                                               |  |
|                                               | You select the Multi-Currency Statements check box if you want<br>this customer's statements to be created in multicurrency format.<br>Such statements are displayed for mass-processing (printing or<br>emailing) if the Foreign Currency Statements check box is select<br>ed on the Print Statements form. |  |
|                                               | This check box becomes available if the Multicurrency Account<br>ing feature has been enabled on the Enable/Disable Features<br>(CS100000) form.                                                                                                                                                              |  |
| Statement Cycles (AR202800)                   | Make sure that the End of Month statement cycle that you want to<br>use for preparing customer statements has been configured.                                                                                                                                                                                |  |
| Customers (AR303000)                          | Make sure that the EOM statement cycle has been selected for the<br>customer accounts in the Statement Cycle ID box in the Financial<br>Settings section on the Financial tab of the current form.                                                                                                            |  |
| Accounts Receivable Preferences<br>(AR101000) | Make sure that on the General tab (Consolidation Settings sec<br>tion), the For Each Branch option is selected in the Prepare State<br>ments box.                                                                                                                                                             |  |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of creating AR documents by specifying additional settings on the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form as follows:

- Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you regenerate customer statements as described in *[Regeneration of Statements: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4bba5990-3835-4ad6-b6fd-39e280fe141e)*.

## <span id="page-82-0"></span>**Vendor Visibility: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for restricting the visibility of vendor records, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially restrict visibility of vendors, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been enabled, as described<br>in Company Without Branches: General Information, Company with<br>Branches that Do Not Require Balancing: General Information, and<br>Company with Branches that Require Balancing: General Informa<br>tion.                                                                                                                                        |
|                                    | Make sure that the Multibranch Support, Multicompany Support,<br>and Customer and Vendor Visibility Restriction features have been<br>enabled, if you need to restrict the visibility of vendor records for<br>particular companies or branches. For details, see Vendor Visibili<br>ty: To Restrict Visibility to a Branch.                                                                                          |
|                                    | Enable the Multibranch Support, Multicompany Support, Cus<br>tomer and Vendor Visibility Restriction, Multicurrency Account<br>ing, and Multiple Base Currencies features, if you need to restrict<br>the visibility of vendor records for a particular company with the<br>base currency different from the tenant's base currency. For de<br>tails, see Vendor Visibility: To Restrict Visibility to a New Company. |
| Vendor Classes (AP201000)          | Be sure that the vendor classes whose visibility you want to re<br>strict have been defined.                                                                                                                                                                                                                                                                                                                          |

| Form                                      | Criteria to Check                                                                                                                                                                                                                                   |
|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Vendors (AP303000)                        | Be sure that the vendor accounts have been defined for the ven<br>dors whose visibility you want to restrict.                                                                                                                                       |
| Branches (CS102000)                       | Make sure that for each branch to which the visibility of any ven<br>dors should be limited, the appropriate role associated with the<br>branch is specified in the Access Role box (Configuration Set<br>tings section) on the Branch Details tab. |
| Companies (CS101500)                      | Make sure that for each company to which the visibility of any<br>vendor should be limited, the appropriate role associated with<br>the company is specified in the Access Role box (Configuration<br>Settings section) on the Company Details tab. |
| Users (SM201010) or User Roles (SM201005) | Make sure that the needed users have been assigned to the roles<br>specified for branches and companies. For details, see User<br>Roles: General Information.                                                                                       |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *Vendor [Visibility:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1194223f-5265-4e15-8eb9-05364876789e) To Restrict Visibility to a Branch* and *Vendor [Visibility:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b07256f2-772c-466a-8629-77725cfcdefb) To Restrict Visibility to a New [Company](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b07256f2-772c-466a-8629-77725cfcdefb)*.

## <span id="page-84-0"></span>**Equipment Management**

## <span id="page-84-1"></span>**Equipment Management: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the managing equipment entities and processing service contracts in the system, and to specify the needed settings that affect this processing workflow.

#### **Prerequisites**

Before you start configuring equipment management, you should make sure that the needed configuration tasks have been performed, as summarized in the following checklist.

| Form                                    | Criteria to Check                                                                                                                                                                                                                                             |
|-----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Multiple forms                          | Make sure that the minimum company settings are<br>specified, as described in Company Without Branches,<br>Company with Branches that Do Not Require Balancing,<br>or Company with Branches that Require Balancing (de<br>pending on your company structure). |
| Multiple forms                          | To offer the provision of inventory items as part of pro<br>viding field services, make sure that the sales order<br>management configuration has been implemented, as<br>described in Configuration of Order Management: Imple<br>mentation Checklist .      |
| Multiple forms                          | Make sure that the service management configuration<br>has been implemented, as described in Basic Service<br>Management Configuration.                                                                                                                       |
| Numbering Sequences (CS201010) form     | Make sure that the numbering sequences have been<br>created for equipment entities.                                                                                                                                                                           |
| Enable/Disable Features (CS100000) form | Make sure that the Service Management feature has<br>been enabled.                                                                                                                                                                                            |

## **Required Settings**

To make it possible for users to manage equipment entities and process service contracts, you should navigate to the form listed in the following table and specify the settings that are described.

| Form                                             | Action                                                                                      |
|--------------------------------------------------|---------------------------------------------------------------------------------------------|
| Equipment Management Preferences (FS100300) form | Specify the equipment numbering sequence, as well<br>as the equipment and billing settings. |

## <span id="page-85-3"></span><span id="page-85-0"></span>**General Ledger**

## <span id="page-85-1"></span>**Adjusting Transactions: Implementation Checklist**

Before users begin processing auto-reversing GL batches, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                          | Settings to Validate                                                                                                                           | Notes                                                                                            |
|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure the Standard Financials<br>feature has been enabled.                                                                                 |                                                                                                  |
| Multiple forms                                | Make sure that the system has been<br>configured properly, as described<br>in Company Without Branches: Gen<br>eral Information.               |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                    |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which auto-reversing transac<br>tions will be created and the next<br>periods have a status of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

## **Settings That Can Affect the Processing Workflow**

The following settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow:

- If the *On Post* option is selected in the **Generate Reversing Entry** box, the system generates a reversing batch when the original batch is posted. If the *On Period Closing* option is selected, the system generates a reversing batch when a user closes the posting period related to the original batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.
- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, enter the batch control total before they save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.

## <span id="page-85-2"></span>**Allocation Rules: Implementation Checklist**

The following tables provide details that you can use to ensure that the system is configured properly for the creation of allocation rules.

| Form                                       | Things to Check                                                                                                                                                                                                                                                                                                                                       | Notes |
|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the Standard Finan<br>cials and General Ledger Allocation<br>Templates (under Advanced Finan<br>cials) features have been enabled.                                                                                                                                                                                                     |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed and the general ledger<br>functionality has been implement<br>ed, as described in Company With<br>out Branches: General Information<br>Company with Branches that Do Not<br>Require Balancing: General Informa<br>tion, and General Ledger: General<br>Information. |       |
| Ledgers (GL201500) form                    | Make sure that the ledgers used for<br>allocations have been created.                                                                                                                                                                                                                                                                                 |       |
| Chart of Accounts (GL202500) form          | Check whether the necessary ac<br>counts have been created, and cre<br>ate them if not.                                                                                                                                                                                                                                                               |       |

## **Additional Configuration to Confirm**

If your company uses subaccounts, the subaccounts have to be configured, as described in *[Subaccounts:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=64736a3d-89c3-41ca-b0a4-0af7bcb11372) [Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=64736a3d-89c3-41ca-b0a4-0af7bcb11372)*.

## <span id="page-86-0"></span>**GL Transactions: Implementation Checklist**

Before users begin processing GL batches, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table

| Form                                       | Settings to Check                                                                                                                                         | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |
| Chart of Accounts (GL202500) form          | Check whether the necessary ac<br>counts have been created.                                                                                               |       |

| Form                                          | Settings to Check                                                                                       | Notes                                                                                            |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which transactions will be creat<br>ed have a status of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

## **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-87-0"></span>**Interbranch Account Mapping: Implementation Checklist**

| Form                                            | Settings to Check                                                                                                                | Notes |
|-------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form      | Make sure that the following fea<br>tures have been enabled:<br>•<br>Standard Financials<br>•<br>Inter-Branch Transactions       |       |
| Companies (CS101500) form                       | Make sure that the necessary com<br>panies and branches have been<br>configured and the necessary<br>ledgers have been assigned. |       |
| Inter-Branch Account Mapping<br>(GL101010) form | Make sure that all the necessary ac<br>count mapping rules have been de<br>fined.                                                |       |

Before users begin to create intercompany and interbranch transactions, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

## <span id="page-87-1"></span>**Recurring Transactions: Implementation Checklist**

To ensure that the system is configured properly for creating recurring batches, make sure that the features and settings listed in the table are configured as described in the following table.

| Form                                          | Settings to Check                                                                                                                                         | Notes                                                                                            |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |                                                                                                  |
| Multiple forms                                | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                               |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which transactions will be creat<br>ed have a status of Open.                                                   | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

#### **Settings That Affect Workflow**

The following settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.
- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, enter the batch control total before they save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.

## <span id="page-88-0"></span>**Reversing Transactions: Implementation Checklist**

Before users begin processing GL batches, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                       | Settings to Validate                                                                                                                                      | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |

### **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-89-0"></span>**Running of Allocations: Implementation Checklist**

The following table provides details that you can use to ensure that the system is configured properly for the running of allocations.

| Form                                          | Things to Check                                                                                                                                                                                                                                                                                                         | Notes                                                                                            |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure that the Standard Finan<br>cials and General Ledger Allocation<br>Templates (under Advanced Finan<br>cials) features have been enabled.                                                                                                                                                                       |                                                                                                  |
| Multiple forms                                | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Com<br>pany Without Branches: General In<br>formation, Company with Branches<br>that Do Not Require Balancing: Gen<br>eral Information, and Company with<br>Branches that Require Balancing:<br>General Information. |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which allocations will be run<br>have a status of Open.                                                                                                                                                                                                                       | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

| Form                        | Things to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Notes                                                                                                                                                                                                                                                                                                                 |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Allocations (GL204500) form | Make sure that the allocations that<br>are going to be run have been cre<br>ated. For details, see Allocation<br>Rules: To Create an Allocation Rule<br>That Uses a Fixed Ratio (Weight),<br>Allocation Rules: To Create an Allo<br>cation Rule That Uses a Fixed Ra<br>tio (Percentage), Allocation Rules: To<br>Create an Allocation Rule That Us<br>es a Dynamic Ratio of the Period-to<br>Date Account Balances, and Alloca<br>tion Rules: To Create an Allocation<br>Rule Based on Budget Data. | The system behavior when gener<br>ating transactions that update the<br>destination accounts depends on<br>whether the AllocateSource Ac<br>counts Separately check box is se<br>lected on the Allocation tab. For<br>the listed allocation rules, the Allo<br>cateSource AccountsSeparately<br>check box is cleared. |

## <span id="page-90-0"></span>**Splitting Transactions: Implementation Checklist**

Before users begin splitting GL transactions, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                       | Settings to Validate                                                                                                                                      | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |

## **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-91-0"></span>**Transactions with Subaccounts: Implementation Checklist**

Before users begin processing GL transactions with subaccounts, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                          | Settings to Check                                                                                                                                                     | Notes                                                                                            |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure the Standard Financials<br>and Subaccounts(under Advanced<br>Financials) features have been en<br>abled.                                                    |                                                                                                  |
| Multiple forms                                | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation.             |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                                           |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which transactions will be creat<br>ed have a status of Open.                                                               | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Segmented Keys (CS202000) form                | Be sure that the SUBACCOUNTS<br>segmented key has been config<br>ured to meet the company's busi<br>ness needs, as described in Subac<br>counts: General Information. |                                                                                                  |

## **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-92-3"></span><span id="page-92-0"></span>**Financial Periods**

## <span id="page-92-1"></span>**Financial Calendar Generation: Implementation Checklist**

Before users begin generating financial calendars, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table

| Form                                       | Settings to Validate                                                                                                                                      | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |

## <span id="page-92-2"></span>**Financial Periods: Implementation Checklist**

To ensure that the system has been configured properly for managing financial periods, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                      | Notes |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled, as described in Company Without<br>Branches: General Information. |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following common settings should be specified on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form:
  - The *Multibranch Support* and *Multicompany Support* features should be enabled to maintain multiple companies in one tenant and multiple branches and to make it possible to enable *Centralized Period Management* feature.
  - The *Centralized Period Management* feature should be disabled to make it possible to open, close, and lock a particular financial period separately for each company within the tenant.
- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Select the **Restrict Access to Closed Periods** check box to allow posting to closed periods to only users belonging to the *Financial Supervisor* role.
- The following settings should be specified on the *[User Roles](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c2879f3c-3739-430a-b02b-c225f5480966)* (SM201005) form:
  - Make sure that the user you are going to use in the process activities later has been assigned to the *Financial Supervisor* role. Users assigned to this role can reopen *Closed* periods and unlock *Locked*

periods, and also post to closed periods even if the **Restrict Access to Closed Periods** check box is selected on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* form.

With these settings specified, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-93-0"></span>**Opening Financial Periods: Implementation Checklist**

To ensure that the system has been configured properly for the opening of financial periods, make sure that the criteria listed in the table have been met in the system as described.

| Form                                    | Criteria to Check                                                                                                                                                    | Notes |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)      | Make sure the minimal features have been<br>enabled, as described in Company Without<br>Branches: General Information.                                               |       |
| Master Financial Calendar<br>(GL201000) | Make sure that the financial year for which<br>you need to generate periods exists. For de<br>tails, see To Add the Next Financial Year and<br>Generate Its Periods. |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following common settings should be specified on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form:
  - The *Multibranch Support* and *Multicompany Support* features should be enabled to maintain multiple companies in one tenant and multiple branches and to make it possible to enable *Centralized Period Management* feature.
  - The *Centralized Period Management* feature should be disabled to make it possible to open, close, and lock a particular financial period separately for each company within the tenant.
- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Select the **Restrict Access to Closed Periods** check box to allow posting to closed periods to only users belonging to the *Financial Supervisor* role.

With these settings specified, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-93-1"></span>**Closing Financial Periods: Implementation Checklist**

To ensure that the system has been configured properly for the closing of financial periods, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                      | Notes |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled, as described in Company Without<br>Branches: General Information. |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following common settings should be specified on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form:
  - The *Multibranch Support* feature should be enabled to maintain multiple branches and to make it possible to enable *Centralized Period Management* feature.
  - The *Multicompany Support* feature should be enabled to maintain multiple companies within one tenant
  - The *Centralized Period Management* feature should be disabled to make it possible to open, close, and lock a particular financial period separately for each company within the tenant.
- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Select the **Restrict Access to Closed Periods** check box to allow posting to closed periods to only users belonging to the *Financial Supervisor* role.
- The following settings should be specified on the *[User Roles](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c2879f3c-3739-430a-b02b-c225f5480966)* (SM201005) form:
  - Make sure that the user you are going to use in the process activity later has been assigned to the *Financial Supervisor* role. Users assigned to this role can reopen *Closed* periods and unlock *Locked* periods, and also post to closed periods even if the **Restrict Access to Closed Periods** check box is selected on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* form.

With these settings specified, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-95-0"></span>**Multicurrency Management**

## <span id="page-95-1"></span>**AP Bills in Foreign Currencies: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing AP bills in a foreign currency, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially process AP bills in a foreign currency, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Steps to Perform                                                                                                                                            |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials and Multicurrency Ac<br>counting features have been enabled.                                                         |
|                                    | For details on configuring the multicurrency functionality, see<br>Multicurrency Functionality: Implementation Activity.                                    |
| Vendors (AP303000)                 | Make sure that the vendor accounts for the vendors for which<br>you will create AP documents have been defined.                                             |
| Currency Rates (CM301000)          | Make sure that the effective currency rate for the currency of the<br>AP document has been defined.                                                         |
|                                    | For details, see Configuration of Rate Types and Rates: To Config<br>ure Rates and Configuration of Rate Types and Rates: To Set Up<br>Refreshing of Rates. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing AP bills by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - To cause every AP transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.
- On the **GeneralSettings** tab of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - To cause all created AP bills to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created AP bills are assigned the *On Hold* status.
  - To make entering a vendor reference number in the**Vendor Ref.** box mandatory when creating an AP bill on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form, select the **RequireVendor Reference** check box in the

**Data EntrySettings** section. If this check box is cleared, you can leave the**Vendor Ref.** box empty when creating an AP bill.

• To cause AP bills to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process AP bills in a foreign currency by performing instructions similar to those described in *[AP Bills in Foreign Currencies:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e93585fc-5f1b-4ee3-828f-f7bb43c67c43) [Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e93585fc-5f1b-4ee3-828f-f7bb43c67c43)*.

## <span id="page-96-0"></span>**AR Invoices in Foreign Currencies: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing AR invoices in a foreign currency, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process AR invoices in a foreign currency, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                           |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials and Multicurrency Ac<br>counting features have been enabled.                                                         |
|                                    | For details on configuring the multicurrency functionality, see<br>Multicurrency Functionality: Implementation Activity.                                    |
| Customers (AR303000)               | Make sure that the customer accounts for the customers for<br>which you will create AR documents have been defined.                                         |
| Currency Rates (CM301000)          | Make sure that the effective currency rate for the currency of the<br>AR document has been defined.                                                         |
|                                    | For details, see Configuration of Rate Types and Rates: To Config<br>ure Rates and Configuration of Rate Types and Rates: To Set Up<br>Refreshing of Rates. |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing AR invoices in a foreign currency by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - To cause every AR transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates

into a single batch all transactions in the same currency posted to the same period for all documents being released.

- On the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - To cause all created AR invoices to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created AR invoices are assigned the *On Hold* status.
  - To make entering a payment reference number in the **Payment Ref.** box mandatory when creating a payment on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form, select the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. If this check box is cleared, you can leave the **Payment Ref.** box empty when creating a payment.
  - To cause AR invoices to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process AR invoices in a foreign currency by performing instructions similar to those described in *[AR Invoices in Foreign](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ab812c9e-e0df-4c7b-a81b-7b8e5f5c5553) [Currencies: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ab812c9e-e0df-4c7b-a81b-7b8e5f5c5553)*.

## <span id="page-97-0"></span>**Credit Memos in Foreign Currencies: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for applying a credit memo in a foreign currency to an invoice, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially create a credit memo, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                           |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials and Multicurrency Ac<br>counting features have been enabled.                                                         |
|                                    | For details on configuring the multicurrency functionality, see<br>Multicurrency Functionality: Implementation Activity.                                    |
| Customers (AR303000)               | Make sure that the customer accounts for the customers for<br>which you will create AR documents have been defined.                                         |
| Currency Rates (CM301000)          | Make sure that the effective currency rate for the currency of the<br>AR document has been defined.                                                         |
|                                    | For details, see Configuration of Rate Types and Rates: To Config<br>ure Rates and Configuration of Rate Types and Rates: To Set Up<br>Refreshing of Rates. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing credit memos by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - To cause every AR transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.
- On the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - To cause all created credit memos to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created credit memos are assigned the *On Hold* status.
  - To make entering a payment reference number in the **Payment Ref.** box mandatory when creating a payment on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form, select the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. If this check box is cleared, you can leave the **Payment Ref.** box empty when creating a payment.
  - To cause credit memos to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you create and apply credit memos in a foreign currency by performing instructions similar to those described in *[Credit Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dcf20e6a-4a2e-404b-87c9-f1eb668aac3a) [in Foreign Currencies: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dcf20e6a-4a2e-404b-87c9-f1eb668aac3a)*.

## <span id="page-98-0"></span>**Debit Adjustments in Foreign Currencies: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing debit adjustments in a foreign currency, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process a debit adjustment, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Steps to Perform                                                                                                         |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials and Multicurrency Ac<br>counting features have been enabled.                      |
|                                    | For details on configuring the multicurrency functionality, see<br>Multicurrency Functionality: Implementation Activity. |
| Vendors (AP303000)                 | Make sure that the vendor accounts for the vendors for which<br>you will create AP documents have been defined.          |

| Form                      | Steps to Perform                                                                                                                                            |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Currency Rates (CM301000) | Make sure that the effective currency rate for the currency of the<br>AP document has been defined.                                                         |
|                           | For details, see Configuration of Rate Types and Rates: To Config<br>ure Rates and Configuration of Rate Types and Rates: To Set Up<br>Refreshing of Rates. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing debit adjustments by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - To cause every AP transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.
- On the **GeneralSettings** tab of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - To cause all created debit adjustments to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created debit adjustments are assigned the *On Hold* status.
  - To make entering a vendor reference number in the**Vendor Ref.** box mandatory when creating an AP bill on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form, select the **RequireVendor Reference** check box in the **Data EntrySettings** section. If this check box is cleared, you can leave the**Vendor Ref.** box empty when creating an AP bill.
  - To cause AP bills to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process debit adjustments in a foreign currency by performing instructions similar to those described in *[Debit Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8ccb63aa-cf28-46fd-857d-eb9281d044bf) [in Foreign Currencies: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8ccb63aa-cf28-46fd-857d-eb9281d044bf)*.

## <span id="page-99-0"></span>**Multicurrency Cash Account: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for configuring a cash account in a foreign currency, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially configure a cash account, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                          | Criteria to Check                                                                                                                           |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)            | Make sure that the Multicurrency Accounting feature has been en<br>abled.                                                                   |
| General Ledger Preferences (GL102000)         | Make sure that the rounding gain and loss accounts have been speci<br>fied.                                                                 |
| Currency Management Preferences<br>(CM101000) | Make sure that the realized gain and loss accounts have been speci<br>fied.                                                                 |
| Currencies (CM202000)                         | Make sure that the foreign currency in which you want to denominate<br>the new cash account has been activated for use in accounting.       |
| Currency Rates (CM301000)                     | Make sure that a currency rate for the needed currency has been de<br>fined for the financial period in which you want to create documents. |

For details on configuring the functionality, see *[Multicurrency Functionality: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b6d51802-f951-44ef-8ecb-f9244ed438bf)*. For details on configuring currency rates, see *[Configuration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=00d85958-d6ad-4d36-90bc-bf749c6f7213) of Rate Types and Rates: To Configure Rates* and *[Configuration of Rate](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=aae84e9e-4b5c-4b8a-9c51-a3cd040eb7d1) Types and Rates: To Set Up [Refreshing](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=aae84e9e-4b5c-4b8a-9c51-a3cd040eb7d1) of Rates*.

## **Other Settings That Affect the Workflow**

You can affect the workflow of configuring foreign currency cash accounts by specifying additional settings as follows:

• To cause a separate GL batch to be generated for each released document, clear the **Generate Consolidated Batches** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form.

If you select this check box, on release of multiple documents, the system will group documents by branch, posting period, and currency, and will generate the batches on a per-group basis rather than on a perdocument basis. Because multiple documents combined into one batch may have different currency rates, in the batch, the system always shows the rate that was effective on the**Transaction Date** of the batch. In a batch that combines transactions from multiple documents, the single displayed rate may differ from the actual document rates.

• To cause all saved batches to be saved with the *Balanced* status, clear the **Hold Batches on Entry** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* form. If the check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so you can process it further.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you create a GL transaction with a cash account denominated in a foreign currency by performing instructions similar to those described in *[Multicurrency](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=3007d6de-dffa-4786-87aa-3da129bfc5a7) Cash Accounts: To Process a GL Transaction*.

## <span id="page-100-0"></span>**Multicurrency Funds Transfers: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing funds transfers in a foreign currency, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially perform funds transfers, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                     | Settings to Check                                                                                       | Note                                                                                                                                                                                                   |
|------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)       | Make sure that the Standard Finan<br>cials and Multicurrency Accounting<br>features have been enabled.  | For details on configuring the mul<br>ticurrency functionality, see Multi<br>currency Functionality: Implementa<br>tion Activity.                                                                      |
| Chart of Accounts (GL202500)             | Check whether the necessary ac<br>counts have been created.                                             |                                                                                                                                                                                                        |
| Cash Accounts (CA202000)                 | Check whether the necessary cash<br>accounts have been configured.                                      | For details on configuring a cash<br>account in a foreign currency, see<br>Multicurrency Cash Accounts: To<br>Configure an Account                                                                     |
| Company Financial Calendar<br>(GL201100) | Make sure that the periods during<br>which funds transfers may occur<br>have a status of Open.          | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form.<br>For details on opening financial pe<br>riods, see Opening Financial Peri<br>ods: Process Activity. |
| Currency Rates (CM301000)                | Make sure that the effective curren<br>cy rate for the currency of the AR in<br>voice has been defined. | For details, see Configuration of<br>Rate Types and Rates: To Config<br>ure Rates and Configuration of Rate<br>Types and Rates: To Set Up Re<br>freshing of Rates.                                     |

## **Other Settings That Affect the Workflow**

You can affect the workflow of configuring foreign currency cash accounts by specifying additional settings on the *[Cash Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b)* (CA101000) form as follows:

- To cause transactions to be posted to the general ledger when cash documents are released, select the **Automatically Post to GL on Release** check box. If this check box is cleared, you have to post the batch aer you release the document.
- To cause new transactions and funds transfers to be assigned the *Balanced* status when they are entered, clear the **Hold Transactions on Entry** check box in the **Data EntrySettings** section. If the **Hold Transactions on Entry** check box is cleared, the transactions and funds transfers are assigned the *On Hold* status.
- To make filling in the **Document Ref.** box on the *Funds [Transfers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=814c5c8d-45bc-4e4d-98df-1b6785defc6c)* (CA301000) form mandatory for new funds transfers, select the **Require Document Ref. Nbr. on Entry** check box. If this check box is cleared, you can leave the **Document Ref.** box blank.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform funds transfers in a foreign currency by performing instructions similar to those described in *[Multicurrency Funds](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e8465a5d-8bf5-4afe-9870-9f4b58e200da) [Transfers:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e8465a5d-8bf5-4afe-9870-9f4b58e200da) Process Activity*.

## <span id="page-102-0"></span>**Multicurrency Payment of Invoices: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing AR invoices in a foreign currency by using the base currency and another foreign currency, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially process AR invoices in a foreign currency, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                           |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials and Multicurrency Ac<br>counting features have been enabled.                                                         |
|                                    | For details on configuring the multicurrency functionality, see<br>Multicurrency Functionality: Implementation Activity.                                    |
| Customers (AR303000)               | Make sure that the customer accounts for the customers for<br>which you will create AR documents have been defined.                                         |
| Currency Rates (CM301000)          | Make sure that the effective currency rate for the currency of the<br>AR document has been defined.                                                         |
|                                    | For details, see Configuration of Rate Types and Rates: To Config<br>ure Rates and Configuration of Rate Types and Rates: To Set Up<br>Refreshing of Rates. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing AR invoices by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - To cause every AR transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.
- On the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - To cause all created AR invoices to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created AR invoices are assigned the *On Hold* status.

- To make entering a payment reference number in the **Payment Ref.** box mandatory when creating a payment on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form, select the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. If this check box is cleared, you can leave the **Payment Ref.** box empty when creating a payment.
- To cause AR invoices to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process AR invoices in a foreign currency by performing instructions similar to those described in *[Multicurrency Payment of](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8b6cd884-3293-4c3e-80f3-8c3c24ba04c7) Invoices: To Pay a Foreign [Currency](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8b6cd884-3293-4c3e-80f3-8c3c24ba04c7) Invoice by Using the Base Currency* and *[Multicurrency](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=cce4ab21-e2f5-40d8-b251-f20310cfe621) Payment of Invoices: To [Pay a Foreign Currency Invoice by Using Another Currency](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=cce4ab21-e2f5-40d8-b251-f20310cfe621)*.

## <span id="page-103-0"></span>**Multicurrency Payment of Bills: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for paying multicurrency bills, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process AP bills in a foreign currency, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Steps to Perform                                                                                                                                            |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials and Multicurrency Ac<br>counting features have been enabled.                                                         |
|                                    | For details on configuring the multicurrency functionality, see<br>Multicurrency Functionality: Implementation Activity.                                    |
| Vendors (AP303000)                 | Make sure that the vendor accounts for the vendors for which<br>you will create AP documents have been defined.                                             |
| Currency Rates (CM301000)          | Make sure that the effective currency rate for the currency of the<br>AP document has been defined.                                                         |
|                                    | For details, see Configuration of Rate Types and Rates: To Config<br>ure Rates and Configuration of Rate Types and Rates: To Set Up<br>Refreshing of Rates. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing AP bills by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - To cause every AP transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates

into a single batch all transactions in the same currency posted to the same period for all documents being released.

- On the **GeneralSettings** tab of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - To cause all created AP bills to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created AP bills are assigned the *On Hold* status.
  - To make entering a vendor reference number in the**Vendor Ref.** box mandatory when creating an AP bill on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form, select the **RequireVendor Reference** check box in the **Data EntrySettings** section. If this check box is cleared, you can leave the**Vendor Ref.** box empty when creating an AP bill.
  - To cause AP bills to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process AP bills in a foreign currency by performing instructions similar to those described in *[Multicurrency Payment of](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ed01e83e-dfba-4331-8c3e-ef689c457886) Bills: To Pay a Foreign [Currency](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ed01e83e-dfba-4331-8c3e-ef689c457886) Bill by Using the Base Currency* and *[Multicurrency](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=62b80f1c-6225-4e19-b714-dc469f04bbc9) Payment of Bills: To Pay a Foreign [Currency Bill by Using Another Currency](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=62b80f1c-6225-4e19-b714-dc469f04bbc9)*.

## <span id="page-104-0"></span>**Documents in Different Base Currencies: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing documents between companies that use different base currencies, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process documents between companies with different base currencies, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                     |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Multibranch Support, Multicompany Support, Customer and Ven<br>dor Visibility Restriction, Multicurrency Accounting, and Multiple Base<br>Currencies features have been enabled.                                                                                                                                  |
| Multiple forms                     | The necessary settings have been specified, as demonstrated in the<br>examples of Multiple Base Currencies: Implementation Activity, Compa<br>ny Groups: Implementation Activity,Customer Visibility: To Restrict Visi<br>bility to a New Company, and Vendor Visibility: To Restrict Visibility to a<br>New Company. |
| Non-Stock Items (IN202000)         | The CONSULT non-stock item has been defined.                                                                                                                                                                                                                                                                          |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing AR invoices by specifying additional settings as follows:

• On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:

- To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
- To cause every AR and AP transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.
- On the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - To cause all created AR invoices to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created AR invoices are assigned the *On Hold* status.
  - To cause AR invoices to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.
- On the **GeneralSettings** tab of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - To cause all created AP bills to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created AP bills are assigned the *On Hold* status.
  - To cause AP bills to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process documents between companies with different base currencies by performing instructions similar to those described in *Documents in Different Base [Currencies:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=45e6c6fc-a643-4cd3-bdb8-c4334eec1a1b) To Process an AR Invoice* and *[Documents in Different Base](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=589650bb-e84e-4604-ace2-d579ee56bb85) [Currencies:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=589650bb-e84e-4604-ace2-d579ee56bb85) To Process an AP Bill*.

## <span id="page-105-0"></span>**Revaluation of AP Documents: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing revaluation of open AP documents, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially perform revaluation of open AP documents, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                             |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials and Multicur<br>rency Accounting features have been enabled.                           |
|                                    | For details on configuring the multicurrency function<br>ality, see Multicurrency Functionality: Implementation Ac<br>tivity. |
| Chart of Accounts (GL202500)       | Check whether the necessary accounts have been cre<br>ated.                                                                   |

| Form                                       | Criteria to Check                                                                                                                                                           |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Master Financial Calendar (GL201000)       | Make sure that a financial period next to the one dur<br>ing which revaluation will occur has been opened in<br>the master financial calendar.                              |
| Currency Rates (CM301000)                  | Make sure that the effective currency rates have been<br>defined.                                                                                                           |
|                                            | For details, see Configuration of Rate Types and Rates:<br>To Configure Rates and Configuration of Rate Types and<br>Rates: To Set Up Refreshing of Rates.                  |
| Currency Management Preferences (CM101000) | Make sure that the accounts to which unrealized gains<br>and losses are posted have been specified in the Un<br>realized Gain Account and Unrealized Loss Account<br>boxes. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of revaluing open AP documents by specifying additional settings as follows:

- To cause batches generated from currency management to be automatically posted to the general ledger, on the *[Currency Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* (CM101000) form, select the **Automatically Post to GL on Release** check box.
- To cause unrealized gains and losses to be posted to a separate account instead of the AP account of the vendor, specify the AP provisioning account for the needed currency in the **AP Provisioning Account** box on the *[Currency Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* form.
- To cause unrealized gains and losses to be posted to the accounts specific for the vendor class, select the needed accounts in the **Unrealized Gain Account** and **Unrealized Loss Account** boxes on the **GL Accounts** tab of the *Vendor [Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=20dc8b93-d83a-49cf-8cfb-d2ffd2f0db87)* (AP201000) form.

If these boxes on the *Vendor [Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=20dc8b93-d83a-49cf-8cfb-d2ffd2f0db87)* form are le empty, the system will post unrealized gains and losses to the account for the currency, which is specified in the **Unrealized Gain Account** and **Unrealized Loss Account** box on the **GL Accounts** tab of the *[Currencies](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=533be28d-b9e1-4d77-9b62-b06bb90a8b3b)* (CM202000) form.

### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you revalue balances of open AP documents by performing instructions similar to those described in *[Revaluation of AP](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a4dfba6d-4c14-4d55-9804-d85255643e74) [Documents: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a4dfba6d-4c14-4d55-9804-d85255643e74)*.

## <span id="page-106-0"></span>**Revaluation of AR Documents: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing revaluation of open AR documents, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially perform revaluation of open AR documents, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                           |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | Make sure that the Standard Financials and Multicur<br>rency Accounting features have been enabled.                                                                         |
|                                            | For details on configuring the multicurrency function<br>ality, see Multicurrency Functionality: Implementation Ac<br>tivity.                                               |
| Chart of Accounts (GL202500)               | Check whether the necessary accounts have been cre<br>ated.                                                                                                                 |
| Master Financial Calendar (GL201000)       | Make sure that a financial period next to the one dur<br>ing which revaluation will occur has been opened in<br>the master financial calendar.                              |
| Currency Rates (CM301000)                  | Make sure that the effective currency rates have been<br>defined.                                                                                                           |
|                                            | For details, see Configuration of Rate Types and Rates:<br>To Configure Rates and Configuration of Rate Types and<br>Rates: To Set Up Refreshing of Rates.                  |
| Currency Management Preferences (CM101000) | Make sure that the accounts to which unrealized gains<br>and losses are posted have been specified in the Un<br>realized Gain Account and Unrealized Loss Account<br>boxes. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of revaluing open AR documents by specifying additional settings as follows:

- To cause batches generated from currency management to be automatically posted to the general ledger, on the *[Currency Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* (CM101000) form, select the **Automatically Post to GL on Release** check box.
- To cause unrealized gains and losses to be posted to a separate account instead of the AR account of the customer, specify the AR provisioning account for the needed currency in the **AR Provisioning Account** box on the *[Currency Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* form.
- To cause unrealized gains and losses to be posted to the accounts specific for the customer class, select the needed accounts in the **Unrealized Gain Account** and **Unrealized Loss Account** boxes on the **GL Accounts** tab of the *[Customer Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=806e39d6-6f89-4e6c-9a24-61c6fb0c9a57)* (AR201000) form.

If these boxes on the *[Customer Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=806e39d6-6f89-4e6c-9a24-61c6fb0c9a57)* form are le empty, the system will post unrealized gains and losses to the account for the currency, which is specified in the **Unrealized Gain Account** and **Unrealized Loss Account** box on the **GL Accounts** tab of the *[Currencies](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=533be28d-b9e1-4d77-9b62-b06bb90a8b3b)* (CM202000) form.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you revalue balances of open AP documents by performing instructions similar to those described in *[Revaluation of AR](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4e811ccf-a3de-4a19-b3a3-0ab1a5d3792c) [Documents: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4e811ccf-a3de-4a19-b3a3-0ab1a5d3792c)*.

## <span id="page-108-0"></span>**Revaluation of Bank Accounts: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing revaluation of a bank account, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially revalue a bank account, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                           |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | Make sure that the Standard Financials and Multicur<br>rency Accounting features have been enabled.                                                                         |
|                                            | For details on configuring the multicurrency function<br>ality, see Multicurrency Functionality: Implementation Ac<br>tivity.                                               |
| Chart of Accounts (GL202500)               | Check whether the necessary accounts have been cre<br>ated.                                                                                                                 |
| Master Financial Calendar (GL201000)       | Make sure that a financial period next to the one dur<br>ing which revaluation will occur has been opened in<br>the master financial calendar.                              |
| Currency Rates (CM301000)                  | Make sure that the effective currency rates have been<br>defined.                                                                                                           |
|                                            | For details, see Configuration of Rate Types and Rates:<br>To Configure Rates and Configuration of Rate Types and<br>Rates: To Set Up Refreshing of Rates.                  |
| Currency Management Preferences (CM101000) | Make sure that the accounts to which unrealized gains<br>and losses are posted have been specified in the Un<br>realized Gain Account and Unrealized Loss Account<br>boxes. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of revaluing bank accounts by specifying additional settings as follows:

• To cause batches generated from currency management to be automatically posted to the general ledger, on the *[Currency Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* (CM101000) form, select the **Automatically Post to GL on Release** check box.

• To cause the system to use the default rate for revaluation of a particular account, you clear the **Revaluation RateType** column for this account on the *[Chart of Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=85557f41-a4af-47a8-b198-2a01461ce9c3)* (GL202500) form. The system will use the default rate type specified in the **GL Revaluation RateType** box on the *[Currency Management](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* form.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you revalue the balance of a bank account by performing instructions similar to those described in *[Revaluation of Bank](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ce62153b-2a36-4e6d-b500-217e4c6c79bb) [Accounts: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ce62153b-2a36-4e6d-b500-217e4c6c79bb)*.

## <span id="page-109-0"></span>**Translation of Financial Statements: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for translating financial statements, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially translate financial statements, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Tasks to Perform                                                                                                                             |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)         | Make sure that the Standard Financials, Multicurren<br>cy Accounting, and Translation of Financial Statements<br>features have been enabled. |
|                                            | For details on configuring the multicurrency function<br>ality, see Multicurrency Functionality: Implementation Ac<br>tivity.                |
| Chart of Accounts (GL202500)               | Make sure that the accounts that will be used for<br>recording translation gains and losses have been cre<br>ated.                           |
| Company Financial Calendar (GL201100)      | Make sure that the financial period for which you want<br>to configure a translation definition has the Open sta<br>tus.                     |
| Currency Management Preferences (CM101000) | Make sure that the accounts for recording translation<br>gains and losses have been specified.                                               |
| Currencies (CM202000)                      | Make sure that the translation gain and loss accounts<br>have been specified for each foreign currency.                                      |
| Currency Rate Types (CM201000)             | Make sure that the rate types used for translations<br>have been defined.                                                                    |

| Form                              | Tasks to Perform                                                                                                                                                                                                                                            |
|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Currency Rates (CM201000)         | Make sure that the effective exchange rates to be used<br>for translations have been defined. For details, see<br>Configuration of Rate Types and Rates: To Configure<br>Rates and Configuration of Rate Types and Rates: To<br>Set Up Refreshing of Rates. |
| Ledgers (GL201500)                | You create a ledger of the Reporting type to be used for<br>keeping the results of translations. For details on re<br>porting ledgers, see Reporting Ledgers.                                                                                               |
| Translation Definition (CM203000) | You create a translation definition that will be used for<br>translating financial statements. For details, see Trans<br>lation Definitions: Implementation Activity.                                                                                       |

## **Other Settings That Affect the Workflow**

You can affect the workflow of translating financial statements by specifying additional settings as follows:

• To cause translation batches to be automatically posted to the general ledger, on the *[Currency Management](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* (CM101000) form, select the **Automatically Post to GL on Release** check box.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you translate financial statements by performing instructions similar to those described in *[Translation](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35846545-2364-42a0-9e44-3d27267a88cd) of Financial [Statements: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35846545-2364-42a0-9e44-3d27267a88cd)*.

## <span id="page-110-0"></span>**Consolidated Financial Statement: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for preparing a consolidated financial statement, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially perform translation of financial statements and then preparation of a consolidated financial statement, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                  |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Standard Financials, Multibranch Support, Multi<br>company Support, Customer and Vendor Visibility Restriction, Multicur<br>rency Accounting, Multiple Base Currencies, and Translation of Finan<br>cial Statements features have been enabled. |
|                                    | For details on configuring multiple base currencies, see Multiple Base<br>Currencies: Implementation Activity, Customer Visibility: To Restrict Visi<br>bility to a New Company, and Vendor Visibility: To Restrict Visibility to a<br>New Company.                |

| Form                                          | Criteria to Check                                                                                                                                            |  |
|-----------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Chart of Accounts (GL202500)                  | Make sure that the accounts that will be used for recording transla<br>tion gains and losses have been created.                                              |  |
| Company Financial Calendar (GL201100)         | Make sure that the financial period for which you want to configure a<br>translation definition has the Open status.                                         |  |
| Currency Management Preferences<br>(CM101000) | Make sure that the accounts for recording translation gains and loss<br>es have been specified.                                                              |  |
| Currencies (CM202000)                         | Make sure that the translation gain and loss accounts have been<br>specified for each base currency.                                                         |  |
| Currency Rate Types (CM201000)                | Make sure that the rate types used for translations have been de<br>fined.                                                                                   |  |
| Currency Rates (CM201000)                     | Make sure that the effective exchange rates to be used for transla<br>tions have been defined.                                                               |  |
| Ledgers (GL201500)                            | You create a ledger of the Reporting type to be used for keeping the<br>results of translations. For details on reporting ledgers, see Reporting<br>Ledgers. |  |
| Translation Definition (CM203000)             | You create a translation definition that will be used for translating fi<br>nancial statements.                                                              |  |

## **Other Settings That Affect the Workflow**

You can affect the workflow of translating financial statements by specifying additional settings as follows:

• To cause translation batches to be automatically posted to the general ledger, on the *[Currency Management](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=978e9b8f-a3a3-461f-929f-b83c3407bc49)* (CM101000) form, select the **Automatically Post to GL on Release** check box.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform a translation of financial statements as described in *[Consolidated](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5405558c-f81b-421e-bcaa-dcc398b076a7) Financial Statement: Performing a Translation* and prepare a consolidated financial statement as described in *[Consolidated Financial Statement: Creating a Customized](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ee9b98cc-3c81-461f-bcf0-6e8289f47096) [Report](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ee9b98cc-3c81-461f-bcf0-6e8289f47096)*.

## <span id="page-112-1"></span><span id="page-112-0"></span>**Payroll Basic Configuration: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing payroll documents, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Prerequisites**

We recommend that before you start performing the minimum configuration of payroll, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                    |  |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Multiple forms                     | Minimum company settings have been specified and<br>the minimal required functionality has been imple<br>mented for all other functional areas to be integrated<br>with the payroll functionality, as described in Company<br>Without Branches: General Information. |  |
| Work Calendar (CS209000)           | The work calendar that reflects the work days, work<br>times for each day, and unpaid break time of the em<br>ployees that are involved in payroll has been defined.                                                                                                 |  |
| Numbering Sequences (CS201010)     | The numbering sequences have been created for pay<br>roll batches and transactions.                                                                                                                                                                                  |  |
| Departments (EP201500)             | The departments that are used in your organization<br>have been created.                                                                                                                                                                                             |  |
| Positions (EP201000)               | The positions taken by the employees in your organi<br>zation have been defined.                                                                                                                                                                                     |  |
| Employees (EP203000)               | The employees involved in payroll processes have<br>been defined in the system.                                                                                                                                                                                      |  |
| Payment Methods (CA204000)         | Payment methods and a cash account for each pay<br>ment method to be used to generate paychecks for an<br>employee have been defined.                                                                                                                                |  |
| Vendors (AP303000)                 | Vendors to be used with payroll, such as tax agencies,<br>benefit providers, and unions, have been created.                                                                                                                                                          |  |
| Enable/Disable Features (CS100000) | The Payroll feature has been enabled, which adds the<br>forms and UI elements related to the payroll function<br>ality.                                                                                                                                              |  |

## **Minimum Required Settings**

To make it possible for users to process payroll documents, you should navigate to the forms listed below and perform the tasks described in the table.

| Form                           | Criteria to Check                                                                |
|--------------------------------|----------------------------------------------------------------------------------|
| Payroll Preferences (PR101000) | The numbering sequences have been specified and<br>the settings have been saved. |

## <span id="page-114-2"></span><span id="page-114-0"></span>**Prices and Discounts**

## <span id="page-114-1"></span>**Sales Prices: Implementation Checklist**

To ensure that the system is configured properly for defining sales price common to all customers, specific to a particular customer price class, or specific to a particular customer, make sure that the following features and settings are configured as described in the following table.

| Form                               | Settings to Validate                                                                                                                | Note                                                                                                                                                                                                                                                                                       |  |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Enable/Disable Features (CS100000) | The Standard Financials feature has<br>been enabled.                                                                                | Standard Financials provides the<br>standard financial functionality.                                                                                                                                                                                                                      |  |
|                                    | The Inventory feature has been en<br>abled.                                                                                         | Inventory provides the function<br>ality of maintaining stock items<br>and must be enabled if you plan to<br>maintain prices for your stock items<br>in Acumatica ERP.<br>Volume Pricing supports the main<br>tenance of prices based on the<br>quantity or amount of items being<br>sold. |  |
|                                    | The Volume Pricing feature has<br>been enabled.                                                                                     |                                                                                                                                                                                                                                                                                            |  |
|                                    | The Multiple Warehouses feature<br>has been enabled.                                                                                |                                                                                                                                                                                                                                                                                            |  |
|                                    | The Multiple Units of Measure fea<br>ture has been enabled.                                                                         |                                                                                                                                                                                                                                                                                            |  |
|                                    |                                                                                                                                     | Multiple Warehouses supports<br>the distributed structure of ware<br>houses. This feature is required for<br>defining warehouse-specific prices.                                                                                                                                           |  |
|                                    |                                                                                                                                     | Multiple Units of Measure supports<br>multiple units of measure for each<br>stock item and the rules of conver<br>sion between these units. This fea<br>ture is required for defining UOM<br>specific prices.                                                                              |  |
| Customers (AR303000)               | Make sure that the customers for<br>which you want to define sales<br>prices have been created.                                     | For more information on configur<br>ing customers, see Customers: Gen<br>eral Information.                                                                                                                                                                                                 |  |
|                                    | For prices based on the customer<br>price class, make sure that the<br>customer price class has been as<br>signed to the customers. |                                                                                                                                                                                                                                                                                            |  |
| Customer Price Classes (AR208000)  | Make sure that the customer price<br>class for which you want to define<br>sales prices have been created.                          |                                                                                                                                                                                                                                                                                            |  |

|  |  | Table: Table 1: Implementation Checklist |  |
|--|--|------------------------------------------|--|
|--|--|------------------------------------------|--|

| Form                                                     | Settings to Validate                                                                          | Note                                                                                                  |
|----------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| Non-Stock Items (IN202000) and<br>Stock Items (IN202500) | Make sure the required stock and<br>non-stock items have been config<br>ured and activated.   | For more information on configur<br>ing non-stock items, see Non-Stock<br>Items: General Information. |
|                                                          |                                                                                               | For more information on config<br>uring stock items, see Stock Items:<br>General Information.         |
| Units of Measure (CS203500)                              | For UOM-specific prices: Make sure<br>that the necessary units of measure<br>are configured.  | For more information, see Stock<br>Items: Units of Measure.                                           |
| Warehouses (IN204000)                                    | For warehouse-specific prices:<br>Make sure that the necessary ware<br>houses are configured. | For more information on configur<br>ing warehouses, see Warehouses:<br>General Information.           |

### **Known Process Limitation**

When the *Lot/Serial Attributes* feature is enabled on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form, units of a stock item with a particular lot or serial class may have specific sales prices and descriptions. If the**Specify Lot/Serial Price and Description** check box is selected for the lot or serial class on the *[Lot/Serial Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=9806d94b-097e-4082-9f01-9ca66d031ab7)* (IN207000) form, you cannot add an item with this class to a sales price list or worksheet on the following forms:

- *[Sales Prices](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=62bfca2c-0893-495b-bb1d-125b64899afc)* (AR202000)
- *[Sales Price Worksheets](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6379952d-248a-421d-aa29-285e371be559)* (AR202010)

## <span id="page-115-0"></span>**Prices in Base Currencies: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for maintaining prices and costs in different base currencies, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially set up prices and costs for companies in different base currencies, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                       |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Multibranch Support, Multicompany Support, Customer and Vendor<br>Visibility Restriction, Multicurrency Accounting, and Multiple Base Curren<br>cies features have been enabled.                                                                    |
| Multiple forms                     | The necessary settings have been specified, as demonstrated in the ex<br>amples of Multiple Base Currencies: Implementation Activity, Company<br>Groups: Implementation Activity, and Customer Visibility: To Restrict Visibil<br>ity to a New Company. |

| Form                       | Criteria to Check                            |
|----------------------------|----------------------------------------------|
| Non-Stock Items (IN202000) | The CONSULT non-stock item has been defined. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing AR invoices by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - To cause every AR transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box. If this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.
- On the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - To cause all created AR invoices to have the *Balanced* status, clear the **Hold Documents on Entry** check box in the **Data EntrySettings** section. If this check box is selected, the created AR invoices are assigned the *On Hold* status.
  - To cause AR invoices to be automatically posted to the general ledger once they are released, select the **Automatically Post on Release** check box in the **PostingSettings** section. If this check box is cleared, you have to post the batch aer you release the document.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you maintain prices and costs in multiple base currencies by performing instructions similar to those described in *[Prices in Base Currencies: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e626a3bd-399b-422b-a3c7-afa75c175318)*.

## <span id="page-117-0"></span>**Project Accounting**

## <span id="page-117-2"></span><span id="page-117-1"></span>**Committed Costs: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing cost commitments on projects, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially process cost commitments, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                 |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure the following features are enabled:                                                                                                                                                                                                                                    |
|                                         | •<br>Inventory and Order Management, if you want to<br>process purchase orders with non-stock items and<br>track them as cost commitments to projects                                                                                                                            |
|                                         | •<br>Inventory, if you want to process purchase orders<br>with stock items and track them as cost commit<br>ments to projects                                                                                                                                                    |
|                                         | •<br>Construction, if you want to process subcontracts<br>and track them as cost commitments to projects                                                                                                                                                                         |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
|                                         | Also, make sure that the Internal Cost Commitment<br>Tracking check box is selected on the General tab<br>(General Settings section).                                                                                                                                            |
| Account Groups (PM201000) form          | Make sure that all needed account groups have been<br>configured and that for all the needed account groups<br>of the Expense type, the Create Commitment check<br>box is selected on the Change RequestSettings tab.                                                            |
| Projects (PM301000) form                | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation.                                                                                                                                                       |
| Vendors (AP303000) form                 | Make sure that all needed vendors have been defined<br>in the system, as described in Vendors: General Infor<br>mation.                                                                                                                                                          |
|                                         | Also, make sure that the expense account of the ven<br>dor specified in the Expense Account box on the GL<br>Accounts tab is mapped to an account group.                                                                                                                         |

| Form                            | Tasks to Perform                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Non-Stock Items (IN202000) form | Make sure that all needed labor items, non-stock<br>items, and services have been defined. For more infor<br>mation about labor items, non-stock items, and ser<br>vices, see Labor Items: General Information, Non-Stock<br>Items: General Information, and Service Items: General<br>Information, respectively.<br>Make sure that Purchases is selected in<br>the Post Cost to Expenses box on the<br>Price/Cost tab; otherwise, the expens<br>es related to the non-stock item will not<br>be recorded to the cost budget of the ap<br>plicable project.<br>Also, make sure that the following accounts are<br>mapped to account groups of the Expense type:<br>•<br>The expense account of the item specified in the<br>Expense Account box on the GL Accounts tab of<br>the Non-Stock Items form<br>•<br>The expense account of the corresponding posting<br>class specified in the COGS/Expense Account box<br>on the GL Accounts tab of the Posting Classes form<br>if the non-stock item requires receipt—that is, the<br>Require Receipt check box is selected on the Gen<br>eral tab (Item Defaults section) of the Non-Stock<br>Items form |
| Stock Items (IN202500) form     | Make sure that all stock items have been defined. For<br>more information about stock items, see Stock Items:<br>General Information.<br>Also, make sure that the COGS account of the item<br>specified in the COGS Account box on the GL Ac<br>counts tab of the Stock Items form is mapped to an ac<br>count group of the Expense type.<br>We recommend that you not map the<br>Inventory account (which is an account<br>of the Asset type) to an account group<br>of the Expense type. If you need to track<br>stock items purchased for the project in<br>the project cost budget, we recommend<br>that you use the commitment tracking<br>functionality. For more information, see<br>Tracking Cost Commitments.                                                                                                                                                                                                                                                                                                                                                                                                                                |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing commitments by specifying additional settings as follows:

• To change the format of purchase order identifiers, adjust the *POORDER* numbering sequence on the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form or create a new numbering sequence and select this sequence in the **Regular Order NumberingSequence** box on the **General** tab of the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form. For more information on numbering sequences, see *[Use of Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f)*.

![](_page_119_Picture_2.jpeg)

A user can create purchase orders by using the **Create Purchase Orders** button on the **Commitments** tab of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* (PM301000) form only if the numbering sequence that is used for numbering purchase orders is auto-numbered.

- To cause the system to automatically select a project task when a particular project is selected during the creation of a purchase order, select the **Default** check box on the**Tasks** tab of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* (PM301000) form for one of the tasks of the project.
- To avoid obligatory printing of created purchase orders, clear the **Print Orders** check box on the **Purchase Settings** tab (**Default Location Settings** section) of the *[Vendors](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a9584be3-f2bd-4d67-80d4-8041d809df56)* (AP303000) form for all applicable vendors. (A user can still print any purchase order of the vendor, if needed.)
- To avoid obligatory emailing of created purchase orders, clear the**Send Orders by Email** check box on the **PurchaseSettings** tab (**Default Location Settings** section) of the *[Vendors](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a9584be3-f2bd-4d67-80d4-8041d809df56)* form for all applicable vendors. (A user can still email any purchase order of the vendor, if needed.)
- To cause the system to automatically release inventory receipts created on release of purchase receipts, select the **Release IN Documents Automatically** check box on the **General** tab (**Other** section) of the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* PO101000 form.
- To cause the system to create purchase receipts with the *Balanced* status, clear the **Hold Receipts On Entry** check box on the **General** tab (**Other** section) of the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form.
- To cause the system to not copy non-stock lines of the *Service* type in purchase orders of the *Normal* type to purchase receipts and bill such lines directly from purchase orders, clear the **ProcessService Lines from Normal Purchase Orders via Purchase Receipt** check box on the **General** tab (**Other** section) of the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form.
- To cause the system to not copy non-stock lines of the *Service* type in purchase orders of the *Drop-Ship* type to purchase receipts and bill such lines directly from purchase orders, clear the **ProcessService Lines from Drop-Ship Purchase Orders via Purchase Receipt** check box on the **General** tab (**Other** section) of the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form.

With these settings specified, users in your company can process commitments quickly and accurately with a minimum of manual actions.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that you perform instructions similar to those described in *[Committed Costs: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0444-16c1-4385-a86e-d9cecd34d4c0)*.

## <span id="page-119-0"></span>**Change Requests: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of change requests, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially create change requests, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                 |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting, Change Orders,<br>and Change Requests features are enabled.                                                                                                                                                                               |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
|                                         | Also, make sure that the default markups are specified<br>on the General tab (Markups section). For more infor<br>mation about configuring markups, see Change Re<br>questsTwo-Tier Change Management: Configuration of<br>Markups.                                              |
| Change Order Classes (PM203000) form    | Make sure that all needed change order classes have<br>been configured and the Two-Tier Change Manage<br>ment check box has been selected for these classes in<br>the Summary area.                                                                                              |
| Account Groups (PM201000) form          | Make sure that the default line markup is specified for<br>all the needed account groups of the Expense type in<br>the Default Line Markup (%) box on the Change Re<br>quest Settings tab.                                                                                       |
| Non-Stock Items (IN202000) form         | Make sure that the default price markup is specified for<br>all the needed inventory items in the Markup % box<br>on the Price/Cost tab (Price Management section).                                                                                                              |
| Stock Items (IN202500) form             | Make sure that the default price markup is specified for<br>all the needed inventory items in the Markup % box<br>on the Price/Cost tab (Price Management section).                                                                                                              |
| Projects (PM301000) form                | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation.                                                                                                                                                       |
|                                         | Also, make sure that the Change Order Workflow<br>check box is selected on theSummary tab (Project<br>Properties section) and the document markups are<br>configured properly on the Defaults tab (Document<br>Markups table).                                                   |

## **Project Commitment Checklist**

If you want to use the functionality of change requests to manage changes in commitments, make sure that all the needed features have been enabled and settings have been specified, as described in *[Committed Costs:](#page-117-2) [Implementation Checklist](#page-117-2)*.

#### **Other Settings That Affect the Workflow**

You can affect the workflow of managing changes in projects by specifying additional settings as follows:

- By default, the *CHANGERST* numbering sequence specifies that the change request identifier is an automatically generated numeric string of six digits, such as *000001*. To change the format of change request identifiers, adjust the *CHANGERST* numbering sequence on the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form or create a new auto-numbered numbering sequence and select this sequence in the **Change Request NumberingSequence** box on the **General** tab (**NumberingSequence** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form. For more information on numbering sequences, see *[Use of Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f)*.
- To allow users to create change requests by using the **Create Change Request** command on the More menu of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* (PM301000) form, for the numbering sequence used for change requests, clear the **Manual Numbering** check box in the Summary area of the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* form.
- To make it possible to create a change order for a change request selected on the *[Change Requests](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0c26a0eb-ef8d-4a61-97c8-732aea21cf25)* (PM308500) form, select the change order class that supports the two-tier change management in the **Default Change Order Class** box on the **General** tab (**GeneralSettings** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* form. That is, the selected change order class must have the**Two-Tier Change Management** check box selected on the *[Change Order Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fdac3e07-8ea5-4c44-85bc-bae8850df2f0)* (PM203000) form.

Even if the default change order class selected in the project accounting preferences does not support the two-tier change management, you still can add a change request to a change order by creating a change order directly on the *[Change Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0c26a0eb-ef8d-4a61-97c8-237aea21cf25)* (PM308000) form, selecting for this change order a change order class that supports the two-tier change management, and adding the change request to the change order.

- To cause the system to automatically select a revenue account group for new estimation lines of a change request if there are multiple account groups of the *Income* type defined on the *[Account Groups](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=94a2cdce-c36a-49a1-b572-9cd33cb5fa73)* (PM201000) form, specify the **Default Revenue Account Group** for account groups of the *Expense* type in the Summary area of the *[Account Groups](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=94a2cdce-c36a-49a1-b572-9cd33cb5fa73)* form. For more information on account groups, see *[Account Groups: General](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f8734904-a3f6-4cef-820b-330894038634) [Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f8734904-a3f6-4cef-820b-330894038634)*.
- To cause the system to automatically select the **Creates Commitment** check box for a new estimation line with a particular account group selected on the *[Change Requests](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0c26a0eb-ef8d-4a61-97c8-732aea21cf25)* form, which results in creation of a commitment based on such an estimation line, select the **Creates Commitment** check box on the**Settings** tab of the *[Account Groups](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=94a2cdce-c36a-49a1-b572-9cd33cb5fa73)* form for this account group. For example, it can be an account group to which you map the expense accounts of the services that a subcontractor usually provides.

With these settings specified, users in your company can process change requests quickly and accurately with a minimum of manual actions.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that you process a change request by performing instructions similar to those described in *Change [RequestsTwo-Tier](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c42c0444-1421-4225-a42e-d9ce4224d4c0) Change Management: [Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c42c0444-1421-4225-a42e-d9ce4224d4c0)*.

## <span id="page-121-0"></span>**Employee Time Billing: Implementation Checklist**

To ensure that the system is configured properly for billing employee time spent for projects, make sure that the features and settings listed in the table are configured as described in the following table.

| Form           | Validation of Settings                                                                                                                                                                                                                                               |
|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Multiple forms | Make sure that all necessary settings of time tracking<br>have been specified, as demonstrated in the exam<br>ples of Time Tracking Configuration: To Configure Time<br>Tracking in Projects and Time Tracking Configuration: To<br>Track Time with Time Activities. |

| Form                                             | Validation of Settings                                                                                                                                                                                             |
|--------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Non-Stock Items (IN202000), Employees (EP203000) | Create the needed labor items to represent project<br>work and assign them to employees, as illustrated in<br>the Labor Items: To Configure a Labor Item.                                                          |
| Labor Rates (PM209900)                           | Define labor cost rates for employees, as demonstrat<br>ed in Labor Items: To Define Labor Cost Rates.                                                                                                             |
| Projects (PM301000)                              | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation, and that labor items are assigned to the ap<br>propriate project tasks on theTasks tab. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of time reporting by specifying additional settings as follows:

- To cause the system to require a particular employee to enter time cards, select the**Time Card is Required** check box on the *[Employees](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dae5144b-49b3-43a4-bce0-93f31b3f2321)* (EP203000) form. If the reporting of time with time activities is configured, the selection of this check box means that time activities can be released only within a time card.
- To cause the system to post project transactions that have been generated on release of time activities to the off-balance account group, select *Post PM to Off-Balance Account Group* in the **Posting Option for Non-Payroll Employee** box, and specify the account group of the *Off-Balance Type* in the **Off-Balance Account Group** on the *Time and Expenses [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* (EP101000) form.
- To cause project transactions to be automatically generated and released on release of time cards, select the **Automatically Release PM Documents** on the *Time and Expenses [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* (EP101000) form.
- To associate an earning type with a particular project or project task, on the *[Earning](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=02757e0d-2d3f-4846-80c8-f2c2490fd386) Types* (EP102000) form, for an earning type, specify the project or project task in the **Default Project Code** box and **DefaultTask** box, respectively.
- To copy notes and attached documents from time cards to generated project transactions, select the **Copy Files to PM Documents** and **Copy Notes to PM Documents** check boxes on the *Time and [Expenses](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* form.

## <span id="page-122-0"></span>**Expense Receipts with Corporate Cards: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for processing expense receipts with the corporate cards, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process expense receipts with corporate cards, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                       | Criteria to Check                                                                                           |
|----------------------------|-------------------------------------------------------------------------------------------------------------|
| Corporate Cards (CA202500) | The corporate card has been configured. For more in<br>formation, see Corporate Cards: General Information. |

| Form                            | Criteria to Check                                                                                                                 |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Employees (EP203000) form       | The employees who are going to use the corporate<br>cards have been created. For more information, see<br>Employee Settings.      |
| Non-Stock Items (IN202000) form | The inventory items to be used in expense receipts<br>have been created and the Expense type has been<br>specified for the items. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing expense receipts with the corporate cards by specifying additional settings on the *Time and Expenses [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* (EP101000) form, as follows:

- To make a newly created expense claim have the *On Hold* status by default, you select the **Hold Expense Claims on Entry** check box.
- To cause the system to automatically release corresponding accounts payable documents created on release of an expense claim, select the **Automatically Release AP Documents** check box.
- To cause the system to create a single cash purchase or cash return for each group of expense claim lines that are paid with a corporate card and have the same date, corporate card, reference number, and tax calculation mode, select the **PostSummarized Company Expenses by Corporate Card** check box. If the check box is cleared, which is the default state, the system creates a separate cash purchase (if the total amount of lines is positive or equals *0*) or cash return (if the total amount of lines is negative) for each expense claim line that is paid with a corporate card.
- To make the **Ref. Nbr.** box in the **Expense Details** section on the **Details** tab of the *[Expense Receipts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0759209d-e85d-4f7e-9269-e827556a80be)* (EP301010) form required, you select the **Require Ref. Nbr. in Expense Receipts** check box. If this check box is cleared, a value in the **Ref. Nbr.** box is not required.
- If approval of expense receipts is necessary, you create an approval map, and assign this map in the **Expense Receipt Approval Map** box. If approval notifications are necessary, you select a template in the **Expense Receipt Notification** box.
- If approval of expense claims is necessary, you create an approval map, and assign this map in the **Expense Claim Approval Map** box. If approval notifications are necessary, you select a template in the **Expense Claim Notification** box.

With these settings specified, users in your company can process expense receipts with corporate cards quickly and accurately with a minimum of manual actions.

## **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process expense receipts with corporate cards, as described in *Expense Receipts with [Corporate](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e05f8f66-7eee-43bb-be83-12a10b1bcd12) Cards: To Claim Expenses for a Project*.

## <span id="page-123-0"></span>**Expense Returns to Corporate Cards: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for processing expense returns to corporate cards, and to understand (and change, if needed) the settings that affect the processing workflow.

### **Implementation Checklist**

We recommend that before you initially process expense returns to corporate cards, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                            | Criteria to Check                                                                                                                  |
|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| Corporate Cards (CA202500)      | The corporate card has been configured. For more in<br>formation, see Corporate Cards: General Information.                        |
| Employees (EP203000) form       | The employees who are going to use the corporate<br>cards have been created. For more information, see<br>Employee Settings.       |
| Non-Stock Items (IN202000) form | The inventory items to be used in expense receipts<br>have been created, and the Expense type has been<br>specified for the items. |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing expense returns to corporate cards by specifying additional settings on the *Time and Expenses [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* (EP101000) form, as follows:

- To cause the system to make a newly created expense claim have the *On Hold* status by default, select the **Hold Expense Claims on Entry** check box.
- To cause the system to create a single cash purchase or cash return for each group of expense claim lines that are paid with a corporate card and have the same date, corporate card, reference number, and tax calculation mode, select the **PostSummarized Company Expenses by Corporate Card** check box. If the check box is cleared, which is the default state, the system creates a separate cash purchase (if the total amount of lines is positive or equals *0*) or cash return (if the total amount of lines is negative) for each expense claim line that is paid with a corporate card.
- To make it optional to specify a value in the **Ref. Nbr.** box on the **Details** tab (**Expense Details** section) of the *[Expense Receipts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0759209d-e85d-4f7e-9269-e827556a80be)* (EP301010) form, clear the **Require Ref. Nbr. in Expense Receipts** check box. If this check box is selected, users must specify a value in the **Ref. Nbr.** box.
- To cause the system to automatically release corresponding accounts payable documents created on release of an expense claim, select the **Automatically Release AP Documents** check box.

With these settings specified, users in your company can process expense returns quickly and accurately with a minimum of manual actions.

## <span id="page-124-0"></span>**Overhead in the Project Budget: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for considering the project overhead, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially consider the project overhead, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                 |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting feature is en<br>abled.                                                                                                                                                                                                                    |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
| Account Groups (PM201000) form          | Make sure that an account group of the Expense type<br>for the overhead has been created. For details on con<br>figuring account groups, see Account Groups: General<br>Information.                                                                                             |
| Allocation Rules (PM207500) form        | Make sure that an allocation rule is configured as de<br>scribed in Overhead in the Project Budget: Implementa<br>tion Activity.                                                                                                                                                 |
| Projects (PM301000)                     | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation.                                                                                                                                                       |

## **Other Settings That Affect the Workflow**

To cause the system to automatically release allocation transactions, including allocation reversal transactions, select the **Automatically Release Allocations** check box on the **General** tab (**GeneralSettings** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you allocate projects by performing instructions similar to those described in *[Overhead in the Project Budget: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d080755a-1ab3-411d-9fe8-d113c321b13b)*.

## <span id="page-125-0"></span>**Pro Forma Invoices: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing pro forma invoices, and to understand (and change, if needed) the settings that affect the processing workflow.

### **Implementation Checklist**

We recommend that before you initially process pro forma invoices, you make sure the needed settings have been specified and entities have been created, as summarized in the following checklist.

| Form                                 | Criteria to Check                                                                                                                                                                                                                                                                |
|--------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Projects Preferences (PM101000) form | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
| Billing Rules (PM207000) form        | Make sure that all needed billing rules have been con<br>figured in the system. For more information about<br>billing rules, see Billing Rules: General Information.                                                                                                             |
| Projects (PM301000) form             | Make sure that the project has been created and pre<br>pared for billing. For more details, see Project Creation<br>and Processing: General Information.                                                                                                                         |
|                                      | For each project for which you want to turn on the<br>pro forma invoice workflow, make sure that the Cre<br>ate Pro Forma on Billing check box is selected on the<br>Summary tab (Billing and Allocation Settings sec<br>tion).                                                  |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing pro forma invoices by specifying additional settings as follows:

• To change the format of pro forma invoice identifiers, adjust the *PROFORMA* numbering sequence on the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form, or create a new numbering sequence and select this sequence in the **Pro Forma NumberingSequence** box on the **General** tab (**NumberingSequence** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form. For more information on numbering sequences, see *[Use of](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f) [Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f)*.

![](_page_126_Picture_5.jpeg)

Pro forma invoice identifiers must be assigned only automatically. That is, the **Manual Numbering** check box must be cleared in the Summary area of the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* form for the numbering sequence used for pro forma invoices.

By default, the *PROFORMA* numbering sequence specifies that the pro forma invoice identifier is an automatically generated numeric string of six digits, such as *000001*.

- To give accounts receivable invoices, including those created based on pro forma invoices, the *On Hold* status on creation, select the **Hold Documents on Entry** check box on the **General** tab (**Data EntrySettings** section) of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form.
- To make sending by email accounts receivable invoices optional, including those created based on pro forma invoices that have been agreed upon with the customer, clear the**Send Invoices by Email** check box on the **BillingSettings** tab (**Print and EmailSettings** section) of the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* (AR303000) form for applicable customers.
- To make printing accounts receivable invoices optional, including those created based on pro forma invoices that have been agreed upon with the customer, clear the **Print Invoices** check box on the **Billing Settings** tab (**Print and EmailSettings** section) of the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* form for applicable customers.
- To cause the system to automatically post general ledger transactions generated on release of all accounts receivable invoices, select the **Automatically Post on Release** check box on the **General** tab (**Posting Settings** section) of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* form.

• To cause the system to post every accounts receivable document as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box in the **PostingSettings** section of the *[General](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form.

With these settings specified, users in your company can process pro forma invoices quickly and accurately with a minimum of manual actions.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process a pro forma invoice by performing instructions similar to those described in *Pro Forma [Invoices:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0234-16c1-4385-a12e-d9cecd34d4c0) To Process a Pro [Forma Invoice for a Project](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0234-16c1-4385-a12e-d9cecd34d4c0)*.

## <span id="page-127-0"></span>**Project Quotes: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the creation of project quotes and projects based on project quotes, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially create project quotes, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                 |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting and Project<br>Quotes features are enabled.                                                                                                                                                                                                |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
| Project Templates (PM208000) form       | Make sure that all needed project templates have been<br>configured. For more information about project tem<br>plates, see Project Templates and Common Tasks: Gen<br>eral Information.                                                                                          |
| Business Account Classes (CR208000)     | Make sure that business account classes with the nec<br>essary settings and attributes have been created, as<br>described in Defining Business Account Classes.                                                                                                                  |
| Business Accounts (CR303000)            | Make sure that business accounts with the neces<br>sary settings and attributes have been created, as de<br>scribed in Creating Business Accounts.                                                                                                                               |

#### **CRM Settings Checklist**

If you want to use the functionality of opportunities to create project quotes, make sure that the needed features have been enabled and settings have been specified, as summarized in the following checklist.

| Form                                            | Criteria to Check                                                                                                                                             |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form         | Make sure that the Customer Management feature is<br>enabled.                                                                                                 |
| Customer Management Preferences (CR101000) form | Make sure that all necessary settings related to cus<br>tomer management have been specified.                                                                 |
| Opportunity Classes (CR209000)                  | Make sure that opportunity classes with the necessary<br>settings, attributes, and stages have been created, as<br>described in Defining Opportunity Classes. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing project quotes by specifying additional settings as follows:

• To change the format of project quote identifiers, adjust the *PMQUOTE* numbering sequence on the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form or create a new numbering sequence and select this sequence in the **Quote NumberingSequence** box on the **General** tab (**NumberingSequence** section) of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form. Project quote identifiers must be assigned only automatically. For more information on numbering sequences, see *[Use of Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f)*.

By default, the *PMQUOTE* numbering sequence specifies that the project quote identifier is an automatically generated alphanumeric string that starts with the *PQ* prefix and followed by six digits, such as *PQ000001*.

- To cause the system to automatically select a project template on creation of project quotes, select the project template in the **Default QuoteTemplate** box on the **General** tab (**DefaultSettings** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* form.
- To cause the system to automatically select the revenue account group for new estimation lines of a project quote if there are multiple income account groups defined on the *[Account Groups](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=94a2cdce-c36a-49a1-b572-9cd33cb5fa73)* (PM201000) form, specify the **Default Revenue Account Group** for expense account groups in the Summary area of the *[Account](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=94a2cdce-c36a-49a1-b572-9cd33cb5fa73) [Groups](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=94a2cdce-c36a-49a1-b572-9cd33cb5fa73)* form. For more information on account groups, see *[Account Groups: General Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f8734904-a3f6-4cef-820b-330894038634)*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process a project quote by performing instructions similar to those described in *Project Quotes: To [Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fb10511a-7654-46fd-9fe8-df66c3cfb01b) a Project Quote Based on an [OpportunityProject](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fb10511a-7654-46fd-9fe8-df66c3cfb01b) Quotes: To Create a Project Quote Based on an Opportunity*.

## <span id="page-128-0"></span>**Project Budget: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for managing project budgets, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially manage project budgets, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Tasks to Perform                                                                                                                                                                                                                                                                                  | Notes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|--------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the Project Account<br>ing feature is enabled.                                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Projects Preferences (PM101000)<br>form    | Make sure that all necessary set<br>tings related to project accounting<br>have been specified. For more in<br>formation about the configuration<br>steps that you have to perform be<br>fore you can start accounting for<br>projects, see Basic Project Configu<br>ration: General Information. | If you are going to use inventory<br>items in the revenue budget of your<br>projects, on the General tab, se<br>lect Detailed in the Revenue Bud<br>get Update box. With this option<br>selected, if a transaction has an<br>inventory item specified and the<br>revenue budget has no line with<br>this item, the system creates a new<br>budget line with this item.<br>With the Summary option selected<br>(the default option), if such a line<br>exists in the revenue budget, the<br>system updates it with the emp<br>ty item code (N/A) instead of the<br>inventory item of the transaction.<br>If no such line exists, the system<br>creates a new budget line with the<br>empty item code.<br>The system updates the cost bud<br>get similarly based on the option<br>selected in the Cost Budget Up<br>date box on the General tab. |
| Account Groups (PM201000) form             | Make sure that all needed account<br>groups have been configured. For<br>more information about account<br>groups, see Account Groups: Gener<br>al Information.                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Non-Stock Items (IN202000) form            | Make sure that all needed labor<br>items, non-stock items, and ser<br>vices have been defined. For more<br>information, see Labor Items: Gen<br>eral Information, Non-Stock Items:<br>General Information, and Service<br>Items: General Information, respec<br>tively.                           | Make sure that Pur<br>chases is selected in<br>the Post Cost to Ex<br>penses box on the<br>Price/Cost tab; oth<br>erwise, the expens<br>es related to the non<br>stock item will not be<br>recorded to the cost<br>budget of the applica<br>ble project.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

| Form                     | Tasks to Perform                                                                                                             | Notes                                                                                                                                                                                                                                                                       |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Projects (PM301000) form | Make sure that the project has been<br>created, as described in Project<br>Creation and Processing: General In<br>formation. | If you need to make the revenue<br>budget more detailed by adding<br>the inventory item to the budget<br>structure, select Task and Item in<br>the Revenue Budget Level box.<br>With this setting, a user can select<br>an inventory item in a revenue bud<br>get line.     |
|                          |                                                                                                                              | If you need to make the cost bud<br>get less detailed by excluding the<br>inventory item from the budget<br>structure, select Task in the Cost<br>Budget Level box. With this set<br>ting, a user will not be able to select<br>an inventory item in a cost budget<br>line. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of managing the project budget by specifying additional settings as follows:

- To allow a user to enter subcontract lines and purchase order lines related to a project if the project budget key in these lines was not initially specified in the cost budget of the project, select the **Allow Adding New Items on the Fly** check box on the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* (PM301000) form.
- To cause the system to control whether an entered document is within the cost budget of a project, select *Show a Warning* in the **Budget Control** box on the **General** tab (**GeneralSettings** section) of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form.
- To change the default empty item code (*<N/A>*), which is selected in a project budget line to indicate that no specific item is associated with the line, specify the needed value in the **Empty Item Code** box on the **General** tab (**GeneralSettings** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form.

With these settings specified, users in your company can manage the project budget quickly and accurately.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you manage the project budget by performing instructions similar to those described in *Project Budget: To [Configure](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fb50755a-1813-11fd-9fe8-df13c321b13b) and Update [the Budget](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fb50755a-1813-11fd-9fe8-df13c321b13b)*.

## <span id="page-130-0"></span>**Project Budget Forecasts: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for creating project budget forecasts, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially create project budget forecasts, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                 |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting and Budget Fore<br>cast features are enabled.                                                                                                                                                                                              |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
| Projects (PM301000) form                | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation, the project budget is not locked, and the<br>Change Order Workflow check box is cleared on the<br>Summary tab (Project Properties section).           |

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you create a project budget forecast by performing instructions similar to those described in *[Project Budget Forecasts: Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0111-16c1-4385-a86e-d9cecd31d1c0) [Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0111-16c1-4385-a86e-d9cecd31d1c0)*.

## <span id="page-131-0"></span>**Project Templates and Common Tasks: Implementation Checklist**

To ensure that the system is configured properly for creating project templates and common tasks, make sure that the features and settings listed in the table are configured as described in the following table.

| Form                                    | Task to Perform                                                                      |
|-----------------------------------------|--------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting check box is<br>selected.                      |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings of project ac<br>counting have been specified. |
| Account Groups (PM201000) form          | Make sure that all the necessary account groups have<br>been configured.             |

## <span id="page-131-1"></span>**Project Transactions: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for processing project transactions, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially process project transactions, you make sure that the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                 | Tasks to Perform                                                                                                                                                                                                                                                                                                  |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Projects Preferences (PM101000) form | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information.                                  |
| Account Groups (PM201000) form       | Make sure that all needed account groups have been<br>configured and that all needed general ledger ac<br>counts are mapped to these groups. For more informa<br>tion about account groups, see Account Groups: Gen<br>eral Information.                                                                          |
| Projects (PM301000) form             | Make sure that the project has been created. For more<br>details, see Project Creation and Processing: General In<br>formation.                                                                                                                                                                                   |
| Non-Stock Items (IN202000) form      | Make sure that all needed labor items, non-stock<br>items, and services have been defined. For more infor<br>mation about labor items, non-stock items, and ser<br>vices, see Labor Items: General Information, Non-Stock<br>Items: General Information, and Service Items: General<br>Information, respectively. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing project transactions by specifying additional settings as follows:

• To change the format of project transaction identifiers, adjust the *PMTRAN* numbering sequence on the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form, or create a new numbering sequence and select this sequence in the **Transaction NumberingSequence** box on the **General** tab (**NumberingSequence** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form. For more information on numbering sequences, see *[Use of](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f) [Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f)*.

![](_page_132_Picture_7.jpeg)

Project transaction identifiers must be assigned only automatically. That is, the **Manual Numbering** check box must be cleared in the Summary area of the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* form for the numbering sequence used for project transactions.

By default, the *PMTRAN* numbering sequence specifies that the project transaction identifier is an automatically generated alphanumeric string that starts with the *PM* prefix and is followed by eight digits, such as *PM00000001*.

- To cause the system to post every document you enter as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box in the **PostingSettings** section of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form.
- To make the system automatically associate additional project transactions that are generated (such as discounts or freight charges) with specific project tasks, map specific general ledger accounts to these

project tasks within the project in the **DefaultTask for GL Account** section on the **Defaults** tab of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* form. For more information, see *Default Project Tasks in [Record](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d7fbd4aa-6e32-4bf7-acc2-1aa2f22dc0fe) Lines*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process a project transaction by performing instructions similar to those described in *Project [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0111-16c1-4385-a86e-d9cecd34d4c0) Process Activity*.

## <span id="page-133-0"></span>**Project Inventory Tracking by Warehouse Location: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for tracking project inventory by location, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

Before you start working with a project and tracking project inventory by location, you should make sure that the project accounting functionality is configured and the project has the needed settings, as summarized in the following checklist.

| Form                                    | Criteria to Check                                                                                                                                                                                                                                                                                                 |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting feature is en<br>abled.                                                                                                                                                                                                                                                     |
| Account Groups (PM201000) form          | Make sure that all needed account groups have been<br>configured. For more information about account<br>groups, see Account Groups: General Information.                                                                                                                                                          |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified, as described in the Ba<br>sic Project Configuration: General Information.                                                                                                                                             |
| Projects (PM301000)                     | Make sure that the necessary project and project tasks<br>have been created. In the project settings, Track by Lo<br>cation needs to be selected in the Inventory Track<br>ing box on theSummary tab. For more information on<br>creating a project, see Project Creation and Processing:<br>General Information. |

| Form                       | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Warehouses (IN204000) form | Make sure that a separate location is created and asso<br>ciated with each project task for which you need to re<br>ceive inventory items in a warehouse. (For a location<br>associated with a project task, the CostSeparately<br>check box is selected automatically.)<br>We also recommend that you specify a<br>higher Pick Priority value for project<br>locations than for other locations, to<br>avoid issuing project materials for oth<br>er projects or to customers outside of<br>projects. |

## **Inventory and Order Management Checklist**

We recommend that before you start working with a project and tracking project inventory by location, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the following features are enabled:<br>•<br>Inventory and Order Management<br>•<br>Inventory<br>•<br>Multiple Warehouses<br>•<br>Multiple Warehouse Locations                                                                                                                                                                                                                                                                                                                             |
| Multiple forms                          | Make sure that the basic inventory and order manage<br>ment preferences have been configured, as described<br>in Configuration of Order Management: General Informa<br>tion.                                                                                                                                                                                                                                                                                                                             |
| Stock Items (IN202500) form             | Make sure that all stock items have been defined. For<br>more information about stock items, see Stock Items:<br>General Information.<br>We recommend that you not map the in<br>ventory accrual account (which is an ac<br>count of the Asset type) to an account<br>group. If you need to track stock items<br>purchased for the project in the project<br>cost budget, we recommend that you use<br>the commitment tracking functionality.<br>For more information, see Tracking Cost<br>Commitments. |

| Form                            | Tasks to Perform                                                                                                                                                                                                                       |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Non-Stock Items (IN202000) form | Make sure that all non-stock items have been defined,<br>as described in Non-Stock Items: General Information.<br>Also, make sure that the expense account of the items<br>is mapped to the appropriate account group.                 |
|                                 | Make sure that Purchases is selected in<br>the Post Cost to Expenses box on the<br>Price/Cost tab; otherwise, the expens<br>es related to the non-stock item will not<br>be recorded to the cost budget of the ap<br>plicable project. |
| Vendors (AP303000) form         | Make sure that all needed vendors have been defined<br>in the system, as described in Vendors: General Infor<br>mation.                                                                                                                |

### **Other Settings That Affect the Workflow**

You can affect the workflow of sales and purchases of items for projects by specifying additional settings as follows:

- To cause the system to automatically select a project task when a particular project is selected during the creation of a purchase order, select the **Default** check box on the**Tasks** tab of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* (PM301000) form for one of the tasks of the project.
- To cause the system to include non-stock lines of the *Service* type in purchase receipts created from the purchase orders of the *Normal* type, select the **ProcessService Lines from Normal Purchase Orders via Purchase Receipt** check box on the **General** tab (**Other** section) of the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that you perform instructions similar to those described in *Project Inventory Tracking by [Warehouse](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0111-16c1-abb5-1234-d9cecd31d1c0) Location: To Purchase Materials and Services [for a Project](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0111-16c1-abb5-1234-d9cecd31d1c0)*.

## <span id="page-135-0"></span>**Purchasing Services for Projects: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing purchases for projects with accounts payable bills, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process purchases for projects with AP bills, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                                                                                                 |  |
|-----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting feature is en<br>abled.                                                                                                                                                                                                                                                                                                    |  |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information.                                                                                 |  |
| Projects (PM301000) form                | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation.                                                                                                                                                                                                                                       |  |
| Non-Stock Items (IN202000) form         | Make sure that all needed labor items, non-stock<br>items, and services have been defined. Make sure that<br>the Require Receipt check box is cleared in the Item<br>Defaults section on the General tab.                                                                                                                                                        |  |
|                                         | Make sure that Purchases is selected in<br>the Post Cost to Expenses box on the<br>Price/Cost tab; otherwise, the expens<br>es related to the non-stock item will not<br>be recorded to the cost budget of the ap<br>plicable project.                                                                                                                           |  |
|                                         | For more information about labor items, non-stock<br>items, and services, see Labor Items: General Informa<br>tion, Non-Stock Items: General Information, and Service<br>Items: General Information, respectively.                                                                                                                                               |  |
| Account Groups (PM201000) form          | Make sure that all needed account groups have been<br>configured. Also, make sure that the expense accounts<br>of the inventory items specified in the Expense Ac<br>count box on the GL Accounts tab of the Non-Stock<br>Items form are mapped to the account groups. For<br>more information about account groups, see Account<br>Groups: General Information. |  |
| Vendors (AP303000) form                 | Make sure that all needed vendors have been defined<br>in the system, as described in Vendors: General Infor<br>mation.                                                                                                                                                                                                                                          |  |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing purchases for projects by specifying additional settings as follows:

- To cause the system to automatically select a project task when a particular project is selected during the creation of a bill, select the **Default** check box on the**Tasks** tab of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* (PM301000) form for one of the tasks of the project.
- To cause the system to create accounts payable bills with the *Balanced* status, clear the **Hold Documents on Entry** check box on the **General** tab (**Data EntrySettings** section) of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form.

• To cause the system to automatically post general ledger batches generated during processing account payable documents, select the **Automatically Post on Release** check box in the **PostingSettings** section on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form.

With these settings specified, users in your company can process purchases for projects with AP bills quickly and accurately with a minimum of manual actions.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that you perform instructions similar to those described in *[Purchasing Services for Projects: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c53c0444-16c1-4385-1234-d9cecd34d4c0)*.

## <span id="page-137-0"></span>**Single-Tier Change Management: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of change orders, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially create change orders, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                       | Tasks to Perform                                                                                                                                                                                                                                                                              | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the Project Account<br>ing and Change Orders features are<br>enabled.                                                                                                                                                                                                          |       |
| Projects Preferences (PM101000)<br>form    | Make sure that all necessary set<br>tings related to project account<br>ing have been specified. For more<br>information about configuration<br>steps that you have to perform be<br>fore you can start accounting for<br>projects, see Basic Project Configu<br>ration: General Information. |       |
| Change Order Classes (PM203000)<br>form    | Make sure that all needed change<br>order classes have been config<br>ured, as described in Change Or<br>ders for Commitments: To Create a<br>Change Order Class.                                                                                                                             |       |

| Form                     | Tasks to Perform                                                                                                                                                                                                                                               | Notes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Projects (PM301000) form | Make sure that the project has been<br>created, as described in Project<br>Creation and Processing: General In<br>formation.<br>Also, make sure that the Change<br>Order Workflow check box is<br>selected on the Summary tab<br>(Project Properties section). | If the Internal Cost Commitment<br>Tracking check box is selected on<br>the General tab (General Settings<br>section) of the Projects Preferences<br>(PM101000) form, and a project has<br>related purchase orders, you can<br>select the Change Order Work<br>flow check box for the project if the<br>project has no open related pur<br>chase order lines. That is, the sta<br>tus of the related purchase order<br>lines of the project is only Complet<br>ed, Closed, or Canceled. |

## **Checklist for Project Commitments**

If you want to use the functionality of change orders to manage changes in commitments, make sure that all the needed features have been enabled and settings have been specified, as described in *[Committed Costs:](#page-117-2) [Implementation Checklist](#page-117-2)*.

## **Other Settings That Affect the Workflow**

You can affect the workflow of managing changes in projects by specifying additional settings as follows:

- To change the format of change order identifiers, adjust the *CHANGEORD* numbering sequence on the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form or create a new auto-numbered sequence and select this sequence in the **Change Order NumberingSequence** box on the **General** tab (**NumberingSequence** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form. For more information on numbering sequences, see *[Use of](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f) [Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=71c26175-c78f-4e70-8518-2115f5bfaf2f)*.
- To allow users to create change orders by using the **Create Change Order** command on the More menu of the *[Projects](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81c86417-3bde-444b-8f1c-682928d31a0c)* (PM301000) form, clear the **Manual Numbering** check box in the Summary area of the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* form for the numbering sequence used for change orders.
- To cause the system to automatically select a change order class on creation of change orders, select the change order class in the **Default Change Order Class** box on the **General** tab (**GeneralSettings** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* form.

With these settings specified, users in your company can process change orders quickly and accurately with a minimum of manual actions.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that you process a change order by performing instructions similar to those described in *Single-Tier Change [Management:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fb50755a-1813-46fd-9fe8-dfabb321b137) To Track Changes to the [Project Budget](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fb50755a-1813-46fd-9fe8-dfabb321b137)* and *[Change Orders for Commitments: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fb50755a-1813-46fd-9fe8-dfaccc21b137)*.

## <span id="page-138-0"></span>**Taxes in Projects: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for calculating tax in project-related documents, and to understand (and change, if needed) the settings that affect the processing workflow.

## **General Setting Checklist**

To ensure that the system is configured properly for creating project-related documents with taxes applied automatically, make sure that the criteria listed in the table have been met in the system as described.

| Form                                                  | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tax Zones(TX206000)                                   | All needed tax zones have been defined to include the applic<br>able taxes in the location that corresponds to each tax zone.                                                                                                                                                                                                                                                                                                                                                                                    |
|                                                       | For details, see Tax Zones and Categories: To Review Tax Cat<br>egories and Create a Tax Zone for Sales Taxes.                                                                                                                                                                                                                                                                                                                                                                                                   |
| Tax Categories (TX205500)                             | The needed tax categories have been created for all goods<br>and services (which are represented as stock items and non<br>stock items in Acumatica ERP) that your company buys or<br>sells. For each tax category, you should add all taxes that are<br>applied to the corresponding category of goods and services<br>in all geographical locations where your company conducts<br>business.<br>For details, see Tax Zones and Categories: To Review Tax Cat<br>egories and Create a Tax Zone for Sales Taxes. |
| Vendors (AP303000)                                    | The needed vendors should be created in the system. To de<br>fine which taxes are applied in the location of each vendor,<br>the appropriate tax zone should be assigned to the vendor.                                                                                                                                                                                                                                                                                                                          |
| Customers (AR303000)                                  | The needed customers should be created in the system. To<br>define which taxes are applied in the location of each cus<br>tomer, the appropriate tax zone should be assigned to the<br>customer.                                                                                                                                                                                                                                                                                                                 |
| Stock Items (IN202500), Non-Stock Items<br>(IN202000) | For the calculation of tax amounts in the documents in which<br>you specify inventory IDs, stock items (for goods) and non<br>stock items (for services) should be created and the appropri<br>ate tax category should be assigned to each item.                                                                                                                                                                                                                                                                 |

## **Project-Specific Tax Checklist**

We recommend that before you initially process project-related documents with project-specific tax zones, you make sure the needed settings have been specified, as summarized in the following checklist.

| Form                            | Criteria to Check                                                                 |
|---------------------------------|-----------------------------------------------------------------------------------|
| Projects Preferences (PM101000) | The Calculate Project-SpecificTaxes check box is se<br>lected on the General tab. |

| Form                | Criteria to Check                                                                                                                                                                  |
|---------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Projects (PM301000) | In the TaxSettings section of the Addresses tab of<br>the form, the following project-specific tax zones have<br>been specified:                                                   |
|                     | •<br>CostTax Zone: The tax zone to be used in the cost<br>documents (such as bills, purchase orders, and<br>subcontracts) related to the project instead of the<br>vendor tax zone |
|                     | •<br>RevenueTax Zone: The tax zone to be used in the<br>revenue documents (such as invoices and sales or<br>ders) related to the project instead of the customer<br>tax zone       |

## **Sales Tax Checklist**

To ensure that the system is configured properly for creating project-related documents with a sales tax applied automatically, make sure that the criteria listed in the table have been met in the system as described.

This table lists only project-specific part of configuring the system for application of sales taxes. For a detailed description on configuring sales taxes, see *Sales [Taxes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=998faa0b-d6ce-4d2c-b60f-2f128e265444)*.

| Form                           | Criteria to Check                                                                                                                                                                   |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Chart of Accounts (GL202500)   | The following GL accounts, which you will use for tax report<br>ing purposes have been added:                                                                                       |
|                                | •<br>A liability account that will be used for accumulating the<br>tax amounts to be paid to the tax agency in a tax period                                                         |
|                                | •<br>The Tax Expense account that will be used to record the<br>tax adjustments and expenses for the tax agency<br>•<br>The tax rounding gains and losses accounts                  |
| Account Groups (PM201000) form | An account group of the Expense type has been configured<br>and the Tax Expense account has been mapped to this ac<br>count group.                                                  |
|                                | For details, see Account Groups: To Create an Expense Ac<br>count Group.                                                                                                            |
| Taxes (TX205000)               | The sales tax should be created. The settings for the tax in<br>clude the tax rate, the tax calculation method, the tax validity<br>period (if any), and other required parameters. |
|                                | Also, make sure on the GL Accounts tab, the UseTax Ex<br>pense Account check box is selected and theTax Expense<br>Account is specified.                                            |
|                                | For details, see Sales Taxes: To Configure a Sales Tax for Use<br>in AP.                                                                                                            |

### **Use Tax Checklist**

To ensure that the system is configured properly for creating project-related documents with a use tax applied automatically, make sure that the criteria listed in the table have been met in the system as described.

This table lists only the project-specific part of configuring the system for application of use taxes. For a detailed description of the process of configuring use taxes, see *[Use](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=95fee3b0-df58-44ef-bfd7-15b3bc6c868c) Tax*.

| Form                           | Criteria to Check                                                                                                                                                                                                    |
|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Chart of Accounts (GL202500)   | The following GL accounts, which you will use for tax report<br>ing purposes, have been added:                                                                                                                       |
|                                | •<br>A liability account that will be used for accumulating the<br>tax amounts to be paid to the tax agency in a tax period                                                                                          |
|                                | •<br>The Tax Expense account that will be used to record tax<br>adjustments and expenses for the tax agency                                                                                                          |
|                                | •<br>The tax rounding gains and losses accounts                                                                                                                                                                      |
| Account Groups (PM201000) form | An account group of the Expense type has been configured<br>and the Tax Expense account has been mapped to this ac<br>count group. For details, see Account Groups: To Create an<br>Expense Account Group.           |
| Taxes (TX205000)               | The use tax to be applied to your documents should be cre<br>ated. The settings for the tax include the tax rate, the tax cal<br>culation method, the tax validity period (if any), and other re<br>quired settings. |
|                                | Also, on the GL Accounts tab, the UseTax Expense Account<br>check box should be selected and theTax Expense Account<br>should be specified.                                                                          |
|                                | For details, see Use Taxes: Implementation Activity.                                                                                                                                                                 |

For a detailed description of configuring sales taxes, see *Sales [Taxes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=998faa0b-d6ce-4d2c-b60f-2f128e265444)*.

## <span id="page-141-0"></span>**Time Tracking Configuration: Implementation Checklist**

The following sections provide details you can use to ensure that the time tracking functionality in the system is configured properly to be used in accounting for projects.

## **Prerequisite Configuration**

To ensure that the prerequisite configuration has been implemented properly, make sure that the necessary entities have been defined,and settings have been specified, as described in the following checklist.

| Form                           | Criteria to Check                                                                                                                                                                                                                                                                                                                      |
|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Multiple forms                 | The minimum company settings have been specified,<br>as described in Company Without Branches: General In<br>formation.                                                                                                                                                                                                                |
| Earning Types (EP102000)       | Additional earning types, if needed, have been defined<br>in addition to the predefined earning types. Also, for<br>the earning types that relate to the employee time to<br>be billed within the project, the Billable check box will<br>be selected. For information on earning types, see Em<br>ployee Time Entry: Time Activities. |
| Employees (EP203000)           | All employees for whom time will be tracked have<br>been defined. For details, see Employee Settings.                                                                                                                                                                                                                                  |
| Activity Types (CR102000) form | Activity types have been defined, if needed, in addition<br>to those that are predefined in the system                                                                                                                                                                                                                                 |

## **Configuration of Reporting Time with Time Cards**

To ensure that the basic time reporting configuration has been implemented properly and the employees will be able to log time spent on projects in time cards, make sure that the necessary features have been enabled, entities have been defined, and settings have been specified, as described in the following checklist.

| Form                                     | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)       | The Advanced Financials and Projects features are en<br>abled.                                                                                                                                                                                                                                                                                                                                                                        |
| Time and Expenses Preferences (EP101000) | In the Posting Option for Non-Payroll Employee box<br>(in the Time Reporting Settings section of the Gen<br>eral Settings tab), Post PM and GL Transactions is se<br>lected, which means that on release of time cards and<br>time activities, the system generates project account<br>ing and general ledger transactions.                                                                                                           |
| Projects Preferences (PO101000)          | In the Visibility Settings section, the Time Entries<br>and Expenses check boxes are selected.<br>In the Expense AccountSource and Expense Accru<br>al Account boxes of the Account Settings section, the<br>sources for the expense account and expense accru<br>al account have been selected; these settings define<br>the debit and credit accounts to be used in the project<br>transactions generated on release of time cards. |
| Non-Stock Items (IN202000)               | The labor items that are needed for all employees for<br>all available earning types have been created, as illus<br>trated in the Labor Items: To Configure a Labor Item.                                                                                                                                                                                                                                                             |
| Labor Rates (PM209900)                   | Labor cost rates for employees have been defined, as<br>illustrated in Labor Items: To Define Labor Cost Rates.                                                                                                                                                                                                                                                                                                                       |

## **Configuration of Reporting Time with Time Activities**

To ensure that the employees will be able to log time with time activities, make sure that the necessary features have been enabled and settings have been specified, as described in the following checklist.

| Form                               | Criteria to Check                                                                                                                 |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Time Management feature is enabled.                                                                                           |
| Activity Types (CR102000)          | The TrackTime and Costs check box is selected for<br>the activity types for which you want to track billable<br>time in projects. |

## **Other Settings That Affect the Workflow**

You can affect the workflow of time reporting by specifying additional settings as follows:

- To cause the system to require a particular employee to enter time cards, select the**Time Card is Required** check box on the *[Employees](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dae5144b-49b3-43a4-bce0-93f31b3f2321)* (EP203000) form. If the reporting of time with time activities is configured, the selection of this check box means that time activities can be released only within a time card.
- To cause the system to post project transactions that have been generated on release of time activities to the off-balance account group, select *Post PM to Off-Balance Account Group* in the **Posting Option for Non-Payroll Employee** box, and specify the account group of the *Off-Balance Type* in the **Off-Balance Account Group** on the *Time and Expenses [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* (EP101000) form.
- To cause project transactions to be automatically generated and released on release of time cards, select the **Automatically Release PM Documents** on the *Time and Expenses [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* (EP101000) form.
- To associate an earning type with a particular project or project task, on the *[Earning](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=02757e0d-2d3f-4846-80c8-f2c2490fd386) Types* (EP102000) form, for an earning type, specify the project or project task in the **Default Project Code** box and **DefaultTask** box, respectively.
- To copy notes and attached documents from time cards to generated project transactions, select the **Copy Files to PM Documents** and **Copy Notes to PM Documents** check boxes on the *Time and [Expenses](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e9f4a914-c4ce-4c4f-95d9-f385451e5856)* form.

## <span id="page-143-0"></span>**Vendor Payments for a Project: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for paying AP bills for a project, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you start preparing payments for AP bills, you make sure the needed settings have been specified and entities have been created, as summarized in the following checklist.

| Form                                    | Criteria to Check                                                                                                                                   |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| Accounts Payable Preferences (AP101000) | Make sure that the accounts payable settings have been con<br>figured as described in Accounts Payable: To Specify Accounts<br>Payable Preferences. |

| Form                       | Criteria to Check                                                                                                                                                                          |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Vendors (AR303000)         | Verify the existence of the vendor accounts for the vendors<br>whose bills you will pay. For details, see Vendors: Implementa<br>tion Activity.                                            |
| Cash Accounts (CA202000)   | Make sure that the cash account to be used in the payments<br>has been configured as described in Cash Management: To<br>Create Cash Accounts.                                             |
| Payment Methods (CA204000) | Make sure that the payment method you will use has been<br>configured as described in Cash Management: To Create Cash<br>Accounts.                                                         |
| Projects (PM301000)        | Make sure that the necessary project (that is, the project for<br>which the vendor performed the billed work) has been creat<br>ed and necessary project tasks of this project are active. |

## **Payment by Line Checklist**

If you intend to pay individual lines of the vendor's bill or bills, make sure the needed features have been enabled and settings have been specified, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                     |
|--------------------------------------------|-----------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form    | Make sure that the Payment Application by Line feature<br>is enabled. |
| Payment tab of the Vendors (AR303000) form | Be sure the Pay by Line check box is selected.                        |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing payments for AP bills by specifying additional settings as follows:

- To cause the system to generate separate payment documents for each bill of a particular vendor, select the **PaySeparately** check box on the **Payment** tab of the *[Vendors](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a9584be3-f2bd-4d67-80d4-8041d809df56)* (AR303000) form.
- To cause the system to automatically post AP payments once they are released, select the **Automatically Post on Release** check box on the **General** tab of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form.
- To cause AP payments to be created with the *On Hold* status, select the **Hold Documents on Entry** check box on the **General** tab of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form.
- To cause the system to automatically post general ledger batches generated during the processing of payments, select the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form. For information on processing general ledger batches, see *GL [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) General [Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367)*.
- To make the system consolidate into one batch all generated transactions posted to the same period for all documents being released, select the **Generate Consolidated Batches** check box on the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* form.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *Vendor [Payments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7dc160fb-b24a-4102-ab26-882ffabfa7a2) for a Project: To Process a Payment for Multiple Bills* and *Vendor [Payments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f6a73333-5058-4654-8d13-5921459be639) for a Project: To Process a Payment of Bill Lines*.

## <span id="page-145-0"></span>**WIP Labor Costs in Cost-Plus Projects: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for billing a cost-plus projects with WIP costs, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially bill a cost-plus projects with WIP costs, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                 |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting feature is en<br>abled.                                                                                                                                                                                                                    |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
| Chart of Accounts (GL202500) form       | Make sure that an asset account for work in progress<br>has been created. For details on configuring the chart<br>of accounts, see Chart of Accounts.                                                                                                                            |
| Account Groups (PM201000) form          | Make sure that an account group of the Asset type<br>for work in progress has been created and the WIP<br>account has been added to the account group. For<br>details on configuring account groups, see Account<br>Groups: General Information.                                 |
| Allocation Rules (PM207500) form        | Make sure that an allocation rule is configured as de<br>scribed in WIP Labor Costs in Cost-Plus Projects: Gen<br>eral Information.                                                                                                                                              |
| Billing Rules (PM207000) form           | Make sure that all the needed billing rules have been<br>configured to process allocation transactions posted<br>to the WIP account group. For details on configuring<br>billing rules, see Billing Rules: General Information.                                                  |
| Projects (PM301000)                     | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation.                                                                                                                                                       |

#### **Other Settings That Affect the Workflow**

To cause the system to automatically release allocation transactions, including allocation reversal transactions, select the **Automatically Release Allocations** check box on the **General** tab (**GeneralSettings** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form.

### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you allocate projects by performing instructions similar to those described in *[WIP Labor Costs in Cost-Plus Projects: Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1b50755a-1ab3-461d-9fe8-d113c321b13b) [Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1b50755a-1ab3-461d-9fe8-d113c321b13b)*.

## <span id="page-146-0"></span>**WIP Labor Costs in Fixed-Price Projects: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for billing a cost-plus projects with WIP costs, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially bill a cost-plus projects with WIP costs, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Tasks to Perform                                                                                                                                                                                                                                                                 |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the Project Accounting feature is en<br>abled.                                                                                                                                                                                                                    |
| Projects Preferences (PM101000) form    | Make sure that all necessary settings related to project<br>accounting have been specified. For more information<br>about configuration steps that you have to perform<br>before you can start accounting for projects, see Basic<br>Project Configuration: General Information. |
| Chart of Accounts (GL202500) form       | Make sure that an asset account for work in progress<br>has been created. For details on configuring the chart<br>of accounts, see Chart of Accounts.                                                                                                                            |
| Account Groups (PM201000) form          | Make sure that an account group of the Asset type<br>for work in progress has been created and the WIP<br>account has been added to the account group. For<br>details on configuring account groups, see Account<br>Groups: General Information.                                 |
| Allocation Rules (PM207500) form        | Make sure that an allocation rule is configured as de<br>scribed in WIP Labor Costs in Fixed-Price Projects: Gen<br>eral Information.                                                                                                                                            |

| Form                          | Tasks to Perform                                                                                                                                                                                                                |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Billing Rules (PM207000) form | Make sure that all the needed billing rules have been<br>configured to process allocation transactions posted<br>to the WIP account group. For details on configuring<br>billing rules, see Billing Rules: General Information. |
| Projects (PM301000)           | Make sure that the project has been created, as de<br>scribed in Project Creation and Processing: General In<br>formation.                                                                                                      |
| Project Tasks (PM302000)      | Make sure the WIP account group is selected for the<br>project tasks in the Non-Billable WIP Account Group<br>box on theSummary tab (Billing and Allocation Set<br>tings section).                                              |

## **Other Settings That Affect the Workflow**

To cause the system to automatically release allocation transactions, including allocation reversal transactions, select the **Automatically Release Allocations** check box on the **General** tab (**GeneralSettings** section) of the *[Projects Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=de2ca225-4a0c-4129-b09d-3f3ed05198f9)* (PM101000) form.

## **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you allocate projects by performing instructions similar to those described in *[WIP Labor Costs in Fixed-Price Projects: Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6b50755a-1ab3-411d-9fe8-d113c321b13b) [Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6b50755a-1ab3-411d-9fe8-d113c321b13b)*.

## <span id="page-148-0"></span>**Route Management**

## <span id="page-148-1"></span>**Route Management: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the management of routes and the processing of route service contracts in the system.

## **Prerequisites**

Before you start configuring route management, you should make sure that the needed configuration tasks have been performed, as summarized in the following checklist.

| Form                                | Criteria to Check                                                                                                                                                                                                                                             |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Multiple forms                      | Make sure that the minimum company settings are<br>specified, as described in Company Without Branches,<br>Company with Branches that Do Not Require Balancing,<br>or Company with Branches that Require Balancing (de<br>pending on your company structure). |
| Multiple forms                      | To offer the provision of inventory items as part of pro<br>viding field services, make sure that the sales order<br>management configuration has been implemented, as<br>described in Configuration of Order Management: Imple<br>mentation Checklist .      |
| Multiple forms                      | Make sure that the service management configuration<br>has been implemented, as described in Basic Service<br>Management Configuration.                                                                                                                       |
| Numbering Sequences (CS201010) form | The numbering sequence for route executions has<br>been created.                                                                                                                                                                                              |
| Employees (EP203000) form           | The employees that are drivers have been defined in<br>the system.                                                                                                                                                                                            |

## **Required Steps**

To make it possible for users to execute routes and process route service contracts, you should navigate to the forms listed in the following table and perform the configuration actions that are described.

| Form                                         | Action                                                                                                    |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Service Management Preferences (FS100100)    | Specify the Map API Key.                                                                                  |
| Route Management Preferences (FS100400) form | Specify the route numbering sequence and the billing<br>settings for contracts with standardized billing. |

| Form                                | Action                                                                                                                                                   |  |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Service Order Types (FS202300) form | Create the service order type for route appointments,<br>as described in Service Order Types: To Create a Ser<br>vice Order Type for Route Appointments. |  |
| Skills (FS206000) form              | Create the driver skills.                                                                                                                                |  |
| Employees (EP203000) form           | Assign a driver skill to all the employees that are dri<br>vers.                                                                                         |  |
| Vehicle Types (FS204200) form       | Create all the types of vehicles of the company.                                                                                                         |  |
| Vehicles (FS203600) form            | Create vehicle records.                                                                                                                                  |  |
| Item Classes (IN201000) form        | Modify the item classes to contain the default settings<br>of the company's route services. Create at least one<br>route service.                        |  |

#### **Additional Settings**

For faster data entry, you can specify a route service order type that will be selected on the data entry forms in the **DefaultService OrderType** box of the *[Route Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=01bdb61b-39a5-4089-a729-c9269cab8448)* (FS100400) form.

You can also perform the following optional steps on the same form:

• To set up the system to calculate route execution statistics using the Azure Maps service and display them on the *[Route Document Details](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b26fcf32-359a-4ef3-97e4-ab697fcfcdb1)* (FS304000) form, select the **Calculate RouteStatistics Automatically** check box.

If this check box is cleared, to calculate route execution statistics, users will have to click the **Calculate RouteStatistics** button on the *[Route Document Details](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b26fcf32-359a-4ef3-97e4-ab697fcfcdb1)* form.

- To enable the tracking of GPS locations at start and end point of the executed route, select the**TrackStart and Complete Location of Route** check box. The GPS locations will be displayed on the **Location** tab of the *[Route Document Details](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b26fcf32-359a-4ef3-97e4-ab697fcfcdb1)* form.
- To set an appointment manually added to a route on the *[Routes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=174a8c81-a57a-41fa-b59e-0f043854a40c)* (FS203700) form to appear first in the route, select the**Set Appointments Created Manually as First in Route** check box.

If this check box is cleared, the added appointment will be placed last in the route.

• To make it possible to specify months in route contract schedules when they are applicable, select the **EnableSeasons in Schedule Contracts** check box. The system will make the**Season Settings** section available on the **Recurrence** tab of the *[Service Contract Schedules](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f435f472-2bdd-4d76-9e41-08591b878f3a)* (FS305100) and *[Route Service Contract](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=648377cc-38b8-4711-a0e1-8182f337168c) [Schedules](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=648377cc-38b8-4711-a0e1-8182f337168c)* (FS305600) forms.

## <span id="page-150-0"></span>**Service Management**

## <span id="page-150-1"></span>**Service Order Types: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the creation of service order types.

## **Prerequisites**

Before you create a service order type to be used for service orders and appointments for which sales orders or SO invoices will not be generated, you should make sure the minimum configuration of service management functionality has been performed, as described in *[Basic Service Management Configuration: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=41c105f2-33db-406c-bc24-a15ff54d3e4e)*.

## **Implementation Checklist**

We recommend that before you start to create service order types, you make sure the needed features have been enabled and entities have been configured, as summarized in the following checklist.

| Form                                    | Criteria to Check                                                       |
|-----------------------------------------|-------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | The Service Management feature has been enabled.                        |
| Numbering Sequences (CS201010) form     | At least one numbering sequence for service orders<br>has been created. |
| Credit Terms (CS206500) form            | At least one set of credit terms has been created.                      |

## **Minimum Required Settings for a Service Order Type**

For each service order type that you are going to use, you should specify the following minimum configuration settings.

| Form                                                           | Settings to Specify                                                                             |  |
|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------|--|
| The Summary area of the Service Order Types<br>(FS202300) form | •<br>The identifier of the service order type<br>•<br>The description of the service order type |  |

| Form                                            | Settings to Specify                                                                                                                                                                                                                               |  |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| The General tab of the Service Order Types form | •<br>The Numbering Sequence to be used to assign ser<br>vice order reference numbers to service orders of<br>the type                                                                                                                             |  |
|                                                 | •<br>The needed Behavior of the service order type is<br>selected                                                                                                                                                                                 |  |
|                                                 | •<br>The AR Documents option in the Generated Billing<br>Documents box, which indicates that an AR docu<br>ment will be generated to bill the customer for ser<br>vices specified in service orders and appointments<br>of the service order type |  |
|                                                 | •<br>The needed option in the DefaultTerms for AR<br>and SO box                                                                                                                                                                                   |  |

## **Other Settings That Affect the Workflow**

For a particular service order type, you can specify additional settings on the **General** tab of the *[Service Order](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=06fd8a36-dd81-4df9-b609-92c3d552c542) [Types](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=06fd8a36-dd81-4df9-b609-92c3d552c542)* (FS202300) form that will affect the processing of service orders and appointments of this type:

- If the **CompleteService Orders When Its Appointments Are Completed** check box (**GeneralSettings** section) is selected, the system changes the status of a service order of the type to *Completed* when all appointments of this service order have the *Completed* status. If this check box is cleared, a user has to manually complete the service order.
- If the **CloseService Orders When Its Appointments Are Closed** check box (**GeneralSettings** section) is selected, the system changes the status of a service order of the type to *Closed* when all appointments of this service order have the *Closed* status. If this check box is cleared, a user has to manually close the service order.
- If the **Require Contact** check box (**GeneralSettings** section) is selected, users have to select a contact person in the **Contact** box on the**Settings** tab of the *[Service Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6e5277d3-274e-45f5-b77d-4410ed736d21)* (FS300100) or *[Appointments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ac486e9c-f5df-4829-94f0-2df8821361a0)* (FS300200) form when they create service orders or appointments of this service order type. If this check box is cleared, the service orders and appointments of the type can be created without the contact person being specified.
- If the **Require CustomerSignature on Mobile App** check box (**GeneralSettings** section) is selected, before a user completes an appointment of the type by using a mobile device, the customer's signature has to be obtained and saved in the mobile app. If this check box is cleared, the user can complete an appointment of the type without the customer's signature.
- If the **Bill Only Closed Appointments** check box (**BillingSettings** section) is selected, billing documents can be generated only for closed appointments of the service order type. If this check box is cleared, billing documents an be generated for appointments of the type that are not closed.

To simplify the process of creating service orders and appointments in the system, you can leave the default settings.

## <span id="page-152-1"></span><span id="page-152-0"></span>**Cash Entries with Taxes: Implementation Checklist**

To ensure that the system is configured properly for creating a cash entry a sales tax applied automatically, make sure that the criteria listed in the table have been met in the system as described.

| Form                                                    | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                         | Notes                                                                                                                                                                                                   |
|---------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Fea<br>tures(CS100000)                   | If you are going to apply a VAT to a cash entry,<br>make sure that the VAT Reporting feature has<br>been enabled.                                                                                                                                                                                                                                                                         |                                                                                                                                                                                                         |
| Taxes (TX205000)                                        | You should create the sales tax or VAT that your<br>company uses. The settings for the tax include<br>the tax rate, the tax calculation method, the tax<br>validity period (if any), and other required para<br>meters.                                                                                                                                                                   | For details, see Sales Taxes: To<br>Create a Sales Tax for Use in<br>AR and Value-Added Taxes: To<br>Create a General VAT and Ex<br>empt VAT.                                                           |
| Tax Zones(TX206000)                                     | You should create all needed tax zones and in<br>clude the taxes applied in the corresponding lo<br>cation in each tax zone. You then associate an<br>appropriate tax zone with each of your vendors<br>according to their locations.                                                                                                                                                     | For details, see Tax Zones and<br>Categories: To Review Tax Cate<br>gories and Create a Tax Zone for<br>Sales Taxes and Tax Zones and<br>Categories: To Create a Tax Cat<br>egory and Tax Zone for VAT. |
| Tax Categories (TX205500)                               | You should create the needed tax categories for<br>all goods or services (which are represented as<br>stock items and non-stock items in Acumatica<br>ERP) that your company buys. For each tax cat<br>egory, you should add all taxes that are applied<br>to the corresponding category of goods and ser<br>vices in all geographical locations where your<br>company conducts business. | For details, see Tax Zones and<br>Categories: To Review Tax Cate<br>gories and Create a Tax Zone for<br>Sales Taxes and Tax Zones and<br>Categories: To Create a Tax Cat<br>egory and Tax Zone for VAT. |
| Vendors (AP303000)                                      | For each tax agency to which you will submit tax<br>reports, you should create a vendor account with<br>the Vendor isTax Agency check box selected.                                                                                                                                                                                                                                       | For details, see Tax Agency: To<br>Set Up a Tax Agency for Sales<br>Taxes and Tax Agency: To Set<br>Up a Tax Agency for VAT.                                                                            |
| Stock Items(IN202500),<br>Non-Stock Items<br>(IN202000) | To calculate tax amounts in the documents in<br>which you specify inventory IDs, you should cre<br>ate stock items (for goods) and non-stock items<br>(for services) and associate each item with the<br>appropriate tax category.                                                                                                                                                        |                                                                                                                                                                                                         |
| Entry Types (CA203000)                                  | An entry type for taxable sales must be available<br>in the system.                                                                                                                                                                                                                                                                                                                       |                                                                                                                                                                                                         |

| Form                    | Criteria to Check                                                                                                                        | Notes |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Cash Accounts(CA202000) | The entry type for taxable sales must be assigned<br>to the needed tax account. This entry type must<br>be assigned the needed tax zone. |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-153-0"></span>**Credit Memos with Sales Taxes: Implementation Checklist**

To ensure that the system is configured properly for creating and releasing credit and debit memos, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                               | Notes |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information.                                                           |       |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers for which you will correct<br>create a credit memo. For details, see Cus<br>tomers: Implementation Activity. |       |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable preferences settings should be specified on the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:

- Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-154-0"></span>**Funds Transfers with Taxable Fees: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing funds transfers with taxable fees, and to understand (and change, if needed) the settings that affect the workflow of funds transfers processing.

#### **Implementation Checklist**

We recommend that before you initially perform funds transfers, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                  | Criteria to Check                                                                                                                                                                                                         |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)    | Make sure that the Standard Financials feature has been enabled.                                                                                                                                                          |
| Chart of Accounts (GL202500)          | Check whether the necessary accounts have been created.                                                                                                                                                                   |
| Entry Types (CA203000)                | Make sure that a needed entry type has been created.                                                                                                                                                                      |
| Cash Accounts (CA202000)              | Check whether the necessary cash accounts have been config<br>ured and the Disbursement entry type has been added to the cash<br>accounts on the EntryTypes tab.                                                          |
| Company Financial Calendar (GL201100) | Make sure that the periods during which funds transfers may oc<br>cur have a status of Open.                                                                                                                              |
|                                       | You can generate the necessary periods on the Master Financial<br>Calendar (GL201000) form.                                                                                                                               |
|                                       | For details on opening financial periods, see Opening Financial<br>Periods: Process Activity.                                                                                                                             |
| Taxes (TX205000)                      | Make sure that the taxes that your company uses have been cre<br>ated. The settings for the tax include the tax rate, the tax calcula<br>tion method, the tax validity period (if any), and other required<br>parameters. |
|                                       | For an example of creating a sales tax, see Sales Taxes: To Create<br>a Sales Tax for Use in AR.                                                                                                                          |
| Tax Zones (TX206000)                  | Make sure that the needed tax zone has been created and include<br>the needed tax, as described in Tax Zones and Categories: To Re<br>view Tax Categories and Create a Tax Zone for Sales Taxes.                          |

| Form                      | Criteria to Check                                                                                                                                                                                     |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tax Categories (TX205500) | Make sure that the needed tax category has been created and in<br>cludes the needed tax, as described in Tax Zones and Categories:<br>To Review Tax Categories and Create a Tax Zone for Sales Taxes. |

## **Other Settings That Affect the Workflow**

The following settings on the *[Cash Management Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47321412-f6f6-4565-a2c5-d24ab8167e4b)* (CA101000) form can affect the processing workflow:

- If the **Automatically Post to GL on Release** check box is selected, the system posts transactions to the general ledger when cash management documents are released. If this check box is cleared, you have to post the batch aer you release the document.
- If the **Hold Transactions on Entry** check box is selected in the **Data EntrySettings** section, when new transactions and funds transfers are entered, they are assigned the *On Hold* status. If the **Hold Transactions on Entry** check box is cleared, the transactions and funds transfers are assigned the *Balanced* status.
- If the **Require Document Ref. Nbr. on Entry** check box is selected, you must fill in the **Document Ref.** box on the *Funds [Transfers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=814c5c8d-45bc-4e4d-98df-1b6785defc6c)* (CA301000) form for new funds transfers. If this check box is cleared, you can decide whether to leave the **Document Ref.** box blank or fill it in.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you perform funds transfers with taxable fees by performing similar steps to those described in *Funds [Transfers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8dba8161-f2b2-481c-943f-82ab4754304c) with Taxable Fees: Process Activity*.

## <span id="page-155-0"></span>**Invoices with Inclusive Sales Taxes: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing invoices with an inclusive sales tax, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process invoices with an inclusive sales tax, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form             | Tasks to Perform                                                                                                                                                                                                                                                                 |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Taxes (TX205000) | You should create each inclusive sales tax that your<br>company uses. The settings for each tax include the<br>tax rate, the tax calculation method, and the tax validi<br>ty period (if any). For details, see Invoices with Inclusive<br>Sales Taxes: Implementation Activity. |

| Form                                               | Tasks to Perform                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Tax Zones(TX206000)                                | You should create all needed tax zones and include the<br>taxes that should be applied in the corresponding lo<br>cation in each tax zone. You then associate an appro<br>priate tax zone with each of your customers according<br>to their locations. For details, see Tax Zones and Cate<br>gories: To Review Tax Categories and Create a Tax Zone<br>for Sales Taxes.                                                                                                                                      |
| Tax Categories (TX205500)                          | You should create the needed tax categories for all<br>goods or services (which are represented as stock<br>items and non-stock items in Acumatica ERP) that your<br>company sells. For each tax category, you should add<br>all taxes that should be applied to the corresponding<br>category of goods and services in all geographical lo<br>cations where your company conducts business. For<br>details, see Tax Zones and Categories: To Review Tax<br>Categories and Create a Tax Zone for Sales Taxes. |
| Vendors (AP303000)                                 | For each tax agency to which you will submit tax re<br>ports, you should create a vendor account with the<br>Vendor isTax Agency check box selected.                                                                                                                                                                                                                                                                                                                                                          |
| Stock Items (IN202500), Non-Stock Items (IN202000) | To calculate tax amounts in the documents in which<br>you specify inventory IDs, you should create stock<br>items (for goods) and non-stock items (for services)<br>and associate each item with the appropriate tax cate<br>gory.                                                                                                                                                                                                                                                                            |
| Customers (AR303000)                               | You should create needed customers if they don't al<br>ready exist. Depending on the geographical location of<br>the sale transaction, different taxes can be applied to<br>the document. To define which taxes are applied in the<br>location of your customer, you should assign the ap<br>propriate tax zone to each new or existing customer.                                                                                                                                                             |
| Chart of Accounts (GL202500)                       | You should make sure that the following GL accounts<br>that you will use for tax reporting purposes have been<br>added:                                                                                                                                                                                                                                                                                                                                                                                       |
|                                                    | •<br>A liability account that will be used for accumulat<br>ing the tax amounts to be paid to the tax agency in<br>a tax period.                                                                                                                                                                                                                                                                                                                                                                              |
|                                                    | •<br>Expense accounts that will be used to record tax<br>adjustments and expenses for the tax agency, and<br>tax rounding gains and losses.                                                                                                                                                                                                                                                                                                                                                                   |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing invoices with an inclusive sales tax by specifying additional settings as follows:

• On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form, specify the following general ledger settings:

- To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
- Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- In the **RoundingSettings** section, specify a rounding limit in the **Rounding Limit** box. This setting causes the system to post any discrepancy between the document-level tax and the total of tax amount of each document line, which is under the specified value to a special account.
- On the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form, specify the accounts receivable settings as follows:
  - To give AR invoices the *On Hold* status when they are created, select the **Hold Documents on Entry** check box in the **Data EntrySettings** section.
  - Select the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section, if you want users to enter a payment reference number in the **Payment Ref.** box when they create an AR invoice on the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* (AR301000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AR invoices to be automatically posted to the general ledger once they are released.
- On the *Tax [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dc691b0b-cc58-4b08-a029-82b2586582f2)* (TX103000) form, specify the following tax settings:
  - In the **Tax Rounding Gain Account** box, an account where the system will post amounts resulting from tax rounding gains
  - In the **Tax Rounding Loss Account** box, an account where the system will post amounts resulting from tax rounding losses

## **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process invoices with an inclusive sales tax by performing instructions similar to those described in *Invoices with [Inclusive](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5315449e-350f-4f87-8acb-bde22d477096) Sales Taxes: Process [Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5315449e-350f-4f87-8acb-bde22d477096)*.

## <span id="page-157-0"></span>**Invoices with Sales Taxes: Implementation Checklist**

To ensure that the system is configured properly for creating an AR invoice with a sales tax applied automatically, make sure that the criteria listed in the table have been met in the system as described.

| Form                 | Criteria to Check                                                                                                                                                                                                                       | Notes                                                                                                                  |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| Taxes (TX205000)     | You should create the sales tax that your com<br>pany uses. The settings for the tax include the<br>tax rate, the tax calculation method, the tax<br>validity period (if any), and other required pa<br>rameters.                       | For details, see Sales<br>Taxes: To Create a Sales<br>Tax for Use in AR.                                               |
| Tax Zones (TX206000) | You should create all needed tax zones and<br>include the taxes applied in the correspond<br>ing location in each tax zone. You then asso<br>ciate an appropriate tax zone with each of<br>your customers according to their locations. | For details, see Tax<br>Zones and Categories: To<br>Review Tax Categories<br>and Create a Tax Zone for<br>Sales Taxes. |

| Form                                                 | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                               | Notes                                                                                                                  |
|------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| Tax Categories (TX205500)                            | You should create the needed tax categories<br>for all goods or services (which are repre<br>sented as stock items and non-stock items in<br>Acumatica ERP) that your company sells. For<br>each tax category, you should add all taxes<br>that are applied to the corresponding catego<br>ry of goods and services in all geographical lo<br>cations where your company conducts busi<br>ness. | For details, see Tax<br>Zones and Categories: To<br>Review Tax Categories<br>and Create a Tax Zone for<br>Sales Taxes. |
| Vendors (AP303000)                                   | For each tax agency to which you will submit<br>tax reports, you should create a vendor ac<br>count with the Vendor isTax Agency check<br>box selected.                                                                                                                                                                                                                                         | For details, see Tax<br>Agency: To Set Up a Tax<br>Agency for Sales Taxes.                                             |
| Stock Items(IN202500), Non-Stock<br>Items (IN202000) | To calculate tax amounts in the documents in<br>which you specify inventory IDs, you should<br>create stock items (for goods) and non-stock<br>items (for services) and associate each item<br>with the appropriate tax category.                                                                                                                                                               |                                                                                                                        |
| Customers (AR303000)                                 | You should create needed customers in the<br>Accounts Receivable subledger if they don't<br>already exist. Depending on the geographical<br>location of the sale transaction, different tax<br>es can be applied to the document. To define<br>which taxes are applied in the location of your<br>customer, you should assign the appropriate<br>tax zone to each new or existing customer.     |                                                                                                                        |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **GeneralSettings** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices the *On Hold* status.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a payment reference number in the **Payment Ref.** box when creating an AR invoice on the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* (AR301000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AR invoices to be automatically posted to the general ledger once they are released.

• On the **Company Details** tab of the *[Companies](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=fedad435-8496-4397-b8a3-50a473629f76)* (CS101500) form, *Document Amount* is selected in the **Cash Discount Base** box. This setting indicates that the cash discount percent will be applied to the total amount of a document plus the tax amount.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-159-0"></span>**Purchases with Inclusive Sales Taxes: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing a purchase with an inclusive sales tax applied, and to understand (and change, if needed) the settings that affect the processing workflow.

## **Implementation Checklist**

We recommend that before you initially process a purchase of taxable items, you make sure the needed settings have been specified and entities have been created, as summarized in the following checklist.

| Form                       | Tasks to Perform                                                                                                                                                                                   |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Taxes (TX205000)           | Make sure that each inclusive document-level sales tax<br>your company intends to use have been created as de<br>scribed in Invoices with Inclusive Sales Taxes: Imple<br>mentation Activity.      |
| Tax Preferences (TX103000) | Make sure that the tax rounding gain and loss ac<br>counts have been defined; the system will post tax<br>rounding gains and losses that may occur when post<br>ing tax amounts to these accounts. |
| Stock Items (IN202500)     | Make sure that the needed stock items have been con<br>figured.                                                                                                                                    |

## **Other Settings That Affect the Workflow**

You can affect the workflow of processing purchases with an inclusive sales tax by specifying additional settings as follows:

- On the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form, specify the following general ledger settings:
  - To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
  - In the **RoundingSettings** section, specify a rounding limit in the **Rounding Limit** box. This setting causes the system to post any discrepancy between the document-level tax and the total of tax amount of each document line, which is under the specified value to a special account.
- On the **GeneralSettings** tab of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form, specify the following accounts payable preferences:
  - To give AP bills the *On Hold* status when they are created, select the **Hold Documents on Entry** check box in the **Data EntrySettings** section.

- Select the **RequireVendor Reference** check box in the **Data EntrySettings** section, if you want users to enter a payment reference number in the**Vendor Ref.** box when creating an AP bill on the *[Bills and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234) [Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AP bills to be automatically posted to the general ledger once they are released.
- On the *Tax [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dc691b0b-cc58-4b08-a029-82b2586582f2)* (TX103000) form, specify the following tax settings:
  - In the **Tax Rounding Gain Account** box, an account where the system will post amounts resulting from tax rounding gains
  - In the **Tax Rounding Loss Account** box, an account where the system will post amounts resulting from tax rounding losses

### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process a purchase with an inclusive sales tax by performing instructions similar to those described in *[Purchases](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5fdd3b98-e19c-40ea-9cb9-70db15fe7e41) with Inclusive Sales Taxes: [Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5fdd3b98-e19c-40ea-9cb9-70db15fe7e41)*.

## <span id="page-160-0"></span>**Purchases with Sales Taxes: Implementation Checklist**

To ensure that the system is configured properly for creating an AP bill with a sales tax applied automatically, make sure that the criteria listed in the table have been met in the system as described.

| Form                      | Tasks to Perform                                                                                                                                                                                                                                                                                                                                                                               | Notes                                                                                                                  |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| Taxes (TX205000)          | You should create the sales tax that your com<br>pany uses. The settings for the tax include the<br>tax rate, the tax calculation method, the tax<br>validity period (if any), and other required pa<br>rameters.                                                                                                                                                                              | For details, see Sales<br>Taxes: To Configure a<br>Sales Tax for Use in AP.                                            |
| Tax Zones(TX206000)       | You should create all needed tax zones and<br>include the taxes applied in the correspond<br>ing location in each tax zone. You then asso<br>ciate an appropriate tax zone with each of<br>your vendors according to their locations.                                                                                                                                                          | For details, see Tax<br>Zones and Categories: To<br>Review Tax Categories<br>and Create a Tax Zone for<br>Sales Taxes. |
| Tax Categories (TX205500) | You should create the needed tax categories<br>for all goods or services (which are repre<br>sented as stock items and non-stock items in<br>Acumatica ERP) that your company buys. For<br>each tax category, you should add all taxes<br>that are applied to the corresponding catego<br>ry of goods and services in all geographical lo<br>cations where your company conducts busi<br>ness. | For details, see Tax<br>Zones and Categories: To<br>Review Tax Categories<br>and Create a Tax Zone for<br>Sales Taxes. |
| Vendors (AP303000)        | For each tax agency to which you will submit<br>tax reports, you should create a vendor ac<br>count with the Vendor isTax Agency check<br>box selected.                                                                                                                                                                                                                                        | For details, see Tax<br>Agency: To Set Up a Tax<br>Agency for Sales Taxes.                                             |

| Form                                                 | Tasks to Perform                                                                                                                                                                                                                                                                                                                                                                          | Notes |
|------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Stock Items(IN202500), Non-Stock<br>Items (IN202000) | To calculate tax amounts in the documents in<br>which you specify inventory IDs, you should<br>create stock items (for goods) and non-stock<br>items (for services) and associate each item<br>with the appropriate tax category.                                                                                                                                                         |       |
| Vendors (AP303000)                                   | You should create needed vendors in the Ac<br>counts Payable subledger if they don't al<br>ready exist. Depending on the geographical<br>location of the purchase transaction, different<br>taxes can be applied to the document. To de<br>fine which taxes are applied in the location of<br>your vendor, you should assign the appropri<br>ate tax zone to each new or existing vendor. |       |

## **Other Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **GeneralSettings** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AP bills the *On Hold* status.
  - Clear the **RequireVendor Reference** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a payment reference number in the**Vendor Ref.** box when creating an AP bill on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AP bills to be automatically posted to the general ledger once they are released.

## <span id="page-161-0"></span>**Purchases with Use Taxes: Implementation Checklist**

To ensure that the system is configured properly for creating an AP bill with a use tax applied automatically, make sure that the criteria listed in the table have been met in the system as described.

| Form             | Criteria to Check                                                                                                                                                                                                        | Notes                                                        |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| Taxes (TX205000) | You should create the use tax to be applied to<br>your documents. The settings for the tax in<br>clude the tax rate, the tax calculation method,<br>the tax validity period (if any), and other re<br>quired parameters. | For details, see Use Tax<br>es: Implementation Activi<br>ty. |

| Form                                                 | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                              | Notes                                                                      |
|------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| Tax Zones(TX206000)                                  | You should create all needed tax zones and<br>include the taxes applied in the correspond<br>ing location in each tax zone. You then asso<br>ciate an appropriate tax zone with each of<br>your vendors according to their locations.                                                                                                                                                          | For details, see Use Tax<br>es: Implementation Activi<br>ty.               |
| Tax Categories (TX205500)                            | You should create the needed tax categories<br>for all goods or services (which are repre<br>sented as stock items and non-stock items in<br>Acumatica ERP) that your company buys. For<br>each tax category, you should add all taxes<br>that are applied to the corresponding catego<br>ry of goods and services in all geographical lo<br>cations where your company conducts busi<br>ness. | For details, see Use Tax<br>es: Implementation Activi<br>ty.               |
| Vendors (AP303000)                                   | For each tax agency to which you will submit<br>tax reports, you should create a vendor ac<br>count with the Vendor isTax Agency check<br>box selected.                                                                                                                                                                                                                                        | For details, see Tax<br>Agency: To Set Up a Tax<br>Agency for Sales Taxes. |
| Stock Items(IN202500), Non-Stock<br>Items (IN202000) | To calculate tax amounts in the documents in<br>which you specify inventory IDs, you should<br>create stock items (for goods) and non-stock<br>items (for services) and associate each item<br>with the appropriate tax category.                                                                                                                                                              |                                                                            |
| Vendors (AP303000)                                   | You should create needed vendors in the ac<br>counts payable subledger if they don't al<br>ready exist. Depending on the geographi<br>cal location of the purchase transaction, you<br>must assign an appropriate tax zone to the<br>vendor.                                                                                                                                                   |                                                                            |

## **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **GeneralSettings** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AP bills the *On Hold* status.

- Clear the **RequireVendor Reference** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a payment reference number in the**Vendor Ref.** box when creating an AP bill on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AP bills to be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-163-0"></span>**Sales Tax Adjustments: Implementation Checklist**

To ensure that the system is configured properly for making a tax adjustment to a tax report, make sure that the criteria listed in the table have been met in the system as described.

| Form                          | Criteria to Check                                                                                                                                                                                                                                                     | Notes                                                                                        |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| Vendors (AP303000)            | For each tax agency to which you will submit<br>tax reports, you should create a vendor ac<br>count with the Vendor isTax Agency check<br>box selected.                                                                                                               | For details, see Tax<br>Agency: To Set Up a Tax<br>Agency for Sales Taxes.                   |
| Tax Preferences (TX103000)    | Make sure that a numbering sequence has<br>been specified for Adjust Input and Adjust Out<br>put documents. You can select the predefined<br>numbering sequence (TXADJUST) or create a<br>new one for tax adjustments on the Number<br>ing Sequences (CS201010) form. |                                                                                              |
| Reporting Settings (TX205100) | Make sure that the tax report is properly and<br>fully configured for the particular tax agency.                                                                                                                                                                      | For details, see Tax Re<br>port Configuration: To<br>Create a Tax Report for<br>Sales Taxes. |
| Release Tax Report (TX502000) | Make sure that a tax report for a specified tax<br>period has been prepared.                                                                                                                                                                                          | For details, see Prepar<br>ing a Tax Report for Sales<br>Taxes.                              |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you create a tax adjustment by performing instructions similar to those described in *Sales Tax [Adjustments:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4ce74a9-bfc5-4a64-a5da-ee0bc3d041f2) Process Activity*.

## <span id="page-163-1"></span>**Tax Report Preparation: Implementation Checklist**

To ensure that the system is configured properly for preparing a tax report, make sure that the criteria listed in the table have been met in the system as described.

| Form                          | Criteria to Check                                                                                                                                       | Notes                                                                                      |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Vendors (AP303000)            | For each tax agency to which you will submit<br>tax reports, you should create a vendor ac<br>count with the Vendor isTax Agency check<br>box selected. | For details, see Tax Agency: To<br>Set Up a Tax Agency for Sales<br>Taxes.                 |
| Reporting Settings (TX205100) | Make sure that the tax report is properly and<br>fully configured for the particular tax agency.                                                        | For details, see Tax Report Con<br>figuration: To Create a Tax Re<br>port for Sales Taxes. |

## <span id="page-164-0"></span>**Release of Sales Tax Report: Implementation Checklist**

To ensure that the system is configured properly for releasing a tax report, make sure that the criteria listed in the table have been met in the system as described.

| Form                             | Criteria to Check                                                                                                                                   | Notes                                                                                     |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Vendors (AP303000)               | For each tax agency to which you will submit tax<br>reports, you should create a vendor account with<br>the Vendor isTax Agency check box selected. | For details, see Tax Agency: To<br>Set Up a Tax Agency for Sales<br>Taxes.                |
| Reporting Settings<br>(TX205100) | Make sure that the tax report is properly and fully<br>configured for the particular tax agency.                                                    | For details, see Tax Report Con<br>figuration: To Create a Tax Report<br>for Sales Taxes. |
| Release Tax Report<br>(TX502000) | Make sure that a tax report for a specified tax pe<br>riod has been prepared and ready for release.                                                 | For details, see Preparing a Tax<br>Report for Sales Taxes.                               |

## <span id="page-164-1"></span>**Taxes Included in the Cost of Items: Implementation Checklist**

To ensure that the system is configured properly for including taxes in the cost of items, make sure that the criteria listed in the following table have been met in the system as described.

| Form                    | Criteria to Check                                                                                                                             | Notes                                                                                                                                                                                                                                                |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Taxes (TX205000)        | In a tax that will be included in the cost of pur<br>chased items, the UseTax Expense Account<br>check box is cleared on the GL Accounts tab. | For details on config<br>uring taxes of different<br>types, see Sales Taxes:<br>To Configure a Sales Tax<br>for Use in AP, Use Tax<br>es: Implementation Activi<br>ty, and Value-Added Tax<br>es: To Create a Statistical<br>VAT and Inclusive VATs. |
| Reason Codes (CS211000) | The reason code of the Adjustment type that<br>will be used for tax-related inventory adjust<br>ments has been defined in the system.         | For details, see Reason<br>Codes: Implementation<br>Activity.                                                                                                                                                                                        |

| Form                                      | Criteria to Check                                                                                                                                       | Notes |
|-------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Purchase Orders Preferences<br>(PO101000) | The reason code of the Adjustment type that<br>will be used for tax-related inventory adjust<br>ments has been specified in the Tax Reason<br>Code box. |       |

## <span id="page-165-0"></span>**Voiding of a Sales Tax Report: Implementation Checklist**

To ensure that the system is configured properly for voiding a tax report, make sure that the criteria listed in the table have been met in the system as described.

| Form                             | Criteria to Check                                                                                                                                   | Notes                                                                                      |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Vendors (AP303000)               | For each tax agency to which you will submit tax<br>reports, you should create a vendor account with<br>the Vendor isTax Agency check box selected. | For details, see Tax Agency: To<br>Set Up a Tax Agency for Sales<br>Taxes.                 |
| Reporting Settings<br>(TX205100) | Make sure that the tax report is properly and fully<br>configured for the particular tax agency.                                                    | For details, see Tax Report Con<br>figuration: To Create a Tax Re<br>port for Sales Taxes. |
| Release Tax Report<br>(TX502000) | Make sure that a tax report for a specified tax peri<br>od has been prepared.                                                                       | For details, see Preparing a Tax<br>Report for Sales Taxes.                                |