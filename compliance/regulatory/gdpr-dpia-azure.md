---
title: DPIA Azure for the GDPR
description: Find information to determine if a Data Protection Impact Assessment (DPIA) is necessary when using Microsoft Azure.
keywords: DPIA, Microsoft 365, Microsoft 365 Education, Microsoft 365 documentation, GDPR
localization_priority: Priority
ms.prod: microsoft-365-enterprise
ms.topic: article
f1.keywords:
- NOCSH
ms.author: robmazz
author: robmazz
manager: laurawi
audience: itpro
ms.collection: 
- GDPR
- M365-security-compliance
- MS-Compliance
hideEdit: true
titleSuffix: Microsoft GDPR
ms.custom: seo-marvel-mar2020
---

# Data Protection Impact Assessments: Guidance for Data Controllers Using Microsoft Azure

Under the General Data Protection Regulation (GDPR), data controllers are required to prepare a Data Protection Impact Assessment (DPIA) for processing operations that are "likely to result in a high risk to the rights and freedoms of natural persons." There is nothing inherent in Microsoft Azure itself that would necessarily require the creation of a DPIA by a data controller using it. Rather, whether a DPIA is required will be dependent on the details and context of *how* the data controller deploys, configures, and uses Microsoft Azure.

The purpose of this document is to provide data controllers with information about Microsoft Azure that will help them to determine whether a DPIA is needed and, if so, what details to include.

>[!Note]
>Microsoft is not providing any legal advice in this document. This document is being provided for informational purposes only. Customers are encouraged to work with their privacy officers and legal counsel to determine the necessity and content of any DPIAs related to their use of Microsoft Azure or any other Microsoft online service.

## Part 1: Determining whether a DPIA is needed

Article 35 of the GDPR requires a data controller to create a Data Protection Impact Assessment (DPIA) "[w]here a type of processing in particular using new technologies, and taking into account the nature, scope, context, and purposes of the processing, is likely to result in a high risk to the rights and freedoms of natural persons." It further sets out particular factors that would indicate such a high risk, which is discussed in the following table: To determine whether a DPIA is needed, a data controller should consider these factors, along with any other relevant factors, in light of the controller's specific implementation(s) and use(s) of Microsoft Azure.

