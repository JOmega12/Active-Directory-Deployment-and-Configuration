

<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>


<h1>Active Directory Deployment</h1>
This tutorial outlines the setup for Active Directory(AD)
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- Powershell

<h2> Objectives</h2>

- Install Active Directory
- Create a Domain Admin user within the domain
- Join Client-1 to your domain (mydomain.com)
- Setup Remote Desktop for non-administrative users on Client-1

<h2> Configuration </h2>

<h3>Install Active Directory</h3>

- Go to Dc-1, in Server Manager, we are going to setup a new forest for AD as mydomain.com, then restart and login as mydomain.com\labuser
![InstallADinDC](https://github.com/user-attachments/assets/5779bf4d-04b6-4659-bb8b-819a03b010ee)

![clickOnThisToInstallAD](https://github.com/user-attachments/assets/cb0c79af-86b1-477b-9d1f-b36f53783fdc)
![addingDomainCom](https://github.com/user-attachments/assets/8cc078e1-ec76-45e2-b000-68b768f4b824)

<h3>Create a Domain Admin user within the domain</h3>

- In Active Directory Users and Computers (found in windows), create an Organizational Unit (OU) called "_EMPLOYEES"
![ADUC](https://github.com/user-attachments/assets/d703b689-05ac-49b3-b291-82f7f63b6552)

- Create a new employee named Jane Doe with username as 'jane_admin' with password as 'Cyberlab123!'
![createJaneAdmin](https://github.com/user-attachments/assets/c2b5b3d3-04e7-4fb0-816e-ac8a63598a30)

  
- log out and login as mydomain.com\jane_admin. This will now be used as administrator purposes for the rest of the project/lab to simulate being an administrator 
![makeHeradminMemberOf](https://github.com/user-attachments/assets/cc7b1360-eb6f-4df3-8867-08c643578301)

<h3>Join Client-1 to your domain (mydomain.com)</h3>
![ConnectClient1ToDC](https://github.com/user-attachments/assets/400d821c-6b1d-4032-bd7a-d572dc6cb025)


<h3>Setup Remote Desktop for non-administrative users on Client-1</h3>
![inClient1AdminTurnonRDP](https://github.com/user-attachments/assets/f81329ba-a4aa-49b0-af7e-7fb3e3cfd56f)


<br />
<h2>Conclusion</h2>

<p>Now you've set up Active Directory in your Virtual Machine with users that can be used in your organization (mydomain.com)</p>
- If you want to see how the next step, click on the next project: <a href="https://github.com/JOmega12/Active-Directory-Deployment-and-Configuration">Next Project</a>

<br />
