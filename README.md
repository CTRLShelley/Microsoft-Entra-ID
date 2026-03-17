👥 Identity and Access Management 👥

<h1>Microsoft Entra ID</h1>
<h2>Overview</h2>
This project demonstrates fundamental Identity and Access Management (IAM) concepts using Microsoft Entra ID. Identity and Access Management is a core cybersecurity discipline focused on ensuring that the right individuals have access to the right resources at the right time, while preventing unauthorized access.<br>
<br>
Organizations rely on IAM systems to manage employee identities, control permissions, and enforce security policies across cloud services, applications, and internal infrastructures.  Microsoft Entra ID is a cloud-based identity service that allows organizations to centrally manage user accounts, authentication, and authorization.<br>
<br>
<img width="957" height="543" alt="Screenshot 2026-03-13 at 1 58 56 PM" src="https://github.com/user-attachments/assets/e788eaf1-92cb-40f2-9dca-5c23344531ef" />


<h2>Objective</h2>
The objective was to simulate a small organization's identity environment by creating 40 users, organizing them into 5 groups based on departments, and demonstrating how identities are managed within a cloud directory service.  This project also highlights security concepts such as user provisioning, role-based access controls (RBAC), least privilege access, and identity lifecycle management.

<h2>Technologies Used</h2>
- Microsoft Entra ID<br>
- Microsoft Azure Portal<br>
- Administrative access to the Entra ID portal<br>
<br>
The Entra ID tenant acts as the central identity directory where user accounts, groups, and access permissions are stored and managed.

<h2>IAM Concepts Demonstrated</h2>
<img width="957" height="543" alt="Screenshot 2026-03-13 at 2 00 40 PM" src="https://github.com/user-attachments/assets/82115141-2806-4f0d-8a6c-40c681eca31b" />
<br>

<h2>User Provisioning</h2>
Step 1 - Create Users<br>
<br>
<img width="763" height="427" alt="Screenshot 2026-03-17 at 2 09 05 PM" src="https://github.com/user-attachments/assets/b1fbed3f-ff77-41d7-aaef-4e1943e4c2ba" />
<br>
The first step demonstrates user provisioning, which is the process of creating and managing digital identities within an organization.<br>
<br>
<br>
User provisioning ensures that:<br>
- New employees receive accounts when they join the company<br>
- Access to systems can be assigned appropriately<br>
- Identity information is stored securely in a central directory
<br>
Forty user accourns were created across multiple departments that represent employees within a fictional organization.<br>
<br>Department Structure:<br>
- 5 Users - Human Resources<br>
- 6 Users - Accounting<br>
- 8 Users - IT<br>
- 10 Users - Engineering<br>
- 6 Users - Sales<br>
- 5 Users - Contractors<br>
<br>
Each User account represents an individual employee that would normally exist within a company's directory system.
<br>
<img width="597" height="584" alt="Screenshot 2026-03-13 at 6 15 12 PM" src="https://github.com/user-attachments/assets/95f93259-6127-4566-bfe9-02eb9086789f" />
<br>
<br>
Step 2 - Add Users to Tenant<br>
<br>
<img width="763" height="427" alt="Screenshot 2026-03-17 at 2 10 17 PM" src="https://github.com/user-attachments/assets/906af539-278e-4bb9-b3dd-ce2c58fbc49f" />
A tenant is a dedicated instance of Microsoft Entra ID that represents a single organization.  It acts as the central identity container where all users, groups, applications, and security policies are stored.  Instead of creating accounts individually across multiple systems, administrators manage all identities from one secure platform.
<br>
This centralization improves:
- Visibilitiy
- Security monitoring
- Access control
- Identity governance

When users are added to a tenant, they become recognized identities within that organizations directory.<br>

Users were added to the tenant through the Entra ID portal by creating them directly within the tenant directory.

