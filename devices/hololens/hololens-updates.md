---
title: Manage updates to HoloLens (HoloLens)
description: Administrators can use mobile device management to manage updates to HoloLens devices.
ms.prod: hololens
ms.sitesec: library
author: jdeckerms
ms.author: jdecker
ms.topic: article
ms.localizationpriority: medium
ms.date: 04/30/2018
---

# Manage updates to HoloLens 2

>**Looking for how to get the latest update? See [Update HoloLens](https://support.microsoft.com/help/12643/hololens-update-hololens).**

For a complete list of Update policies, see [Policies supported by Windows Holographic for Business](https://docs.microsoft.com/windows/client-management/mdm/policy-configuration-service-provider#a-href-idhololenspoliciesapolicies-supported-by-hololens-2).

To configure how and when updates are applied, use the following policies:

-	[Update/AllowAutoUpdate](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-allowautoupdate)
-	[Update/DeferFeatureUpdates](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-scheduledinstallday)
-	[Update/DeferQualityUpdates](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#PauseQualityUpdates)
-	[Update/PauseFeatureUpdates](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-scheduledinstallday)
-	[Update/PauseQualityUpdates](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#PauseQualityUpdates)
-	[Update/ScheduledInstallDay](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-scheduledinstallday)
-	[Update/ScheduledInstallTime](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-scheduledinstalltime)

In Microsoft Intune, you can use **Automatic Update Behavior** to change this policy. (See [Manage software updates in Microsoft Intune](https://docs.microsoft.com/intune/windows-update-for-business-configure))

For information on how to defer/pause updates, see [Deploy updates using Windows Update for Business](https://docs.microsoft.com/en-us/windows/deployment/update/waas-manage-updates-wufb)

# Manage Updates to HoloLens (Windows Holographic for Business)


For a complete list of Update policies, see [Policies supported by Windows Holographic for Business](https://docs.microsoft.com/windows/client-management/mdm/policy-configuration-service-provider#a-href-idhololenspoliciesapolicies-supported-by-hololens).

>[!NOTE]
>HoloLens devices must be [upgraded to Windows Holographic for Business](hololens-upgrade-enterprise.md) to manage updates.

To configure how and when updates are applied, use the following policies:

-	[Update/AllowAutoUpdate](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-allowautoupdate)
-	[Update/ScheduledInstallDay](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-scheduledinstallday)
-	[Update/ScheduledInstallTime](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-scheduledinstalltime)

To turn off the automatic check for updates, set the following policy to value 5 – Turn off Automatic Updates:

-	[Update/AllowAutoUpdate](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-allowautoupdate)

In Microsoft Intune, you can use **Automatic Update Behavior** to change this policy. (See [Manage software updates in Microsoft Intune](https://docs.microsoft.com/intune/windows-update-for-business-configure))

For devices on Windows 10, version 1607 only: You can use the following update policies to configure devices to get updates from Windows Server Update Service (WSUS) instead of Windows Update:

- [Update/AllowUpdateService](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-allowupdateservice) 
- [Update/RequireUpdateApproval](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-requireupdateapproval) 
- [Update/UpdateServiceUrl](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-update#update-updateserviceurl)

## Related topics

- [Policies supported by HoloLens 2](https://docs.microsoft.com/en-us/windows/client-management/mdm/policy-configuration-service-provider#policies-supported-by-hololens-2)
- [Policies supported by Windows Holographic for Business](https://docs.microsoft.com/windows/client-management/mdm/policy-configuration-service-provider#a-href-idhololenspoliciesapolicies-supported-by-windows-holographic-for-business)
- [Manage software updates in Microsoft Intune](https://docs.microsoft.com/intune/windows-update-for-business-configure)
