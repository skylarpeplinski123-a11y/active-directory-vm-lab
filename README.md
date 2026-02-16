# Active Directory Setup on Windows Server 

## 🎥 Video Walkthrough
Watch the full demo here:  
👉 https://www.loom.com/share/3fec8c01effb438f8dd104ddaee4c3b4

---

## Overview
This project demonstrates how to install and configure Active Directory Domain Services (AD DS) on a Windows Server machine and promote it to a Domain Controller.  

This lab is designed to be simple and beginner-friendly.

---

## Key Skills Demonstrated
- Active Directory installation
- Windows Server administration
- Domain Controller promotion

---

## Tools / Environment
- Windows Server 2019 or 2022
- Virtual Machine (AWS EC2)
- Remote Desktop (RDP)

---

## What I Built
- Installed Active Directory Domain Services
- Promoted Windows Server to Domain Controller
- Created a new domain

---

## Simplest Possible Setup Steps

### Step 1 — Open Server Manager
1. Log into Windows Server
2. Open **Server Manager**
3. Click **Add Roles and Features**

---

### Step 2 — Install Active Directory
1. Click **Next** until you reach **Server Roles**

3. Click **Add Features**
4. Click **Next → Install**
5. Wait for installation to complete

---

### Step 3 — Promote to Domain Controller
After installation:

1. Click the notification flag (top right)
2. Click: promote this server to a domain controller

---

### Step 4 — Create new Forest

1. Creat new root domain name
2. make sure whatever it is called is followed by .local
3. Create a directory services restore mode password (type it twice make sure it matches)
4. Next
5. Once the new root domain name shows press next until it asks you to install

### Step 5 —  Install

1. press install and when done it will prompt you to restart and you'll have a provisioned virtual machine for active directory