|**High Risk Factor**|**Relevant Information about Microsoft Azure**|
|:----|:----|
| A systematic and extensive evaluation of personal aspects relating to natural persons that is based on automated processing, including profiling and on which decisions are based that produce legal effects concerning the natural person or similarly significantly affect the natural person.| Microsoft Azure does not provide capabilities to perform certain automated processing of data. <br><br> *However, because Azure is a highly customizable service, a data controller could potentially configure it to be used for such processing*. Controllers should make this determination based on their usage of Azure. |
| Processing on a large scale of special categories of data (personal data revealing racial or ethnic origin, political opinions, religious or philosophical beliefs, or trade union membership, and the processing of genetic data, biometric data for the purpose of uniquely identifying a natural person, data concerning health or data concerning a natural person's sex life or sexual orientation), or of personal data relating to criminal convictions and offenses. | Microsoft Azure is not designed to process special categories of personal data and the usage of Azure does not increase the inherent risk of a controller's processing. <br><br> *However, a data controller could use Microsoft Azure to process the enumerated special categories of data*. Microsoft Azure is a highly customizable service that enables the customer to track or otherwise process any type of data, including special categories of personal data. But as the data processor, Microsoft has no control over such use and has little or no insight into such use. It is incumbent upon the data controller to determine appropriate uses of the data controller's data. |
| A systematic monitoring of a publicly accessible area on a large scale.  | Microsoft Azure is not designed to conduct or facilitate such monitoring. <br><br> *However, a data controller could use Azure to process data collected through such monitoring.* Microsoft Azure is a highly customizable service that enables the customer to track or otherwise process any type of data, including monitoring data. But as the data processor, Microsoft has no control over such use and has little or no insight into such use.   It is incumbent upon the data controller to determine appropriate uses of the data controller's data. |

## Part 2: Contents of a DPIA

Article 35(7) mandates that a Data Protection Impact Assessment specifies the purposes of processing and a systematic description of the envisioned processing. A systematic description of a comprehensive DPIA might include factors such as the types of data processed, how long data is retained, where the data is located and transferred, and what third parties may have access to the data. In addition, the DPIA must include:

- an assessment of the necessity and proportionality of the processing operations in relation to the purposes;
- an assessment of the risks to the rights and freedoms of natural persons; and
- the measures envisaged to address the risks, including safeguards, security measures, and mechanisms to ensure the protection of personal data and to demonstrate compliance with this Regulation taking into account the rights and legitimate interests of data subjects and other persons concerned.

The following table contains information about Microsoft Azure that is relevant to each of those elements. As in Part 1, data controllers must consider the details provided in the table, along with any other relevant factors, in the context of the controller's specific implementation(s) and use(s) of Microsoft Azure.

|**Element of a DPIA**|**Relevant Information About Microsoft Azure**|
|:---|:---|
| Purpose(s) of processing | The purpose(s) of processing data using Microsoft Azure is determined by the controller that implements, configures, and uses it. <br><br> As specified by the [Online Services Terms](https://www.microsoftvolumelicensing.com/DocumentSearch.aspx?Mode=3&DocumentTypeId=46) and [Data Protection Addendum](https://www.microsoftvolumelicensing.com/DocumentSearch.aspx?Mode=3&DocumentTypeId=67), Microsoft, as a data processor, processes Customer Data to provide Customer the Online Services in accordance with Customer's documented instructions. <br><br> As detailed in the standard [Online Services Terms](https://www.microsoftvolumelicensing.com/DocumentSearch.aspx?Mode=3&DocumentTypeId=46) and [Data Protection Addendum](https://www.microsoftvolumelicensing.com/DocumentSearch.aspx?Mode=3&DocumentTypeId=67), Microsoft also uses Personal Data to support a limited set of legitimate business operations consisting of: (1) billing and account management; (2) compensation (for example, calculating employee commissions and partner incentives); (3) internal reporting and modeling (for example, forecasting, revenue, capacity planning, product strategy); (4) combatting fraud, cybercrime, or cyber-attacks that may affect Microsoft or Microsoft Products; (5) improving the core functionality of accessibility, privacy, or energy efficiency; and (6) financial reporting and compliance with legal obligations (subject to the limitations on disclosure of Customer Data outlined in the Online Service Terms). <br><br> Microsoft is controller of the processing of personal data to support these specific legitimate business operations. Generally, Microsoft aggregates Personal Data before using it for our legitimate business operations, removing Microsoft's ability to identify specific individuals, and uses personal data in the least identifiable form that will support processing necessary for legitimate business operations. <br><br> Microsoft will not use Customer Data or information derived from it for profiling or for advertising or similar commercial purposes. |
| Categories of personal data processed  | *Customer Data—All data, including all text, sound, video, or image files, and software, that are provided to Microsoft by, or on behalf of, a customer through use of the enterprise service.  Customer Data includes both (1) identifiable information of end users (for example, user names and contact information in Azure Active Directory) and customer content that a customer uploads into or creates in specific services (for example, customer content in an Azure Storage account, customer content of an Azure SQL Database, or a customer's virtual machine image in Azure Virtual Machines).<br><br> *Service-Generated Data—Logs and related data generated by Microsoft that help Microsoft provide enterprise services to users. Service-generated logs contain primarily pseudonymized data, associated with unique identifiers generated by the system, that cannot on their own identify an individual person but are used to deliver the enterprise services to users. These service-generated logs may also contain identifiable information about end users, such as a username. <br><br> *Support Data—This is data provided to Microsoft by or on behalf of Customer (or that Customer authorizes Microsoft to obtain from an Online Service) through an engagement with Microsoft to obtain technical support for Online Services. <br><br> For more information regarding data processed by Azure, see the [Online Services Terms](https://www.microsoftvolumelicensing.com/DocumentSearch.aspx?Mode=3&DocumentTypeId=46), including the Data Processing Agreement as well as [Microsoft Trust Center](https://www.microsoft.com/trustcenter).</p> |
| Data retention | Microsoft will retain and process Customer Data for the duration of the Customer's right to use the Online Service and until all Customer Data is retrieved by Customer or deleted in accordance with the terms of the OST.  At all times during the term of Customer's subscription, the Customer will have the ability to access and extract Customer Data stored in each Online Service. Except for free trials and LinkedIn services, Microsoft will retain Customer Data stored in the Online Service in a limited function account for 90 days after expiration or termination of Customer's subscription so that Customer may extract the data. After the 90-day retention period ends, Microsoft will disable Customer's account and delete the Customer Data. The customer can delete personal data pursuant to a Data Subject Request using the capabilities described in the [Azure Data Subject Request GDPR Documentation.](https://servicetrust.microsoft.com/ViewPage/GDPRDSR) |
| Location and transfers of personal data | Customers have the ability to provision Customer Data at rest within specified [geographic regions](https://azuredatacentermap.azurewebsites.net/), subject to certain exceptions as set out in the OST. Additional details regarding service deployments and data residency can also be found in Attachment 1 of the Online Services Terms (OST) and the [Azure Global Infrastructure](https://azure.microsoft.com/global-infrastructure/) webpage.<br><br>For personal data from the European Economic Area and Switzerland, Microsoft will ensure that transfers of Personal Data to a third country or an international organization are subject to appropriate safeguards as described in Article 46 of the GDPR. In addition to Microsoft's commitments under the Standard Contractual Clauses for processors and other model contracts, Microsoft is certified to the EU-U.S. and Swiss-U.S. Privacy Shield Frameworks and the commitments they entail. |
| Data sharing with third-party subprocessors | Microsoft shares data with third parties acting as our subprocessors to support functions such as customer and technical support, service maintenance, and other operations. Any subcontractors to which Microsoft transfers Customer Data, Support Data, or Personal Data will have entered into written agreements with Microsoft that are no less protective than the Data Protection Terms of the [Online Services Terms](https://www.microsoftvolumelicensing.com/DocumentSearch.aspx?Mode=3&DocumentTypeId=46). All third-party subprocessors with which Customer Data from Microsoft's Core Online Services is shared are included in the Online Services Subcontractor list. All third-party subprocessors that may access Support Data (including Customer Data that customers choose to share during their support interactions) are included in the [Microsoft Commercial Support Contractors](https://www.microsoft.com/trustcenter/privacy/who-can-access-your-data-and-on-what-terms#subcontractors) list. |
| Data subject rights | When operating as a processor, Microsoft makes available to the customer (also known as the data controller) the personal data of its data subjects and the ability to fulfill data subject requests when they exercise their rights under the GDPR. Microsoft does so in a manner consistent with the functionality of the product and its role as a data processor.  If Microsoft receives a request from the customer's data subjects to exercise one or more of its rights under the GDPR, the request will be redirected to the data controller. <br><br> The Azure Data Subject Requests Guide provides a description to the data controller on how to support data subject rights using the capabilities in Azure. <br><br> Requests from a data subject to exercise rights under the GDPR for personal data  processed to support the legitimate business processes should be directed to Microsoft, as clarified in the Microsoft Privacy Statement. <br><br> Microsoft generally aggregates personal before using it for our legitimate business operations and is not in a position to identify personal data for a specific individual in the aggregate. This action significantly reduces the privacy risk to the individual.  Where Microsoft is not in a position to identify the individual, it cannot support data subject rights for access, erasure, portability, or the restriction or objection of processing. <br><br> The [Azure Data Subject Request GDPR Documentation](https://servicetrust.microsoft.com/ViewPage/GDPRDSR) provides a description of how to support data subject rights using the capabilities in Azure. |
| An assessment of the necessity and proportionality of the processing operations in relation to the purposes | Such an assessment will depend on the data controller's needs and purposes of processing.<br><br> Microsoft takes measures such as the anonymization or aggregation of personal data used by Microsoft to support legitimate business operations to support provision of the services, minimizing the risk of such processing to data subjects that use the service. <br><br> With regard to the processing carried out by Microsoft, such processing is necessary and proportional for the purpose of providing the services to the data controller. Microsoft makes this commitment in the OST. |
| An assessment of the risks to the rights and freedoms of data subjects | The key risks to the rights and freedoms of data subjects from the use of Microsoft Azure will be a function of how and in what context the data controller implements, configures, and uses Microsoft Azure.<br><br> However, as with any service, personal data held in the service may be at risk of unauthorized access or inadvertent disclosure. Measures Microsoft takes to address such risks are discussed in the OST, as further detailed later in this article. |
| The measures envisaged to address the risks, including safeguards, security measures, and mechanisms to ensure the protection of personal data and to demonstrate compliance with the GDPR taking into account the rights and legitimate interests of data subjects and other persons concerned | Microsoft is committed to helping protect the security of Customer Data. The security measures Microsoft takes are described in detail in the OST. <br><br> Microsoft complies with strict security standards and industry-leading data protection methodology. Microsoft is continually improving its systems to deal with new threats. More information regarding cloud governance and privacy practices is available at [Trust Center's Cloud Governance & Privacy](https://www.microsoft.com/trustcenter/guidance/ensure-compliance) page. <br><br> Microsoft takes reasonable and appropriate technical and organizational measures to safeguard the personal data that it processes.  These measures include, but are not limited to, internal privacy policies and practices, contractual commitments, and international and regional standard certifications. More information is available at [Trust Center's Privacy Standards page](https://www.microsoft.com/trustcenter/privacy/we-set-and-adhere-to-stringent-standards). <br><br> Microsoft provides significant, transparent customer facing security and privacy materials to help explain Microsoft's use and processing of personal data. Customers are encouraged to contact Microsoft with questions. <br><br> Further, Microsoft complies with all other GDPR obligations that apply to data processors, including but not limited to, data protection impact assessments and record keeping. <br><br> Where Microsoft processes personal data for its legitimate business operations, it complies with GDPR obligations that apply to data controllers. |

## Learn more

- [Microsoft Trust Center](https://www.microsoft.com/trust-center/privacy/gdpr-overview)