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

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/XVk3w0j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Admin Panel -> Agents -> Roles.
Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/oyIvtDP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Agents -> Departments.
Service Level Agreement for tickets routed to this Department. This the expected amount of time (in hours) that a ticket is expected to be closed once opened. If the ticket is not closed in the allotted amount of time, it will then be Overdue.
</p>
<br />

<p>
<img src="https://i.imgur.com/S3RHqpy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Agents -> Teams.
Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
</p>
<br />

<p>
<img src="https://i.imgur.com/EVSje3k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Agents -> Add New.
Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
</p>
<br />

<p>
<img src="https://i.imgur.com/P9BMOVP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agent Panel -> Users -> Add New.
Users can now create an account and log-in to create a ticket or check a ticket’s status. As always with osTicket, users or ticket creators are associated with their email address as the unique identifier of each user. The User Directory, located on the Agent Panel, allows agents to search tickets by user as well as create Organizations to associate the user to. Agents can be configured as internal Account Managers for tickets created by users of an Organization.
</p>
<br />

<p>
<img src="https://i.imgur.com/sFwH8yU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Manage -> SLA.
SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.
</p>
<br />

<p>
<img src="https://i.imgur.com/WE7MxuX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Manage -> Help Topics.
Help Topics will help streamline your end-user’s help desk experience to ensure proper assignment and prompt response to the ticket.
</p>
<br />


