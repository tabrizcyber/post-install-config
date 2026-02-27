<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configuring Roles
- Configuring Departments
- Configuring Teams
- Configuring Agents, Users
- Configuring SLA
- Configuring Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/tabrizcyber/images/blob/main/Agent_panel.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm in Agent section of an the Admin panel of osTicket. I'm creating the new role which I'll call "Supreme Admin" and give all the permissions.The basic steps are following:<br/>Admin Panel -> Agents -> Roles -> New Role</strong></i></p>
<p>

  <p>
<img src="https://github.com/tabrizcyber/images/blob/main/New_rule.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm in Agent section of an the Admin panel of osTicket. I'm creating the new role which I'll call "Supreme Admin" and give all the permissions.The basic steps are following:<br/>Admin Panel -> Agents -> Roles -> New Role</strong></i></p>
<p>

  <p>
<img src="https://github.com/tabrizcyber/images/blob/main/departments.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm going to create a new department. "Departments" section is located in Agents panel. Basic steps are following:<br/>
Admin Panel -> Agents -> Departments</strong></i></p>
<p>

  <p>
<img src="https://github.com/tabrizcyber/images/blob/main/NewDepartment.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm creating a new department and calling it as SysAdmin. </strong></i></p>
<p>

  <p>
<img src="https://github.com/tabrizcyber/images/blob/main/settings.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm giving access to any random user to create a ticket. Basic steps are following:<br/>
Admin Panel -> Settings -> User Settings (uncheck: Require registration and login to create tickets)
</strong></i></p>
<p>

  <p>
<img src="https://github.com/tabrizcyber/images/blob/main/registrationUncheck.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm making sure that the "Require registration and login to create tickets" section is unchecked.</strong></i></p>
<p>

  <p>
<img src="https://github.com/tabrizcyber/images/blob/main/Agent_panel.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm basically going to agent panel to create a new agent. The steps are following:<br/>
Admin Panel -> Agents -> Add New</i></p>
<p>

  <p>
<img src="https://github.com/tabrizcyber/images/blob/main/creatingAgent.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm creating a new agent. We can choose a department and roles. We can use the departments we've areated or any department as well as the roles. I've assigned a new agent "Chris" to Support/SysAdmin and gave him arole of SupremeAdmin.</strong></i></p>

<p>
<img src="https://github.com/tabrizcyber/images/blob/main/slaSection.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm going to the Manage panel to look and create SLA rules. There is default rules as well as the section to create custome SLAs.</strong></i></p>

<p>
<img src="https://github.com/tabrizcyber/images/blob/main/SLACreating.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>Here I'm creating 3 custom SLAs:<br/>Sec-A: Requires 1 hour to be completed and has to be done 24/7<br/>Sec-b:Requires 4 hours to be completed and has to be done 24/7<br/>Sec-C:Requires 8 hours to be completed and has to be done 24/5 like normal business days</strong></i></p>

<p>
<img src="https://github.com/tabrizcyber/images/blob/main/slaEnd.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><i><strong>And this is just a view of SLAs after they've been added</strong></i></p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
