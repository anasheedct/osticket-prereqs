<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install Virtual Machines for osTicket Installation](https://youtu.be/lkYW9GEHup0 )

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Connect to your Virtual Machine with Remote Desktop
- Install / Enable IIS in Windows
- Install Web Platform Installer
- Install osTicket v1.15.8
- Download and Install HeidiSQL
- Created database for "osTicket
- Clean up
- Change File Permissions

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/6oNHQE9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we install/enable ISS which stands for Internet Information Services, this is needed because osTicket is a web based service.  
</p>
<br />

<p>
<img src="https://i.imgur.com/gRv8LPd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To confirm that it's enabled just type in your browser the 
  loop back address 127.0.0.1 and you should get the results of the image above. 
</p>
<br />

<p>
<img src="https://i.imgur.com/KKnYVMq.png"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When running PHP one MUST install the x86 version of C++ 2015 Redistributable.
<br />
# osticket-prereqs
