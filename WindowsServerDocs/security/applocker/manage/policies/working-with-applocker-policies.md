---
title: Working with AppLocker Policies
description: "Windows Server Security"
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: security-applocker
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: d5d2dede-00f6-43d0-b320-ca2139d6fd41
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# Working with AppLocker Policies

>Applies To: Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

This topic provides links to procedural topics about creating, maintaining, and testing AppLocker policies.

-   [Configure the Application Identity Service](configure-the-application-identity-service.md)

-   [Configure an AppLocker Policy for Audit Only](configure-an-applocker-policy-for-audit-only.md)

-   [Configure an AppLocker Policy for Enforce Rules](configure-an-applocker-policy-for-enforce-rules.md)

-   [Display a Custom URL Message When Users Try to Run a Blocked Application](display-a-custom-url-message-when-users-try-to-run-a-blocked-application.md)

-   [Export an AppLocker Policy from a GPO](export-an-applocker-policy-from-a-gpo.md)

-   [Export an AppLocker Policy to an XML File](export-an-applocker-policy-to-an-xml-file.md)

-   [Import an AppLocker Policy from Another Computer](import-an-applocker-policy-from-another-computer.md)

-   [Import an AppLocker Policy into a GPO](import-an-applocker-policy-into-a-gpo.md)

-   [Add Rules for Packaged Apps to Existing AppLocker Rule-set](add-rules-for-packaged-apps-to-existing-applocker-rule-set.md)

-   [Merge AppLocker Policies by Using Set-applockerPolicy](merge-applocker-policies-by-using-set-applockerpolicy.md)

-   [Merge AppLocker Policies Manually](merge-applocker-policies-manually.md)

-   [Refresh an AppLocker Policy](refresh-an-applocker-policy.md)

-   [Test an AppLocker Policy by Using Test-applockerPolicy](test-an-applocker-policy-by-using-test-applockerpolicy.md)

## What does AppLocker do?
AppLocker helps reduce administrative overhead and helps reduce the organization's cost of managing computing resources by decreasing the number of help desk calls that result from users running unapproved applications. AppLocker addresses the following application security scenarios:

-   Application inventory

    AppLocker has the ability to enforce its policy in an audit-only mode where all application access activity is registered in event logs. These events can be collected for further analysis. Windows PowerShell cmdlets also help you analyze this data programmatically.

-   Protection against unwanted software

    AppLocker has the ability to deny applications from running when you exclude them from the list of allowed applications.  Once AppLocker rules are enforced in the production environment any application that is not covered by the allow rules is blocked from executing.

-   Licensing conformance

    AppLocker can help you create rules that preclude unlicensed software from running and restricting licensed software to authorized users.

-   Software standardization

    AppLocker policies can be configured to allow only supported or approved applications to run on computers within a business group. This permits a more uniform application deployment.

-   Manageability improvement

    AppLocker includes a number of improvements in manageability as compared to its predecessor Software Restriction Policies (SRP). Importing and exporting policies, automatic generation of rules from multiple files, audit-only mode deployment and PowerShell cmdlets are a few of the improvements over SRP.


For information about Software Restriction Policies and AppLocker policies, see [Use AppLocker and Software Restriction Policies in the Same Domain](../use-applocker-and-software-restriction-policies-in-the-same-domain.md).

