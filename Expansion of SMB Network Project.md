## Expansion of SMB Network Project

### Project Update Overview

As part of our ongoing efforts to enhance the functionality and accessibility of our SMB network within the virtual environment, we've successfully added an Ubuntu server to our workspace. This new addition is geared towards hosting DokuWiki, an open-source wiki software that facilitates documentation and collaboration. Furthermore, we've implemented a Virtual IP (VIP) for the public side of the webserver on our firewall. These steps are pivotal in augmenting our network's capabilities and ensuring secure, external access to our resources.

### Recent Additions and Configurations
#### Ubuntu Server Integration
- **Ubuntu Server Setup**: Introduced an Ubuntu server into our network infrastructure, selecting it for its reliability and versatility in hosting applications.
- **DokuWiki Installation and Configuration**: Deployed DokuWiki on the Ubuntu server. This platform will serve as a centralized repository for our project documentation, allowing for easy access and collaboration among team members.
  
![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/c3ca86f7-3141-4e5d-ae11-802f0d27d818)
![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/7511346c-9ee0-4e9c-8327-78855187876c)

### Webserver Accessibility Enhancement
- **Virtual IP (VIP) Setup**: Configured a VIP on the firewall for the webserver. This setup is critical for securely exposing the webserver to the public internet, enabling controlled access to our DokuWiki installation from external networks.
Technical Details
- **Firewall Configuration**: Adjustments were made to the FortiNet firewall to allocate a VIP, directing specific external traffic to the internal webserver hosting DokuWiki. This ensures that external access is streamlined and secure.
- **Security Measures**: Additional security measures were taken during the configuration of the Ubuntu server and DokuWiki installation. This includes setting up firewalls, applying the principle of least privilege to user accounts, and regularly updating software to mitigate vulnerabilities.

![image](https://github.com/sannicJP/Pen-Test-Project/assets/161343927/31b39552-365d-44d3-92a1-097b479b5465)
  
### Collaboration and Skills Enhancement
This phase of the project provided an excellent opportunity for the team to delve into advanced network configurations, server management, and application hosting. Collaboratively, we navigated the complexities of configuring secure access to network resources from the internet, reinforcing our commitment to learning and applying cybersecurity best practices.

### Conclusion
The addition of an Ubuntu server hosting DokuWiki, coupled with the setup of a VIP for the webserver, marks a significant milestone in our SMB network project. These enhancements not only broaden the network's capabilities but also improve accessibility and security. As we move forward, we will continue to refine our network setup, explore new technologies, and implement features that support the dynamic needs of a small/medium business environment.
