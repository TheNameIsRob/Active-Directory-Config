# Active-Directory-Config
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Install Active Directory
- Create a Domain Admin user within the domain
- Join Client-1 to domain
- Set up remote desktop for non-administrative users on Client-1
- Create additional users and attempt to log into Client-1 with users created.

<h2>Deployment and Configuration Steps</h2>

<h3>Step 1: Install Active Directory</h3>
<h4>Use Remote Desktop Connection to log onto our DC-1 (Domain controller) virtual machine</h4>
<img src="https://i.imgur.com/3UfuPtN.png">

<h4>Open service manager and click "Add roles and features"</h4>
<img src="https://i.imgur.com/hMf3kDJ.png">

<h4>Click Server Roles</h4>
<img src="https://i.imgur.com/G4zKViV.png">

<h4>In the column of different roles identify "Active Directory Domain Services" and clock on it.Also click "features" when the new tab opens.</h4>
<img src="https://i.imgur.com/OPsN30T.png">

<h4>Click "Confirmation" and "Install. Observe the installation and wait until it is complete.</h4>
<img src="https://i.imgur.com/ydIwo5B.png">
<img src="https://i.imgur.com/TQGPHpP.png">

Step 2:
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
