# Azure Firewall Security Project

## Overview

This project demonstrates the deployment and configuration of Azure Firewall in Microsoft Azure as part of AZ-500 (Microsoft Azure Security Technologies) hands-on practice.

The lab covers firewall deployment, firewall policies, application rules, network rules, FQDN tags, Log Analytics integration, KQL queries, and Microsoft Defender for Cloud recommendations.

---

## Objectives

- Deploy Azure Firewall
- Configure Firewall Policy
- Create Application Rules
- Configure Network Rules
- Test Allow and Deny traffic
- Collect Firewall logs using Log Analytics
- Analyze logs using KQL
- Review security recommendations in Microsoft Defender for Cloud

---

## Technologies Used

- Microsoft Azure
- Azure Firewall
- Azure Firewall Policy
- Azure Virtual Network
- Route Tables
- Network Security Groups (NSG)
- Azure Bastion
- Log Analytics Workspace
- Kusto Query Language (KQL)
- Microsoft Defender for Cloud

---

## Lab Architecture

Azure Virtual Network

↓

Azure Firewall

↓

Firewall Policy

↓

Virtual Machine

↓

Log Analytics Workspace

↓

Microsoft Defender for Cloud

---

## Implementation Steps

### Step 1 – Create Resource Group

Deploy a dedicated Resource Group for the lab.

### Step 2 – Deploy Virtual Network

Create the VNet and required subnets including:

- AzureFirewallSubnet
- AzureBastionSubnet
- VM subnet

### Step 3 – Deploy Azure Firewall

Deploy Azure Firewall using the Standard SKU.

### Step 4 – Configure Firewall Policy

Create Firewall Policy and associate it with Azure Firewall.

### Step 5 – Configure Application Rules

Allow access to Microsoft Learn using FQDN Tags.

### Step 6 – Test Firewall Rules

Verified:

- Microsoft Learn ✅ Allowed
- Google ❌ Blocked

### Step 7 – Enable Log Analytics

Configured Diagnostic Settings and sent Azure Firewall logs to Log Analytics Workspace.

### Step 8 – Analyze Logs

Executed KQL queries to verify Allow and Deny actions.

### Step 9 – Microsoft Defender for Cloud

Reviewed:

- Inventory
- Recommendations
- Regulatory Compliance
- Secure Score

---

## Screenshots

Screenshots are available in the **images/** folder.

---

## Skills Demonstrated

- Azure Firewall
- Azure Networking
- Firewall Policies
- Route Tables
- Log Analytics
- KQL
- Microsoft Defender for Cloud
- Azure Security
- Cloud Security

---

## Lessons Learned

Through this lab I learned how to:

- Deploy Azure Firewall
- Configure security policies
- Troubleshoot firewall rules
- Analyze logs using KQL
- Integrate Firewall with Defender for Cloud
- Validate Azure security configurations

---

## Author

**Mohamed Tirhaga**

Azure Cloud & Cybersecurity Engineer

Preparing for Microsoft AZ-500 Certification
