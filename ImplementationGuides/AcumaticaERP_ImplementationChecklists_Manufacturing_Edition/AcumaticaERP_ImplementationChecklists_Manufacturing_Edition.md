# **Manufacturing Edition 2025 R1**

![](_page_0_Picture_2.jpeg)

## **Contents**

| Copyright5                             |                                                                                 |  |  |
|----------------------------------------|---------------------------------------------------------------------------------|--|--|
| Acumatica ERP Manufacturing Edition  6 |                                                                                 |  |  |
| Basic Company Configuration7           |                                                                                 |  |  |
|                                        | Preparing an Instance: Implementation Checklist 7                               |  |  |
|                                        | Company Without Branches: Implementation Checklist 7                            |  |  |
|                                        | Company with Branches that Do Not Require Balancing: Implementation Checklist10 |  |  |
|                                        | Company with Branches that Require Balancing: Implementation Checklist 13       |  |  |
| General Ledger 17                      |                                                                                 |  |  |
|                                        | Adjusting Transactions: Implementation Checklist 17                             |  |  |
|                                        | Allocation Rules: Implementation Checklist 17                                   |  |  |
|                                        | GL Transactions: Implementation Checklist 18                                    |  |  |
|                                        | Interbranch Account Mapping: Implementation Checklist 19                        |  |  |
|                                        | Recurring Transactions: Implementation Checklist19                              |  |  |
|                                        | Reversing Transactions: Implementation Checklist 20                             |  |  |
|                                        | Running of Allocations: Implementation Checklist 21                             |  |  |
|                                        | Splitting Transactions: Implementation Checklist22                              |  |  |
|                                        | Transactions with Subaccounts: Implementation Checklist23                       |  |  |
| Financial Periods 24                   |                                                                                 |  |  |
|                                        |                                                                                 |  |  |
|                                        | Financial Calendar Generation: Implementation Checklist 24                      |  |  |
|                                        | Financial Periods: Implementation Checklist 24                                  |  |  |
|                                        | Opening Financial Periods: Implementation Checklist 25                          |  |  |
|                                        | Closing Financial Periods: Implementation Checklist25                           |  |  |
|                                        | Accounts Payable27                                                              |  |  |
|                                        | AP Bills: Implementation Checklist 27                                           |  |  |
|                                        | AP Bill Payments: Implementation Checklist28                                    |  |  |
|                                        | AP Documents from PDFs: Implementation Checklist 29                             |  |  |
|                                        | Bill Prepayments: Implementation Checklist30                                    |  |  |
|                                        | Debit and Credit Adjustments: Implementation Checklist31                        |  |  |
|                                        | Interbranch Bills Without Balancing: Implementation Checklist32                 |  |  |
|                                        | Interbranch Bills with Balancing: Implementation Checklist33                    |  |  |
|                                        | Check Reprinting: Implementation Checklist 35                                   |  |  |
|                                        | Multiple Bill Payments: Implementation Checklist36                              |  |  |
|                                        | Payments for a Shared Vendor: Implementation Checklist 37                       |  |  |

#### Contents | **3**

| Voiding Payments: Implementation Checklist 39                                       |  |
|-------------------------------------------------------------------------------------|--|
| Accounts Receivable41                                                               |  |
| AR Invoices: Implementation Checklist41                                             |  |
| AR Invoice Correction: Implementation Checklist 42                                  |  |
| Auto-Applying Payments: Implementation Checklist43                                  |  |
| Refunds: Implementation Checklist 44                                                |  |
| Interbranch Invoices with Balancing: Implementation Checklist44                     |  |
| Interbranch Invoices Without Balancing: Implementation Checklist 46                 |  |
| Intercompany Sales: Implementation Checklist47                                      |  |
| Invoice Payments: Implementation Checklist49                                        |  |
| Invoice Prepayments: Implementation Checklist50                                     |  |
| Invoice with Combined Subaccounts: Implementation Checklist 50                      |  |
| Payments with Write-Offs: Implementation Checklist52                                |  |
| Customers and Vendors54                                                             |  |
| Customer Statements: Implementation Checklist54                                     |  |
| Customer Visibility: Implementation Checklist55                                     |  |
| On-Demand Statements: Implementation Checklist56                                    |  |
| Regenerating Statements: Implementation Checklist57                                 |  |
| Vendor Visibility: Implementation Checklist58                                       |  |
| Order Management60                                                                  |  |
| Direct Returns: Implementation Checklist 60                                         |  |
| Direct Sales: Implementation Checklist 61                                           |  |
| Items with Lot and Serial Numbers: Implementation Checklist 61                      |  |
| Order Management Basic Configuration: Implementation Checklist63                    |  |
| Configuration of Order Management: Implementation Checklist 64                      |  |
| Purchase Returns at the Original Cost: Implementation Checklist 66                  |  |
| Purchase Returns at the Calculated Cost: Implementation Checklist67                 |  |
| Purchases of Non-Stock Items and Services with Receipts: Implementation Checklist68 |  |
| Purchases of Services Without Receipts: Implementation Checklist69                  |  |
| Sales of Stock Items: Implementation Checklist 70                                   |  |
| Sales Order Types: Implementation Checklist71                                       |  |
| Purchases of Stock Items: Implementation Checklist 72                               |  |
| Two-Step Transfers: Implementation Checklist73                                      |  |
| Manufacturing 75                                                                    |  |
| System Preparation for Manufacturing Implementation: Implementation Checklist75     |  |
| Bills of Material: Implementation Checklist 78                                      |  |

#### Contents | **4**

| Production Order Types: Implementation Checklist 80                     |  |
|-------------------------------------------------------------------------|--|
| Production Processing: Implementation Checklist 81                      |  |
| Inventory Planning with MRP: Implementation Checklist 82                |  |
| Production of Lot- or Serial-Tracked Items: Implementation Checklist 84 |  |
| Outside Processing: Implementation Checklist85                          |  |
| Production with Backflushing: Implementation Checklist 87               |  |
| Scrap and Waste In Production: Implementation Checklist 89              |  |
| Estimating: Implementation Checklist 90                                 |  |
| Product Configurator: Implementation Checklist 91                       |  |
| Capable to Promise: Implementation Checklist 93                         |  |
| Engineering Change Control: Implementation Checklist94                  |  |
|                                                                         |  |

## <span id="page-4-0"></span>**Copyright**

#### **© 2025 Acumatica, Inc.**

#### **ALL RIGHTS RESERVED.**

No part of this document may be reproduced, copied, or transmitted without the express prior consent of Acumatica, Inc.

3075 112th Avenue NE, Suite 200, Bellevue, WA 98004, USA

#### **Restricted Rights**

The product is provided with restricted rights. Use, duplication, or disclosure by the United States Government is subject to restrictions as set forth in the applicable License and Services Agreement and in subparagraph (c)(1)(ii) of the Rights in Technical Data and Computer Soware clause at DFARS 252.227-7013 or subparagraphs (c)(1) and (c)(2) of the Commercial Computer Soware-Restricted Rights at 48 CFR 52.227-19, as applicable.

#### **Disclaimer**

Acumatica, Inc. makes no representations or warranties with respect to the contents or use of this document, and specifically disclaims any express or implied warranties of merchantability or fitness for any particular purpose. Further, Acumatica, Inc. reserves the right to revise this document and make changes in its content at any time, without obligation to notify any person or entity of such revisions or changes.

#### **Trademarks**

Acumatica is a registered trademark of Acumatica, Inc. HubSpot is a registered trademark of HubSpot, Inc. Microso Exchange and Microso Exchange Server are registered trademarks of Microso Corporation. All other product names and services herein are trademarks or service marks of their respective companies.

Soware Version: 2025 R1 Last Updated: 06/01/2025

## <span id="page-5-0"></span>**Acumatica ERP Manufacturing Edition**

You can refer to this guide when configuring business processes in Acumatica ERP Manufacturing Edition. Each chapter of this guide is focused on the implementation of a particular functional area, and includes the implementation checklists that you use to make sure that the system is configured properly for performing particular business processes.

The checklists within each part of the guide are grouped by functional areas and are sorted in an alphabetical order.

#### **Functional Areas**

