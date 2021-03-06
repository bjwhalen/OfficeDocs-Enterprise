---
title: "Office 365 Yammer Enterprise Access Controls"
ms.author: robmazz
author: robmazz
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: O365-seccomp
localization_priority: Normal
search.appverid:
- MET150
ms.collection:
- Strat_O365_IP
- M365-security-compliance
f1.keywords:
- NOCSH
description: "Summary: A brief summary about Yammer Enterprise Access Controls in the production environment."
---

# Yammer Enterprise Access Controls 

Physical and logical access to the Yammer production environment is restricted to a small set of people (infrastructure and operations). As with other Office 365 engineers, Yammer engineers have zero standing access to Customer Data. Access must be requested using an approval-based just-in-time access control system similar to Lockbox with a limited number of approvers. Approvers verify the request (for example, they verify whether the request is legitimate based on need, business case, time, etc.), and then approve or deny the request. If the request is approved, JIT access is granted for a defined and limited time. After access time is exceeded, the access automatically expires.

As with other Office 365 services, all access to the Yammer production environment uses multi-factor authentication. All access and command history is attributed to a user, and logged and reviewed regularly by the Yammer security team.

For more information about Yammer administration and management, see [Yammer Admin Help](https://support.office.com/article/yammer-–-admin-help-e1464355-1f97-49ac-b2aa-dd320b179dbe?ui=en-US&rs=en-US&ad=US).