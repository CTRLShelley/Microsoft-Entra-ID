👥 Identity and Access Management 👥

<h1>Microsoft Entra ID</h1>

<img width="858" height="489" alt="Screenshot 2026-03-13 at 1 38 58 PM" src="https://github.com/user-attachments/assets/40a5db39-5a25-4bb9-a80b-c06be37a2020" />


<h2>Overview</h2>
This project demonstrates core Identity and Access Management (IAM) concepts using Microsoft Entra ID. The objective was to simulate a small organization's identity environment by provisioning users, creating departmental security groups, implementing role-based access control (RBAC), and applying authentication and access policies.  This environment models how organizations manage identities, control access to resources, and enforce security policies in a cloud-based identity platform.

<h2>Technologies Used</h2>
- Microsoft Entra ID<br>
- Microsoft Azure Portal<br>
- Conditional Access Policies<br>
- Multi-Factor Authentication (MFA)

<h2>IAM Concepts Demonstrated</h2>
<b>Identity Provisioning</b><br>
 - Creation and management of user identities within an organization.<br>
<br>
<b>Group-Based Access Control</b><br>
 - Users were assigned to security groups based on their department. Permissions were assigned to groups rather than individuals.<br>
<br>
<b>Role-Based Access Control (RBAC)</b><br>
 - Administrative roles were assigned to groups to manage privileges in a structured and scalable manner.<br>
<br>
<b>Least Privilege Access</b><br>
 - Users only receive permissions required for their role and nothing more.<br>
<br>
<b>Joiner-Mover-Leaver Lifecycle</b><br>
 - A simulation of employees onboarding, department transfers, and offboarding to demonstrate the identity lifecycle management.<br>
<br>
<b>Multi-Factor Authentication (MFA)</b><br>
 - MFA was implemented to strengthen authentication security.<br>
<br>
<b>Conditional Access Policies</b><br>
 - Access policies were configured to require MFA for specific user groups when accessing cloud applications.<br>


<h2>Security Controls Implemented</h2>
- Group-Based Access Control<br>
- Role-Based Access Control<br>
- Multi-Factor Authentication<br>
- Conditional Access Policies<br>
- Identity Lifecycle Management<br>

<h2>Departmental Security Groups</h2>
Six security groups were created to simulate organizational departments:<br>
<br>
1. HR<br>
2. Accounting<br>
3. IT<br>
4. Engineering<br>
5. Sales<br>
6. Contractors<br>

<h2>User Provisioning</h2>
Forty users were created to simulate employees within the organization.  These identities represent employee accounts that would normally access company resources such as email, internal systems, and SaaS (software-as-a-service) applications.<br>
<br>
<img width="544" height="534" alt="Screenshot 2026-03-13 at 1 48 05 PM" src="https://github.com/user-attachments/assets/0a67d45a-078a-4e5e-b4f1-3e4de17afa66" />




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
