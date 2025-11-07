# Active-Directory-Home-Lab

# Overview
This project demonstrates my hands-on experience setting up and managing an Active Directory (AD) environment in a virtualized home lab. I designed and deployed a simulated enterprise network with a domain controller, multiple client systems, and integrated security monitoring using Splunk.

Through this project, I strengthened my skills in Windows Server administration, Group Policy management, DNS/DHCP configuration, and user access control — key areas that align with IT Support, Systems Administration, and Cybersecurity roles.

# LAB SETUP/DIAGRAM 

[INSERT LAB SETUP IMAGE]

# Tools & Technologies Used

VirtualBox – for virtualization

Windows Server 2022 – for AD DS, DNS, and DHCP

Windows 10 Pro – as a client machine

Splunk Enterprise – for log monitoring and SIEM simulation

PowerShell – for automation and user management

# Configurations and Setups:

1. Installed VirutalBox along with all VMs.

![image_alt](https://github.com/Darell-Samedy/Active-Directory-Home-Lab/blob/main/vm.jpeg?raw=true)
   

3. Configured Splunk and setup Splunk Enterprise
![image_alt](https://github.com/Darell-Samedy/Active-Directory-Home-Lab/blob/main/Screenshot%202025-11-07%20001658.jpeg?raw=true)
![image_alt](https://github.com/Darell-Samedy/Active-Directory-Home-Lab/blob/main/Screenshot%202025-11-07%20001607.jpeg?raw=true)


5. Configured Windows Server to static IP of 192.168.10.7

6. Installed ADDS within Server Manager and added Users with login credentials
- Darell Samedy
- Larry Junior

![image_alt]()

6. Applied GPOs changes for users within different departments
      - Password Policy

      ![image_alt]()

Please note that this project is intended for educational and demonstration purposes only. All systems are deployed in an isolated lab environment.


