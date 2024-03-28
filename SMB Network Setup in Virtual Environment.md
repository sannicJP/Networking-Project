# SMB Network Setup in Virtual Environment

## Project Overview

This project involves configuring a secure, scalable network for a small/medium business (SMB) in a virtual environment, utilizing GNS3 (Graphical Network Simulator-3) for the network simulation. Our team collaboratively worked on establishing the foundational network infrastructure within GNS3, ensuring a balance between security and functionality. The use of GNS3 allowed for a realistic and flexible simulation environment where we could design, configure, and test the network setup accurately. Below is a summary of the components added and configured as part of our virtual lab workspace.

## Network Components and Configuration

### Initial Setup

- **FortiNet Firewall**: Serves as the core of our network security strategy, providing robust protections against various threats.
- **Ethernet Switches**: (x2): Facilitates communication between devices in our network, allowing for data packets to travel efficiently.
- **Win10 Workstation**: A client machine added to the network to simulate end-user interaction within the SMB environment.
  
![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/22b15aa1-4029-4413-89a4-639986a03d8b)


## Configuration Steps

- **FortiNet Firewall Configuration**:
  - Accessed the firewall's Command Line Interface (CLI) via the console interface.
  - Configured the Local Area Network (LAN) settings to establish a secure internal network environment.

![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/d00288f6-4f90-433d-b6b9-505359398503)

- **Adding the Win10 Workstation**:
  - Integrated a Windows 10 workstation into the LAN, ensuring it adheres to our network's security policies and connectivity standards.
- **Firewall GUI Access**:
  - Established a connection to the FortiNet firewall's Graphical User Interface (GUI) from the Windows 10 workstation.
  - This step enabled us to manage and monitor the firewall settings more intuitively, facilitating easier adjustments and ongoing maintenance.

![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/53563604-5ee2-4191-8f1b-fbab41df1875)
![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/85c7cbd3-5cc5-4135-bb59-9d0e54e01f9e)
![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/711e38f9-01b8-416c-9ec5-bdbb3567182b)
    
## Collaboration and Learning

Working on this project has been a highly collaborative and enriching experience for our team. Each member brought unique insights and expertise, contributing to the successful setup of our SMB network in a virtual environment. Through hands-on experience and shared challenges, we've gained valuable knowledge in network configuration, security best practices, and effective team collaboration.

## Conclusion
The configuration of our SMB network infrastructure lays the groundwork for a secure and efficient virtual environment tailored to the needs of small to medium-sized businesses. As we continue to expand and refine our network, we remain committed to applying best practices in cybersecurity and network administration to support the goals and operations of an SMB.
