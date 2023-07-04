<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Step 1: Configure Roles, Departments, and Teams.  
- Step 2: Configure Agents (Workers).
- Step 3: Configure Users (Customers).
- Step 4: Configure SLA (Service Level Agreement).
- Step 5: Configure Help Topics.
<br />
<br />

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/KUhZwbC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Configure Roles, Departments, and Teams. First, configure ROLES by clicking on Admin Panel -> Agents -> Roles. Name the new role "Supreme Admin."
  Next, configure DEPARTMENTS by clicking on Admin Panel -> Agents -> Departments. Name the new department "System Administrators. Finally, configure TEAMS by clicking Admin Panel -> Agents -> Teams. "Level I Support" is already listed, but add a new team named "Level II Support." 
</p>
<br />
<br />
<br />

<p>
<img src="https://i.imgur.com/9okPXdX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Configure Agents (Workers). Create agents by clicking on Admin Panel -> Agents -> Add New.
</p>
<br />
<br />
<br />

<p>
<img src="https://i.imgur.com/2AQ4mt4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3: Configure Users (Customers). In order to add customer's names be sure you are on the AGENT panel.  Click on Agent Panel -> Users -> Add New.
</p>
<br />
<br />
<br />

<p>
<img src="https://i.imgur.com/zAAmAVN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: Configure SLA (Service Level Agreement). Set up three levels of SLA by going back to the Admin Panel.  Click on Admin Panel -> Manage -> SLA.  The three levels are as follows: 1. Sev-A (1 hour, 24/7), 2. Sev-B (4 hours, 24/7), 3. Sev-C (8 hours, business hours).
</p>
<br />
<br />
<br />

<p>
<img src="https://i.imgur.com/g32lpBd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5: Configure Help Topics. When a user (customer) needs help they can select from a list of help topics.  To set up these help topics, click Admin Panel -> Manage -> Help Topics.  Add these help topics to the list: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.
</p>
<br />

