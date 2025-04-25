<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration Walkthrough</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles for (grouping permissions)
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>
<h3>Configure Roles (for grouping permissions)</h3>

<img width="975" alt="Screenshot 2025-04-24 at 7 23 33 PM" src="https://github.com/user-attachments/assets/80053f8a-9280-48e2-8061-18d320fc355e" />


<img width="967" alt="Screenshot 2025-04-24 at 7 26 50 PM" src="https://github.com/user-attachments/assets/f8385410-e1d8-48c1-b479-ede618562e61" />
<p>Login to your OsTicket as admin with username and password. From the admin panel click on Agents then roles.</p>
<img width="958" alt="Screenshot 2025-04-24 at 7 29 09 PM" src="https://github.com/user-attachments/assets/04b127d6-aa4d-4272-95e1-8b9253b6ef67" />
<img width="960" alt="Screenshot 2025-04-24 at 7 33 51 PM" src="https://github.com/user-attachments/assets/1a4eb345-5b86-4d3b-90f0-6eb17f5bf14c" />

 <p>lastly you can add a new role and give it a name and permissions.</p>
<br />
<h3>Configure Departments</h3>
<img width="958" alt="Screenshot 2025-04-24 at 7 40 18 PM" src="https://github.com/user-attachments/assets/dc389250-5a1d-4da2-8082-cdf5573988b2" />

<p>
Make sure your on Admin Panel then go to agents and click on department. 
</p>
<img width="963" alt="Screenshot 2025-04-24 at 7 43 03 PM" src="https://github.com/user-attachments/assets/409a4a8f-99ef-4b5f-adaa-28cbbcee7ba8" />

<p>Click on add new departments and Fill out the department information form and click Create Department</p>
<br />
<h3>Configure Teams</h3>
<img width="961" alt="Screenshot 2025-04-24 at 7 52 16 PM" src="https://github.com/user-attachments/assets/d20c5bfe-48d6-4283-bc72-7891b8d96d84" />
<p>
First we'd go to Admin Panel then agents and teams. Add new Teams
</p>
<img width="958" alt="Screenshot 2025-04-24 at 7 52 34 PM" src="https://github.com/user-attachments/assets/793f5653-29f2-4145-ad16-fe4ec38ec732" />
<p>Fill Out the Team Information and Click Create team</p>
<img width="988" alt="image" src="https://github.com/user-attachments/assets/2f05541b-10c5-4275-9b15-3f23309c7cdc" />
</p>
<h3>Allow Anyone To Create Tickets</h3>
<img width="1090" alt="Screenshot 2025-04-24 at 8 05 37 PM" src="https://github.com/user-attachments/assets/e6207e13-5d92-40af-85e3-e81b53eeb592" />

<p>Make sure your on the Admin panel, then Settings. next click on User Settings. Make Sure Registration required is unchecked</p>
<h3>Configure Agents</h3>
<img width="966" alt="Screenshot 2025-04-24 at 8 10 34 PM" src="https://github.com/user-attachments/assets/015068f9-b530-4bac-9cbb-e32bceacfd4b" />

<p>In the Admin Panel go Agents. Lastly click on Add New Agent</p>
<p>
 <img width="960" alt="Screenshot 2025-04-24 at 8 14 10 PM" src="https://github.com/user-attachments/assets/7fd5d388-a751-4418-b688-f25ec425cf8d" />
<img width="961" alt="Screenshot 2025-04-24 at 8 27 01 PM" src="https://github.com/user-attachments/assets/e92c7ff4-bb9c-49e9-b9e9-d441e4554a6b" />
<img width="958" alt="Screenshot 2025-04-24 at 8 27 22 PM" src="https://github.com/user-attachments/assets/363938dd-0fb0-457e-b885-2d496b7af397" />
<img width="958" alt="Screenshot 2025-04-24 at 8 26 40 PM" src="https://github.com/user-attachments/assets/7aa9fde0-beeb-4fa9-8336-4fc73ac3b5d1" />
</p>

<img width="643" alt="Screenshot 2025-04-24 at 8 14 41 PM" src="https://github.com/user-attachments/assets/818b7b26-ad31-4536-81d7-e5399b91dca9" />

<p>Fill out the neccecary information</p>
<p>Set Agent Password and click create</p>

<h3>Configure Users (Cutomers)</h3>
<img width="966" alt="Screenshot 2025-04-24 at 8 36 10 PM" src="https://github.com/user-attachments/assets/e69ff2a4-61e7-409a-bf29-b18c3552c967" />
<img width="646" alt="Screenshot 2025-04-24 at 8 36 44 PM" src="https://github.com/user-attachments/assets/80364f30-81ff-47f9-9f72-90b6e0993abb" />

<p>Agent Panel -> Users -> Add New

<h3>Configure SLA</h3>
<img width="962" alt="Screenshot 2025-04-24 at 8 43 21 PM" src="https://github.com/user-attachments/assets/cb223c9f-9155-4358-b3b6-c2fece5a61a4" />
<img width="962" alt="Screenshot 2025-04-24 at 8 43 21 PM" src="https://github.com/user-attachments/assets/1fd99d24-18c3-4acb-91f0-114d515da094" />
<p>Admin Pamel then Manage and lasltly click SLA</p>
<img width="960" alt="image" src="https://github.com/user-attachments/assets/0c55e611-971a-457b-b4cc-0b05f8ef216a" />
<p>Fill it out and click Add Plan</p>
</p>
<h3>Configure Help Topics</h3>
<img width="961" alt="Screenshot 2025-04-24 at 8 52 09 PM" src="https://github.com/user-attachments/assets/0cf7a3f1-9a73-4df2-8e60-de487751f96f" />
<p>Admin Panel -> Manage -> Help Topics</p>
<img width="963" alt="Screenshot 2025-04-24 at 8 52 21 PM" src="https://github.com/user-attachments/assets/7d01fb92-916f-4591-9465-09e8ea34f8b2" />
<p>Fill it out and click ADD Topic</p>


