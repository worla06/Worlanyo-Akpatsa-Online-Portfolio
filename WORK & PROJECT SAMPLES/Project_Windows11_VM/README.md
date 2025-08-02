Windows 11 Virtual Machine Setup and Configuration – Personal Practice Project

This project involved setting up and configuring a Windows 11 virtual environment using VMware Workstation as a part of my hands-on exploration into desktop OS deployment and administrative management.

Project Overview

As part of my learning journey in the Cloud Computing Technologies program at George Brown College, I performed a series of system administration tasks in a Windows 11 VM. These tasks simulate real-world IT workflows, from system setup and policy configuration to PowerShell networking and advanced file management.

What I Did
    1.    Installed Windows 11 in VMware Workstation
Set up a new virtual machine running Windows 11 and named it using a customized naming format for identification.
    2.    Created a Windows Provisioning Package
Built and applied a provisioning package that automatically created a local administrator account named “yourname Admin” with a predefined secure password.
    3.    Modified Local Security Policies
Configured User Account Control (UAC) to enforce dialog prompts and enable dimming of the screen for added security.
    4.    Customized Start Menu and Taskbar
Pinned the Microsoft News app to the Start Menu and exported the taskbar layout for future deployment purposes.
    5.    Configured Static IP with PowerShell
Used PowerShell to manually assign a static IP address (192.168.168.101/24) to the system’s network adapter.
    6.    Created a Resilient Storage Space
Built a 2-way mirrored storage space to ensure redundancy, simulating enterprise-level storage management.
    7.    Created and Secured a File Share Directory
Inside the new storage space, I created a folder named “File Share” and set custom NTFS permissions:
    •    Authenticated Users: Read-only
    •    Administrators: Full Control
    8.    Shared the Folder Over the Network
Configured sharing permissions for the folder:
    •    Everyone: Read
    •    Administrators: Full Control
    9.    Installed a Microsoft Store App
Installed the Microsoft Whiteboard application directly from the Microsoft Store to simulate app deployment.
    10.    Enabled File History
Configured File History on the storage space to retain previous versions of files for up to 30 days.