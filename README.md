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

- Access osTicket
- Agent Panel vs. Admin Panel
- Configuring Roles, Departments, and Teams 
- Allowing User Ticket Creation
- Configuring Agents and Users
- Configuring SLAs and Help Topics

<h1>Configuration Steps</h1>

<h2>1. Accessing osTicket</h2>
<p>
Before I could configure osTicket, I had to access the respective panels:

- Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php
- End-User Ticket Portal: http://localhost/osTicket

</p>
<p>
<img src="https://i.imgur.com/r6k75l3.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>2. Understanding the Agent Panel vs. Admin Panel</h2>
<p>
osTicket has two primary interfaces:

- Admin Panel: For configuring settings, roles, and permissions.
- Agent Panel: Where support staff manage tickets and interact with users.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>3. Configuring Roles (Permissions Grouping)</h2>
<p>
Roles help define different permission levels for agents.

- Navigate to Admin Panel → Agents → Roles
- Example Role:
    - Supreme Admin (Full access to settings and tickets)
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>4. Configuring Departments (Ticket Visibility & Assignment)</h2>
<p>
Departments help categorize tickets based on expertise.

- Go to Admin Panel → Agents → Departments
- Example Departments:
    - Help Desk
    - SysAdmins
    - Networking
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>5. Configuring Teams (Cross-Department Collaboration)</h2>
<p>
Teams allow agents from different departments to collaborate.
  
- Go to Admin Panel → Agents → Teams
- Example Team:
    - Online Banking (Pulls agents from multiple departments)

</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>6. Allowing User Ticket Creation</h2>
<p>
By default, osTicket allows ticket creation by anyone. You can restrict this by enabling user registration.

- Navigate to Admin Panel → Settings → User Settings
- Uncheck "Unregistered users can create tickets" to require login for ticket creation.

</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>7. Configuring Agents (Support Staff)</h2>
<p>
Agents handle tickets and are assigned to specific departments.

- Navigate to Admin Panel → Agents → Add New
- Example Agents:
    - Sally (SysAdmins)
    - Kyle (Support)

</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>8. Configuring Users (Customers)</h2>
<p>
Users are the customers who submit tickets.

- Navigate to Agent Panel → Users → Add New
- Example Users:
    - Karen
    - Bobby

</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>9. Configuring SLAs (Service Level Agreements)</h2>
<p>
SLAs define response and resolution timeframes.

- Go to Admin Panel → Manage → SLA
- Example SLA Policies:
    - Sev-A: 1-hour grace period, 24/7 support
    - Sev-B: 4-hour grace period, 24/7 support
    - Sev-C: 8-hour grace period, business hours

</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h2>10. Configuring Help Topics (User Ticket Categorization)</h2>
<p>
Help topics simplify ticket submission by categorizing issues.

- Navigate to Admin Panel → Manage → Help Topics
- Example Topics:
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset
    - Other

</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>
<br />

<h1>My Conclusion</h1>
<p>
When A ticketing System (osTicket) is set up correctly it ensures a smooth and organized support experience. By configuring roles, departments, teams, agents, SLA's and help topics, an organization can strengthen its customer support efficiency.

</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt=""/>
</p>

