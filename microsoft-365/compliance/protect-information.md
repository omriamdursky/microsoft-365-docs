---
title: "Protect information using Microsoft 365"
f1.keywords:
- NOCSH
ms.author: cabailey
author: cabailey
manager: laurawi
ms.date: 
audience: Admin
ms.topic: hub-page
ms.service: O365-seccomp
localization_priority: Normal
search.appverid: 
- MOE150
- MET150
ms.assetid: a6ef28a4-2447-4b43-aae2-f5af6d53c68e
description: "Identify the Microsoft 365 capabilities and supporting documentation to help you protect your organization's important data."
---

# Protect information using Microsoft 365

>*[Licensing for Microsoft 365 Security & Compliance](https://docs.microsoft.com/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance)*

Use Microsoft Information Protection capabilities to help discover, classify, and protect sensitive information wherever it lives or travels.

## Know your data

To understand your data landscape and identify important data across your hybrid environment, use the following capabilities:
 
|Capability|What problems does it solve?|Get started|
|:------|:------------|:--------------------|:-----------------------------|
|[Sensitive information types](sensitive-information-type-entity-definitions.md)| Identifies sensitive data by using built-in or custom regular expressions or a function, together with corroborative evidence that includes keywords, confidence levels, and proximity.| [Customize a built-in sensitive information type](customize-a-built-in-sensitive-information-type.md)|
|[Trainable classifiers (preview)](classifier-getting-started-with.md)| Classifies data for you, using one of the built-in classifiers or train a classier with your own content | [Create a trainable classifier (preview)](classifier-creating-a-trainable-classifier.md) |
|[Data classification](data-classification-overview.md) | Identifies items that have a sensitivity label, a retention label, or have been classified as a sensitive information type in your organization and the actions that your users are taking on them  | [Get started with content explorer](data-classification-content-explorer.md)<br /><br /> [Get started with activity explorer](data-classification-activity-explorer.md) |

## Protect your data

To apply flexible protection actions that include encryption, access restrictions, and visual markings, use the following capabilities:

|Capability|What problems does it solve?|Get started|
|:------|:------------|---------------------|:----------------------------|
|[Sensitivity labels](sensitivity-labels.md)| A single solution across apps, services, and devices to label and protect your data as it travels inside and outside your organization <br /><br />Example scenario: [Apply and view sensitivity labels in Power BI, and protect data when it is exported](https://docs.microsoft.com/power-bi/admin/service-security-data-protection-overview)|[ Get started with sensitivity labels](get-started-with-sensitivity-labels.md) |
|[Azure Information Protection unified labeling client](https://docs.microsoft.com/azure/information-protection/rms-client/aip-clientv2)| For Windows computers, extends sensitivity labels for additional features and functionality that includes labeling and protecting all file types from File Explorer and PowerShell<br /><br /> Example additional features: [Custom configurations for the Azure Information Protection unified labeling client](https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-customizations)| [Azure Information Protection unified labeling client administrator guide](https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide)|
|[Double Key Encryption](double-key-encryption.md)| Under all circumstances, only you can ever decrypt protected content, or for regulatory requirements you must hold encryption keys within a geographical boundary | [Deploy Double Key Encryption](double-key-encryption.md#deploy-double-key-encryption)|
|[Office 365 Message Encryption](ome.md) (OME)| Encrypts email messages and attached documents that are sent to any user on any device, so only authorized recipients can read emailed information  <br /><br />Example scenario: [Revoke email encrypted by Advanced Message Encryption](revoke-ome-encrypted-mail.md) | [Get started with Office 365 Message Encryption](set-up-new-message-encryption-capabilities.md)|
|[Service encryption with Customer Key](customer-key-overview.md) | Protects against viewing of data by unauthorized systems or personnel, and complements BitLocker disk encryption in Microsoft datacenters | [Set up Customer Key for Office 365](customer-key-set-up.md)|
|[SharePoint Information Rights Management (IRM)](set-up-irm-in-sp-admin-center.md#irm-enable-sharepoint-document-libraries-and-lists)|Protects SharePoint lists and libraries so that when a user checks out a document, the downloaded file is protected so that only authorized people can view and use the file according to policies that you specify | [Set up Information Rights Management (IRM) in SharePoint admin center](set-up-irm-in-sp-admin-center.md)|
[Rights Management connector](https://docs.microsoft.com/azure/information-protection/deploy-rms-connector) |Protection-only for existing on-premises deployments that use Exchange or SharePoint Server, or file servers that run Windows Server and File Classification Infrastructure (FCI) | [Steps to deploy the RMS connector](https://docs.microsoft.com/azure/information-protection/deploy-rms-connector#steps-to-deploy-the-rms-connector)
|[Azure Information Protection unified labeling scanner](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner)| Discovers, labels, and protects sensitive information that resides in data stores that are on premises | [Configuring and installing the Azure Information Protection unified labeling scanner](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-configure-install)|
|[Microsoft Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)| Discovers, labels, and protects sensitive information that resides in data stores that are in the cloud | [Discover, classify, label, and protect regulated and sensitive data stored in the cloud](https://docs.microsoft.com/cloud-app-security/best-practices#discover-classify-label-and-protect-regulated-and-sensitive-data-stored-in-the-cloud)|
|[Microsoft Information Protection SDK](https://docs.microsoft.com/information-protection/develop/overview#microsoft-information-protection-sdk)|Extends sensitivity labels to third-party apps and services  <br /><br /> Example scenario: [Set and get a sensitivity label (C++)](https://docs.microsoft.com/information-protection/develop/quick-file-set-get-label-cpp) |[Microsoft Information Protection (MIP) SDK setup and configuration](https://docs.microsoft.com/information-protection/develop/setup-configure-mip)|

## Prevent data loss

To help prevent accidental oversharing of sensitive information, use the following capabilities:


|Capability|What problems does it solve?|Get started|
|:------|:------------|:---------------------|:-----------------------------|
|[Data loss prevention](data-loss-prevention-policies.md) (DLP)| Helps prevent unintentional sharing of sensitive items <br /><br />Example scenario: [Protect sensitive information in Microsoft Teams chat and channel messages](dlp-microsoft-teams.md) | [Get started with the default DLP policy](get-started-with-the-default-dlp-policy.md)|
|[Endpoint data loss prevention (preview)](endpoint-dlp-learn-about.md)| Extends DLP capabilities to items that are used and shared on Windows 10 computers | [Get started with Endpoint data loss prevention (preview)](endpoint-dlp-getting-started.md)|
