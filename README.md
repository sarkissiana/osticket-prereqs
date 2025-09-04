<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial demonstrates the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

Microsoft Azure (Virtual Machines / Compute)

Remote Desktop (RDP)

Internet Information Services (IIS)

MySQL / HeidiSQL

PHP Manager for IIS
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

1. Create a Virtual Machine in Microsoft Azure running Windows 10.

2. Enable IIS (Internet Information Services) in Windows.

3. Install Web Platform Installer and necessary IIS components.

4. Install PHP Manager for IIS.

5. Install and configure MySQL and HeidiSQL.

6. Download and install osTicket from the official website.

<h2>Installation Steps</h2>

<p>
 <img width="1920" height="899" alt="Screenshot 2025-09-04 093653" src="https://github.com/user-attachments/assets/0e722963-00d7-4786-afa6-e49ea122f95d" />
<img <img width="1909" height="1080" alt="Screenshot 2025-09-04 102432" src="https://github.com/user-attachments/assets/44228f19-1415-41db-ab3f-6b06e7e45a2b" />

</p>
<p>
1. Create and Connect to a Virtual Machine  
Provision a Windows 10 VM on **Microsoft Azure** and connect using RDP. 


</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Enable IIS (Internet Information Services)  
Enable IIS and required components (CGI, Common HTTP Features).  
Verify by browsing to `http://localhost`. 

Verify IIS by navigating to http://localhost.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open Windows Features → Enable IIS + CGI.

Verify IIS by navigating to http://localhost..
</p>
<br />
