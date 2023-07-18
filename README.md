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

<h2>Configuration Steps</h2>

Step 1: Open and log into osTicket via your web broswer (http://localhost/osTicket/scp/login.php)
<p>
<img Screenshot 2023-07-18 at 3 02 21 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/f8e1c93a-e430-4fe9-9f5f-d462f377b1f1">
<p>
<img Screenshot 2023-07-18 at 3 04 08 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/d4e7974f-ad83-45aa-a2d6-8fc3627b1f87">
</p>
<br />

Step 2: Click "Admin Panel" located on the top right ribbon to switch over from Agent Panel
<p>
<img Screenshot 2023-07-18 at 3 04 08 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/ba550df5-011b-4182-9f02-e12018fe1bfc">
</p>
<img Screenshot 2023-07-18 at 3 11 04 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/3241eb9e-7b2e-4cad-93c0-1366fd2e7d1e">
</p>
<br />

Step 3: Add a Supreme Admin Role by choosing the Agents tab - Roles - Add New Role
<p>
<img Screenshot 2023-07-18 at 3 18 30 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/67d32715-4692-48b9-a0cc-cced7a21b874">
</p>
Name the role "Supreme Admin"
<p>
<img Screenshot 2023-07-18 at 3 21 07 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/fc029373-1d8a-439b-bc53-a96396b0f6c4">
</p>
Head over to the Permissions tab and check every box in the Tickets, Tasks, and Knowledgebase sections then save changes
<p>
<img Screenshot 2023-07-18 at 3 21 39 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/1660ee1f-3e00-459f-a4da-1b36942a5f60">
</p>
<br />

Step 4: Add a Systems Administrator Department by choosing the Agents tab - Departments - Add New Department - Fill in the name System Administrators - Create Dept
<p>
<img Screenshot 2023-07-18 at 3 32 18 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/8a222599-140f-4372-9b02-72cf465b4176">
</p>
<br />

Step 5: Add a Level II Support Team by choosing the Agents tab - Teams - Add New Team
<p>
<img Screenshot 2023-07-18 at 3 37 15 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/d5f01327-7345-41d5-a2b1-a91b42cfef8d">
</p>
Name the team "Level II Support"
<p>
<img Screenshot 2023-07-18 at 3 34 42 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/1a689af0-58d1-49a9-a837-536af8ff8194">
</p>
On the Members tab select yourself as the team member and create the team
<p>
<img Screenshot 2023-07-18 at 3 34 50 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/702736cf-8a32-4e2f-992b-b41a74c988b3">
</p>
<br />

Step 6: Configure the Agents who will be working on the tickets by choosing the Agents tab - Agents - Add New Agent
<p>
<img Screenshot 2023-07-18 at 3 53 55 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/d1e5d542-11f3-4016-a034-c6404193f181">
</p>
Fill out the account information for the new agent
<p>
<img Screenshot 2023-07-18 at 3 57 31 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/63e4158d-effd-4bec-bff8-d042b3e6c373">
</p>
Click Set Password - Uncheck the box - Create password for agent - Uncheck the box - Click Set
<p>
<img Screenshot 2023-07-18 at 4 01 11 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/b317b83a-d54f-4765-9c2f-6ecb66be6a33">
</p>
Head over to the Access tab and assign the user's Primary Department
<p>
<img Screenshot 2023-07-18 at 4 04 49 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/a8446a74-4699-462c-ba25-1a903bcef850">
</p>
Next head over to the Teams tab and assign the user to the Level II Support and click Create
<p>
<img Screenshot 2023-07-18 at 4 09 54 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/a192e718-397e-43fd-be10-7cf9aacbd38a">
</p>
Repeat Step 6 to create another Agent with their Department being Support
<p>
<img Screenshot 2023-07-18 at 5 08 18 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/f33d7356-6b70-4f8b-bfa7-5281afee2cbc">
</p>
<br />

Step 7: Switch over to Agent Panel to create users
<p>
<img Screenshot 2023-07-18 at 4 18 29 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/6f4ec4df-eefa-45f6-beff-85b0c6f56ee8">
</p>
Choose Users - User Directory - Add User (Create two users)
<p>
<img Screenshot 2023-07-18 at 4 20 25 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/148556de-0ef5-4eec-9881-0d14aa9c0e07">
</p>
<img Screenshot 2023-07-18 at 4 24 27 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/fa89f447-b3a8-4936-bb72-a43a00c74f44">
<p>
<img Screenshot 2023-07-18 at 4 28 36 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/3e040f8e-b1af-4cb4-821d-495472223685">
</p>
<br />

Step 8: Switch back over to the Admin Panel to configure SLAs by selecting Manage - SLA - Add New SLA Plan
<p>
<img Screenshot 2023-07-18 at 4 31 02 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/52a97b83-28a6-43c8-8d28-47aac9f8bd38">
</p>
Add 3 different Severity Plans (SEV-A, SEV-B, SEV-C) with (24/7 & 1 grace period, 24/7 & 4 grace period, and business hours & 8 hours)
<p>
<img Screenshot 2023-07-18 at 4 38 36 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/69c93f5c-e6d8-471f-8637-c5dddf23d862">
</p>
<img Screenshot 2023-07-18 at 4 40 05 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/50bda397-c73d-4738-9799-cf4bd2c66ecf">
<p>
<img Screenshot 2023-07-18 at 4 40 33 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/073a6173-7650-43fb-903f-0b17b17af873">
</p>
<img Screenshot 2023-07-18 at 4 40 41 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/9ef639f5-700a-416c-ae56-9f244dfce4c8">
</p>
<br />

Step 9: Configure Help Topics by selecting Manage - Help Topics - Add New Help Topic
<p>
<img Screenshot 2023-07-18 at 4 46 59 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/c5b72d50-4cb3-44aa-b1a2-c47d1c001126">
</p>
Create 4 new help topics (Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset)
<p>
<img Screenshot 2023-07-18 at 4 50 43 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/5c1c62fd-0d36-48b0-b850-bbab59d480c3">
</p>
<img Screenshot 2023-07-18 at 4 51 13 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/90dc0113-274f-4204-8ac3-a3156a4bb5ff">
<p>
<img Screenshot 2023-07-18 at 4 51 57 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/57c80c3d-a2a8-4d64-98dc-4bdc1baad661">
</p>
<img Screenshot 2023-07-18 at 4 52 53 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/869268e3-7c49-491d-a21f-0110bec7643b">
<p>
<img Screenshot 2023-07-18 at 4 53 12 PM" src="https://github.com/areyes302/post-install-config/assets/139584521/4b39e41c-75b8-4f60-808e-6c68ac2a6366">
</p>
<br />

CONGRATULATIONS 🎉, you've finished basic configuration of osTicket! 

