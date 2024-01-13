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
- Configure SLAs
- Configure Help Topics


<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/vannessacates/post-install-config/assets/140145473/e626a98c-9ae8-485c-9cea-600b672fd141"/>
</p>
<p>
Go to http://localhost/osTicket/scp/login.php  

Navigate to Admin Panel on the top right. Click on the Agents tab and then Roles. Create a role named Supreme Admin. Make sure all permissions are checked off for this role before clicking Add
</p>
<br />

<p>
<img src="https://github.com/vannessacates/post-install-config/assets/140145473/447ec483-3f99-4607-ab49-43971c307054"/>
</p>
<p>
Navigate to Admin Panel on the top right. Click on the Agents tab and then Departments. Create a department named System Administrators
</p>
<br />

<p>
<img src="https://github.com/vannessacates/post-install-config/assets/140145473/2ced14ea-23b9-402b-87e8-194f84b5a85d"/>
</p>
<p>
Navigate to Admin Panel on the top right. Click on the Agents tab and then Teams. Create a team named Level II Support.
</p>
<br />

<p>
<img src="https://github.com/vannessacates/post-install-config/assets/140145473/39087b4e-1a75-4a06-8607-bdcc7a20a9f1"/>
</p>
<p>Navigate to Agents and then add new. Add two new agents remembering to give them access to a department and role.
</p>
<br />

<p>
<img src="https://github.com/vannessacates/post-install-config/assets/140145473/4e0155d0-0446-445e-ab92-ff739f6d7e4a"/>
</p>
<p>Navigate to the Agent Panel at the top right. Click on the Users tab and add two new users.
</p>
<br />

<p>
<img src="https://github.com/vannessacates/post-install-config/assets/140145473/609ed2e5-e533-460c-a5be-8e9239efd939"/>
</p>
<p>Navigate back to the Admin Panel on the top right and go to the Manage tab and click on SLA. Create 3 different SLAs. 

Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://github.com/vannessacates/post-install-config/assets/140145473/233d4082-57a3-41af-af2a-71364225535d"/>
</p>
<p>Go back to the Manage tab and click on Help Topics. Create 4 new topics titled as such:

Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset
</p>
<br />
