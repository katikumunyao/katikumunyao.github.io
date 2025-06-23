---
layout: single
title: "Lab Challenges"
permalink: /lab-challenges/
---

## 🟢 Azure Lab: Network Security Basics (NSG Configuration)

**🧩 Problem:**  
Control and secure inbound/outbound traffic to Azure VMs using Network Security Groups (NSGs).

**🛠️ Tools:**  
Azure Portal, Virtual Machines, Network Security Groups

**🔍 Approach:**  
- Identified an existing Windows VM for NSG implementation.  
- Created and configured an NSG, associating it with the VM’s network interface.  
- Added an inbound rule to allow RDP access from a trusted source.  
- Verified outbound connectivity with default NSG rules.

**🎯 Lessons:**  
NSGs provide basic yet crucial traffic control, helping protect VMs at network level by limiting which ports and sources are accessible.

---

## 🟡 Azure Lab: Managing User Identities (Entra ID)

**🧩 Problem:**  
Manage user identities, licenses, and access permissions in Microsoft Entra ID and Microsoft 365.

**🛠️ Tools:**  
Microsoft Entra ID, Microsoft 365 Admin Center, Defender, Authenticator

**🔍 Approach:**  
- Enabled 365 audit logs to monitor user activities.  
- Created a new user and assigned a Power Apps Developer license.  
- Logged in as the user and configured MFA.  
- Explored group memberships and security roles.

**🎯 Lessons:**  
Entra ID is central to identity and access management. Auditing and MFA are key for securing cloud accounts.

---

## 🟠 Azure Lab: Serverless Containers (Container Apps)

**🧩 Problem:**  
Deploy and manage containerized apps in a serverless Azure environment with minimal infrastructure.

**🛠️ Tools:**  
Azure Container Apps (ACA), Azure portal, Container Images

**🔍 Approach:**  
- Created a Container App and environment in Azure Portal.  
- Deployed a "Hello World" container image without manual server setup.  
- Tested the app via its public DNS endpoint on port 80.

**🎯 Lessons:**  
Azure Container Apps simplify container deployment via serverless, autoscaling services that manage infrastructure behind the scenes.

---

## 🔵 Azure Lab: VM Provisioning & Scaling

**🧩 Problem:**  
Build a scalable and resilient VM infrastructure in Azure for variable workloads.

**🛠️ Tools:**  
Azure VMs, VM Scale Sets, PowerShell, CLI, Availability Zones, Data Disks

**🔍 Approach:**  
- Deployed zone-resilient VMs across multiple availability zones.  
- Resized VMs (vertical scaling) and managed data disk tiers.  
- Created a VMSS across three zones with networking and load balancing.  
- Set up auto-scaling based on CPU thresholds.  
- Automated tasks via CLI/PowerShell.

**🎯 Lessons:**  
Combining vertical and horizontal scaling with automation ensures resource optimization, cost control, and high availability.

---

## 🔵 Azure Lab: Traffic Routing & Load Management

**🧩 Problem:**  
Efficiently distribute and manage incoming application traffic across Azure VMs.

**🛠️ Tools:**  
Azure Load Balancer, Application Gateway, ARM Templates, Virtual Networks, NSGs

**🔍 Approach:**  
- Used an ARM template to deploy the environment (VNet, NSG, 3 VMs).  
- Configured a Layer 4 Load Balancer to distribute HTTP traffic.  
- Configured an Application Gateway (Layer 7) with URL-based routing, SSL offload, and WAF.  
- Checked backend server health and traffic distribution.

**🎯 Lessons:**  
Layer 4 load balancing ensures availability, while Application Gateway adds application-layer routing features and security. ARM templates ease consistent provisioning.  


---

## ⚫️ Azure Lab: Advanced Traffic for Containers (Container Apps + Front Door)

**🧩 Problem:**  
Deploy containerized services globally with intelligent routing and autoscaling.

**🛠️ Tools:**  
Azure Container Apps, Azure Front Door (or Application Gateway), ACA autoscaling

**🔍 Approach:**  
- Started with a Container App deployment.  
- Introduced Azure Front Door to route global HTTP(S) traffic.  
- Integrated autoscaling by linking ACA with Front Door metrics.  
- Secured endpoints with WAF and SSL termination.  
- Monitored performance using Azure Monitor and Log Analytics.

**🎯 Lessons:**  
Front Door provides global, Layer 7 traffic management and security expansion over Gateway. Combining it with ACA autoscaling supports worldwide resilience and scalable container workflows. 
