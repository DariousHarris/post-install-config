<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuring Roles, Departments, and Teams</h2>

<p>
<img src="https://i.imgur.com/0t4Rpi9.png" height="40%" width="40%" alt="Disk Sanitization Steps"/> <img src="https://i.imgur.com/EkQ1Ito.png" height="40%" width="40%" alt="Disk Sanitization Steps"/> 
</p>
<p>
The post-installation setup phase focuses on refining the osTicket environment for specific roles and responsibilities. Administering the Admin Panel involves configuring roles such as "Supreme Admin" and defining departments such as "System Administrators." Further segmentation is achieved through the creation of teams like "Level I Support" and "Level II Support." Additionally, the global setting to allow anyone to create tickets is adjusted in the User Settings.
</p>
<br />

<h2>Agent and User Configuration</h2>

<p>
<img src="https://i.imgur.com/WEkQVHS.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents, who are the workers in the system, are configured through the Admin Panel. New agents, Jane and John, are added to the system, each with their assigned responsibilities. Simultaneously, customers or end-users are configured through the Agent Panel, adding users like Karen and Ken to the system.
</p>
<br />

<h2>Service Level Agreements (SLA) and Help Topics</h2>
<p>
<img src="https://i.imgur.com/rRGzJMT.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
To enhance ticket management, SLAs are configured using the Admin Panel. Different levels of service are defined, such as Sev-A with a 1-hour response time 24/7, Sev-B with a 4-hour response time 24/7, and Sev-C with an 8-hour response time during business hours. Additionally, Help Topics are configured to streamline the categorization of issues. Topics like "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset" are established to provide clarity and efficiency in ticket handling.

</p>
<br />
