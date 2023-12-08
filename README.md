# Configure-AD

<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>
<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation as well as the use of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Azure Virtual machines Configuration
- Step 2: Editing Ip configuration from dynamic to static
- Step 3: Connecting the Ip address of DC1 and Client 1 via SSH Using RDP
- Step 4: Installing Active Directory
- Step 4: DC-1 Outline
- Step 5: Server Manager and Active Directory Configuration
- Step 6: Test of Connection between Virtual Machines

<h2>Deployment and Configuration Steps</h2>

Azure Virtual Machines Configuraton.
![image](https://github.com/Gpassed/Configure-AD/assets/129806612/c4783bdf-3dfb-449c-8a4a-159579e97538)


Editing the Ip configuration from dynamic to static

![image](https://github.com/Gpassed/Configure-AD/assets/129806612/2a643ce1-61ff-420b-83fd-abad4ec44a5b)

Connecting the Ip address of DC1 and Client 1 via SSH Using RDP

![image](https://github.com/Gpassed/Configure-AD/assets/129806612/d36c5ed3-6c4d-456f-b8b4-dacde3e47f11)

Installing Active directory on the Domain Server

![image](https://github.com/Gpassed/Configure-AD/assets/129806612/c622c536-de81-490c-a3a6-99a110ada4bd)

Domain Control DC-1 Virtual Machine outline.
</p>
<br />

![image](https://github.com/Gpassed/Configure-AD/assets/129806612/02934da0-2749-423e-9664-797d65b0de60)

</p>
<p>
<p>
 Virtual Machine2 along with the inbound rule when DC1 and client1 link.
 </p>
<br /> 


![image](https://github.com/Gpassed/Configure-AD/assets/129806612/275a5527-9f70-4082-98ba-de55a9283b23)


</p>
<p>
 
</p>
<br />
This is Wireshark
</p>
<br />

<p>
<img src="https://i.imgur.com/Xc6mecj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Inspecting Network Protocols
<p>
<img src="https://i.imgur.com/R3EzICh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/pIMpd0P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/B0WavBv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
