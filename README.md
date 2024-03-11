# HOMELAB--RUNNING-ACTIVE-DIRECTORY
Home Lab Running Active Directory (Oracle VirtualBox) | Add Users w/PowerShell
<h1></h1>

 ### Description of Project

<h2>NIC Networking instructions</h2>

![Instructions for IP](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/92b787cc-aadd-432f-9c9c-389f9f8e532a)






<h2> My Static IP config for my internal NIC, Internet NIC works as a DHCP and did not need to be touched</h2>

![Network settings for NICs](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/b34287d7-4f70-43ef-bfbb-2447e4fb8515)



Server Manager Installs and configurations 
1. DHCP
2. RAS/NAT
3. DNS

![Server Managers installs](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/e41e6691-7f5d-4944-b11a-67747d455b4f)



These are my two VM's I created using Oracle Virtual BOX

![Sever and client](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/d0137388-a60a-4a22-99b2-955e6c61783f)



- <b>Powershell:</b> Script Ran in Powershell to populate 10000 users.

![PowerShell Script to Generate Users for AD](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/1c8839a9-7035-4337-b92c-cc862c4a9045)

![My AD USERS](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/b398728c-db7f-4419-bd35-6b656984184e)

  

<h2>IP configurations on Windows 10 after creating VM VM</h2> 

![IPCONFIG ON WINDOWS 10 VM](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/3b1f0289-74a2-4402-b904-83d007bb66b4)




Domain join and PC name change on Windows 10 Client to finish the Project.

![image](https://github.com/Dmoore125/HOMELAB--RUNNING-ACTIVE-DIRECTORY-/assets/162640561/dc98f61f-17cf-45ad-84fe-0f87e2ce337f)


</p>

 ### Steps of Project
1. Start Windows Server 2019 VM up and running on Oracle VirtualBox;
2. Set up domain controller, network adapters, assign appropiate IP address, install Active Directory Domain Services, promote server to a domain controller, and finally set up a domain admin account.
3. Install and configure the RAS and NAT.
4. Install and configure DHCP scope.
5. Use costum Powershell script to create 1,000 users for our domain.
6. Create a Windows 10 client VM, rename it and join to Mydomain.com
7. Verify you are on domain by signing into it with user accounts.




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
