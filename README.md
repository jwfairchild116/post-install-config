<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p> The first thing we are going to do is open 2 tabs in our browser, the first is Admin Login Page at http://localhost/osTicket/scp/login.php and the end user ticket page http://localhost/osTicket </p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p> First we are going to add a role of supreme admin. In osTicket, a role defines a set of permissions and access levels assigned to staff members within the helpdesk system. To add a role go to the admin panel > Agents> Roles and we are going to set permissions to everything </p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>Next we are going to configure Departments. a department is a way to organize and manage tickets by categorizing them based on the type of support needed. Go to admin panel > Agents > Departments. Add the department titled “SysAdmin” we are going to leave everything else blank as that will be configured down the line </p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>Next we are going to configure teams. a team is a group of staff members who work together on tickets go to admin Pannel > Agents > Teams . we are going to create a team titled “Online Banking” </p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p> We want anyone to be able to submit tickets so to do this go to admin Panel > settings > user settings and uncheck unregistered users can create tickets </p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p> Now we are going to create two agents. Jane and John. Janes department will be SysAdmin and Johns Department will be support. This can be found at Admin Panel > Agents > Add New </p>

<p>Jane will have a department of sysadmin with a access level of supremeadmin and her team is onlinebanking
Johns Department will be support and view only and leave teams as is </p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p> Now configure 2 users Karen and Ken by going to Agent Panel > Users > add new</p> 

<p> We are going to create 3 Levels of Service Level agreement A Service Level Agreement (SLA) in a help desk is a contract or policy that defines the expected response and resolution times for support tickets, ensuring timely and consistent service based on priority levels. We will have the following 
-	SEV-A – grace period of 1 hour operates 24/7
-	SEV-B Grace Period 4 Hours Operated 24/7
-	SEV-C Grace period 8 hours operates Business hours </p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p> Now we are going to configure help topics a Help Topic is a predefined category that helps users classify their support requests when submitting a ticket you can configure them in Admin Panel > Manage > Help Topics
-	Business Critical Outage (Parent: report a problem)
-	Personal Computer Issues ( Parent:report a problem)
-	Equipment Request ( Parent:General inquiry)
-	Password reset ( parent: report a problem)
-	Other (parent: General Inquiry </p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

