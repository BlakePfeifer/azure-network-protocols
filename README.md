<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Creating Resource Groups</h1>

<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Portal
- Azure Resource Manager(ARM)
- Web Browser
- Windows 11

<h2>Operating Systems Used </h2>

- Windows 11 (23H2)

<h2>High-Level Steps</h2>


# How to Create a Resource Group on Microsoft Azure

## Introduction
In this tutorial, we will walk through how to create a resource group in Microsoft Azure and why they are necessary.

A **Resource Group** in Azure is a container that holds related resources for an Azure solution. It helps organize and manage services like virtual machines, databases, and storage accounts under a single group for easier monitoring, security, and billing.

---

## Prerequisites
- A Microsoft account (free to create if you don't have one).
- An Azure subscription (you can start with the **Azure Free Account** which gives you free credits).
- Access to the Azure portal: [https://portal.azure.com](https://portal.azure.com)

---

## Steps to Create a Resource Group

### 1. Sign in to the Azure Portal
- Open [https://portal.azure.com](https://portal.azure.com).
- Log in with your Microsoft account credentials.




---

### 2. Navigate to Resource Groups
- Once signed in, on the left-hand side menu, click **"Resource groups"**.
- Or, you can search for **"Resource groups"** in the search bar at the top.

![image](https://github.com/user-attachments/assets/c48174e9-7fef-482a-9a81-89ec6d139bc8)


---

### 3. Start Creating a New Resource Group
- Click on the **"+ Create"** button at the top.

<!-- IMAGE: Insert screenshot of clicking "+ Create" -->

---

### 4. Fill in Resource Group Details
- **Subscription**: Choose your available subscription.
- **Resource Group Name**: Enter a meaningful name (example: `MyFirstResourceGroup`).
- **Region**: Select a region closest to where your resources will be hosted (example: `East US`).

<!-- IMAGE: Insert screenshot of the "Create Resource Group" form -->

---

### 5. Review and Create
- After filling out the details, click **"Review + Create"** at the bottom.
- Confirm your details are correct.
- Then click **"Create"** to finish creating the resource group.

<!-- IMAGE: Insert screenshot of the "Review + Create" screen -->

---

### 6. View Your Resource Group
- Once created, you can view your new Resource Group under the **Resource groups** section.
- Click on it to see its overview and manage resources inside it.

<!-- IMAGE: Insert screenshot of the created Resource Group Overview -->

---

## Summary
In this tutorial, you successfully created a Resource Group by:
- Navigating to the Resource Groups section.
- Filling in basic setup details like name, subscription, and region.
- Launching a new Resource Group to organize your Azure resources.

---

## Common Mistakes and Tips

Here are a few important things to watch out for when creating a Resource Group:

- ✅ **Choose the Correct Region**: Always pick a region close to your users or business needs to reduce latency.
- ✅ **Use Clear Naming Conventions**: Use easy-to-understand names (like `WebApp-Resources`) so you can manage them better later.
- ✅ **Remember Resource Group Ownership**: Everything you deploy into a resource group inherits its subscription and region settings.
- ✅ **Deleting a Resource Group Deletes Everything Inside**: If you delete a resource group, **every resource** inside it (VMs, databases, storage accounts) will also be deleted — use caution!
- ✅ **Plan Resource Group Organization Ahead**: Organizing similar services together makes managing permissions, costs, and security much easier.

> **Important Reminder**:  
> A well-organized Azure environment starts with proper Resource Groups. Think of them like folders — once you have a lot of services, good organization saves you time and money!

---
