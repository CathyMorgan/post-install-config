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

1. Configure Roles: Set up different roles within the system to define user permissions and access levels.
2. Configure Departments: Create departments to organize and categorize incoming tickets based on their nature or area of expertise.
3. Configure Teams: Establish teams within the system to assign specific agents to handle tickets related to their expertise.
4. Configure Agents: Add agents to the system, assigning them to specific roles and teams.
5. Configure Users: Create user accounts for customers or end-users who will be submitting tickets.
6. Configure SLA: Define Service Level Agreements (SLAs) to establish response and resolution timeframes for different types of tickets.
7. Configure Help Topics: Set up predefined help topics to streamline ticket categorization and improve ticket routing.
<h2>Configuration Steps</h2>

<p>

</p>
</p>
<br />



Post-Install Configuration Objectives:


1. Configure Roles:
   - Go to Admin Panel -> Agents -> Roles.
   - Create a "Supreme Admin" role with appropriate permissions.

2. Configure Departments:
   - Go to Admin Panel -> Agents -> Departments.
   - Add a "System Administrators" department.

3. Configure Teams:
   - Go to Admin Panel -> Agents -> Teams.
   - Create a "Level II Support" team.

4. Configure Agents (workers):
   - Go to Admin Panel -> Agents -> Add New.
   - Add "Jane Doe" and assign appropriate roles and teams.
   - Add "John Doe" and assign appropriate roles and teams.

5. Configure Users (customers):
   - Go to Admin Panel -> Users -> Add New.
   - Create a "Ken User" account.

6. Repeat step 5 to create a "Karen User" account.

7. Configure SLA:
   - Go to Admin Panel -> Manage -> SLA.
   - Create SLAs for different severity levels:
     - Sev-A (1 hour, 24/7)
     - Sev-B (4 hours, 24/7)
     - Sev-C (8 hours, business hours)

8. Configure Help Topics:
   - Go to Admin Panel -> Manage -> Help Topics.
   - Add the following help topics:
     - Business Critical Outage
     - Personal Computer Issues
     - Equipment Request
     - Password Reset

By following these steps, you will have successfully configured your osTicket system. Remember to practice triaging and solving tickets, as this is a crucial skill for any help desk specialist. It showcases your ability to effectively communicate with customers and resolve issues related to the product or service being provided.
