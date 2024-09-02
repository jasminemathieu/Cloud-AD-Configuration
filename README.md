# Active Directory Cloud Configuration: Users, Roles and Permissions

![AD Img](https://imgur.com/L7SW4zJ.jpg)

## Introduction

This project covers the configuration process for creating new users, assigning subscription-level roles, and managing resource group permissions in Azure using Microsoft Entra ID (formerly known as Azure Active Directory). We’ll walk through each step with detailed explanations and screenshots. 

### Azure components needed to complete project:

- Microsoft Entra ID
- Resource Groups
- Subscriptions

## New User Configuration

### 1. New User Creation

We’ve created a new user named 'globalreaderjohn'. Here’s how we did it:

![New User Creation](https://imgur.com/BWBgnFh.jpg)

### 2. Assigning Role to New User

We assigned the Global Reader role to 'globalreaderjohn'. This role allows read-only access to all resources within the Azure tenant. The confirmation screenshot shows that the role assignment was successful:

![Assign New User Role](https://imgur.com/bwcfRgR.jpg)

![Confirmation of role assignment](https://imgur.com/P4Vq3by.jpg) 

### 3. New User Configuration Check

We verified that 'globalreaderjohn' cannot make password changes for other users, ensuring the role assignment is effective.

![Confirmation of successful assignment](https://imgur.com/wttd9SX.jpg)

## Assigning Subscription-level Role
Next, we assigned the Reader role to another user, 'subreaderjane'. This role provides read-only access to resources within a specific subscription.

![Assign reader role](https://imgur.com/TMtUUDY.jpg)

![Assign reader role2](https://imgur.com/vpErpF0.jpg)

![Assign reader role4](https://imgur.com/K92QVDH.jpg) 

### Subscription-level Role Assignment Check
As shown below while signed in under the 'subreaderjane' account, the assigned role has been successfully implemented as marked under the "My role" column. 

![Confirmation of role assignment](https://imgur.com/HEOm3pR.jpg) 

## Resource Group Permissions

### 1. Creating a Resource Group

We created a resource group named Permissions Tester.

![resource group](https://imgur.com/jJu2Uwa.jpg)

### 2. Assigning Contributor Permissions

We assigned the Contributor role to user 'rgcontributordave' at the resource group level in Access Control (IAM) component. This role allows managing resources within the specified resource group.

![assigning group](https://imgur.com/UlLmIKY.jpg)

![assigning group2](https://imgur.com/GGjFTTL.jpg)

## Resource Group-level Contributor Permissions Assignment Check

We confirmed that the role assignment for 'rgcontributordave' was successful by checking the “My role” column under their account.

![confirm correct rg assignment](https://imgur.com/GGjFTTL.jpg) 

![confirm correct rg assignment2](https://imgur.com/SmpD5zE.jpg) 


## Conclusion

In this Azure configuration project, we successfully accomplished the following tasks:

New User Configuration:
- Created a new user named globalreaderjohn.
- Assigned the Global Reader role to globalreaderjohn, granting read-only access to all Azure resources.
- Verified that globalreaderjohn cannot make password changes for other users.

Subscription-level Role Assignment:
- Assigned the Reader role to subreaderjane, providing read-only access to resources within a specific subscription.

Resource Group Permissions:
- Created a resource group named Permissions Tester.
- Assigned the Contributor role to rgcontributordave at the resource group level, allowing resource management within the specified group.

By following these steps, we’ve established secure access controls and permissions for users across different levels in Azure. We are also able to regularly review and update permissions as needed to maintain security and compliance.

## fin
