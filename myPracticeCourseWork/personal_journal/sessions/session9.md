[Personal Learning Record](../../personal_journal/personal_journal.md) | [Session Notes](../sessions/README.md) 

# Session 9

## Topics covered
*What topics were covered in this session*
During this session, I got to know about OPNsense, which is a firewall and routing system that helps in managing computer networks.


## Personal Notes and research following this session
*Which class sessions and personal research refers to technology in this proposal. Link to examples.*
Installation and configuration of OPNSense through Vagrant and VirtualBox
Knowing the function of a firewall
Configuring WAN and LAN interfaces
Assigning IP address and configuration settings
Using DHCP to get an assigned IP address
Using static IP address on the LAN interface
Checking network connectivity through the Ping utility

## Exercises and results
*What exercises did you complete. What results. Screen shots and notes*
OPNsense is an open-source firewall application which aids in securing networks through the control of inbound and outbound network traffic
I learned that:
The WAN (Wide Area Network) is a link between the firewall and the outside network or internet
- The LAN (Local Area Network) is a link between the firewall and the inside network
- DHCP automatically allocates IP addresses to network devices
- A static IP is where the IP address is manually assigned and remains unchanged
- The Ping utility is used to determine whether a host or server can be reached on the network
It was also discovered that Vagrant can be used to set up and configure virtual machines for networking training purposes.

These are the exercises performed during the present session using Vagrant and VirtualBox in relation to the OPNsense setup.
The exercises carried out include the following:
1. Cloned the OPNsense Vagrant repository from GitHub.
2. Started the virtual machine using vagrant up.
3. Accessed the OPNsense system through the web browser.
4. Completed the initial configuration wizard.
5. Configured the time server and timezone.
6. Configured the WAN interface using DHCP.
7. Configured the LAN interface using a static IP address.
8. Set the root administrator password.
9. Accessed the OPNsense dashboard.
10. Checked the WAN and LAN interface settings.
11. Used the Ping diagnostic tool to test network connectivity.
12. Successfully stopped the virtual machine using vagrant halt

<img width="664" height="273" alt="s9 1" src="https://github.com/user-attachments/assets/c10a2220-481e-484f-a693-aaa6cf9d85da" />
<img width="614" height="556" alt="s9 2" src="https://github.com/user-attachments/assets/1456f4f6-4da8-4851-9a79-eafcb2c8d6e8" />
<img width="1047" height="464" alt="s9 3" src="https://github.com/user-attachments/assets/5d7c18d8-8f0a-45a3-9c39-84375e681f78" />
<img width="1357" height="628" alt="s9 4" src="https://github.com/user-attachments/assets/009d8301-068b-4fb6-bc63-d91bba0a9b5f" />
<img width="1363" height="555" alt="s9 5" src="https://github.com/user-attachments/assets/155c04b7-c5a9-49fd-aa50-f910c83c4f1c" />
<img width="1105" height="342" alt="s9 6" src="https://github.com/user-attachments/assets/31525789-e4a7-46f6-b98c-1105202db464" />


## Summary of learning
*What did you learn through these exercises*
In this lesson, I was able to learn how to set up and configure OPNSense on a virtual machine. I acquired skills on configuring both WAN and LAN interfaces, how to distinguish between DHCP and static IP addresses and the use of the OPNsense dashboard.

In addition, I learned how to use the Ping tool for testing connectivity within a network. This whole exercise helped me learn more about firewalls, network configurations, and network security using OPNsense
