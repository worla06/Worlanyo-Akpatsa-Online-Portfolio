Microsoft 365 Administration & Collaboration Setup – Personal Learning Project

This project was focused on gaining practical experience with the Microsoft 365 admin portals, PowerShell integration, Exchange Online, and SharePoint Online. The objective was to simulate the process of managing an organization’s M365 environment, from user provisioning and branding to collaboration and security configuration.

⸻

Project Summary

As part of my cloud computing coursework, I completed a Microsoft 365 setup and management lab to simulate the real-world responsibilities of an M365 administrator. I used both the graphical admin centers and PowerShell to perform tasks related to user management, branding, email flow, and collaboration using SharePoint and Outlook.

⸻

What I Did

1. Customized the Organization Profile
    •    Uploaded a custom logo to the Microsoft 365 tenant and verified the branding via screenshot.
    •    Changed the color theme to match a custom palette.
    •    Configured the logo as a clickable link redirecting users to a YouTube channel: Ali Ziyaei’s YouTube (https://www.youtube.com/@AliZiyaei).
    •    Added internal Helpdesk contact information for support visibility.
    •    Selected two internal users to join the Targeted Release program so they receive new M365 updates before the general rollout.

2. Used PowerShell to Manage M365
    •    Installed the Microsoft 365 PowerShell module and established a remote session to the tenant.
    •    Created two new users via PowerShell.
    •    Assigned Microsoft 365 licenses to these users using either PowerShell or the M365 Admin Center.

3. Installed and Activated Microsoft 365 Apps
    •    Installed Microsoft 365 Apps for enterprise on a virtual machine.
    •    Logged into the suite using one of the newly created users to activate Office.
    •    Sent an email via Outlook from one user to the other and verified delivery using the Outlook Web App (OWA).

4. Managed Exchange Online Settings
    •    Created a shared mailbox named Worlanyo-Shared and granted both users access.
    •    Created a distribution list called Worlanyo-Dist and added both users as members.
    •    Sent test emails to both the shared mailbox and the distribution list and confirmed receipt in each user’s mailbox.
    •    Captured and documented the configuration settings from the malware protection section of Exchange Online Protection.

5. Configured SharePoint for Internal Collaboration
    •    Displayed the list of active SharePoint sites in the tenant.
    •    Created a new document library site named Worlanyo and added both Task 2 users to the site with permissions.
    •    Modified the OneDrive/SharePoint sharing policy to restrict file sharing to internal users only for improved data security.

⸻

Key Concepts Practiced
    •    Microsoft 365 admin portal configuration
    •    PowerShell scripting for cloud environments
    •    M365 user creation, licensing, and app deployment
    •    Exchange Online mailbox types, malware policy
    •    SharePoint Online and OneDrive sharing security