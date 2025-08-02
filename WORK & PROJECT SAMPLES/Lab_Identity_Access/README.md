Lab Project – Identity and Access Management in Microsoft 365

This lab project focused on implementing and managing identity and access in Microsoft 365 using Entra ID (formerly Azure Active Directory). The goal was to simulate the core tasks an M365 administrator would perform to manage users, protect access, and enforce security controls such as Multi-Factor Authentication and Conditional Access.

⸻

Project Summary

In this hands-on activity, I explored Microsoft Entra ID to gain practical experience with identity governance. The tasks covered everything from user and group management to enforcing security policies and managing roles across the organization. These skills are essential in real-world Microsoft 365 environments where protecting identity and securing access to data is a top priority.

⸻

What I Did

1. Entra ID (Azure Active Directory) Setup and Configuration
    •    Navigated to the Microsoft 365 Admin Center and accessed the Entra ID portal.
    •    Created a new user within the directory and added them to a pre-existing group.
    •    Verified the user’s group membership to ensure correct directory configuration.

2. Configured Multi-Factor Authentication (MFA)
    •    Enabled Multi-Factor Authentication for the newly created user.
    •    Set the user’s MFA method to phone-based verification.
    •    Simulated a login attempt and successfully triggered MFA.
    •    Checked the sign-in logs in Azure AD to confirm MFA was required and used during the login process.

3. Created Conditional Access Policies
    •    Accessed the Conditional Access section in Entra’s Protection area.
    •    Created a new policy targeting a specific group of users.
    •    Set a condition to require MFA when accessing a sensitive Microsoft 365 app.
    •    Tested the policy by attempting to access the app as a target user, verifying that the MFA requirement was enforced as expected.

4. Managed Administrative Roles
    •    Assigned a Global Administrator role to a user and verified elevated access rights.
    •    Navigated through the Admin Center to confirm that the user had full control over tenant-wide settings.
    •    Removed the admin role and confirmed that the user’s permissions were reduced accordingly.

⸻

Key Skills Practiced
    •    Microsoft Entra ID (Azure AD) user and group management
    •    Multi-Factor Authentication setup and verification
    •    Conditional Access Policy creation and testing
    •    Role-based access control and privilege management