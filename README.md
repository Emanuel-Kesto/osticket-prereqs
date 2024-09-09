<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install and enable IIS
- Virtual machine 
- php manager
- SQL
- osTICKET

<h2>Installation Steps</h2>

<p>
<img <img width="893" alt="ticket-os" src="https://github.com/user-attachments/assets/ffdfd24e-7017-4316-9156-f84e8cdbd898">

</p>
<p>
The first intial steps of this project is to create a resource group and virtual machine within Azure. After creating the vm, download osTicket and IIS. After downloading IIS you must enable the CGI and other HTTTP features. 
</p>
<br />

<p>
<img <img width="754" alt="PHP FOLDER" src="https://github.com/user-attachments/assets/e5c90907-b6e9-4cb3-98ab-d7a81847f2c2">
 />
</p>
<p>
Download PHP manager and create a directory within your virtual machine. Create a new folder within your C drive and extract content within that file. Also install a rewrite module that allows certain urls and configs. 
</p>
<br />

<p>
<img <img width="767" alt="osTicket set up" src="https://github.com/user-attachments/assets/d419fd94-5a3e-4735-ac4e-b589bd6939db">
 />
</p>

<p>
 Download mysql server and install osTicket. Extract and copy the upload folder from osTicket and put it in inetpub/wwww.root folder. enable php extensions, add persmissions to config.php file, and download heidi which is a database client. Create a new database wothin heidi and osTicket should be up and running.  
</p>
<br />
