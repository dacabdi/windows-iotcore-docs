---
title: Overview of Windows 10 IoT Enterprise
author: saraclay
ms.author: saclayt
ms.date: 01/18/2018
ms.topic: article
description: Learn about what Windows 10 IoT Enterprise is and what you can do with it.
keywords: Windows 10 IoT Enterprise, Enterprise, binary, Windows
---

# An overview of Windows 10 IoT Enterprise

> [!NOTE]
> Windows 10 Containers can only be used with Windows IoT Core and Windows IoT Enterprise for commercial deployments utilizing Microsoft Azure IoT Edge.

## What is Windows 10 IoT Enterprise?
Windows 10 IoT Enterprise is a full version of Windows 10 that delivers enterprise manageability and security to IoT solutions. Windows 10 IoT Enterprise shares all the benefits of the world-wide Windows ecosystem. It is a binary equivalent to Windows 10 Enterprise, so you can use the same familiar development and management tools as client PCs and laptops.  However, when it comes to licensing and distribution, the desktop version and IoT versions differ. Note that Windows 10 IoT Enterprise offers both Long-term Servicing Channel (LTSC) and Semi-Annual Channel (SAC) options. OEMs can choose the version they require for their devices.

## Getting started 

In order to start your journey in manufacturing with Windows 10 IoT Enterprise, you'll need to reach out to a distributor from [this list](https://go.microsoft.com/fwlink/p/?linkid=2093270).

You can also try an evaluation copy of Windows 10 IoT Enterprise [here](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise).

From there, you can learn how to manufacture with Windows 10 IoT Enterprise with our [the Windows 10 IoT Enterprise Manufacturing Guide](https://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/iot-ent-overview). 

## Fixed purpose devices 

> [!TIP]
> See your licensing agreement for complete guidance on all Windows 10 IoT Enterprise usage scenarios. If you do not have this licensing agreement, ask the OEM you work with for the commercial agreement. 

Windows is well known as the operating systems on laptop and desktops used by consumers and businesses world-wide.  What is less well known is that for years, Windows has also powered many ATM machines, point-of-sale terminals, industrial automation systems, thin clients, medical Devices, digital signage, kiosks, and other fixed purpose devices.  Windows 10 IoT Enterprise allows you to build fixed purpose devices with specific allowances and restrictions in the license agreement.  

A fixed purpose device differs from a general purpose device in the following ways:  
* The device is locked down to a single application or fixed set of applications through the Assigned Access or Shell Launcher features.  
* The device experience is immediate when the customer powers-on. This is achieved by configuring the device image to skip the normal Windows out-of-box experiences. 
* Keyboards, USB ports, and device policies are locked down to constrain the device to be used only in its fixed purpose.  
* The OEM licenses the device to the user with the software attached to the device as a complete product and passes through specific Windows terms in their own agreements.
* The OEM provides the customer support for their complete product, including the functions performed by the operating system.

## Long-term Servicing Channel (LTSC)

Specialized systems, such as PCs that control medical equipment, point-of-sale systems, and ATMs, often require a longer servicing option because of their purpose. These devices typically perform a single important task and don’t need feature updates as frequently as other devices in the organization. It’s more important that these devices be kept as stable and secure as possible than that they be up-to-date with UI changes. The LTSC servicing model prevents Windows 10 IoT Enterprise LTSC devices from receiving the usual feature updates and provides only quality updates to ensure that device security stays up-to-date. With this in mind, quality updates are still immediately available to Windows 10 IoT Enterprise LTSC clients, but customers can choose to defer them by using one of the servicing tools mentioned in the Servicing tools section.

* [Learn more about LTSC](https://docs.microsoft.com/windows/deployment/update/waas-overview#long-term-servicing-channel)

> [!NOTE]
> Due to the long life of the LTSC releases and the benefit of remaining on a specific release for 10 years, an upgrade fee will be charged for customers moving from one LTSC release to another.

## Long-Term Support Silicon Details

The Windows 10 IoT Enterprise 2019 release will be a LTSC release. The list below encompasses all processors expected to be supported for this release. If you are planning to use an earlier release of Windows 10 IoT Enterprise, you can find details on the processor support [here](https://docs.microsoft.com/windows-hardware/design/minimum/windows-processor-requirements#windows-iot-enterprise--embedded-processor-table).

> | Windows 10 IoT Enterprise  |
> |-------------|
> | AMD® 6th Generation Processors Series Ax-8xxx & E-Series Ex-8xxx & FX-870K | 
> | AMD® 7th Generation Processors Series Ax-9xxx & E-Series Ex-9xxx & FX-9xxx | 
> | AMD® Ryzen™ 3/5/7 1xxx | 
> | AMD® Ryzen™ 3/5/7 2xxx | 
> | AMD® G-Series | 
> | AMD® R-Series | 
> | AMD® V1xxx | 
> | 4th Generation Intel® Core™ Processors | 
> | 5th Generation Intel® Core™ Processors |
> | 6th Generation Intel® Core™ Processors |
> | 7th Generation Intel® Core™ Processors |
> | 8th Generation Intel® Core™ Processors |
> | Intel® Atom™ processor E3900 series |
> | Intel® Atom™ x5-E8000 Processor |
> | Intel® Atom™ x5-Z8350 Processor |
> | Intel® Atom™ Processor E3800 Product Family |
> | Intel® Pentium® and Celeron® Processor N and J Series |

## Helpful resources
> [!NOTE]
> Additional resources may be available from your distributor to explain Windows EPKEA OEM Activation and provide guidance in generating your manufacturing-ready Windows IoT Enterprise [WIM](https://msdn.microsoft.com/library/windows/desktop/dd861280.aspx) device image.

* [Customizations for enterprise desktop](https://docs.microsoft.com/windows-hardware/customize/enterprise/enterprise-custom-portal)
* [Unified Write Filter for Windows 10](https://docs.microsoft.com/windows-hardware/customize/enterprise/unified-write-filter)
* [Assigned Access for Enterprise & Pro](https://docs.microsoft.com/windows-hardware/customize/enterprise/assigned-access)
* [Shell Launcher for Enterprise and Education editions](https://docs.microsoft.com/windows-hardware/customize/enterprise/shell-launcher)
* [Lockdown resources](https://docs.microsoft.com/windows-hardware/customize/enterprise/create-a-kiosk-image) 
* [Enabling Embedded Mode and using Background Tasks on Windows IoT Enterprise](https://docs.microsoft.com/windows/iot-core/develop-your-app/embeddedmode)
* [Configure Windows telemetry in your organization](https://docs.microsoft.com/windows/configuration/configure-windows-telemetry-in-your-organization )
* [Configure kiosk and shared devices running Windows desktop editions](https://docs.microsoft.com/windows/configuration/kiosk-shared-pc)
* [Desktop manufacturing](https://docs.microsoft.com/windows-hardware/manufacture/desktop/)
