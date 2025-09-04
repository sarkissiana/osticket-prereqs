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

3. Install PHP Manager for IIS.

4. Install and configure MySQL.

5. Download and install osTicket from the official website.

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
 <img width="1916" height="1080" alt="Screenshot 2025-09-04 103101" src="https://github.com/user-attachments/assets/1731dfcd-42e3-4c40-82a9-9bf7a467cf9c" />
 <img width="1916" height="1080" alt="Screenshot 2025-09-04 103423" src="https://github.com/user-attachments/assets/988b8e5f-8dd2-430a-9745-cd7d04d1dfa4" />

</p>
<p>
2. Enable IIS (Internet Information Services)  
Enable IIS and required components (CGI, Common HTTP Features).  


</p>
<br />

<p>
 <img width="1920" height="1080" alt="Screenshot 2025-09-04 103943" src="https://github.com/user-attachments/assets/1b5a4bcb-8ff6-4f65-8eba-a80bdb1d3d6e" />
 <img width="1916" height="1080" alt="Screenshot 2025-09-04 104024" src="https://github.com/user-attachments/assets/92bdcdc0-2044-45b5-add6-6b2013dff738" />

</p>
<p>
3. Install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi) & Install the Rewrite Module (rewrite_amd64_en-US.msi)

<img width="3804" height="1080" alt="Screenshot 2025-09-04 104825" src="https://github.com/user-attachments/assets/c4876767-6907-40f2-bd09-f9eee613dbe8" />

<img width="1910" height="1080" alt="Screenshot 2025-09-04 105112" src="https://github.com/user-attachments/assets/d9f97a9e-bdcc-4714-b069-dd5cbd0b9589" />



4. Install **MySQL** and configure a root password.  


</p>
<br />
