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
- Configure SLA

<h2>Configuration Steps</h2>
Configure Roles

Roles are permissions for agents according to their department. Some of the role permissions include assigning, creating, and closing tickets. Here are the steps below to configure roles.

![image](https://github.com/cblack5880/post-install-config/assets/138612466/c4f0e202-7bf8-4bee-bb38-0887ac00ef2e)


Admin Panel -> Agents -> Roles

![image](https://github.com/cblack5880/post-install-config/assets/138612466/c363987c-ebbb-4456-8bf0-b6368b21f562)
![image](https://github.com/cblack5880/post-install-config/assets/138612466/1388d2fb-6ffb-40d9-bb13-d1b371d08ce8)
![image](https://github.com/cblack5880/post-install-config/assets/138612466/a6720162-bdb2-49d0-adbb-25ba8c971fcb)

From here, you can enter a new name for the role, and select the permissions you want for that agent.
![image](https://github.com/cblack5880/post-install-config/assets/138612466/e7798959-5743-43e5-b510-8fdf1a29cbd5)


This agent can have all these permissions assigned to them, which would give these abilities on OsTicket
![image](https://github.com/cblack5880/post-install-config/assets/138612466/c3d95810-0bc6-41d6-bb83-78d00e110bd6)


Configure Departments

Departments are basically the different divisions of the company that handle different tasks.

Admin Panel -> Agents -> Departments

 ![image](https://github.com/cblack5880/post-install-config/assets/138612466/c1b66902-83ce-4f2e-bf7f-388602ad6f25)
![image](https://github.com/cblack5880/post-install-config/assets/138612466/ad23b001-60e6-4b11-953d-9f57730edf96)


You could create a department name. There will be areas where you could also set up an SLA for that department's response to tasks. 

![image](https://github.com/cblack5880/post-install-config/assets/138612466/caf91f05-b6be-4032-b518-3c4f2dadaa75)
Once you are done editing your settings, click Create Dept.

Configure Teams

Configure teams could help with delegating tasks to different agents. (Even if they are in different departments.  Having agents from different departments will supersede the department rules. 

![image](https://github.com/cblack5880/post-install-config/assets/138612466/74335764-e1ca-4e44-88bd-296d16e76461)
![image](https://github.com/cblack5880/post-install-config/assets/138612466/454bba0c-7a1e-4829-a9a2-572a17c2c420)

At this moment, You are only naming the team. Once this is done, you can select its members.
![image](https://github.com/cblack5880/post-install-config/assets/138612466/fe51d2d0-9ac9-46a0-a45e-e5f86c1a9242)
![image](https://github.com/cblack5880/post-install-config/assets/138612466/849dfc9e-c3b3-45f7-b889-90388530fdf2)

Configure Agents

Configuring agents would allow you to give access to different agents. When adding an agent, they will need to be assigned to a primary department and given a primary role for the tickets.

Admin Panel -> Agents -> Add New

![image](https://github.com/cblack5880/post-install-config/assets/138612466/d23f2e60-a9a5-4faf-9727-c874b1331cdb)
![image](https://github.com/cblack5880/post-install-config/assets/138612466/4eb2950f-182f-47a1-8ddd-c76ac8eae844)

From here, you would just fill out the name and email address field. And also set a default Password for the agents. 

![image](https://github.com/cblack5880/post-install-config/assets/138612466/1c7e1e19-d302-4932-a047-a7838408f859)

This shows where you can assign agents to different departments and roles.

![image](https://github.com/cblack5880/post-install-config/assets/138612466/2ba4e025-12ad-41dd-95ab-6b622910d57f)

Configure SLA

SLA or Service Level Agreements to provide the length of time it takes to close a ticket.

Admin Panel -> Manage -> SLA

![image](https://github.com/cblack5880/post-install-config/assets/138612466/d011de71-bef3-4df0-a5c0-dcb6c6ecc6f1)
![image](https://github.com/cblack5880/post-install-config/assets/138612466/f87ef936-dd5a-4730-84b4-8accd1d2bc42)

This example shows the SLA name, the grace period in hours to be completed, and an example of a company having a 24/7 schedule.  This means at any time, a ticket from the time its created, worked on, and close,  it should only take one hour.

![image](https://github.com/cblack5880/post-install-config/assets/138612466/655e88d3-6fc9-454a-9350-eef33cbabb28)

This concludes the Post Installation for OSTIcket.






