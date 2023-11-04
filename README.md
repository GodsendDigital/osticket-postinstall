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

- Make an Administrator Account
- Create Agents
- Create Service Level Agreements
- Create and Answer Tickets

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/xHGWRwM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XF3deIF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once osTicket is installed, I begin to create the admin account to essentially control everything. This admin account can create agents, other admins, teams, SLAs, Help Topics, and more.
</p>
<br />

<p>
<img src="https://i.imgur.com/4bdIgjy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I must create agents accounts that will act as an employee of a company. The agents day to day tasks will be focus on working trouble tickets. Agents can be order to answer a ticket from management, end users, and clients. The tickets can require immediate attention or can be address in a timely manner. 
</p>
<br />

<p>
<img src="https://i.imgur.com/FqL5uA1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 Some companies have Service Level Agreements and SLA are a target the agent have to meet pertaining tickets such as
<ul>
 <li>How quickly a ticket is a assigned to an agent</li>
 <li>How quickly the agent initially reach out to the user who created the ticket</li>
 <li>How often the agent communicate with the user until the issue is solved</li>
 <li>How quickly the issue is solve</li>
</ul> 
Tickets will often have a severity assigned to them which is defined by the organization, but the severity is usually related to the business impact. Severity often defines the SLA.
<ul>
  <li>Severity-A: High Impact(1hour, 24/7)</li>
  <li>Severity-B: Medium Impact(4hour, 24/7)</li>
  <li>Severity-C: Low Impact(8hour, Business hours)</li>
</ul>    
Common issues that users face at a business are
<ul>
  <li>Passwords/Credential Reset</li>
  <li>Equipment Problems</li>
  <li>Software Installation or Upgrade</li>
  <li>Computer or Internet Slow Speed</li>
  <li>Printer Issues</li>
  <li>VPN/Connectivity Issues</li>
</ul>   
</p>

<p>
 <img src="https://i.imgur.com/TnFJN0f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/TUSk9xF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/cXQ6qpm.png"height="80%" width="80%" alt="Disk Sanitization Steps"/>
Now I create a ticket so, I can answer it and resolve it myself as a user and agent. First go to the regular site for end users and put in a ticket. After that i log in as an agent and the ticket will appear. I open the ticket and proceed to solve the problem. As the admin I can assign tickets to or other agents and place the ticket for a certain team. After the problem solved, I have to write a brief summary on the update and close the ticket.
</p>
<br />
