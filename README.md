<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

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
- Create a Domain Admin User
- Join a (client) computer to the Domain
- Open Active Directory: Users and Computers and create Orgazational Units

<h2>Deployment and Configuration Steps</h2>

![ADlab1](https://github.com/user-attachments/assets/e0ce2f4d-b1fd-4225-8384-64814cb490af)


<p>
<img src="" height="80%" width="80%" alt="Creating Employees"/>
</p>
<p>
In Active Directory Users and Computers, create Organizational units for: Employees, Admins, and Clients. Once employees are created, observe them by "dragging" them into the corresponding Organizational Unit.
</p>
<br />

![ADlab2](https://github.com/user-attachments/assets/00038a80-06ea-4ca7-ac38-402b9a9917d6)


<p>
<img src="" height="80%" width="80%" alt="Test Employee Sign-on"/>
</p>
<p>
Once you successfully sign-on with an employee account, under the correct domain, congratulations AD is configured. From DC-1, as an Admin, you may deal with account lockouts, Enable/Disable Accounts, and Observing Logs.
<br />
