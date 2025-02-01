<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
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
<h3 align="center">Configure Roles</h3>

<p>
  Configuring Roles
  <img src="https://github.com/user-attachments/assets/87102ead-ccc1-4a72-84ff-b9bdbf981688"height="75%" width="100%"/>
</p>
<p>
Head to the admin panel, then click on agents, and then roles. Click on “Add New Role” to create a Supreme Admin role
</p>
<br />

<p>
  <img src="https://github.com/user-attachments/assets/fdeb6987-e90e-4b5c-9da7-8d91868f6257"height="75%" width="100%"/>
</p>
<p>
give it all the permissions then click “Add Role”
</p>
<br />

<p>
  Configure Departments
  <img src="https://github.com/user-attachments/assets/a5c159ca-4414-493a-b801-15bd7ad78ee5"height="75%" width="100%"/>
</p>
<p>
Admin Panel -> Agents -> Departments.
</p>
<br />

<p>
  Configure Teams
  <img src="https://github.com/user-attachments/assets/dfb50fa2-766b-4c2a-9d92-8a7f71d07510"height="75%" width="100%"/>
</p>
<p>
Admin Panel -> Agents -> Teams.
</p>
<br />

<p>
  Allow anyone to create ticket
  <img src="https://github.com/user-attachments/assets/7dbec7de-2b7b-4120-b03b-e1dc33441ea5"height="75%" width="100%"/>
</p>
<p>
Admin Panel -> Settings -> User Settings.
Make sure "Require registration and login to create tickets" is not selected</p>
<br />

<p>
Configure Agents (workers)
<img src="https://github.com/user-attachments/assets/40a6d7e4-6f0e-4086-99bf-230a75021bbc"height="75%" width="100%"/>
<img src="https://github.com/user-attachments/assets/ca6029b1-f611-4489-892e-b6ed3dc4b1db"height="75%" width="100%"/> 
</p>
<p>
Admin Panel -> Agents -> Add New.
</p>
<br />

<p>
Configure Users (Customers)
<img src="https://github.com/user-attachments/assets/7754e061-ce51-45e2-883f-c79e3bb58230"height="75%" width="100%"/>
</p>
<p>
Agent Panel -> Users -> Add New.
</p>
<br />

<p>
Configure SLA (service level agreement)
<img src="https://github.com/user-attachments/assets/263aef55-2b6b-483b-8dfb-02bc60518ea4"height="75%" width="100%"/>
</p>
<p>
Admin Panel -> Manage -> SLA.
Sev-A (1 hour, 24/7).
Sev-B (4 hours, 24/7).
Sev-C (8 hours, business hours):</p>
<br />

<p>
Configure Help Topics
<img src="https://github.com/user-attachments/assets/9cfd4edb-86b0-408b-9f82-e2d79af1006f"height="75%" width="100%"/>
<img src="https://github.com/user-attachments/assets/f1b202e3-05f4-4a13-9d8d-796bf5102c3f"height="75%" width="100%"/>
</p>
<p>
Admin Panel -> Manage -> Help Topics.
We are going to create these topics:
-Business Critical Outage
-Personal Computer Issues
-Equipment Request
-Password Reset.
</p>
<br />


<p>
Configure Help Topics
<img src="https://github.com/user-attachments/assets/261b2baf-c5e0-4445-ba33-c62d94086436"height="75%" width="100%"/>
</p>
<p>
Congratulations! Your osTicket configuration is now complete. To enhance your skills, it is highly recommended to practice triaging and resolving tickets. These are essential competencies for help desk specialists, who act as the primary point of contact between a company and its customers, addressing and resolving product or service-related issues effectively.
</p>
<br />














