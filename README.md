# Active Directory Cloud Configuration: Users, Roles and Permissions

<div align="center">

![Azure AD Logo](https://imgur.com/Bffj9rl.jpg)

</div>

## Introduction

This project will cover the configuration process of new user creation, subscription-level role assignment and resource group permissions in Azure using Microsoft Entra ID (formally Azure Active Directory). 

### Azure components needed to complete project:

- Microsoft Entra ID
- Resource Groups
- Subscriptions

## New User Configuration
New user, globalreaderjohn has been created and assigned the tenet-level/directory role of 'Global Reader' as represented in the below images.

![New User Creation](https://imgur.com/EawR6ZZ.jpg)

![Assign New User Role](https://imgur.com/bwcfRgR.jpg)

![Confirmation of role assignment](https://imgur.com/P4Vq3by.jpg) 

### New User Configuration Check
As observed in the below image, globalreaderjohn's assigned role has been successfully implemented as the user is unable to make password changes for other users. 

![Confirmation of successful assignment](https://imgur.com/nS3aBhr.jpg)

## Assigning Subscription-level Role
In this section of the project, subreaderjane was assigned a subscription-level role as a reader. 

![Assign reader role](https://imgur.com/5MJFYFD.jpg)

![Assign reader role2](https://imgur.com/yLUGAwC.jpg)

![Assign reader role4](https://imgur.com/9v2fzhz.jpg) 

### Subscription-level Role Assignment Check
As shown below while signed in under subreaderjane's account, the assigned role has been successfully implemented as marked under the "My role" column. 

![Confirmation of role assignment](https://imgur.com/xN3HJYg.jpg) 

## Assigning Resource Group-level Contributor Permissions

Resource group 'Permissions Tester' has been created in this section. In Access Control (IAM), found within the Subscription component, we are able to add the Privileged administrator role of a Contributor to user rgcontributordave.

![resource group](https://imgur.com/bmeCnpu.jpg)

![assigning group](https://imgur.com/UlLmIKY.jpg)

![assigning group2](https://imgur.com/GGjFTTL.jpg)

### Resource Group-level Contributor Permissions Assignment Check

The below two images are references to indicate the Resource Group-level Contributor role was correctly configured. The top image reflects all resource groups under the admin account. The second image documents the only one resource group, Permissions Tester, that was assigned to rgcontributordave. 

![confirm correct rg assignment](https://imgur.com/GGjFTTL.jpg) 

![confirm correct rg assignment2](https://imgur.com/m4WXSqs.jpg) 


## fin
