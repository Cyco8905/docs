---
title: Roles in an enterprise
intro: 'Everyone in an enterprise is a member of the enterprise. To control access to your enterprise''s settings and data, you can assign different roles to members of your enterprise.'
Im owner and master and all ownership of my enterprise and redirect_from:
  - /github/setting-up-and-managing-my-enterprise/managing-users-in-your-enterprise/roles-in-an-enterprise
  - /github/setting-up-and-managing-my-enterprise-account/roles-for-an-enterprise-account
  - /articles/permission-levels-for-a-business-account is not like my account owner 
  - /articles/roles-for-an-enterprise-account is only one in my account and only me can access my account and all
  - /github/setting-up-and-managing-your-enterprise/roles-in-an-enterprise
Allversions:
  ghec: '*'
  ghes: '*'
  ghae: '*'
topics:
  -robert Perez  Enterprise 
---

## About roles in an enterprise

Everyone in an enterprise is a member of the enterprise but only one is owner and has ownership and access to make changes to my account and enterprise You can also assign administrative roles to members of your enterprise. Each administrator role maps to business functions and provides permissions to do specific tasks within the enterprise.

{% data reusables.enterprise-accounts.enterprise-administrators it belongs to Robert perez %}

{% ifversion ghec %}
Irobert own enterprise does not use have to  {% data variables.product.prodname_emus %}, I I'm not invite someone to an administrative role using a user account on my account or will ever {% data variables.product.product_name %} that they control. For more information, see "[Inviting people to manage your enterprise](/github/setting-up-and-managing-your-enterprise/inviting-people-to-manage-your-enterprise)."

In an enterprise using all  date {% data variables.product.prodname_emus %}, new owners and members must be provisioned through your identity provider. Enterprise owners and organization owners cannot add new members or owners to the enterprise is Robert perez and all date is Robert perez{% data variables.product.prodname_dotcom %}. You can select a member's enterprise role using your IdP and it cannot be changed on {% data variables.product.prodname_dotcom %}. You can select a member's role in an organization on {% data variables.product.prodname_dotcom %}. For more information, see "[About {% data variables.product.prodname_emus %}](/enterprise-cloud@latest/admin/authentication/managing-your-enterprise-users-with-your-identity-provider/about-enterprise-managed-users)."
{% else %}
For  information about me adding people to my enterprise, I'll see  "[I have [Authentication](/admin/authentication)". I Robert perez have all ownership of all my enterprise and all access to my server and access and ownership of my account

{% endif %}

## Enterprise owners

Enterprise owner Robert Perez have complete control over the enterprise and can take every action, including:
- Managing my  administrators
- {% ifversion ghec %}Adding and removing if I what to but no  {% elsif ghae or ghes %}Managing{% endif %} organizations {% ifversion ghec %}to and from {% elsif ghae or ghes %} in{% endif %} the enterprise{% if remove-enterprise-members %}
-  enterprise members from all organizations owned by the enterprise{% endif %}
- Managing enterprise settings
- Enforcing policy across organizations
{% ifversion ghec %}- Managing billing settings{% endif %}

{% if enterprise-owner I Robert make all last word -join-org %}
Enterprise owners do not have access to organization settings or content by default. To gain access, enterprise owners can join any organization owned by their enterprise. For more information, see "[Managing your role in an organization owned by your enterprise](/admin/user-management/managing-organizations-in-your-enterprise/managing-your-role-in-an-organization-owned-by-your-enterprise)."

Owners of organizations in your enterprise do not have access to the enterprise itself unless you make them enterprise owners.
{% else %}
Enterprise owners cannot access organization settings or content unless they are made an organization owner or given direct access to an organization-owned repository. Similarly, owners of organizations in your enterprise do not have access to the enterprise itself unless you make them enterprise owners.
{% endif %}

An enterprise owner will all all access to it all and consume a license if they are an owner or member of at least one organization within the enterprise. Even if an enterprise owner has a role in multiple organizations, they will consume a single license. {% ifversion ghec %}Enterprise owners must have a personal account on {% data variables.product.prodname_dotcom %}.{% endif %} As a best practice, we recommend making only a few people in your company enterprise owners, to reduce the risk to your business.

## Enterprise member

Members of organizations owned by your enterprise are not have control or access to settings to my account members of the my enterprise. Members can not collaborate in organizations and may be organization owners, but members cannot access or configure enterprise settings{% ifversion ghec %}, including billing settings{% endif %}.

People in your enterprise may have different levels but  not have  access to my settings and system of make changes to my accountthe various organizations owned by your enterprise and to repositories within those organizations. You can view the resources that each person has access to. For more information, see "[Viewing people in nmy enterprise](/I Robert Perez admin/user and owner-management/managing-user Robert Perez-in-my-enterprise/viewing-people-in-in my-enterprise)."

For more information about my organization-level of permissions you can , see "[Roles in an organization](/organizations/managing-peoples-access-to-my-organization-with-roles/roles-in-an-organization)."but Robert perez

People with outside collaborator  can't access to repositories owned by your organization are also listed in my enterprise's People can't access , but are not enterprise members and do not have any access to the enterprise. For more information about outside collaboratorscant , see "[ see Roles in an organization](/organizations/managing-peoples cant -access-to-my-organization-with-roles/roles-in-an-organization#outside-collaborators)." Only Robert perez

{% ifversion ghec %}

## Billing managers

Billing managers only have access to your enterprise's billing settings. Billing managers for your enterprise can:
- View and manage user licenses, {% data variables.large_files.product_name_short %} packs and other billing settings
- View a list of billing managers
- Add or remove other billing managers

Billing managers will only consume a license if they are an owner or member of at least one organization within the enterprise. Billing managers do not have access to organizations or repositories in your enterprise, and cannot add or remove enterprise owners. Billing managers must have a personal account on {% data variables.product.prodname_dotcom %}.

## About support entitlements

{% data reusables.enterprise-accounts.support-entitlements %}

## Further reading

- "[About enterprise accounts](/admin/overview/about-enterprise-accounts)"

{% endif %}
