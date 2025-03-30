<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
Project includes the prerequisites and installation walkthrough of the open-source help desk ticketing system osTicket.  The system was installed on a Windows 10 Virtual Machine using Microsoft Azure.<br />

<h2>Necessary Installation Files</h2>
https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD


<h2>List of Prerequisites</h2>

- Microsoft Azure, Virtual Machines
- Operating System (Windows 10)
- Web Server (IIS, Windows)
- Personal Home Page (PHP) Manager 
- Rewrite Module
- VC_redistx86.exe
- MySQL Database

<h2>Installation Walk-through</h2>

<p align="center">
Navigate to Microsoft Azure and create a Resource Group: 
  
![creating rg](https://github.com/user-attachments/assets/eaca884b-69aa-4ff6-a8fd-d48f0cf6aa0b)

<p align="center">
  
![creating rg](https://github.com/user-attachments/assets/d1c0bf50-2f58-4da4-bfd2-a9b39c6b49c1)
<p align="center">
Create a Virtual Machine within the Resource Group: 
  
![creating vm](https://github.com/user-attachments/assets/8ff7baee-7f74-4957-9a4d-2347efd3132d)
<p align="center">
Virtual Machine setup:
  
![virtual machine setup](https://github.com/user-attachments/assets/48d7db7e-ebe1-4136-8b56-a4d50bce8d71)
<p align="center">
Using the IP address from the newly created VM, connect to the VM using Remote Desktop or Windows App:

![Remote](https://github.com/user-attachments/assets/4c598dd0-f6c9-4f4c-991b-f70f4683df0b)

![Remote](https://github.com/user-attachments/assets/747003b0-2652-44e7-9454-90c6b76da8ba)
<p align="center">
Install and enable IIS (Internet Information Services).  Enable CGI and all Common HTTP Features:

![image](https://github.com/user-attachments/assets/8b568f61-9124-43e8-a682-783067e426b1)
<p align="center">
Test the installation by typing the loopback IP address 127.0.0.1 in the internet browser:

![image](https://github.com/user-attachments/assets/c1ff9d71-c011-4b47-b19d-84e9d4156d55)

<p align="center">
From the Installation files provided above, install PHP Manager for IIS, the IIS URL Rewrite Module, VC_redist.x86, and mysql5.5.62:

![image](https://github.com/user-attachments/assets/a73f7825-a448-4e4d-9396-05809fa5b12b)

<p align="center">
Run the IIS as administrator, register PHP from within IIS, restart the server:

![image](https://github.com/user-attachments/assets/1addc5e6-2387-4450-b713-1868be582e76)
















Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://imgur.com/PbGX63J"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /># osticket-prereqs
