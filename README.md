<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>


# osTicket - Post-Install Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.


# Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)


# Operating Systems Used
- Windows 10 (21H2)


# Post-Install Configuration Objectives
- Configure Roles, Departments, and Teams
- Configure Agents and Users
- Configure SLA
- Configure Help Topics


# Configuration Steps
![image](https://github.com/Domenick-Ranfone/post-install-config/assets/138722554/f2a6face-b2a3-485a-88a3-666fdca26439)

In this image, I configured Roles, Departments, and Teams to being our workflow. After createing these roles, I updated Agents and Users to have the corresponding permissions on their profiles.



![image](https://github.com/Domenick-Ranfone/post-install-config/assets/138722554/d4927e87-6110-44b4-8e9c-bbe5f6b54a70)
![image](https://github.com/Domenick-Ranfone/post-install-config/assets/138722554/340b4289-6271-4961-a38a-e2a6c8f706c0)

In this portion, I reviewed and configured the SLA expectation by using the tiers below:
- SEV-1 (1 hour, 24/7)
- SEV-2 (4 hours, 24/7)
- SEV-3 (8 hours, business hours)



![image](https://github.com/Domenick-Ranfone/post-install-config/assets/138722554/03bb99bd-1fbe-4cac-83cb-24979b902e34)
![image](https://github.com/Domenick-Ranfone/post-install-config/assets/138722554/1aa54edf-196a-4807-b891-2da8c51be714)

Finally, I updated the Help topics to ensure we had a baseline to help users with FAQ. These topics are the following:
- Business Critical Outage
- Password Reset
- Personal Computer Issues
