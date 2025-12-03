**Pre-requisites:**

As an SAP Concur customer, you can opt for the SAP Joule BASE SKU, which is a “0$” contract with options ranging from 1 year to 3 years. To sign up for this, you can visit the [link here](https://www.sap.com/products/artificial-intelligence/joule-base-entitlement.html) and follow the onscreen instructions. In case of any questions, please feel free to contact your SAP AE or the CSM.  During the contract process, you will be asked to select an SAP Business Technology Platform (SAP BTP) tenant where Joule needs to be contracted. If you are an SAP Concur-only customer and do not have an SAP BTP account, please select New BTP Account and proceed further.

 

**Important Tips: (Please ensure to read them before you work on the license):**

If you are an SAP Concur-only customer, without an SAP footprint
You may have to register yourself first, follow the onscreen instructions in the SAP Store – Buy as a customer. Refer to this document for more information - [Joule Base Entitlement](https://www.linkedin.com/feed/update/urn:li:activity:7377036423763472385/)
If you are an SAP customer and do not have a BTP Account, it will be provisioned free of cost along with Joule
Provisioning of **new** BTP Accounts and Joule contracts may take less than 24 hours, at times up to 48 hours.
If you are **new** to SAP BTP and would like to get familiar, you can request a session [here](https://support.sap.com/en/product/onboarding-resource-center/business-technology-platform.html)
If you have an **existing SAP BTP account**, we recommend using the existing accounts and avoiding creating a new one
Joule requires **SAP Cloud Identity Services (SAP CIS)**.
You can configure your SSO with SAP Concur with SAP CIS as IDP, or
You can configure your SSO with SAP Concur with SAP CIS as IDP, or You can configure your SSO with SAP Concur with SAP CIS as a proxy In case you have an existing IDP, like MS Azure/OKTA, you can continue using it and set up SAP CIS as proxy; however, you need to replicate the users in your SAP CIS. You can find more details as you read below
SAP Concur gives you the option to have multiple SSOs. In case you would like to try with a few users to log in via SAP CIS, you can do so. This ensures that you do not change the entire setup or impact all the users during the testing process. 
Here is the updated Joule documentation link, https://help.sap.com/docs/joule/integrating-joule-with-sap/getting-started-with-joule-basic. Please refer to the information here.
In case you are not sure of the available SAP Cloud Identity Services for you, please validate -
Joule contracts can only be sold once to a customer. If you have the Joule Base or SAP AI Units contracts, you do not have to sign new contracts, and you are good to go ahead with the setup of Joule with SAP Concur.

Once the Contract is signed, you will need to create an Incident and share your **SAP Concur – “Entity ID” and “SAP - Customer Number”** (in case you need support, please contact your AE or your CSM), the required “**SAP Cloud Identity Service Tenant**” for SAP Concur Integration.

Important Tip:

If you are new to SAP, you can find information on how to create SAP incidents [here](https://me.sap.com/home),  to create an SAP for Me case, see this SAP Note: 1296527 Information published on the SAP site—How to create a support case (contact SAP Product Support)—SAP for Me. Use the Component = BNS-CON-SSO.
For more information about creating an [SAP Concur support case](https://help.sap.com/docs/SAP_CONCUR/f959944ebe30460dbe11e7ccbec19319/187ece276f091014aa76d877ebc532b3.html), navigate to the SAP Concur Support Portal and select Case Type = Single Sign On.
 

Joule can be activated with your **SAP Concur Sandbox / Production systems**. Please ensure to raise the tickets based on your point of start to achieve SSO.
If you are an SAP Concur-only customer,
When you sign the new contract, a new CRM ID will be generated with an SAP BTP account.

After that, once the Incident is addressed and processed, you will receive instructions from SAP on how to use MS Entra / OKTA / any other IDP services.  

Some of the processes have been detailed below to ensure you can plan the User Sync with SAP Cloud Identity Services and your IDP.

**Important Tip:**

Overview of SAP Cloud Identity Services
Here is the help portal link step-by-step guide: Concur SSO - Identity Authentication Service for SAP Cloud Identity Services Setup. Ensure to complete Step 1 and Step 2 of this help page.
The SAP Concur Import & Export admin role should be able to follow the help portal document 315 (SAP Global User ID Importer) for the employee file upload. For more information, refer to Step 2 of this blog