Once added, the users could:
- Sign in to organizational systems
- Be assigned to groups
- Receive permissions to applications and services
<br>
<img width="858" height="483" alt="Screenshot 2026-03-17 at 2 10 34 PM" src="https://github.com/user-attachments/assets/a0c49e91-b957-4527-9fcf-440bdb409670" />

<img width="762" height="268" alt="Screenshot 2026-03-17 at 2 10 46 PM" src="https://github.com/user-attachments/assets/d2aab789-02e3-4955-98a4-d88611c53d72" />

<img width="799" height="482" alt="Screenshot 2026-03-17 at 2 10 57 PM" src="https://github.com/user-attachments/assets/54b49bad-4e37-49ab-91ba-6413670b07b3" />
<br>

<img width="571" height="459" alt="Screenshot 2026-03-17 at 2 11 13 PM" src="https://github.com/user-attachments/assets/4ff53b94-a10f-46c5-b73a-d225c0b5de02" />

<img width="623" height="332" alt="Screenshot 2026-03-17 at 2 11 31 PM" src="https://github.com/user-attachments/assets/b5886d95-8736-45f9-843b-e8fd70f23f47" />

<img width="854" height="480" alt="Screenshot 2026-03-17 at 2 11 47 PM" src="https://github.com/user-attachments/assets/34d18a7a-4350-43f9-a036-fa1ed8e70cd2" />

<img width="854" height="480" alt="Screenshot 2026-03-17 at 2 11 52 PM" src="https://github.com/user-attachments/assets/52947f5a-f3de-411a-91a5-d99f82a6096a" />

<img width="854" height="480" alt="Screenshot 2026-03-17 at 2 11 56 PM" src="https://github.com/user-attachments/assets/7176e93c-31f8-44a1-8579-a11c53913368" />

<img width="735" height="315" alt="Screenshot 2026-03-17 at 2 12 09 PM" src="https://github.com/user-attachments/assets/b06a1337-0b83-419f-bca0-f059a23cf0f0" />

<img width="591" height="412" alt="Screenshot 2026-03-17 at 2 12 25 PM" src="https://github.com/user-attachments/assets/5f0aa9a8-cb23-4338-869a-e5c922138f3a" />

<img width="670" height="281" alt="Screenshot 2026-03-17 at 2 12 34 PM" src="https://github.com/user-attachments/assets/f84c69c7-a31c-4734-ade6-1124a36ede2d" />

<img width="851" height="484" alt="Screenshot 2026-03-17 at 2 12 49 PM" src="https://github.com/user-attachments/assets/9054f5a8-6466-49a2-9f54-e53c00ed4b16" />

<img width="851" height="484" alt="Screenshot 2026-03-17 at 2 12 53 PM" src="https://github.com/user-attachments/assets/ebea8a3c-c31c-4a90-8c85-2e9cf117a33f" />

<img width="851" height="484" alt="Screenshot 2026-03-17 at 2 12 57 PM" src="https://github.com/user-attachments/assets/2c5282f7-a346-4020-ac9a-84e48afd329b" />

<img width="851" height="484" alt="Screenshot 2026-03-17 at 2 13 02 PM" src="https://github.com/user-attachments/assets/3d740711-ad56-493c-a6b0-5ba6041aa063" />

<img width="851" height="484" alt="Screenshot 2026-03-17 at 2 13 06 PM" src="https://github.com/user-attachments/assets/776effed-c829-4412-b4f7-ba506376d38d" />

<img width="851" height="484" alt="Screenshot 2026-03-17 at 2 13 09 PM" src="https://github.com/user-attachments/assets/06c973a8-f81e-4ca3-97e9-9734b32d25b7" />

<img width="851" height="484" alt="Screenshot 2026-03-17 at 2 13 13 PM" src="https://github.com/user-attachments/assets/cc582dba-a38d-4af3-9a08-be4063a7f378" />


<h2>Group-Based Access Controls</h2>




<h2>Role-Based Access Controls (RBAC)</h2>



<h2>Joiner-Mover-Leaver (JML) Lifecycle</h2>




<h2>Single Sign-On Integration</h2>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
