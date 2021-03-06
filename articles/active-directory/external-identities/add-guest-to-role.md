---

title: Add a B2B collaboration user to a role - Azure Active Directory
description: Add a guest user to a role in Azure Active Directory

services: active-directory
ms.service: active-directory
ms.subservice: B2B
ms.topic: how-to
ms.date: 05/08/2018

ms.author: mimart
author: msmimart
manager: celestedg
ms.reviewer: mal
ms.custom: "it-pro, seo-update-azuread-jan"                 
ms.collection: M365-identity-device-management
---

# Grant permissions to users from partner organizations in your Azure Active Directory tenant

Azure Active Directory (Azure AD) B2B collaboration users are added as guest users to the directory, and guest permissions in the directory are restricted by default. Your business may need some guest users to fill higher-privilege roles in your organization. To support defining higher-privilege roles, guest users can be added to any roles you desire, based on your organization's needs.

If a directory role is assigned to a guest user, the guest user will be granted with additional permissions that come with the role, including basic read permissions. See [Azure AD built-in roles](../roles/permissions-reference.md).

## Default role

![Screenshot showing the default directory role](./media/add-guest-to-role/default-role.png)

## Global Administrator Role

![Screenshot showing the global administrator role](./media/add-guest-to-role/global-admin-role.png)

## Limited Administrator Role

![Screenshot showing the limited administrator role](./media/add-guest-to-role/limited-admin-role.png)

## Next steps

- [What is Azure AD B2B collaboration?](what-is-b2b.md)
- [B2B collaboration user properties](user-properties.md)