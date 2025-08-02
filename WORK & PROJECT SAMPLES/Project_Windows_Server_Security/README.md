Windows Server Security & Infrastructure Deployment – Contoso Pharmaceuticals Simulation

This project was designed to simulate the real-world deployment and configuration of a secure Windows Server infrastructure for a fictional global company, Contoso Pharmaceuticals. The focus was on implementing critical services and security configurations to protect sensitive data in a distributed environment.

Project Summary

As part of a hands-on exercise in enterprise server management, I took on the role of a systems administrator responsible for deploying, securing, and managing key Windows Server roles and services. The setup was designed to meet the needs of a large organization with multiple office locations.

⸻

What I Did
    1.    Deployed a Windows Server Core Domain Controller
Set up a new domain named worlanyo.local using Windows Server Core, reinforcing security best practices by using a minimal interface and command-line tools.
    2.    Enforced Password Policies with Group Policy
Used Group Policy Management to enforce a domain-wide password expiration policy, requiring users to change their passwords every 30 days.
    3.    Installed and Configured DHCP Server
Set up a DHCP server and created four custom DHCP scopes:
    •    Worlanyo-TorontoLab
    •    Worlanyo-TorontoOffice
    •    Worlanyo-MontrealLab
    •    Worlanyo-MontrealOffice
Each scope used a unique IP range tailored to simulate realistic network segmentation.
    4.    Created Advanced DHCP Features
    •    Configured a superscope called Worlanyo-Superscope for the Montreal subnets.
    •    Set up a multicast scope named Worlanyo-Multicast-Scope.
    •    Reserved an IP address for a specific client device using MAC address mapping.
    •    Configured common DHCP options such as default gateway, DNS, and lease duration.
    5.    Configured DNS Forwarding
Modified the DNS server on the domain controller to forward all unresolved external DNS queries to Google’s public DNS (8.8.8.8), improving name resolution efficiency.
    6.    Created a Storage Pool and Virtual Disk
Used Windows Server storage management tools to create a storage pool and then provisioned a virtual disk on it to simulate enterprise storage allocation.
    7.    Set Up iSCSI Target and Client
    •    Configured an iSCSI target on Server 2.
    •    Connected and attached the iSCSI virtual disk to Server 3, demonstrating centralized storage access in a multi-server environment.
    8.    Installed Hyper-V and Deployed VMs
    •    Installed the Hyper-V role on Server 2 and created a new virtual machine.
    •    Also installed Hyper-V on Server 3 and set up Hyper-V Replica for VM replication, showcasing disaster recovery readiness.
    9.    Deployed Windows Deployment Services (WDS)
Installed and configured WDS on the network to allow automated deployment of operating systems.
Used Group Policy to enforce WDS client behavior, including the removal of the “Pause” option during installation workflows.

⸻

Skills Demonstrated
    •    Windows Server Core domain setup
    •    Group Policy Management
    •    DHCP and DNS Server configuration
    •    Storage virtualization (iSCSI, Storage Pools)
    •    Hyper-V deployment and replication
    •    Windows Deployment Services (WDS) automation
    •    Enterprise network simulation with multiple locations