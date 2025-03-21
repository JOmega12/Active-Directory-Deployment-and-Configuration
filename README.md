

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
<h3>Create a Domain Admin user within the domain</h3>

- In Active Directory Users and Computers (found in windows), create an Organizational Unit (OU) called "_EMPLOYEES"
- Create a new employee named Jane Doe with username as 'jane_admin' with password as 'Cyberlab123!'
- log out and login as mydomain.com\jane_admin. This will now be used as administrator purposes for the rest of the project/lab to simulate being an administrator 

<h3>Join Client-1 to your domain (mydomain.com)</h3>


<h3>Setup Remote Desktop for non-administrative users on Client-1</h3>
<br />
<h2>Conclusion</h2>

<p>Now you've set up Active Directory in your Virtual Machine with users that can be used in your organization (mydomain.com)</p>
- If you want to see how the next step, click on the next project: <a href="https://github.com/JOmega12/Active-Directory-Deployment-and-Configuration">Next Project</a>

<br />