- *[Basic Company Configuration](#page-6-3)*
- *[General Ledger](#page-16-3)*
- *[Financial Periods](#page-23-3)*
- *[Accounts Payable](#page-26-2)*
- *[Accounts Receivable](#page-40-2)*
- *[Customers](#page-53-2) and Vendors*
- *[Order Management](#page-59-2)*
- *[Manufacturing](#page-74-2)*

## <span id="page-6-3"></span><span id="page-6-0"></span>**Basic Company Configuration**

## <span id="page-6-1"></span>**Preparing an Instance: Implementation Checklist**

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

## <span id="page-6-2"></span>**Company Without Branches: Implementation Checklist**

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

| Form                                            | Criteria to Check                                                                                                                                          |
|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Accounts Receivable Preferences (AR101000) form | Make sure that the following settings have been speci<br>fied:                                                                                             |
|                                                 | •<br>The Automatically Post on Release check box is<br>selected.                                                                                           |
|                                                 | •<br>A customer class, which will be used to provide de<br>fault values for customer accounts, has been se<br>lected in the Default Customer Class ID box. |
|                                                 | •<br>The Hold Documents on Entry check box is<br>cleared.                                                                                                  |
|                                                 | •<br>The Validate Document Totals on Entry check box<br>is cleared.                                                                                        |
|                                                 | •<br>The Require Payment Reference on Entry check<br>box is cleared.                                                                                       |

## <span id="page-9-0"></span>**Company with Branches that Do Not Require Balancing: Implementation Checklist**

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

## <span id="page-12-0"></span>**Company with Branches that Require Balancing: Implementation Checklist**

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

## <span id="page-16-3"></span><span id="page-16-0"></span>**General Ledger**

## <span id="page-16-1"></span>**Adjusting Transactions: Implementation Checklist**

Before users begin processing auto-reversing GL batches, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                          | Settings to Validate                                                                                                                           | Notes                                                                                            |
|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure the Standard Financials<br>feature has been enabled.                                                                                 |                                                                                                  |
| Multiple forms                                | Make sure that the system has been<br>configured properly, as described<br>in Company Without Branches: Gen<br>eral Information.               |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                    |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which auto-reversing transac<br>tions will be created and the next<br>periods have a status of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

#### **Settings That Can Affect the Processing Workflow**

The following settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow:

- If the *On Post* option is selected in the **Generate Reversing Entry** box, the system generates a reversing batch when the original batch is posted. If the *On Period Closing* option is selected, the system generates a reversing batch when a user closes the posting period related to the original batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.
- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, enter the batch control total before they save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.

## <span id="page-16-2"></span>**Allocation Rules: Implementation Checklist**

The following tables provide details that you can use to ensure that the system is configured properly for the creation of allocation rules.

| Form                                       | Things to Check                                                                                                                                                                                                                                                                                                                                       | Notes |
|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the Standard Finan<br>cials and General Ledger Allocation<br>Templates (under Advanced Finan<br>cials) features have been enabled.                                                                                                                                                                                                     |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed and the general ledger<br>functionality has been implement<br>ed, as described in Company With<br>out Branches: General Information<br>Company with Branches that Do Not<br>Require Balancing: General Informa<br>tion, and General Ledger: General<br>Information. |       |
| Ledgers (GL201500) form                    | Make sure that the ledgers used for<br>allocations have been created.                                                                                                                                                                                                                                                                                 |       |
| Chart of Accounts (GL202500) form          | Check whether the necessary ac<br>counts have been created, and cre<br>ate them if not.                                                                                                                                                                                                                                                               |       |

#### **Additional Configuration to Confirm**

If your company uses subaccounts, the subaccounts have to be configured, as described in *[Subaccounts:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=64736a3d-89c3-41ca-b0a4-0af7bcb11372) [Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=64736a3d-89c3-41ca-b0a4-0af7bcb11372)*.

## <span id="page-17-0"></span>**GL Transactions: Implementation Checklist**

Before users begin processing GL batches, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table

| Form                                       | Settings to Check                                                                                                                                         | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |
| Chart of Accounts (GL202500) form          | Check whether the necessary ac<br>counts have been created.                                                                                               |       |

| Form                                          | Settings to Check                                                                                       | Notes                                                                                            |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which transactions will be creat<br>ed have a status of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

#### **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-18-0"></span>**Interbranch Account Mapping: Implementation Checklist**

| Form                                            | Settings to Check                                                                                                                | Notes |
|-------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form      | Make sure that the following fea<br>tures have been enabled:<br>Standard Financials<br>•<br>Inter-Branch Transactions<br>•       |       |
| Companies (CS101500) form                       | Make sure that the necessary com<br>panies and branches have been<br>configured and the necessary<br>ledgers have been assigned. |       |
| Inter-Branch Account Mapping<br>(GL101010) form | Make sure that all the necessary ac<br>count mapping rules have been de<br>fined.                                                |       |

Before users begin to create intercompany and interbranch transactions, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

## <span id="page-18-1"></span>**Recurring Transactions: Implementation Checklist**

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

### <span id="page-19-0"></span>**Reversing Transactions: Implementation Checklist**

Before users begin processing GL batches, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                       | Settings to Validate                                                                                                                                      | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |

#### **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-20-0"></span>**Running of Allocations: Implementation Checklist**

The following table provides details that you can use to ensure that the system is configured properly for the running of allocations.

| Form                                          | Things to Check                                                                                                                                                                                                                                                                                                         | Notes                                                                                            |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure that the Standard Finan<br>cials and General Ledger Allocation<br>Templates (under Advanced Finan<br>cials) features have been enabled.                                                                                                                                                                       |                                                                                                  |
| Multiple forms                                | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Com<br>pany Without Branches: General In<br>formation, Company with Branches<br>that Do Not Require Balancing: Gen<br>eral Information, and Company with<br>Branches that Require Balancing:<br>General Information. |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which allocations will be run<br>have a status of Open.                                                                                                                                                                                                                       | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |

| Form                        | Things to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Notes                                                                                                                                                                                                                                                                                                                 |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Allocations (GL204500) form | Make sure that the allocations that<br>are going to be run have been cre<br>ated. For details, see Allocation<br>Rules: To Create an Allocation Rule<br>That Uses a Fixed Ratio (Weight),<br>Allocation Rules: To Create an Allo<br>cation Rule That Uses a Fixed Ra<br>tio (Percentage), Allocation Rules: To<br>Create an Allocation Rule That Us<br>es a Dynamic Ratio of the Period-to<br>Date Account Balances, and Alloca<br>tion Rules: To Create an Allocation<br>Rule Based on Budget Data. | The system behavior when gener<br>ating transactions that update the<br>destination accounts depends on<br>whether the AllocateSource Ac<br>counts Separately check box is se<br>lected on the Allocation tab. For<br>the listed allocation rules, the Allo<br>cateSource AccountsSeparately<br>check box is cleared. |

## <span id="page-21-0"></span>**Splitting Transactions: Implementation Checklist**

Before users begin splitting GL transactions, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                       | Settings to Validate                                                                                                                                      | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |

#### **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-22-0"></span>**Transactions with Subaccounts: Implementation Checklist**

Before users begin processing GL transactions with subaccounts, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                          | Settings to Check                                                                                                                                                     | Notes                                                                                            |
|-----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure the Standard Financials<br>and Subaccounts(under Advanced<br>Financials) features have been en<br>abled.                                                    |                                                                                                  |
| Multiple forms                                | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation.             |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                                           |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Be sure that the financial periods<br>for which transactions will be creat<br>ed have a status of Open.                                                               | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Segmented Keys (CS202000) form                | Be sure that the SUBACCOUNTS<br>segmented key has been config<br>ured to meet the company's busi<br>ness needs, as described in Subac<br>counts: General Information. |                                                                                                  |

#### **Settings That Can Affect the Processing Workflow**

The settings on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form can affect the processing workflow as follows:

- If the **Hold Batches on Entry** check box is selected, a batch is saved with the *On Hold* status by default. If the batch is on hold, you should click **Remove Hold** on the toolbar of the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* (GL301000) form for the batch so that you can process it further. If the check box is cleared, the batch is saved with the *Balanced* status.
- If the **Validate Batch ControlTotals on Entry** check box is selected, you have to enter the batch control total before you save the batch on the *Journal [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dda046bc-5946-407f-88f7-1c0c966fbe72)* form. If this check box is cleared and the status of the batch is *Balanced*, the system automatically validates the batch.
- If the **Automatically Post on Release** check box is selected, the system posts batches on release. If this check box is cleared, you have to post the batches aer release.

## <span id="page-23-3"></span><span id="page-23-0"></span>**Financial Periods**

## <span id="page-23-1"></span>**Financial Calendar Generation: Implementation Checklist**

Before users begin generating financial calendars, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table

| Form                                       | Settings to Validate                                                                                                                                      | Notes |
|--------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form | Make sure the Standard Financials<br>feature has been enabled.                                                                                            |       |
| Multiple forms                             | Make sure that the minimum con<br>figuration of the company has been<br>performed, as described in Compa<br>ny Without Branches: General Infor<br>mation. |       |

## <span id="page-23-2"></span>**Financial Periods: Implementation Checklist**

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

## <span id="page-24-0"></span>**Opening Financial Periods: Implementation Checklist**

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

### <span id="page-24-1"></span>**Closing Financial Periods: Implementation Checklist**

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

## <span id="page-26-2"></span><span id="page-26-0"></span>**Accounts Payable**

## <span id="page-26-1"></span>**AP Bills: Implementation Checklist**

To ensure that the system is configured properly for processing AP bills, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                   |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimum set of features has been enabled as<br>described in Company Without Branches: General Information,<br>Company with Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches that Require Bal<br>ancing: General Information |
| Vendors (AP303000)                 | Verify the existence of the vendor accounts for the vendors<br>for which you will create AP bills. For details, see Vendors: Im<br>plementation Activity.                                                                                                                           |
| Non-Stock Items (IN202000)         | Verify the existence of non-stock items that can be used when<br>creating AP bills. For details, see Non-Stock Item: Implementa<br>tion Activity.                                                                                                                                   |

#### **Settings That Affect the Workflow**

You use accounts payable forms to record purchases you make on credit. The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AP bills the *On Hold* status.
  - Clear the **RequireVendor Reference** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a vendor reference number in the**Vendor Ref.** box when creating an AP bill on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AP bills will be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-27-0"></span>**AP Bill Payments: Implementation Checklist**

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

## <span id="page-28-0"></span>**AP Documents from PDFs: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for recognizing AP documents from PDF files, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you start recognizing AP documents from PDF files, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                              | Criteria to Check                                                                                                                                                                           |  |
|---------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Enable/Disable Features (CS100000)<br>form        | Make sure that the AP Document Recognition Service feature has been<br>enabled.                                                                                                             |  |
|                                                   | The feature is not available in trial mode and can be en<br>abled only if it is included in the license that is applied to<br>the Acumatica ERP instance.                                   |  |
| Email Accounts (SM204002) form                    | Make sure that a system email account is created with incoming mail<br>processing activated and the Submit to Incoming Documents check<br>box selected on the Incoming Mail Processing tab. |  |
|                                                   | This configuration is needed only if you want automatical<br>ly submit PDF attachments of incoming emails for recogni<br>tion.                                                              |  |
| Rebuild Full-Text Entity Index<br>(SM209500) form | Rebuild search indexes before you start using the AP Document Recogni<br>tion Service feature. For details, see Building Search Indexes.                                                    |  |

#### **Project-Related Recognition Checklist**

If you are planning to recognize project-related AP documents from PDF files, you make sure that the following additional configuration steps have been performed, as summarized in the following checklist.

| Form                                       | Criteria to Check                                                                                                                                                                                                                                                                                      |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form | Make sure that the following features are enabled:<br>•<br>Recognition of Project-Related Documents<br>The feature is not available in trial mode and can be en<br>abled only if it is included in the license that is applied<br>to the Acumatica ERP instance.<br>•<br>Projects<br>•<br>Construction |

| Form                                                 | Criteria to Check                                                                                                                                                                                               |
|------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Projects Preferences (PM101000)<br>form, General tab | Make sure that the integration of project accounting and accounts<br>payable is enabled—that is, the AP check box is selected in theVisibility<br>Settings section on the Projects Preferences (PM101000) form. |
| Projects (PM101000) form,Summary<br>tab              | Make sure that for each project for which you plan to recognize AP docu<br>ments, the AP check box is selected in theVisibility Settings section on<br>the Projects Preferences (PM101000) form.                |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *[AP Documents from PDFs: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f229cd53-b896-41c9-a2d8-f6aadd4bc8f5)*.

## <span id="page-29-0"></span>**Bill Prepayments: Implementation Checklist**

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

### <span id="page-30-0"></span>**Debit and Credit Adjustments: Implementation Checklist**

To ensure that the system is configured properly for processing debit and credit adjustments, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |

| Form               | Criteria to Check                                                                                                                                                                | Notes |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Vendors (AP303000) | Verify the existence of the vendor accounts<br>for the vendors for which you will create debit<br>and credit adjustments. For details, see Ven<br>dors: Implementation Activity. |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created debit and credit adjustments the *On Hold* status.
  - Clear the **RequireVendor Reference** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a vendor reference number in the**Vendor Ref.** box when creating a debit or credit adjustment on the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that debit and credit adjustments will be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-31-0"></span>**Interbranch Bills Without Balancing: Implementation Checklist**

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

#### **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts the appropriate transactions to the general ledger when AP documents are released. If this check box is cleared, you have to post the batch aer you release the AP document.
- If the **PostSummary on Updating GL** check box is selected, AP documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AP document specify the same account and branch, then in the GL batch, these rows are combined into one row (that is, one journal entry) with the summarized amount. If this check box is cleared, the lines of the AP document are not combined into one journal entry in the GL batch.
- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **RequireVendor Reference** check box is selected, you must fill in the**Vendor Ref.** box on the *[Bills and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234) [Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* form. If this check box is cleared, you can leave the**Vendor Ref.** box blank.

## <span id="page-32-0"></span>**Interbranch Bills with Balancing: Implementation Checklist**

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

#### **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts the appropriate transactions to the general ledger when AP documents are released. If this check box is cleared, you have to post the batch aer you release the AP document.
- If the **PostSummary on Updating GL** check box is selected, AP documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AP document specify the same account and branch, then in the GL batch, these rows are combined into one row (that is, one journal entry) with the summarized amount. If this check box is cleared, the lines of the AP document are not combined into one journal entry in the GL batch.
- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **RequireVendor Reference** check box is selected, you must fill in the**Vendor Ref.** box on the *[Bills and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234) [Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* form. If this check box is cleared, you can leave the**Vendor Ref.** box blank.

## <span id="page-34-0"></span>**Check Reprinting: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing check reprinting, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially print and reprint checks, you make sure the settings have been specified and entities created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                             |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been enabled<br>as described in Company Without Branches: General<br>Information, Company with Branches that Do Not Re<br>quire Balancing: General Information, and Company with<br>Branches that Require Balancing: General Information. |
| Payment Methods (CA204000)         | Make sure that the CHECK payment method has been<br>specified when creating a payment.                                                                                                                                                                                        |

#### **Settings That Affect the Workflow**

You can affect the workflow of reprinting checks by specifying additional settings as follows:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AP transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts payable settings should be specified on the **General** tab of the *[Accounts Payable](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created checks the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that checks will be automatically posted to the general ledger once they are released.
- The following payment method settings should be specified for the payment method on the *[Payment](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6) [Methods](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=509285d1-cfae-4e87-95c3-a968451952e6)* (CA204000) form:
  - Select the **Print Checks** option in the **Additional Processing** section on the**Settings for Use in AP** tab.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you reprint checks as described in *[Check Reprinting: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=abdf6b04-5556-4cab-9cf2-1b0a7c492886)*.

## <span id="page-35-0"></span>**Multiple Bill Payments: Implementation Checklist**

To ensure that the system is configured properly for processing a payment of multiple bills, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Vendors (AP303000)                 | Verify the existence of the vendor accounts<br>for the vendors whose bills you want to pay<br>with one payment. For details, see Vendors:<br>Implementation Activity.                                                                                                            |       |
| Payment Methods (CA204000)         | Make sure the CHECK payment method has<br>been selected when creating a payment.                                                                                                                                                                                                 |       |

#### **Settings That Affect the Workflow**

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

## <span id="page-36-0"></span>**Payments for a Shared Vendor: Implementation Checklist**

Before users begin processing payments for a vendor shared between different companies, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                          | Settings to Check                                                                                                                                                                                                                                           | Notes                                                                                            |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form    | Make sure that the following fea<br>tures have been enabled:<br>•<br>Standard Financials<br>•<br>Multibranch Support                                                                                                                                        |                                                                                                  |
| Multiple forms                                | Multicompany Support<br>•<br>Make sure that the minimum con<br>figuration of the companies has<br>been performed.                                                                                                                                           |                                                                                                  |
| Chart of Accounts (GL202500) form             | Check whether the necessary ac<br>counts have been created.                                                                                                                                                                                                 |                                                                                                  |
| Company Financial Calendar<br>(GL201100) form | Make sure that all periods for which<br>users may process payments for<br>a shared vendor have a status of<br>Open.                                                                                                                                         | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Vendors (AP303000) form                       | Ensure that all vendors for which<br>shared payments from different<br>companies may be processed are<br>defined in the system. For these<br>vendors, also be sure that no ac<br>count has been specified in the<br>Cash Account box of the Payment<br>tab. |                                                                                                  |
| Payment Methods (CA204000) form               | Be sure that the necessary cash ac<br>counts have been defined as the<br>default accounts for the branches<br>in the payment methods of the ven<br>dor.                                                                                                     |                                                                                                  |

#### **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts the appropriate transactions to the general ledger when AP documents are released. If this check box is cleared, you have to post the batch aer you release the AP document.
- If the **PostSummary on Updating GL** check box is selected, AP documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AP document specify the same account and branch, then in the GL batch, these rows are combined into one row (that is,

one journal entry) with the summarized amount. If this check box is cleared, the lines of the AP document are not combined into one journal entry in the GL batch.

- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Bills and Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* (AP301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **RequireVendor Reference** check box is selected, you must fill in the**Vendor Ref.** box on the *[Bills and](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234) [Adjustments](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=956b4e51-3078-4d2d-85b3-65c080d95234)* form. If this check box is cleared, you can leave the**Vendor Ref.** box blank.

## <span id="page-37-0"></span>**Partial Payments: Implementation Checklist**

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

## <span id="page-38-0"></span>**Voiding Payments: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for voiding payments, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you void payments, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                               |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been enabled as de<br>scribed in Company Without Branches: General Information,<br>Company with Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches that Require Bal<br>ancing: General Information. |
| Vendors (AR303000)                 | Verify the existence of the vendor accounts for the vendors<br>whose payments you want to void. For details, see Vendors:<br>Implementation Activity.                                                                                                                           |
| Payment Methods (CA204000)         | Make sure that the CHECK payment method has been speci<br>fied when creating a payment.                                                                                                                                                                                         |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of payment voiding by specifying additional settings as follows:

- To cause GL batches to be immediately posted aer they are released, select the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form.
- To cause every AP transaction you enter to be posted as an individual batch to the general ledger, clear the **Generate Consolidated Batches** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* form. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- To give the created payments the *On Hold* status, select the **Hold Documents on Entry** check box in the **Data EntrySettings** section on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section on the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* form. This setting indicates that payments will be automatically posted to the general ledger once they are released.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you void a payment as described in *Voiding [Payments:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=238e778f-8c0b-45e4-891e-48067c018943) Process Activity*.

## <span id="page-40-2"></span><span id="page-40-0"></span>**Accounts Receivable**

## <span id="page-40-1"></span>**AR Invoices: Implementation Checklist**

To ensure that the system has been configured properly for the processing of AR invoices, make sure that the criteria listed in the table have been met in the system as described.

#### **Implementation Checklist**

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

## <span id="page-41-0"></span>**AR Invoice Correction: Implementation Checklist**

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

### <span id="page-42-0"></span>**Auto-Applying Payments: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing auto-application of payments, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially auto-apply payments or prepayments to customer documents, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                             |
|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been enabled<br>as described in Company Without Branches: General<br>Information, Company with Branches that Do Not Re<br>quire Balancing: General Information, and Company with<br>Branches that Require Balancing: General Information. |
| Statement Cycles (AR202800)        | Make sure that the End of Month statement cycle has<br>been configured.                                                                                                                                                                                                       |
| Customers (AR303000)               | Verify the existence of the customer accounts for the<br>customers whose payments or prepayments you will<br>auto-apply to documents. For details, see Customers:<br>Implementation Activity.<br>Make sure that the EOM statement cycle has been se                           |
|                                    | lected for the customer accounts in theStatement Cy<br>cle ID box in the Financial Settings section on the Fi<br>nancial tab of the current form.                                                                                                                             |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of the auto-application process by specifying additional settings on the **General Settings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form as follows:

- Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you perform the auto-application process as described in *[Auto-Applying Payments: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=648d7f92-c928-4499-bd82-6acc2f3f2a3a)*.

## <span id="page-43-0"></span>**Refunds: Implementation Checklist**

To ensure that the system is configured properly for creating a refund, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers whose refunds you will<br>process. For details, see Customers: Imple<br>mentation Activity.                                                                                                                   |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **General** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. With this check box cleared, you do not have to fill in payment reference information in the **Payment Ref.** box on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-43-1"></span>**Interbranch Invoices with Balancing: Implementation Checklist**

Before users begin processing invoices between branches that require balancing, you must make sure that the system has been configured properly and that all required entities have been created, as described in the following table.

| Form                                            | Settings to Check                                                                         | Notes                                                                                            |
|-------------------------------------------------|-------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)<br>form      | Make sure that the following fea<br>tures have been enabled:                              |                                                                                                  |
|                                                 | Standard Financials<br>•                                                                  |                                                                                                  |
|                                                 | Multi-Branch Support<br>•                                                                 |                                                                                                  |
|                                                 | •<br>Advanced Financials                                                                  |                                                                                                  |
|                                                 | •<br>Inter-Branch Transactions                                                            |                                                                                                  |
|                                                 | Make sure that the minimum con<br>figuration of the company has been<br>performed.        |                                                                                                  |
| Chart of Accounts (GL202500) form               | Check whether the necessary ac<br>counts have been created.                               |                                                                                                  |
| Inter-Branch Account Mapping<br>(GL101010) form | Be sure that the account mapping<br>rules have been specified for the<br>branches.        | For details on defining these rules,<br>see Interbranch Account Mapping:<br>General Information. |
| Company Financial Calendar<br>(GL201100) form   | Be sure that the periods for which<br>invoices will be defined have a sta<br>tus of Open. | You can generate the necessary pe<br>riods on the Master Financial Calen<br>dar (GL201000) form. |
| Customers (AR303000) form                       | Be sure that the periods for which<br>invoices will be defined have a sta<br>tus of Open. |                                                                                                  |

#### **Settings That Can Affect the Processing Workflow**

The following settings on the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form can affect the processing workflow:

- If the **Automatically Post on Release** check box is selected, the system posts transactions to the general ledger when AR documents are released. If this check box is cleared, you have to post the batch aer you release the AR document.
- If the **PostSummary on Updating GL** check box is selected, AR documents are posted to the general ledger with summarized row amounts if particular criteria are met. That is, if multiple lines in an AR document specify the same account and branch, then in the GL batch, these rows will be combined into one entry with the summarized amount. If this check box is cleared, the lines of the AR document will not be combined into one journal entry in the GL batch.
- If the **Hold Documents on Entry** check box is selected in the **Data EntrySettings** section, when new documents are entered, they are assigned the *On Hold* status. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- If the **Validate DocumentTotals on Entry** check box is selected, the system adds the **Amount** box to the Summary area of the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* (AR301000) form. To save a document with the *Balanced* status, you must enter the document total in this box aer reviewing the document. If this check box is cleared, the system automatically validates the batch when the status of the batch is *Balanced*.
- If the **Require Payment Reference on Entry** check box is selected, you must fill in the **Payment Ref.** box on the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* form. If this check box is cleared, you can leave the **Payment Ref.** box blank.
- If the **Require Invoice/Memo Printing Before Release** check box is selected, you must print an AR invoice or memo before release for those customers who prefer to receive printed copies of the documents. That is, if the **Print Invoices** check box is selected on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* (AR303000) form for a customer account,

each invoice is created with the *Pending Print* status. If this check box is cleared, you can release the invoice without printing.

• If the **Require Invoice/Memo Emailing Before Release** check box is selected, you must send an email with an AR invoice or memo before release for those customers who prefer to receive copies of the documents by email. That is, if the**Send Invoices by Email** check box is selected on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* form for a customer account, each invoice is created with the *Pending Email* status. If this check box is cleared, you can release the invoice without sending an email.

## <span id="page-45-0"></span>**Interbranch Invoices Without Balancing: Implementation Checklist**

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

## <span id="page-46-0"></span>**Intercompany Sales: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing intercompany sales, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

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

#### **Other Settings That Affect the Workflow**

You can affect the workflow of intercompany sales by specifying additional settings as follows:

- To cause AR documents to be posted automatically, select the **Automatically Post on Release** check box on the **GeneralSettings** tab (**PostingSettings** section) of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form.
- To cause the ID of the default customer class to be inserted automatically when a company or branch has been extended to be a customer, select a customer class ID in the **Default Customer Class ID** box on the **GeneralSettings** tab (**Data EntrySettings** section) of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* form. If this box is empty, you will have to specify a customer class for the new customer on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* (AR303000) form.
- To cause the system to insert a sales account from the customer location to an AR invoice, in the **Use IntercompanySales Account From** box, select *Customer Location*. If *Inventory Item* is selected in this box, the system will insert the sales account specified in the**Sales Account** box on the **GL Accounts** tab of the *[Non-Stock Items](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=bf68dd4f-63d4-460d-8dc0-9152f2bd6bf1)* (IN202000) form for non-stock items.
- To cause new documents to be assigned the *On Hold* status when they are created, select the **Hold Documents on Entry** check box on the **GeneralSettings** tab (**Data EntrySettings** section) of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* form. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.
- To cause AP documents to be posted automatically, select the **Automatically Post on Release** check box on the **GeneralSettings** tab (**PostingSettings** section) of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* (AP101000) form.
- To cause the ID of the default vendor class to be inserted automatically when a company or branch has been extended to be a vendor, select a vendor class ID in the **DefaultVendor Class ID** box on the **General Settings** tab (**Data EntrySettings** section) of the *[Accounts Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* form. If this box is empty, you will have to specify a vendor class for the new vendor on the *[Vendors](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a9584be3-f2bd-4d67-80d4-8041d809df56)* (AP303000) form.
- To cause the system to insert an expense account from the vendor location to an AP bill created from an AR invoice, in the **Use Intercompany Expense Account From** box, select *Vendor Location*. If *Inventory Item* is selected in this box, the system will insert the expense account specified in the **Expense Account** box on the **GL Accounts** tab of the *[Non-Stock Items](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=bf68dd4f-63d4-460d-8dc0-9152f2bd6bf1)* (IN202000) form for non-stock items.
- To cause new documents to be assigned the *On Hold* status when they are created, select the **Hold Documents on Entry** check box on the **GeneralSettings** tab (**Data EntrySettings** section) of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7) [Payable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c3f9353e-95e6-448d-bb3f-e20643879ec7)* form. If the **Hold Documents on Entry** check box is cleared, the documents are assigned the *Balanced* status.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process intercompany sales by performing instructions similar to those described in *[Intercompany](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0db4c77c-f877-471a-b025-db9fc303cb15) Sales: To Process [an Intercompany Invoice](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=0db4c77c-f877-471a-b025-db9fc303cb15)*, *[Intercompany](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=eb80dc35-c7a9-4a2a-bd9b-1f59f1c966a0) Sales: To Pay an Intercompany Bill*, and *[Intercompany](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8e65e73c-8eb5-4a97-bab2-ccc158799bd4) Sales: To Pay an [Intercompany Invoice](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=8e65e73c-8eb5-4a97-bab2-ccc158799bd4)*.

## <span id="page-48-0"></span>**Invoice Payments: Implementation Checklist**

To ensure that the system is configured properly for creating a payment and applying it to an invoice, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                | Notes |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers whose invoices you will<br>pay. For details, see Customers: Implementa<br>tion Activity.                                                                                                                      |       |

#### **Settings That Affect the Workflow**

The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **GeneralSettings** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. With this check box cleared, you do not have to fill in payment reference information in the **Payment Ref.** box on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-49-0"></span>**Invoice Prepayments: Implementation Checklist**

To ensure that the system has been configured properly for the processing of prepayments, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                 | Notes |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000) | Make sure the minimal features have been<br>enabled, as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information. |       |
| Customers (AR303000)               | Be sure that the customer accounts for the<br>customers for which you will create and<br>process prepayments have been defined.                                                                                                                                                   |       |

#### **Settings That Affect the Workflow**

In general, you use accounts receivable forms specifically for sales made on credit. The following settings and entities should be specified and defined, respectively:

- The following general ledger settings should be specified on the **PostingSettings** tab of the *[General Ledger](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:
  - Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
  - Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)
- The following accounts receivable settings should be specified on the **GeneralSettings** tab of the *[Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b) [Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:
  - Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created prepayments the *On Hold* status.
  - Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. This setting means that you do not have to enter a payment reference number in the **Payment Ref.** box when creating a prepayment on the *[Payments and Applications](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=ae844bf4-1aef-42cd-9e2f-49b3ee1bc8d7)* (AR302000) form.
  - Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes prepayments to be automatically posted to the general ledger once they are released.

With these settings specified and entities defined, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-49-1"></span>**Invoice with Combined Subaccounts: Implementation Checklist**

To ensure that the system has been configured properly for the processing of AR invoices, make sure that the criteria listed in the table have been met in the system as described.

| Form                                                              | Criteria to Check                                                                                                                                                                                                                                                                                                | Notes |
|-------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Enable/Disable Features (CS100000)<br>form                        | Make sure the Standard Financials and Subac<br>counts(under Advanced Financials) features<br>have been enabled.                                                                                                                                                                                                  |       |
| Multiple forms                                                    | Make sure that the minimum configuration<br>of the company has been performed, as de<br>scribed in Company Without Branches: Gen<br>eral Information, Company with Branches that<br>Do Not Require Balancing: General Information,<br>and Company with Branches that Require Bal<br>ancing: General Information. |       |
| Segmented Keys (CS202000) form,<br>Segment Values (CS203000) form | Be sure that the SUBACCOUNTS segmented<br>key has been configured to meet the compa<br>ny's business needs, as described in Subac<br>counts: General Information.                                                                                                                                                |       |
| Accounts Receivable Preferences<br>(AR101000) form                | Make sure that a proper subaccount mask<br>has been specified for AR documents, as de<br>scribed in Combined Subaccounts: To Define a<br>Subaccount Mask for AR Documents.                                                                                                                                       |       |
| Customers (AR303000)                                              | Be sure that the customer accounts have<br>been defined for the customers for which you<br>will create AR invoices.                                                                                                                                                                                              |       |
| Non-Stock Items (IN202000), Stock<br>Items (IN202500)             | Verify the existence of the non-stock items or<br>stock items (or both) that will be used when<br>you are creating AR invoices. For details, see<br>Non-Stock Item: Implementation Activity.                                                                                                                     |       |

#### **Settings That Affect the Workflow**

For a streamlined workflow of processing AR invoices, we recommend that you specify various settings related to the general ledger and to accounts receivable.

Do the following on the **PostingSettings** tab of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form:

- Make sure that the **Automatically Post on Release** check box is selected. This setting causes GL batches to be immediately posted aer they are released.
- Clear the **Generate Consolidated Batches** check box to cause every AR transaction you enter to be posted as an individual batch to the general ledger. (When this check box is selected, the system consolidates into a single batch all transactions in the same currency posted to the same period for all documents being released.)

Do the following on the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form:

- Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting causes the system to assign the *On Hold* status to the created AR invoices.
- Clear the **Require Payment Reference on Entry** check box in the **Data EntrySettings** section. With this setting, users do not have to enter a payment reference number in the **Payment Ref.** box when creating an AR invoice on the *[Invoices and Memos](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5e6f3b27-b7af-412f-a40a-1d4f4be70cba)* (AR301000) form.

• Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting causes AR invoices to be automatically posted to the general ledger once they are released.

With these settings specified, users in your company can record and process documents in Acumatica ERP quickly and accurately, with a minimum of manual actions.

## <span id="page-51-0"></span>**Payments with Write-Offs: Implementation Checklist**

To ensure that the system is configured properly for creating a credit write-off when you process a payment, make sure that the criteria listed in the table have been met in the system as described.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                                                             | Notes                                                                                                                                                                                      |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure the basic features have been en<br>abled, as described in Company Without<br>Branches: General Information, Company with<br>Branches that Do Not Require Balancing: Gen<br>eral Information, and Company with Branches<br>that Require Balancing: General Information.                                                                              |                                                                                                                                                                                            |
| Customers (AR303000)               | Verify the existence of the customer accounts<br>for the customers whose payments you want<br>to process. For details, see Customers: Imple<br>mentation Activity.<br>The needed customer accounts must be spec<br>ified for write-offs in the Financial Settings<br>section on the Financial tab as follows:<br>•<br>The Enable Write-Offs check box must be |                                                                                                                                                                                            |
|                                    | selected.<br>•<br>A Write-Off Limit value must be specified.                                                                                                                                                                                                                                                                                                  |                                                                                                                                                                                            |
| Chart of Accounts (GL202500)       | Verify the existence of the GL accounts to<br>which the write-off amounts will be posted.                                                                                                                                                                                                                                                                     | The account you use<br>to post credit write<br>off amounts should be<br>an Income account;<br>the account you use to<br>post balance write-off<br>amounts should be an<br>Expense account. |
| Reason Codes (CS211000)            | Verify the existence of the reason codes to be<br>used for write offs.                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                            |

#### **Settings That Affect the Workflow**

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

## <span id="page-53-2"></span><span id="page-53-0"></span>**Customers and Vendors**

## <span id="page-53-1"></span>**Customer Statements: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for preparing customer statements.

#### **Implementation Checklist**

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

## <span id="page-54-0"></span>**Customer Visibility: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for restricting the visibility of customer records, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

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

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *[Customer](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=90609745-18fd-4154-83f6-1d9b23c2f7a3) Visibility: To Restrict Visibility to a Company* and *[Customer](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=786a44af-4e53-4918-a57d-31b2458747d2) Visibility: To Restrict Visibility to a New [Company](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=786a44af-4e53-4918-a57d-31b2458747d2)*.

## <span id="page-55-0"></span>**On-Demand Statements: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for preparing on-demand customer statements.

#### **Implementation Checklist**

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

### <span id="page-56-0"></span>**Regenerating Statements: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for regenerating customer statements and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you regenerate customer statements, you make sure settings have been specified and entities have been created, as summarized in the following checklist.

| Form                                          | Criteria to Check                                                                                                                                                                                                                                                                                             |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Customer Classes (AR201000)                   | In the StatementType box in the Default Print and Email Set<br>tings section on the General Settings tab, you specify what type of<br>statement the customers assigned to this customer class prefer—<br>balance-forward or open-item.                                                                        |
|                                               | You select the Print Statements check box if you want to make<br>this customer's statements available for mass-printing on the Print<br>Statements (AR503500) form.                                                                                                                                           |
|                                               | You select theSend Statements By Email check box if you want to<br>make this customer's statements available for mass-emailing on<br>the Print Statements form.                                                                                                                                               |
|                                               | You select the Multi-Currency Statements check box if you want<br>this customer's statements to be created in multicurrency format.<br>Such statements are displayed for mass-processing (printing or<br>emailing) if the Foreign Currency Statements check box is select<br>ed on the Print Statements form. |
|                                               | This check box becomes available if the Multicurrency Account<br>ing feature has been enabled on the Enable/Disable Features<br>(CS100000) form.                                                                                                                                                              |
| Statement Cycles (AR202800)                   | Make sure that the End of Month statement cycle that you want to<br>use for preparing customer statements has been configured.                                                                                                                                                                                |
| Customers (AR303000)                          | Make sure that the EOM statement cycle has been selected for the<br>customer accounts in the Statement Cycle ID box in the Financial<br>Settings section on the Financial tab of the current form.                                                                                                            |
| Accounts Receivable Preferences<br>(AR101000) | Make sure that on the General tab (Consolidation Settings sec<br>tion), the For Each Branch option is selected in the Prepare State<br>ments box.                                                                                                                                                             |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of creating AR documents by specifying additional settings on the **GeneralSettings** tab of the *[Accounts Receivable Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f7b52067-5299-45e8-b601-485cd709f58b)* (AR101000) form as follows:

- Select the **Hold Documents on Entry** check box in the **Data EntrySettings** section. This setting gives the created AR invoices and credit memos the *On Hold* status.
- Make sure that the **Automatically Post on Release** check box is selected in the **PostingSettings** section. This setting indicates that AR invoices and credit memos will be automatically posted to the general ledger once they are released.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you regenerate customer statements as described in *[Regeneration of Statements: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4bba5990-3835-4ad6-b6fd-39e280fe141e)*.

## <span id="page-57-0"></span>**Vendor Visibility: Implementation Checklist**

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

## <span id="page-59-2"></span><span id="page-59-0"></span>**Order Management**

## <span id="page-59-1"></span>**Direct Returns: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for processing direct returns, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

Before you begin processing direct returns, you should make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                     | Criteria to Check                                                                                                                                                             |
|------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form  | Make sure that the Advanced SO Invoices feature has<br>been enabled.                                                                                                          |
| Sales Orders Preferences (SO101000) form | Make sure that all necessary settings related to or<br>der management have been specified, as described in<br>Configuration of Order Management: Implementation Ac<br>tivity. |
| Customers (AR303000) form                | Make sure that all needed customers have been de<br>fined in the system, as described in Customers: Imple<br>mentation Activity.                                              |
| Stock Items (IN202500) form              | Make sure that all stock items have been defined in the<br>system, as described in Stock Items: Implementation Ac<br>tivity.                                                  |

#### **Other Settings that Affect the Workflow**

You can affect the workflow of processing direct returns by specifying additional settings as follows:

- To cause inventory issues to be automatically generated and released on release of credit memos (invoices of the *Credit Memo* type), select the **Automatically Release IN Documents** check box on the *[Sales Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* (SO101000) form.
- To cause general ledger batches generated during the processing of sales documents to be posted automatically, select the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form. For information on processing general ledger batches, see *GL [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) General [Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367)*.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process a direct return for testing purposes, as described in *[Direct Returns: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=039666b3-671d-4af9-8659-9035ee0bab78)*.

## <span id="page-60-0"></span>**Direct Sales: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for processing direct sales, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

Before you begin processing direct sales, you should make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                     | Criteria to Check                                                                                                                                                             |
|------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form  | Make sure that the Advanced SO Invoices feature has<br>been enabled.                                                                                                          |
| Sales Orders Preferences (SO101000) form | Make sure that all necessary settings related to or<br>der management have been specified, as described in<br>Configuration of Order Management: Implementation Ac<br>tivity. |
| Customers (AR303000) form                | Make sure that all needed customers have been de<br>fined in the system, as described in Customers: Imple<br>mentation Activity.                                              |
| Stock Items (IN202500) form              | Make sure that all stock items are defined in the sys<br>tem, as described in Stock Items: Implementation Activi<br>ty.                                                       |

#### **Other Settings that Affect the Workflow**

You can affect the workflow of processing direct sales by specifying additional settings as follows:

- To cause inventory issues generated on release of sales invoices be released automatically, select the **Automatically Release IN Documents** check box on the *[Sales Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* (SO101000) form.
- To cause general ledger batches generated during the processing of sales documents to be posted automatically, select the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form. For information on processing general ledger batches, see *GL [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) General [Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367)*.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process a direct sale for testing purposes, as described in *[Direct Sales: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=4ded85e9-f3f4-4360-8eb1-09e636b2eaf0)*.

## <span id="page-60-1"></span>**Items with Lot and Serial Numbers: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing items with lot and serial numbers.

#### **Implementation Checklist**

Before you begin processing purchase and sales documents that include stock items with lot and serial numbers, you should make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                        |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | Make sure that the Lot and Serial Tracking feature is enabled.                                                                                                                           |
| Inventory Preferences (IN101000)   | Make sure that all necessary settings related to inventory and order<br>management have been specified, as described in Configuration of Or<br>der Management: General Information.      |
| Lot/Serial Classes (IN207000)      | Make sure that lot and serial classes with the needed settings have<br>been created, as you will learn to do in Items with Lot and Serial Num<br>bers: Implementation Activity.          |
| Item Classes (IN201000)            | Make sure that the needed lot or serial classes are specified in set<br>tings of item classes, as you will learn to do in Items with Lot and Serial<br>Numbers: Implementation Activity. |
| Stock Items (IN202500)             | Make sure that the needed lot or serial classes are specified in set<br>tings of stock items, as you will learn to do in Items with Lot and Serial<br>Numbers: Implementation Activity.  |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process a purchase and a sale of stock items with lot or serial numbers by performing instructions similar to those described in the following activities:

- *Items with Lot and Serial Numbers: To Purchase and Sell [Serialized](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=847ed262-b5fd-42ea-8919-383a931ad56e) Items*
- *Items with Lot and Serial [Numbers:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=19e48e39-acc9-4548-a393-f278958ea7ef) To Sell Items in Lots*
- *Items with Lot and Serial Numbers: To Purchase and Sell [Lot-Numbered](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d7b333c0-bb86-4ac0-9281-6704e8dff04f) Items that Expire*

#### **Known Process Limitations**

The following limitations apply to the processing of sales that include items with lot or serial numbers:

- If a full or partial quantity of the item in a sales order line on the *[Sales Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=19e4021c-1b84-49fd-be12-0320c5f1c7e5)* (SO301000) form is allocated by lot or serial number, only the full item quantity can be deallocated on the *[Manage Sales Allocations](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=98ffa8b8-40c3-40fa-86d5-e7c9c9ef751d)* (SO501010) form. If you manually change the **Qty. to Deallocate** in the line on the *[Manage Sales Allocations](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=98ffa8b8-40c3-40fa-86d5-e7c9c9ef751d)* form, you cannot select this line for processing, and the system shows an error message.
- If the *Lot/Serial Attributes* feature is enabled on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form and the **Specify Lot/Serial Price and Description** check box is selected for the lot or serial class on the *[Lot/Serial](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=9806d94b-097e-4082-9f01-9ca66d031ab7) [Classes](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=9806d94b-097e-4082-9f01-9ca66d031ab7)* (IN207000) form, the following apply to each item of the class:
  - The item cannot be added to a sales price list or sales price worksheet.
  - The item must have a lot or serial number specified in a sales order line. The **Mark for PO** check box cannot be selected for this line.
  - Each unit of a stock item with a lot or serial number must be added to a separate sales order line because each unit may have a unique description and price.

## <span id="page-62-0"></span>**Order Management Basic Configuration: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of sales and purchases with non-stock items, and to specify settings that affect the processing workflow.

#### **Prerequisites**

Before you start configuring order management, you should make sure that the needed features have been enabled and settings have been specified, as described in the following checklist.

| Form                                    | Criteria to Check                                                                                                               |
|-----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
|                                         | Make sure that the minimum company settings are<br>specified, as described in Company Without Branches:<br>General Information. |
| Enable/Disable Features (CS100000) form | Make sure that the Inventory and Order Management<br>feature is enabled.                                                        |
| Order Types (SO201000)                  | Make sure that the IN order type has been activated, as<br>described in Sales Order Types: To Activate the IN Or<br>der Type.   |

#### *Table: Minimum Required Settings*

To make it possible for users to process sales and purchase orders with non-stock items, you should navigate to the following forms and save the default settings.

| Form                                     | Settings to Save           |
|------------------------------------------|----------------------------|
| Sales Orders Preferences (SO101000) form | Save the default settings. |
| Purchase Orders Preferences (PO101000)   | Save the default settings. |

#### **Settings That Affect the Workflow**

When you are configuring order management, you can specify additional settings to configure the company to fit your business requirements:

- To cause the system to verify the customer's credit status and put a sales order on hold if the credit limit has been exceeded, select the **Hold Document on Failed Credit Check** check box on the *[Sales Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* (SO101000) form.
- To reduce input errors during purchase order entry, set up the validation of order totals by selecting the **For Normal and Standard Orders** check box in the**ValidateTotal on Entry** section of the *[Purchase Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form, so that a user will need to enter a control total for each order of this type; the order can be processed further only if the system-calculated total equals the manually entered control total.

## <span id="page-63-0"></span>**Configuration of Order Management: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the order fulfillment and inventory management processes, and to specify settings that affect the processing workflow.

#### **Prerequisites**

Before you start configuring order and inventory management, you should make sure that the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                    | Criteria to Check                                                                                                                                                                                     |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Multiple forms                          | Make sure that the minimum company settings are<br>configured, as described in Company Without Branch<br>es: General Information.                                                                     |
| Enable/Disable Features (CS100000) form | Make sure that the Inventory and Order Management<br>and Inventory features are enabled.                                                                                                              |
| Order Types (SO201000)                  | Make sure that at least one order type (SO) is config<br>ured and activated, as described in Sales Order Types:<br>General Information .                                                              |
| Reason Codes (CS211000)                 | Make sure that the reason codes to be used for pro<br>cessing inventory transactions and vendor returns<br>have been defined in the system as described in Rea<br>son Codes: Implementation Activity. |

#### **Minimum Required Settings**

To be able to keep stock items and track the sales and purchase orders that include these stock items, you should specify and save the minimum settings listed in the following table.

| Form                                     | Settings to Specify                                                                                                                              |
|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| Inventory Preferences (IN101000)         | Specify the Receipt Reason Code, Issue/Return Rea<br>son Code, Adjustment Reason Code, and Phys. In<br>ventory Reason Code; save these settings. |
| Sales Orders Preferences (SO101000) form | Specify SO as the DefaultSales OrderType, and save<br>your change to this form.                                                                  |
| Purchase Orders Preferences (PO101000)   | Specify the PO Return Reason Code, and save your<br>change to this form.                                                                         |

#### **Recommended Settings**

To speed the processing of documents and minimize errors, you should specify and save the recommended settings listed in the following table.

| Form                                     | Settings to Specify                                                                                                                                                                                        |
|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Inventory Preferences (IN101000)         | •<br>Update GL: Selected<br>•<br>Automatically Post on Release: Selected                                                                                                                                   |
| Sales Orders Preferences (SO101000) form | •<br>Hold Shipments on Entry: Cleared<br>•<br>Validate Shipment Total on Confirmation:<br>Cleared<br>•<br>UseShipment Date for Invoice Date: Selected<br>•<br>Automatically Release IN Documents: Selected |
| Purchase Orders Preferences (PO101000)   | •<br>Release IN Documents Automatically: Selected                                                                                                                                                          |

#### **Other Settings That Affect the Workflow**

When you are configuring inventory and order management, you can specify additional settings to configure the company to fit your business requirements:

- To configure the system to post inventory transactions to the general ledger, select the **Update GL** check box on the *[Inventory Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f2eb4e55-f802-4259-a41f-609965c856f1)* (IN101000) form.
- To cause the system to post the generated general ledger transactions automatically, select the **Automatically Post on Release** check box on the *[Inventory Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f2eb4e55-f802-4259-a41f-609965c856f1)* form.
- To cause the system to assign the group of prepared documents the *On Hold* status by default, select the following check boxes:
  - **Hold Documents On Entry** check box on the *[Inventory Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f2eb4e55-f802-4259-a41f-609965c856f1)* form (for inventory transactions)
  - **Hold Shipments on Entry** check box on the *[Sales Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* (SO101000) form (for shipment documents)
  - **Hold Receipts on Entry** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form (for purchase receipt documents)
- To set up the system so that users need to enter control amounts before it processes documents, select the following check boxes:
  - **Validate DocumentTotals on Entry** on the *[Inventory Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f2eb4e55-f802-4259-a41f-609965c856f1)* form (for inventory transactions)
  - **ValidateShipmentTotal on Confirmation** on the *[Sales Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* form (for shipments)
  - **For Normal and Standard Orders** on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form (for purchase orders)
  - **For Receipts** on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form (for purchase receipts)
- To configure the system to automatically release documents that are generated, select the following check boxes:
  - **Automatically Release IN Documents** check box on the *[Sales Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* form (to release inventory transactions generated during the processing of sales orders)
  - **Release IN Documents Automatically** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form (to release inventory documents generated during the processing of purchase orders)
  - **Release AP Documents Automatically** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form (to release accounts payable documents generated during the processing of purchase orders)
- To cause the system to automatically create accounts payable documents on release of purchase documents, select the **Create Bill** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form. By default, the state of this check box is copied to each purchase order or purchase return that is created. If the check box is cleared in a purchase order or purchase return, you can select this check box before releasing the document.

## <span id="page-65-0"></span>**Purchase Returns at the Original Cost: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of purchase returns at the original cost, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

Before you begin processing purchase returns at the original cost, you should make sure the needed settings have been specified, as summarized in the following checklist.

| Form                                           | Criteria to Check                                                                                                                                                          | Notes                                                                                                                                                                                                                                                                                                                        |
|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                | Make sure that the basic invento<br>ry and order management prefer<br>ences are configured, as described<br>in Configuration of Order Manage<br>ment: General Information. |                                                                                                                                                                                                                                                                                                                              |
| Purchase Orders Preferences<br>(PO101000) form | Make sure the Process Return with<br>Original Cost check box is select<br>ed.                                                                                              | By default, the system copies the<br>state of this check box to each pur<br>chase return that is created. (You<br>can change the way to specify the<br>cost in an individual purchase re<br>turn by selecting the Cost by Is<br>sue Strategy or Manual Cost Input<br>options on the Purchase Receipts<br>(PO302000) form.).) |

#### **Settings that Affect the Workflow**

You can affect the workflow of processing purchase returns at the original cost by specifying additional settings as follows:

- To automatically create debit adjustments on release of purchase returns, select the **Create Bill** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form. By default, the state of this check box is copied to each purchase return that is created. If the check box is cleared in a purchase return document, you can select it before releasing a purchase return.
- To set up the system to automatically release debit adjustments that are generated, select the **Release AP Documents Automatically** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process a purchase return at the original cost, as described in the *[Purchase Returns at the Original CostPurchase ReturnsPurchase Returns at the](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f36799e0-830d-4584-b516-581d06e16985) Original Cost: Process ActivityTo Process a Return at the Original [CostProcess](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f36799e0-830d-4584-b516-581d06e16985) Activity*.

## <span id="page-66-0"></span>**Purchase Returns at the Calculated Cost: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of purchase returns at the cost calculated by the system, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

Before you begin processing returns at the calculated cost, you should make sure the needed settings have been specified, as summarized in the following checklist.

| Form                                           | Criteria to Check                                                                                                                                                          | Notes                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                | Make sure that the basic invento<br>ry and order management prefer<br>ences are configured, as described<br>in Configuration of Order Manage<br>ment: General Information. |                                                                                                                                                                                                                                                                                                                                                                          |
| Purchase Orders Preferences<br>(PO101000) form | Make sure that the Process Return<br>with Original Cost check box is<br>cleared.                                                                                           | By default, the system copies the<br>state of this check box to each pur<br>chase return that is created. (You<br>can change the way to specify the<br>cost in an individual purchase re<br>turn by selecting the Cost by Issue<br>Strategy or Manual Cost Input op<br>tions in the Cost of Inventory Re<br>turn From box on the Purchase Re<br>ceipts (PO302000) form.) |

#### **Settings that Affect the Workflow**

You can affect the workflow of processing purchase returns at the system-calculated cost by specifying additional settings as follows:

- To cause debit adjustments to be automatically created on release of purchase returns, select the **Create Bill** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form. By default, the state of this check box is copied to each purchase return that is created. If the check box is cleared in a purchase return document, you can select it before releasing a purchase return.
- To set up the system to automatically release debit adjustments that are generated, select the **Release AP Documents Automatically** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process a purchase return at the system-calculated cost, as described in the *[Purchase Returns at the Calculated CostPurchase Returns: Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1af27d6c-9221-4804-9fcb-2bb25b847b53) ActivityTo Process a Return at the [Calculated](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1af27d6c-9221-4804-9fcb-2bb25b847b53) Cost*.

## <span id="page-67-0"></span>**Purchases of Non-Stock Items and Services with Receipts: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of purchases of non-stock items (including services) with purchase receipts, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process purchases of non-stock items which may include services, you make sure the needed settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                   | Criteria to Check                                                                                                                                                                                                                               |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Purchase Orders Preferences (PO101000) | •<br>Make sure that all necessary settings related to pur<br>chase order management have been specified as<br>described in Order Management Basic Configuration:<br>General Information.                                                        |
|                                        | •<br>Make sure that the ProcessService lines from<br>Normal Purchase Orders via Purchase Receipts<br>check box (in the Other section of the General tab)<br>is selected.                                                                        |
| Vendors (AP303000)                     | Make sure that all needed vendors have been created<br>as described in Vendors: General Information.                                                                                                                                            |
| Non-Stock Items (IN202000)             | Make sure that all non-stock items have been config<br>ured as described in Non-Stock Items: Implementation<br>Activity.                                                                                                                        |
|                                        | Also, make sure that the Require Receipt check box<br>(in the Item Defaults section of the General tab) is se<br>lected in the settings of each non-stock item for which<br>a purchase receipt will be processed when the item is<br>purchased. |
| Enable/Disable Features (CS100000)     | Make sure that the Inventory feature is enabled to be<br>able to create purchase receipts.                                                                                                                                                      |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing purchases by specifying additional settings:

- To cause an accounts payable bill to be created automatically on release of a purchase receipt by default, select the **Create Bill on Receipt Release** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form (in the **Other** section of the **General** tab). In this case, when a user creates a purchase receipt on the *[Purchase Receipts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d9901c8d-486d-45ed-8088-ea3d8ee3af19)* (PO302000) form, the system automatically selects the **Create Bill** check box in the Summary area. (The user can clear this check box for a particular receipt, if needed.)
- To cause the system to automatically release accounts payable bills that are generated on release of purchase receipts, select the **Release AP Documents Automatically** check box on the *[Purchase Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form. For information on processing bills, see *[AP Bills: General Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1ea1e770-b81c-437e-831f-64f702f968f4)*.

- To cause purchase receipts to be created with the *On Hold* status (so that users can verify them before processing them further), select the **Hold Receipts on Entry** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form (in the **Other** section of the **General** tab).
- To cause the system to automatically release inventory receipts generated on release of purchase receipts, select the **Release IN Documents Automatically** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form (in the **Other** section of the **General** tab).
- To cause the system to automatically post general ledger batches generated during processing purchase documents, select the **Automatically Post on Release** check box in the **PostingSettings** section of the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form. For information on processing general ledger batches, see *[GL](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) General Information*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *[Purchases](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b6a47b01-2dc1-47c3-8bd6-66e8dfb30795) of Non-Stock Items and Services with Receipts: To Process a [Purchase of Non-Stock Items](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b6a47b01-2dc1-47c3-8bd6-66e8dfb30795)* and *[Purchases](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81438ba6-46ff-4af8-8870-94c195758e7b) of Non-Stock Items and Services with Receipts: To Process a Purchase of [Services](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=81438ba6-46ff-4af8-8870-94c195758e7b)*.

## <span id="page-68-0"></span>**Purchases of Services Without Receipts: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of purchases of services that will not be included in a purchase receipt, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process purchases of services without receipt, you make sure the needed settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                   | Criteria to Check                                                                                        |
|----------------------------------------|----------------------------------------------------------------------------------------------------------|
| Purchase Orders Preferences (PO101000) |                                                                                                          |
| Vendors (AP303000)                     | Make sure that all needed vendors have been config<br>ured as described in Vendors: General Information. |
| Non-Stock Items (IN202000)             |                                                                                                          |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing purchases of services without receipt by selecting the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form to cause the system to automatically post GL batches generated during processing purchase documents. For information on processing GL batches, see *GL [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) General Information*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process a purchase order by performing instructions similar to those described in *[Purchases](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=973c83fc-a226-41f5-8ba2-3cb73a645ded) of Services Without Receipts: [Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=973c83fc-a226-41f5-8ba2-3cb73a645ded)*.

## <span id="page-69-0"></span>**Sales of Stock Items: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of sales of stock items, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

Before you begin processing sales of stock items, you should make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                                                               | Criteria to Check                                                                                                                                                                  |
|------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form                                            | Make sure that the Inventory feature is enabled.                                                                                                                                   |
| Sales Orders Preferences (SO101000) form, Inventory<br>Preferences (IN101000) form | Make sure that all necessary settings related to sales<br>orders and inventory have been specified, as de<br>scribed in Configuration of Order Management: General<br>Information. |
| Order Types (SO201000) form                                                        | Make sure that the SO and SA order types are active<br>and have been configured, as described in Sales Or<br>der Types: To Activate the SO Order TypeImplementa<br>tion Activity.  |
| Customers (AR303000) form                                                          | Make sure that all needed customers have been de<br>fined in the system, as described in Customers: Imple<br>mentation Activity .                                                  |
| Stock Items (IN202500) form                                                        | Make sure that all stock items have been defined in the<br>system, as described in Stock Items: Implementation Ac<br>tivity.                                                       |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing inventory sales by specifying additional settings as follows:

- To cause shipments to be created with the *On Hold* status (so that the user can verify them before processing them further), select the **Hold Shipments on Entry** check box on the *[Sales Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* (SO101000) form.
- To cause inventory issues to be automatically generated and released on release of sales invoices, select the **Automatically Release IN Documents** check box on the *[Sales Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* form.
- To cause the shipment dates to appear in invoices as invoice dates, select the **UseShipment Date for Invoice Date** check box on the *[Sales Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1817779c-413b-4187-b7fe-38e97845a1cb)* form.
- To cause general ledger batches generated during the processing of sales documents to be posted automatically, select the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form. For information on processing general ledger batches, see *GL [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) General [Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367)*.

#### **Testing of Settings**

To make sure that all settings are configured correctly, we recommend that you process a sale of stock items, as described in *[Sales of Stock Items: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=45433ef7-a12c-49aa-8721-007ea09401df)*.

## <span id="page-70-0"></span>**Sales Order Types: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for the processing of sales orders, and to specify settings that affect the processing workflow for orders of different types.

#### **Enabling the Needed Features**

You should make sure the following features have been enabled on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form based on the types of orders you want to configure and use:

- The *Inventory and Order Management* feature to be able to configure and use orders of any of the following types: *QT*, *IN*, *CM*, *CS*, *CR*, and *MO*.
- The *Inventory and Order Management* and *Inventory* features to be able to configure and use orders of any of the following types: *BL*, *SO*, *SA*, *RR*, *RM*, and *RC*
- The *Inventory and Order Management*, *Inventory*, and *Multiple Warehouses* features to be able to configure and use orders of the *TR* order type

#### **Configuring the System**

Before you begin configuring order types, you should make sure that on the *[Chart of Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=85557f41-a4af-47a8-b198-2a01461ce9c3)* (GL202500) form, all GL accounts that you will use for configuring an order type have been added. For details, see *[General](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=535eabd7-26e2-4777-ac7d-fedf23846eb1) Ledger: To [Create a Chart of Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=535eabd7-26e2-4777-ac7d-fedf23846eb1)*.

#### **Minimum Required Settings**

For each sales order type that you are going to use, you should specify the following minimum settings to configure and activate the order type.

| Form                                                  | Criteria to Check                                                                                                                                                    |
|-------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| The General tab of the Order Types<br>(SO201000) form | •<br>The Order Numbering Sequence, which is the sequence to be used<br>to assign order reference numbers, is specified.                                              |
|                                                       | •<br>The Invoice Numbering Sequence, which is the sequence to be used<br>to assign reference numbers for invoices prepared for orders of this<br>type, is specified. |
|                                                       | •<br>The Freight Account, which is the account for posting freight charges,<br>is specified.                                                                         |
| The Summary area of Order Types<br>form               | The Active check box, indicating that the order type is available for use,<br>is selected.                                                                           |

#### **Settings That Affect the Workflow**

For a particular order type, you can specify additional settings on the **General** tab of the *Order [Types](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e6984218-4260-4438-99e1-aee2b3765369)* (SO201000) form that will affect the processing of orders of this type:

- To cause new orders to be created with the *On Hold* status (so that they can be verified before further processing), select the **Hold Orders on Entry** check box.
- To make the system verify the customer's credit status and put an order on credit hold if the credit limit has been exceeded, select the **Hold Document on Failed Credit Check** check box.

To make the system automatically remove a sales order of the type from credit hold when a payment has been applied to the full order amount, make sure that the **Remove Credit Hold on Payment Application** check box is selected. (The system automatically selects this check box when a user selects **Hold Documents on Failed Credit Check**, but you can clear it.)

If the customer specified in a sales order has the *Credit Hold* status on the *[Customers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=652929bc-9606-4056-aa6e-0c2d1147171b)* (AR303000) form, the order cannot be moved from the *Credit Hold* status. It keeps the status even if the **Remove Credit Hold on Payment Application** check box is selected for the order type on the *Order [Types](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e6984218-4260-4438-99e1-aee2b3765369)* form and a payment has been applied to the full order amount. The status of the order can be changed only when the customer's status is no longer *Credit Hold*.

- To reduce input errors during order entry, set up the validation of order totals by selecting the **Require ControlTotal** check box, so that a user will need to enter a control total for an order of this type; the order can be processed further only if the system-calculated total equals the manually entered control total.
- To cause the system to prepare separate bills for multiple orders of the type for the same customer, select the **BillSeparately** check box.
- To cause the system to prepare separate shipment documents for multiple orders of the type for the same customer, select the**Ship Separately** check box.
- To cause the system to calculate freight charges for an order of the type, select the **Calculate Freight** check box.
- To cause the system to require a user to enter a customer order number for an order of the type, select the **Require Customer Order Nbr.** check box. To allow users to enter duplicated customer order numbers, select *Allow Duplicates* in the **Customer Order Nbr.Validation**; to warn users if they have entered a duplicated number, select *Warn About Duplicates*. To prevent users from entering duplicated customer order numbers in orders of the type, select *Forbid Duplicates*.

On the **Template** tab of the *Order [Types](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e6984218-4260-4438-99e1-aee2b3765369)* form, to configure an order type for quick processing, you select the **Allow Quick Processing** check box. This causes the **Quick Processing** tab to appear, and you specify the needed settings on this tab. For more information, see *Sales Order Types: Quick [Processing](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2920c85c-5678-40f7-b80a-e068ac3a137f) of Sales Orders*.

If your organization's policies require the approval of sales orders of a type, you can set up their approval, as described in *[Specific Approvals: Sales Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=9073dc65-9824-4a3c-b924-c16ddd75728c)*.

## <span id="page-71-0"></span>**Purchases of Stock Items: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for the processing of purchases of stock items, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process purchases of stock items, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                                   | Criteria to Check                                                                                                                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Purchase Orders Preferences (PO101000) | Make sure that all necessary settings related to pur<br>chase order management have been specified as de<br>scribed in Configuration of Order Management: General<br>Information. |
| Vendors (AP303000)                     | Make sure that all needed vendors have been config<br>ured as described in Vendors: General Information.                                                                          |
| Stock Items (IN202500)                 | Make sure that all stock items have been configured as<br>described in Stock Items: General Information.                                                                          |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing purchases by specifying additional settings:

- To reduce input errors when users enter orders, set up the validation of order totals by selecting the **For Normal and Standard Orders** check box in the**ValidateTotal on Entry** section of the *[Purchase Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* (PO101000) form (**GeneralSettings** tab). If this check box is selected, when a user creates a new purchase order on the *[Purchase Orders](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5565686c-96c4-4bfa-a51d-9a2566baa808)* (PO301000) form, to take the order off hold, the user must enter the order total in the **ControlTotal** box aer verifying the order details.
- To cause an accounts payable bill to be created automatically on release of a purchase receipt by default, select the **Create Bill on Receipt Release** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form. In this case, when a user creates a purchase receipt on the *[Purchase Receipts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=d9901c8d-486d-45ed-8088-ea3d8ee3af19)* (PO302000) form, the system automatically selects the **Create Bill** check box. (The user can clear this check box for a particular bill.)

To cause the system to automatically release accounts payable bills generated on release of purchase receipts, select the **Release AP Documents Automatically** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form. For information on processing bills, see *[AP Bills: General Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1ea1e770-b81c-437e-831f-64f702f968f4)*.

- To cause purchase receipts to be created with the *On Hold* status (so that users can verify them before processing them further), select the **Hold Receipts on Entry** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form.
- To cause the system to automatically release inventory receipts generated on release of purchase receipts, select the **Release IN Documents Automatically** check box on the *[Purchase Orders Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=13d09c43-8696-4f92-ad9b-3d0209ee3d9b)* form.
- To cause the system to automatically post general ledger batches generated during processing purchase documents, select the **Automatically Post on Release** check box on the *[General Ledger Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e4913d06-c511-4258-a0f9-f36c1b854e6b)* (GL102000) form. For information on processing general ledger batches, see *GL [Transactions:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367) General [Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=35393020-6269-466d-8a08-df558cd43367)*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process a purchase order, as described in *[Purchases of Stock Items: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b561401a-41f5-423b-87bb-ec15118282d5)*.

## <span id="page-72-0"></span>**Two-Step Transfers: Implementation Checklist**

Before you start processing two-step transfers, you should make sure that the system is configured properly, as described in the following sections.

#### **Implementation Checklist**

In the following table, you can find features, settings, and other actions that are required for processing two-step transfers.

| Form                                    | Criteria to Check                                                                                                                        |
|-----------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) form | Make sure that the following features are enabled:                                                                                       |
|                                         | •<br>Inventory                                                                                                                           |
|                                         | •<br>Multiple Warehouses                                                                                                                 |
| Inventory Preferences (IN101000) form   | Make sure that all necessary settings related to inven<br>tory have been specified, as described in Order Man<br>agement with Inventory. |
| Warehouses (IN204000) form              | Make sure that the required warehouses have been<br>created, as described in Warehouses: Implementation<br>Activity.                     |
| Stock Items (IN202500) form             | Make sure that the required stock items have been cre<br>ated, as described in the Stock Items: Implementation<br>Activity.              |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of the processing of two-step transfers by specifying additional settings:

- To cause transfers with the *On Hold* status to be created (so that a user can verify the documents before further processing), you select the **Hold Documents on Entry** check box in the **Data EntrySettings** section on the *[Inventory Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f2eb4e55-f802-4259-a41f-609965c856f1)* (IN101000) form.
- To cause general ledger batches generated during the processing of inventory documents to be posted automatically, you select the **Automatically Post on Release** check box in the **PostingSettings** sections on the *[Inventory Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f2eb4e55-f802-4259-a41f-609965c856f1)* form.

#### **Validation of Settings**

To make sure that all settings are configured correctly, process a sale of stock items, as described in *[Two-Step](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=cfc0d321-2547-47ff-afc0-fabe37f46596) [Transfers:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=cfc0d321-2547-47ff-afc0-fabe37f46596) Process Activity*.

## <span id="page-74-2"></span><span id="page-74-0"></span>**Manufacturing**

## <span id="page-74-1"></span>**System Preparation for Manufacturing Implementation: Implementation Checklist**

The following section provides details you can use to ensure that the system is configured properly for implementing manufacturing.

#### **Implementation Checklist**

We recommend that before you start configuring manufacturing-specific settings, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                                                                  |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:                                                                                                                                                                                                                                                                                                                          |
|                                    | The Manufacturing group of features. If you use ad<br>•<br>ditional manufacturing functionality (such as esti<br>mates), make sure that the corresponding features<br>have been enabled within this group of features.<br>•<br>The Inventory feature, and the Lot and Serial Track<br>ing feature within the Inventory and Order Manage<br>ment group of features. |
| Numbering Sequences (CS201010)     | Required numbering sequences have been created for<br>the following entities:                                                                                                                                                                                                                                                                                      |
|                                    | •<br>Bill of material                                                                                                                                                                                                                                                                                                                                              |
|                                    | •<br>Production order                                                                                                                                                                                                                                                                                                                                              |
|                                    | •<br>Batches of move transactions                                                                                                                                                                                                                                                                                                                                  |
|                                    | •<br>Batches of labor transactions                                                                                                                                                                                                                                                                                                                                 |
|                                    | •<br>Batches of material transactions                                                                                                                                                                                                                                                                                                                              |
|                                    | •<br>Batches of WIP adjustment transactions                                                                                                                                                                                                                                                                                                                        |
|                                    | •<br>Batches of cost transactions                                                                                                                                                                                                                                                                                                                                  |
|                                    | •<br>Forecast                                                                                                                                                                                                                                                                                                                                                      |
|                                    | •<br>MPS type                                                                                                                                                                                                                                                                                                                                                      |
|                                    | You can use the same numbering se<br>quence for the batches of move, labor,<br>and material transactions.                                                                                                                                                                                                                                                          |
| Companies (CS101500)               | The number of decimal places for quantities in the<br>Quantity Decimal Places box and for prices and costs<br>in the Price/Cost Decimal Places box of the Compa<br>ny Details tab is specified according to the business<br>processes of your organization.                                                                                                        |

| Form                                      | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Chart of Accounts (GL202500)              | The following GL accounts have been created:<br>•<br>Work in Progress (required)<br>•<br>WIP Variance (required)<br>•<br>Direct Labor (required)<br>•<br>Indirect Labor<br>•<br>Overhead<br>•<br>Tooling Usage<br>•<br>Machine Usage<br>•<br>Scrap Expense                                                                                                                                                                                                                                                                                                |
| Posting Classes (IN206000)                | Posting classes to be used for the inventory items in<br>volved in manufacturing have been created, and the<br>Work in Progress and WIP Variance accounts have<br>been specified in the posting class settings.<br>If the GL accounts are not specified in the posting<br>class, when creating a production order, the system<br>will copy the accounts specified in the production or<br>der type, which is assigned to the production order.<br>For more information, see System Preparation for Man<br>ufacturing Implementation: General Information. |
| Availability Calculation Rules (IN201500) | Availability calculation rules have been created for the<br>stock items to be involved in manufacturing.                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Replenishment Classes (IN208800)          | If the Inventory Replenishment feature (in the Inven<br>tory and Order Management group of features) is en<br>abled on the Enable/Disable Features (CS100000) form,<br>the replenishment classes that will be used for items in<br>manufacturing processes have been created. At least<br>two classes must be created, one with the Manufac<br>turing replenishment source (for items being manu<br>factured) and one with the Purchase replenishment<br>source (for items being purchased).                                                              |
| Item Classes (IN201000)                   | The item classes that will provide the default settings<br>for the newly created stock items involved in manufac<br>turing have been created.<br>If the Inventory Replenishment feature is<br>disabled on the Enable/Disable Features<br>form, specify the replenishment source<br>for the items of the class in theSource<br>box of the Inventory Planning tab.                                                                                                                                                                                          |
| Stock Items (IN202500)                    | Stock items to be used in manufacturing have been<br>created—both the components and the items to be<br>produced.                                                                                                                                                                                                                                                                                                                                                                                                                                         |

| Form                              | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Warehouses (IN204000)             | The needed warehouses and warehouse locations that<br>will be involved in manufacturing have been defined.<br>If the Material Requirements Planning feature is en<br>abled, the following should be considered:<br>•<br>Set the item plans that should be con<br>sidered during the inventory planning<br>process on the Inventory Planning<br>tab for the warehouse<br>•<br>For warehouse locations that should<br>not be planned using inventory plan<br>ning, clear the check box in the Inven<br>tory Planning column. An example is<br>a quarantine location that should not<br>be planned. |
| Item Warehouse Details (IN204500) | For items involved in manufacturing that can be stored<br>in multiple warehouses, all applicable item settings<br>have been specified that are specific to a particular<br>warehouse, such as the replenishment source, cost in<br>formation, and default warehouse locations for receiv<br>ing and issuing items.                                                                                                                                                                                                                                                                               |
| Employees (EP203000)              | The Production Employee check box is selected for<br>each employee for which labor may be entered in a<br>production order.<br>You can define labor rates for employees on the Labor<br>Rates (PM209900) form if you want to track labor rates<br>by employee.                                                                                                                                                                                                                                                                                                                                   |
| Order Types (SO201000)            | Sales order types have been configured that will be<br>used for production management so that users can<br>create production orders from orders of this type.                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| User Roles (SM201005)             | The appropriate user roles have been configured and<br>assigned to users who must have access to manufac<br>turing functionality.                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Reason Codes (CS211000)           | The appropriate reason code for scrap and the GL ac<br>count that will be used for scrap costs have been con<br>figured.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Vendors (AP303000)                | The vendor accounts who will represent subcontrac<br>tors have been created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Lot/Serial Classes (IN207000)     | The lot or serial classes to be used for produced items<br>and for materials that must be tracked in the system<br>by lot or serial numbers have been created.                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Labor (AM301000)                  | The specific labor account for labor expenses to be re<br>ported has been configured.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

| Form                              | Criteria to Check                                                                                                                                                                              |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Production Order Types (AM201100) | The production order types needed for creating a pro<br>duction order have been created.                                                                                                       |
| Labor Codes (AM206500)            | The labor codes have been created and the corre<br>sponding account in the settings of the labor code has<br>been specified. Labor codes should be specified when<br>you create a work center. |
| Overhead (AM205000)               | The overhead costs for each overhead has been spec<br>ified. Overhead entities should be specified when you<br>create a work center or bill of material.                                       |
| Tools (AM205500)                  | The GL account used for tool costs has been specified.<br>Tool entities must be specified when you create a bill<br>of material.                                                               |
| Machines (AM204500)               | The GL account for machine costs has been specified.<br>Machine entities must be specified when you create a<br>work center.                                                                   |
| Shifts (AM205000)                 | The appropriate shis required for calculating work<br>time in the work center has been created. Shi entities<br>must be specified when you create a work center.                             |
| Work Centers (AM207000)           | The work center has been created with the appropri<br>ate production cost drivers.                                                                                                             |
| Bill of Material (AM208000)       | The bill of material has been created.                                                                                                                                                         |

## <span id="page-77-0"></span>**Bills of Material: Implementation Checklist**

The following section provides details you can use to ensure that the bill of material and the related entities are configured properly for processing production transactions.

#### **Implementation Checklist**

We recommend that before you initially process manufacturing transactions, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                       | Criteria to Check                                                                                                                                                                                                                                          |
|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| BOM Preferences (AM101000) | The following basic settings have been specified on<br>the General tab:                                                                                                                                                                                    |
|                            | •<br>The numbering sequence for bills of material in the<br>BOM Numbering Sequence box (Numbering Set<br>tings section)                                                                                                                                    |
|                            | •<br>The default revision identifier in the Default Revi<br>sion box (Data Entry Settings section)                                                                                                                                                         |
|                            | •<br>The appropriate options in the Duplicates on Op<br>eration and Duplicates on BOM boxes (Data Entry<br>Settings section) to indicate whether the duplicat<br>ed materials can be added at the operation and bill<br>of material levels                 |
|                            | •<br>The default work center in the Default Work Cen<br>ter box (Data Entry Settings section)                                                                                                                                                              |
|                            | •<br>The appropriate state of the Hold BOM Revisions<br>on Entry check box (Data Entry Settings section)<br>to indicate whether the default status of new BOM<br>revisions must be On Hold (if the check box is se<br>lected) or Active (if it is cleared) |
| Labor Codes (AM206500)     | At least one labor code of the Direct type has been cre<br>ated.                                                                                                                                                                                           |
| Machines (AM204500)        | The machines that are involved in production have<br>been created.                                                                                                                                                                                         |
| Tools (AM205500)           | The tools that are used in production and whose costs<br>must be included in the cost of the finished goods have<br>been created.                                                                                                                          |
| Overhead (AM202500)        | The overhead entities have been created to represent<br>the extra costs that must be included in the cost of the<br>finished goods, and in each overhead entity, the unit<br>cost associated with this overhead entity.                                    |
| Stock Items (IN202500)     | For the stock items used as materials, costs have been<br>specified on the Price/Cost tab.                                                                                                                                                                 |
|                            | If these items are to be produced, if the item is pro<br>duced in lots, the lot size has been specified in the Lot<br>Size box on the Manufacturing tab.                                                                                                   |
| Non-Stock Items (IN202000) | For the non-stock items used as materials, costs have<br>been specified on the Price/Cost tab.                                                                                                                                                             |
| Work Calendar (CS209000)   | The work calendars that define the available hours for<br>the manufacturing floor have been created.                                                                                                                                                       |
| Shifts (AM205000)          | At least one shi has been created. If the shi de<br>scribes overtime or holiday work, the differential com<br>pared to the base pay must be specified.                                                                                                   |

| Form                        | Criteria to Check                                                                                                                                 |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| Work Centers (AM207000)     | At least one work center has been created; a work<br>center represents the physical or virtual location in a<br>warehouse or production facility. |
| Bill of Material (AM208000) | Bills of material have been created for all stock items<br>to be produced.                                                                        |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *[Bills of Material: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=baf33d8b-6f79-4cdd-8694-cd2003c37483)*.

## <span id="page-79-0"></span>**Production Order Types: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for creating production order types, and to understand (and change, if needed) the minimum required settings of a production order type.

#### **The Needed Feature Enablement**

You should make sure the *Manufacturing* feature has been enabled on the *[Enable/Disable Features](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1555e43-1bc5-4f6f-ba9d-b323f94d8a6b)* (CS100000) form.

#### **System Configuration**

You need to make sure the following tasks have been performed in Acumatica ERP before you begin to create production order types:

- On the *[Chart of Accounts](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=85557f41-a4af-47a8-b198-2a01461ce9c3)* (GL202500) form, the Work in Process and WIP Variance GL accounts have been created.
- On the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form, at least one numbering sequence for production orders has been created.

We recommend that you create a separate numbering sequence for planning orders on the *[Numbering Sequences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=a8d11c23-21f2-42a3-b17d-9637c9cf8031)* (CS201010) form to distinguish them from regular production orders.

- On the *[BOM Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7224e637-50bc-468d-bfb6-e97b87378ff6)* (AM101000) form, the system settings for bills of material have been specified.
- On the *[Production Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3)* (AM102000) form, the numbering sequences for WIP adjustments, move, material, labor, and cost transactions have been specified.

For more information on configuring the system before you start to create order types, see *[System Preparation for](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2fdbd4d4-6195-4c85-80a9-8a260873ac0a) [Manufacturing Implementation: General Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2fdbd4d4-6195-4c85-80a9-8a260873ac0a)*.

#### **Minimum Required Settings**

For each production order type that you are going to use, you should specify the following minimum settings to configure and activate the order type on the *[Production](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6283187d-54b7-4db1-8c3a-97d3ebc39a95) Order Types* (AM201100) form.

| Location on the Form | Settings to Specify                                                                                                                                                                                                                                            |
|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Summary area         | •<br>The Active check box, indicating that the production order type is available<br>for use, is selected.                                                                                                                                                     |
|                      | •<br>The Function, which determines the workflow of production orders of this<br>type, is selected.                                                                                                                                                            |
| General tab          | •<br>The Order Numbering Sequence, which is the sequence to be used to as<br>sign order reference numbers, is specified.                                                                                                                                       |
|                      | •<br>The Work in Process Account, which is the account for posting item costs<br>until the production order is closed, is specified.                                                                                                                           |
|                      | •<br>The WIP Variance Account, which is the account for posting a difference<br>between the cost of the produced item recorded to the Work in Progress ac<br>count and the final cost of the produced item in the completed production<br>order, is specified. |
|                      | •<br>The Costing Method, which is the method for calculating item costs pro<br>duced by using the production orders of the type, is selected.                                                                                                                  |

#### **Recommended Settings**

We recommend that you specify the following on the *[Production Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3)* (AM102000) form when you have created production order types for regular and disassembly orders:

| Location on the Form                              | Settings to Specify                                                                                                                                                                                                                                                                                                       |
|---------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data Entry Settings section<br>of the General tab | •<br>In the Default OrderType box, the production order type that will be used<br>by the system by default for regular production orders is specified.<br>•<br>In the Default Disassemble OrderType box, the production order type<br>that will be used by the system by default for disassembly orders is speci<br>fied. |

## <span id="page-80-1"></span><span id="page-80-0"></span>**Production Processing: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for production processing, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Prerequisites**

Make sure that the following tasks have been performed before you start implementing production processing:

- The system has been prepared for manufacturing implementation, as described in *[System Preparation for](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f713201a-66c5-403a-a531-62fa3cb09a1a) [Manufacturing Implementation: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f713201a-66c5-403a-a531-62fa3cb09a1a)*.
- Bills of material and all the related entities have been created, as described in *[Implementing Bills of Material:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e11a085c-1a86-499f-9f33-f6b4d312476b) [General Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e11a085c-1a86-499f-9f33-f6b4d312476b)*.

#### **Implementation Checklist**

We recommend that before you initially start processing production orders, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                     |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:                                                                                                                                                                                                                                                                             |
|                                    | The Manufacturing group of features. If you use ad<br>•<br>ditional manufacturing functionality (such as esti<br>mates), make sure that the corresponding features<br>have been enabled within this group of features.<br>•<br>The Inventory feature within the Inventory and Or<br>der Management group of features. |
| Production Order Types (AM201100)  | Production order types have been created, as de<br>scribed in Production Order Types: General Information.                                                                                                                                                                                                            |
| Production Preferences (AM102000)  | All necessary settings related to production manage<br>ment have been specified.                                                                                                                                                                                                                                      |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of processing production orders by specifying additional settings on the *[Production](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3) [Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3)* (AM102000) form as follows:

- To cause labor, move, material, and WIP adjustment transactions to be created with the *On Hold* status (so that the user can verify them before processing them further), on the *[Production Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3)* (AM102000) form, you select the **Hold Documents on Entry** check box.
- To make the system validate totals on labor, move, material, and WIP adjustment transactions, on the *[Production Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3)* form, you select the**Validate DocumentTotals on Entry** check box.
- To make the system immediately update the available quantities of items, on the *[Inventory Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f2eb4e55-f802-4259-a41f-609965c856f1)* (IN101000) form, you select the **Automatically Post on Release** check box.
- To make production orders follow a new production order workflow which changes a production order with the status *Complete* to *Locked*, and then to *Closed*, you select the **Lock Production Orders Before Closing** check box. If the **Lock Production Orders Before Closing** check box is cleared, then the production order will follow the current workflow which changes a production order with the status *Completed* to *Closed*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *Production Processing: To Process [Production-Related](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=cf1dfe9e-7ae6-40ef-8e41-5aaa5324e1a1) Documents and [Transactions](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=cf1dfe9e-7ae6-40ef-8e41-5aaa5324e1a1)*.

## <span id="page-81-0"></span>**Inventory Planning with MRP: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for inventory planning, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially perform inventory planning, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist. You can perform a sample configuration of inventory planning, as described in *Inventory Planning [Configuration:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7a71bef5-764e-4eab-821c-eb125556ae79) To [Implement MRP](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7a71bef5-764e-4eab-821c-eb125556ae79)*.

| Form                                      | Criteria to Check                                                                                                                                                                                                                                                                       |
|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000)        | The Material Requirements Planning feature has been<br>enabled.                                                                                                                                                                                                                         |
| Numbering Sequences (CS201010)            | The numbering sequences for planning recommenda<br>tions, MPS orders, and forecast have been created.<br>We recommend that you create a sepa<br>rate numbering sequence for planning<br>recommendations to distinguish these<br>orders from regular production orders in<br>the system. |
| Production Order Types (AM201100)         | At least one production order type with the Planning<br>function has been created.                                                                                                                                                                                                      |
| Work Calendar (CS209000)                  | Work calendars that will be used in inventory planning<br>have been created.                                                                                                                                                                                                            |
| MPS Type (AM203000)                       | At least one MPS type has been created.                                                                                                                                                                                                                                                 |
| Inventory Planning Preferences (AM100000) | The system settings that affect the inventory planning<br>process have been specified.                                                                                                                                                                                                  |
| Inventory Planning Buckets (AM201200)     | The inventory planning buckets have been created.                                                                                                                                                                                                                                       |
| Warehouses (IN204000)                     | The needed settings for the warehouse and warehouse<br>locations involved in inventory planning have been<br>specified.                                                                                                                                                                 |
| Stock Items (IN202500)                    | For items that should be included in inventory plan<br>ning and are stored in only one warehouse, inventory<br>planning and replenishment settings have been speci<br>fied.                                                                                                             |
| Item Warehouse Details (IN204500)         | For items that are stored in multiple warehouses, in<br>ventory planning and replenishment settings for ware<br>house-stock item pairs have been specified.                                                                                                                             |

#### **Other Settings That Affect the Workflow**

You can affect the processing by specifying additional settings on the *[Inventory Planning Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c73f184e-6d99-47ff-a550-ae2d4f711ec2)* (AM100000) form as follows:

- To include sales orders, purchase orders, and production orders that have the *On Hold* status in the processing, select the **Include On Hold Sales Orders**, **Include On Hold Purchase Orders**, and **Include On Hold Production Orders** check boxes in the **General** section.
- To make the system calculate lead times for a planned order based on the run units and run times specified for each operation of a bill of material on the *[Bill of Material](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=1aae7d3a-d5f9-4693-b91f-663c4c2d362b)* (AM208000) form, select the **Use Fixed ManufacturingTimes** check box in the **General** section.
- You may want the system to consolidate items with the same ID from multiple demand documents into a single planning recommendation during inventory planning. To do this, select the **Use Days ofSupply to Consolidate Orders** check box in the **Consolidation** section.
- You may want the system to consolidate items with the same ID from multiple demand documents with deferred due dates into a single planning recommendation. To do this, select the **Use Long-Term Consolidation Bucket** check box in the **Consolidation** section. Then specify the following settings:
  - **Consolidate Aer (Days)**: The delay period aer which the system starts consolidating items in demand documents
  - **Bucket (Days)**: The number of days within which the due dates in the demand documents must fall

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you run inventory planning by performing instructions similar to those described in *[Inventory Planning with MRP: Process](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=008875d2-45e9-4a9f-9fb5-231363f007a2) [Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=008875d2-45e9-4a9f-9fb5-231363f007a2)*.

## <span id="page-83-0"></span>**Production of Lot- or Serial-Tracked Items: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for tracking the production of lot or serial-tracked items.

#### **Prerequisites**

Make sure that the following tasks have been performed before you start implementing the tracking of the production of lot or serial-tracked items:

- The system has been prepared for the implementation of manufacturing functionality, as shown in *[System](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f713201a-66c5-403a-a531-62fa3cb09a1a) [Preparation for Manufacturing Implementation: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f713201a-66c5-403a-a531-62fa3cb09a1a)*.
- The production of items has been configured, as described in *[Production Processing: Implementation](#page-80-1) [Checklist](#page-80-1)*.

#### **Implementation Checklist**

We recommend that before you initially track the production of lot or serial-tracked items, you make sure the needed features have been enabled and settings have been specified, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                        |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Lot and Serial Tracking feature within the Invento<br>ry and Order Management group of features has been<br>enabled. |

| Form                              | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                         |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Lot/Serial Classes (IN207000)     | The lot or serial classes to be used for produced items<br>and for materials have been created. For the lot or seri<br>al class of the item to be produced, in the Assignment<br>Method box, the When Received option has been spec<br>ified for users to be able to preassign lot or serial num<br>bers to production orders.                                                                            |
| Stock Items (IN202500)            | The stock items for the items to be produced and ma<br>terials used in production of these items have been<br>created. The appropriate lot or serial class is specified<br>in the Lot/Serial Class box of the Item Defaults sec<br>tion on the General tab for each lot- or serial-tracked<br>item.                                                                                                       |
| Bill of Material (AM208000) form  | The bills of material for producing the lot- or seri<br>al-tracked items have been created.                                                                                                                                                                                                                                                                                                               |
| Production Order Types (AM201100) | If you need to set up the preassignment of lot or seri<br>al numbers to produced items, the Allow Preassign<br>ing Lot/Serial Numbers check box is selected on this<br>form (in the Data Entry section of the General tab) for<br>the production order type that you use for production<br>orders of these items. The production order type must<br>have the Regular option selected in the Function box. |
|                                   | If you want users to assign the lot or serial number<br>of each unit of the produced item to the lot- or seri<br>al-tracked materials used to produce the item, you<br>make sure that the appropriate value has been speci<br>fied in the Require Parent Lot/Serial Number box of<br>the same section.                                                                                                    |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you process production orders with lot- or serial-tracked items by performing instructions similar to those described in .*Production of Lot- or [Serial-Tracked](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=dc3e61a7-eda1-43f7-bbcc-76ad47119100) Items: To Assign Parent Serial Numbers to Materials on Issue* and *[Production of](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=edf0b39f-2737-4e21-82c8-fb35f1a029e5) Lot- or [Serial-Tracked](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=edf0b39f-2737-4e21-82c8-fb35f1a029e5) Items: To Assign Parent Serial Numbers to Materials on Completion*.

## <span id="page-84-0"></span>**Outside Processing: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for performing the outside processing, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Prerequisites**

Mare sure that the following tasks have been performed before you start implementing production processing:

• The system has been prepared for manufacturing implementation, as described in *[System Preparation for](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f713201a-66c5-403a-a531-62fa3cb09a1a) [Manufacturing Implementation: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=f713201a-66c5-403a-a531-62fa3cb09a1a)*.

• *[Configuring Production Cost Drivers: Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=c1604cdc-a0d1-4df7-82e0-97c53bafd053)* so that the needed cost drivers have been created in a company with the *U100* dataset preloaded.

#### **Implementation Checklist**

We recommend that before you initially perform outside processing, you make sure the needed settings have been specified and entities have been created, as described in *[Outside Processing: Configuration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=534cebcd-130a-4e82-b7a2-4b4e80f19b7b)* and summarized in the following checklist.

| Form                                                 | Criteria to Check                                                                                                                                                                                                                                                                                             |
|------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Numbering Sequences (CS201010)                       | The numbering sequence for vendor shipments has<br>been created.                                                                                                                                                                                                                                              |
| Production Preferences (AM102000)                    | The numbering sequence for vendor shipments has<br>been specified in the Vendor Shipment Numbering<br>Sequence box in the Numbering Settings section of<br>the General Settings tab.                                                                                                                          |
| Work Centers (AM207000)                              | At least one work center has been created for outside<br>processing with the Outside Process check box select<br>ed in the Summary area.                                                                                                                                                                      |
| Stock Items (IN202500)<br>Non-Stock Items (IN202000) | The needed stock items or non-stock items that you<br>will use to pay each vendor for its services have been<br>created.                                                                                                                                                                                      |
| Vendors (AP303000)                                   | The needed vendors who will represent subcontrac<br>tors have been created.                                                                                                                                                                                                                                   |
| Bill of Material (AM208000)                          | The needed bills of material that you will use for track<br>ing outside processing operations have been created.<br>The settings for each bill of material must be specified<br>as follows:                                                                                                                   |
|                                                      | •<br>The Operations table must include the needed<br>work centers dedicated for tracking the outside<br>processing operations.                                                                                                                                                                                |
|                                                      | •<br>For each outside processing operation, the Mate<br>rials tab must include at least one material with a<br>MaterialType of Subcontract and the appropriate<br>SubcontractSource.                                                                                                                          |
|                                                      | •<br>The warehouse from which a material with the Ship<br>to Vendor subcontract source will be issued has<br>been specified in the Warehouse column of the<br>material line. If the column is empty, the material<br>will be issued from the warehouse specified in the<br>Warehouse box of the Summary area. |
|                                                      | •<br>The appropriate vendor information has been spec<br>ified on the Outside Process tab for each outside<br>processing operation.                                                                                                                                                                           |

#### **Recommended Settings for Work Centers**

When you create a work center dedicated for outside processing, we recommend that you specify the following settings in the Summary area of the *[Work Centers](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6543295f-b1eb-4991-868f-503435b1d67a)* (AM207000) form:

- **Outside Process**: Selected
- **Standard Cost**: 0
- **Basis for Capacity**: *Crew Size*
- **Scrap Action Default:** *No Action*
- **Backflush Materials**: Selected
- **Backflush Labor**: Selected

#### **Other Settings That Affect the Workflow**

You can affect the workflow of outside processing by specifying additional settings in the**VendorShipment Settings** section of the *[Production Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3)* (AM102000) form as follows:

- To cause vendor shipments to be created with the *On Hold* status (so that the user can verify them before processing them further), you select the **Hold Shipments on Entry** check box.
- To make the system validate totals on vendor shipments, you select the**ValidateShipmentTotal on Confirmation** check box.

We recommend that you set up backflushing for the material you use to record subcontracting costs. If this material is not backflushed, you will need to create a material transaction to record the subcontracting costs.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you perform instructions similar to those described in *[Outside Processing: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=e2759030-a424-4b66-9261-69455dc5adfd)*.

### <span id="page-86-0"></span>**Production with Backflushing: Implementation Checklist**

The following sections provide details that you can use to ensure that the system is configured properly for recording the production of items with material or labor backflushing, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Prerequisites**

Make sure that before you start implementing the production of items with backflushing, the system has been prepared for specifying manufacturing-specific settings, as described in *[System Preparation for Manufacturing](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2fdbd4d4-6195-4c85-80a9-8a260873ac0a) [Implementation: General Information](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=2fdbd4d4-6195-4c85-80a9-8a260873ac0a)*.

#### **Implementation Checklist**

We recommend that before you initially start processing production orders with material or labor backflushing, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:                                                                                                                                                                                                                                        |
|                                    | •<br>The Manufacturing group of features. If you use ad<br>ditional manufacturing functionality (such as esti<br>mates), make sure that the corresponding features<br>have been enabled within this group of features.<br>•<br>The Inventory feature within the Inventory and Or |
|                                    | der Management group of features.                                                                                                                                                                                                                                                |
| Production Order Types (AM201100)  | Production order types have been created, as de<br>scribed in Production Order Types: General Information.                                                                                                                                                                       |
| Production Preferences (AM102000)  | All necessary settings related to production manage<br>ment have been specified.                                                                                                                                                                                                 |
| Work Centers (AM207000)            | A work center for each operation with material or la<br>bor backflushing has been created. For the work cen<br>ter, in the Summary area, the Backflush Materials or<br>Backflush Labor check box is selected, or both check<br>boxes are selected.                               |
| Bill of Material (AM208000)        | The bill of material has been created and one or both<br>of the following criteria are met for each operation<br>with material or labor backflushing:                                                                                                                            |
|                                    | •<br>The Backflush Labor check box is selected in the<br>row of the Operations table.                                                                                                                                                                                            |
|                                    | •<br>On the Materials tab, the Backflush Materials<br>check box is selected for some or all of the materi<br>als required for each operation                                                                                                                                     |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of item production with material and labor backflushing by specifying additional settings. If you want the system to validate whether the material quantity in stock is available for the item quantity that a user records in a move or labor transaction for an operation with material backflushing, you select the *Not Allow* option in the **Under Issue Backflush Material** box on the *[Production](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=6283187d-54b7-4db1-8c3a-97d3ebc39a95) Order Types* (AM201100) form. If the previous operations also have materials backflushed, the system will validate the availability of the needed material quantity for these operations as well.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you manage item production with backflushed materials and labor by performing instructions similar to those described in *[Production with Backflushing: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=3a6705c8-0dc2-4ff5-a0fd-cb84bcbec174)*.

## <span id="page-88-0"></span>**Scrap and Waste In Production: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for processing scrap and waste during item production, and to understand (and change, if needed) the settings that affect the processing workflow.

#### **Implementation Checklist**

We recommend that before you initially process scrap and waste, you make sure that the needed features have been enabled, settings have been specified and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                                             |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The following features have been enabled:                                                                                                                                                                                                                                                                                                     |
|                                    | •<br>The Manufacturing group of features. If you use ad<br>ditional manufacturing functionality (such as esti<br>mates), make sure that the corresponding features<br>have been enabled within this group of features.<br>The Inventory feature within the Inventory and Or<br>•<br>der Management group of features.                         |
| Chart of Accounts (GL202500)       | The GL account to be used for posting scrap costs has<br>been created.                                                                                                                                                                                                                                                                        |
| Reason Codes (CS211000)            | The reason code that shop-floor employees will speci<br>fy when entering scrap quantities has been created.                                                                                                                                                                                                                                   |
|                                    | The reason code is required only for operations with<br>the Write-Off or Quarantine scrap action.                                                                                                                                                                                                                                             |
| Production Order Types (AM201100)  | The needed settings of scrap storage have been speci<br>fied for each production order type with the Regular or<br>Disassemble function.                                                                                                                                                                                                      |
| Work Centers (AM207000)            | A work center for each operation that may have scrap<br>or waste as an output has been created. For the work<br>center, in the Scrap Action Default box on the Gener<br>al tab, the appropriate option is selected.                                                                                                                           |
| Bill of Material (AM208000)        | The bill of material has been created, and in the Op<br>erations table, the needed option is selected in the<br>Scrap Action column of each operation row. In addi<br>tion, in the Scrap Factor column on the Materials tab,<br>the scrap percentage is specified for the materials for<br>which waste must be included in the material cost. |

| Form                                                           | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|----------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Item Warehouse Details (IN204500)<br>Stock Items<br>Warehouses | The scrap warehouse and location have been speci<br>fied on the Manufacturing tab of the needed form, de<br>pending on the option selected in the Scrap Source<br>box of the Production Order Types form of a production<br>order type with the Regular or Disassemble function.<br>The scrap warehouse and location are needed only<br>when multiple warehouses or warehouse locations are<br>used in the system and when movement of scrapped<br>items to storage is tracked (that is, the scrap action for<br>some or all production operations is Quarantine). |

#### **Other Settings That Affect the Workflow**

If you want the system to regard scrapped items as completed items and mark the operations of a production order as completed when the sum of completed items and scrapped items equals the quantity to produce of the production order, you select the **IncludeScrap in Completions** check box on the *[Production Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=678a1833-f1f6-44f1-afce-55aa7438b3f3)* (AM102000) form. For more information, see *[Configuration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b29b7509-9952-4c7d-8b70-1d2d4270148d) of Scrap, Waste, and By-Products in Production: General [InformationConfiguration](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=b29b7509-9952-4c7d-8b70-1d2d4270148d) of Scrap and Waste in Production: General Information*.

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you manage item production that may also produce scrap or waste by performing instructions similar to those described in *Scrap and Waste in [Production:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=52acbfec-e50d-45c9-b29c-0012e211c0e7) To Process a Production Order with No Scrap Settings* and *Scrap and [Waste](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47589ba7-ca7e-4d08-8cfa-19d20044647a) in Production: To Process a Production Order That Includes [Quarantined](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=47589ba7-ca7e-4d08-8cfa-19d20044647a) Scrap*.

## <span id="page-89-0"></span>**Estimating: Implementation Checklist**

The estimating functionality uses master data from the bills of material forms for estimating labor, overhead, tooling, and machine costs. Therefore you need to define this elements and create the necessary work centers before operation details.

#### **Estimating Configuration Check List**

| No. | Task                                                   | Description                                                                                                                                                           |
|-----|--------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Enable the estimating feature                          | On the Enable/Disable Features (CS100000) form, make sure<br>that the Estimating feature is enabled under the Manufac<br>turing Suite group of features.              |
| 2   | Create the required estimate classes                   | Use the Estimate Classes (AM206000) form to define them.<br>You must specify a class when you build an estimate.                                                      |
| 3   | Define the numbering sequence for the<br>estimation ID | Create a numbering sequence for estimate IDs on the Num<br>bering Sequences (CS201010) form and specify the se<br>quence on the Estimate Preferences (AM103000) form. |

| No. | Task                                                                | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-----|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 4   | Define work centers                                                 | Use the Work Centers (AM207000) form to define the areas<br>where work will be performed. Normally these are areas<br>of a warehouse intended to be used in the production pro<br>cessing such as assembly, cutting, painting, and testing.<br>These can also be used to track outside processing. These<br>track standard labor rates (optional), overheads (optional)<br>and machines (optional). You cannot add an estimate oper<br>ation details on the Estimate Operation (AM304000) form un<br>less you define a work center. |
| 5   | Complete the estimate setup                                         | Use the Estimate Preferences (AM103000) form. This must be<br>completed before you can use the estimating functionality.                                                                                                                                                                                                                                                                                                                                                                                                            |
| 6   | Optionally create notification tem<br>plates                        | Estimates use Employees (EP203000) records to indicate the<br>Owner and/or Engineer of an estimate. You can use busi<br>ness events functionality to track changes of estimates. For<br>details, see Using Business Events.                                                                                                                                                                                                                                                                                                         |
| 7   | Determine if estimates will be used on<br>customer management forms | On the Customer Management Preferences (CR101000) form,<br>select the Allow Estimating check box.                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 8   | Determine if estimates will be used in<br>sales orders              | On the Order Types (SO201000) form, select the Allow Esti<br>mating check box. Typically, estimates are used for orders<br>with the Quote type because they may contain non-invento<br>ry items.                                                                                                                                                                                                                                                                                                                                    |

## <span id="page-90-0"></span>**Product Configurator: Implementation Checklist**

Before you start using the product configurator functionality, you must configure the system as described in the following table.

| No. | Task                                                         | Description                                                                                                                                                       |
|-----|--------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Enable the Product Configurator fea<br>ture                  | On the Enable/Disable Features (CS100000) form, make sure<br>that the Product Configurator feature is enabled under the<br>Manufacturing Suite group of features. |
| 2   | Define the numbering sequences for<br>the configuration data | Create numbering sequences for the configuration ID and<br>defaults ID by using the Numbering Sequences (CS201010)<br>form.                                       |
| 3   | Specify preferences                                          | Use the Configurator Preferences (AM104000) form. This<br>must be completed before you can use the functionality.                                                 |

| No. | Task                                                                             | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-----|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 4   | Create stock items                                                               | Use the Stock Items (IN202500) form to create the items.<br>Once you have built a configuration you will need to select<br>the configuration ID of the active revision. Do the same on<br>the Item Warehouse Details (IN204500) form. Stock items<br>should have a lot or serial class specified,where the lot or<br>serial number is assigned upon receipt to help the system<br>in selecting the proper item to allocate or ship. You can use<br>the sales order number and line as the lot or serial number<br>(such as SO123456/3) because the number is the reference<br>in the production order. Alternatively, you can use the pro<br>duction order number as the lot or serial number because it<br>is referenced in the sales order line. |
| 5   | Create bills of material for configured<br>items                                 | The bill of material defines the manufacturing process and<br>fixed materials for each configured stock item. Use the Bill<br>of Material (AM208000) form to create the bill. The bill need<br>to have a least one operation in order to attach the selected<br>inventory items to the configuration. A fixed material is one<br>always used to build the configured item.                                                                                                                                                                                                                                                                                                                                                                         |
| 6   | Define the attributes you will use in<br>configurations                          | Attributes are optional are used to capture the data en<br>tered. When you add an attribute to a configuration defini<br>tion you assign each a variable that can be used for formu<br>las. The configurator uses the same attributes used else<br>where in Acumatica ERP. Create the data using the Attributes<br>(CS205000) form.                                                                                                                                                                                                                                                                                                                                                                                                                |
| 7   | Define the features and their options<br>you will use for your configured items. | Defined the features and options on the Features<br>(AM203500) form. Features can be used in multiple configu<br>rations. The options are inventory items available for each<br>feature as well as non-inventory items used for calculations,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| 8   | Build and test the configuration                                                 | You use the Configuration Maintenance (AM207500) from to<br>define configurations. You add features, modify the list of<br>options as required, add attributes, pricing rules, and add<br>rules. Once built, you can test the configuration directly<br>from the form. When your satisfied, you make the configura<br>tion and its revision active and add the configuration ID on<br>the Stock Items and Item Warehouse Details forms.                                                                                                                                                                                                                                                                                                            |
| 10  | Configure the Order Types                                                        | You must select the Allow Configuration Entry and Allow<br>Production Orders check boxes for a sales order type on<br>the Order Types (SO201000) form for which you will use the<br>product configurator and create production orders. For in<br>formation on printing the configuration options selected on<br>sales order forms, see Product Configurator: Adding Configu<br>ration Data to Forms.                                                                                                                                                                                                                                                                                                                                               |
| 11  | Configure the CRM Preferences                                                    | On the Customer Management Preferences (CR101000) form,<br>select the Allow Configuration Entry check box for oppor<br>tunities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

## <span id="page-92-0"></span>**Capable to Promise: Implementation Checklist**

The following sections provide details you can use to ensure that the system is configured properly for using the capable-to-promise (CTP) functionality.

#### **Implementation Checklist**

We recommend that before you initially run the calculation of projected dates for sales orders, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist. You can perform the instructions similar to those described in *[Capable to Promise:](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=268e5b86-6e52-489c-ac12-33251a3a42ee) [Implementation Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=268e5b86-6e52-489c-ac12-33251a3a42ee)* to configure the system.

| Form                               | Criteria to Check                                                                                                                                                                                                                                                                                                                                                                                                        |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Advanced Planning and Scheduling feature has<br>been enabled.                                                                                                                                                                                                                                                                                                                                                        |
| Numbering Sequences (CS201000)     | The numbering sequence has been created for the<br>CTP-related planning orders to be created by the CTP<br>process.<br>We recommend that you create a sepa<br>rate numbering sequence for these plan<br>ning to distinguish them from the plan<br>ning orders unrelated to CTP.                                                                                                                                          |
| Production Order Types (AM201100)  | The production order type has been created for the<br>CTP-related planning orders, and the following recom<br>mended settings have been specified:<br>•<br>Function: Planning<br>•<br>Order Numbering Sequence: The specific number<br>ing sequence for CTP-related planning orders<br>•<br>Exclude from MRP: Cleared<br>We recommend that you create a sepa<br>rate order type for all CTP-related plan<br>ning orders. |
| Production Preferences (AM102000)  | The order type for the CTP-related planning orders has<br>been specified in the Capable to Promise OrderType<br>box in the Data Entry Settings section.                                                                                                                                                                                                                                                                  |
| Stock Items (IN202500)             | The CTP Item check box has been selected on the<br>Manufacturing tab (General section) for all stock<br>items for which you want to calculate projected dates.                                                                                                                                                                                                                                                           |

| Form                   | Criteria to Check                                                                                                                                                                                                                                        |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Order Types (SO201000) | The Allow Production Orders - Approved and Allow<br>Production Orders - Hold check boxes have been se<br>lected in the Manufacturing Settings section of the<br>General tab for the sales order type for which project<br>ed dates should be calculated. |

#### **Validation of Configuration**

To make sure that all configuration has been performed correctly, we recommend that in your system, you calculate the projected dates for items in sales order by performing instructions similar to those described in *[Capable to Promise: Process Activity](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=5b14d52c-9ad4-4827-899a-452e43ccad96)*.

## <span id="page-93-0"></span>**Engineering Change Control: Implementation Checklist**

The following sections provides details that you can use to ensure that engineering change control is configured properly.

#### **Implementation Checklist**

We recommend that before you start using engineering change control, you make sure the needed features have been enabled, settings have been specified, and entities have been created, as summarized in the following checklist.

| Form                               | Criteria to Check                                                                                                                  |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| Enable/Disable Features (CS100000) | The Engineering Change Control feature is enabled un<br>der the Manufacturing group of features.                                   |
| Numbering Sequences (CS201010)     | The numbering sequences have been created for the<br>identifiers of engineering change requests and engi<br>neering change orders. |
| BOM Preferences (AM101000)         | The following settings have been specified on the Gen<br>eral tab (Numbering Settings):                                            |
|                                    | •<br>The numbering sequence for ECRs in the ECR Num<br>bering Sequence box                                                         |
|                                    | •<br>The numbering sequence for ECOs in the ECO Num<br>bering Sequence box                                                         |
| Email Templates (SM204003)         | The corresponding notification templates have been<br>created if you want to inform users about any of the<br>following events:    |
|                                    | •<br>An ECR or ECO has been created.                                                                                               |
|                                    | •<br>An ECR or ECO is waiting for an approval.                                                                                     |
|                                    | •<br>An ECR or ECO has been approved.                                                                                              |
|                                    | •<br>An ECR or ECO has been rejected.                                                                                              |

#### **Other Settings That Affect the Workflow**

You can affect the workflow of engineering change control by doing any of the following on the *[BOM Preferences](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=7224e637-50bc-468d-bfb6-e97b87378ff6)* (AM101000) form:

- If you want to restrict the creation of new revisions of bills of material based on engineering change requests or engineering change orders so that the revisions can be created only by using an ECR or an ECO, you select the **Require ECR/ECO for New BOM Revisions** check box in the **Data EntrySettings** section of the **General** tab.
- If you want to allow engineers to create engineering change orders without creating engineering change requests, you clear the **Require ECR Before Creating ECO** check box in the **Data EntrySettings** section of the **General** tab.
- If you want to use approvals for engineering change requests, on the **ECR Approval** tab, you select the **ECR Require Approval** check box, and in the table, you add the needed approval map for ECRs, which is created on the *[Assignment and Approval Maps](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=54d9618b-c27b-47d5-9748-24441084e99e)* (EP205500) form.
- If you want to use approvals for engineering change orders, on the **ECO Approval** tab, you select the **ECO Require Approval** check box, and in the table, you add the approval map for ECOs, which is created on the *[Assignment and Approval Maps](https://help-2025r1.acumatica.com/Help?ScreenId=ShowWiki&pageid=54d9618b-c27b-47d5-9748-24441084e99e)* form.