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
<img src="https://imgur.com/vsUkdZN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, Log into osTicket with the login information used during setup. Then, navigate to Admin Panel -> Agents -> Roles and try adding a role. For example, you can create an "Owner" role and give that role all permissions.
</p>
<br />

<p>
<img src="https://imgur.com/uahcKS8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, create departments by going to Admin Panel -> Agents -> Departments. These departments can be used to group different agents together. In this example, a "System Admin" department was created.
</p>
<br />

<p>
<img src="https://imgur.com/HXVdPVo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then, configure teams by going to Admin Panel -> Agents -> Teams. Agents can be placed into teams as a way to dedicate certain tickets to specific people who may be trained in a specific setting. Notice that there is already a "Level I Support" team, so we can create a new one and just call it "Level II Support".
</p>
<br />

<p>
<img src="https://imgur.com/B7PE2Wb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, you can configure some requirements for end-users like requiring a Login to submit a ticket, registration policies, and lockout settings. To do this, navigate to Admin Panel -> Settings -> User Settings. For the example, the user settings are set up so that end users do not need to log in to submit a ticket, but this can be changed if desired.
</p>
<br />

<p>
<img src="https://imgur.com/YJDgLg0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, configure agents (workers) by going to Admin Panel -> Agents -> Add New. Here, you can insert the information of your employee such as name, email, phone number, etc. After setting the username, you can elect to send the agent an email to set his or her password, or you can set it up manually. You also have the option to require the agent to change their password at sign-in. This is always good practice in real-world applications, but it is not necessary for the example. You can also assign agents to departments and teams from this tab, as well as change any permissions. 
</p>
<br />

<p>
<img src="https://imgur.com/DaWRtfm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, we will set up users (customers) by going to Agent Panel -> Users -> Add New. Note that this can be done by any agent with the add user permission, and it does not require Administrative permissions. User accounts can also be created by end-users from the ticket submission website.
</p>
<br />

<p>
<img src="https://imgur.com/Sw3mhnv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, configure SLA settings from Admin Panel -> Manage -> SLA. From here, click "add new". SLAs are used to triage tickets and set response standards based on severity/business impact. Here, the SLA created corresponds to tickets that require immediate assistance. For these, you may want to set the grace period to one hour, and the schedule to 24/7 because these are issues that correspond to major business impact, such as an entire department outage. You can also select to override SLA plan on ticket transfer or help topic change.
</p>
<br />

<p>
<img src="https://imgur.com/4trKk3f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/K474zty.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, we can create some help topics that end-users can choose as a way to generally describe the issue they may be having. To do this, navigate to Admin Panel -> Manage -> Help Topics. From here, we can name our topic as well as specify the SLA, department, priority, and team for tickets created with this topic. For example, you might want to auto-assign the SLA plan and priority of any tickets in the topic "business outage" as the highest severity and priority. 
</p>
<br />

<h2>🤳Connect with me:</h2>

[<img align="left" alt="Joseph | LinkedIn" width="22px" src="https://imgur.com/yJ22BHw.png" />][linkedin]
[<img align="left" alt="Joseph | Instagram" width="22px" src="https://imgur.com/JnlEgDK.png" />][instagram]
[<img align="left" alt="Joseph | Discord" width="22px" src="https://imgur.com/YGezWPR.png" />][discord]


[instagram]: https://www.instagram.com/jenkins5937/
[linkedin]: https://www.linkedin.com/in/joseph-jenkins-521a49241
[discord]: https://www.discordapp.com/users/262825628695396352
