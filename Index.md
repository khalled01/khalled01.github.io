---
title: "Welcome"
layout: single
author_profile: true
---

# 👋 Welcome to My Knowledge Hub

I am **Khaled Elsayed**, an IT, Information Security, and Cloud Professional with a strong foundation in:
- **Cybersecurity**: 4 years of hands-on experience with Microsoft Defender Admin Center, Intune, and Sophos Central.  
- **Network & Infrastructure Management**: Over 20 years of experience in designing, implementing, and managing servers, networks, and IT operations.  
- **Cloud Technologies**: Skilled in Microsoft Azure services and security configurations.  
- **Leadership & Administration**: Proven track record in managing IT operations, strategic planning, and transitioning systems to advanced digital maturity.  

---

## 🔐 Cybersecurity & Cloud
I share practical insights on:
- InfoSec & Compliance  
- Endpoint Security (Defender, Intune, Sophos)  
- Cloud Security & Azure AD  

---

## 🌐 Networking & Infrastructure
My background covers:
- Data center and on-premises infrastructure  
- Servers, virtualization, and enterprise IT systems  
- IT governance and policy enforcement  

---

## ⚡ PowerShell Corner
Here’s a simple **PowerShell script** to list connected USB devices using `Get-PnpDevice`:

```powershell
# Show Connected USB Devices
Get-PnpDevice -PresentOnly | Where-Object { $_.InstanceId -match '^USB' } |
Select-Object -Property Name, Status, InstanceId
