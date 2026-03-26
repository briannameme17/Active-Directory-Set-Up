# Active Directory Setup in Microsoft Azure  
This project demonstrates how to deploy a basic Active Directory environment in Microsoft Azure by creating a Domain Controller (DC-1) using Windows Server 2025 Datacenter and a client machine (Client-1). The setup includes configuring networking, assigning a static IP, installing Active Directory Domain Services, and validating connectivity between systems.  

## Steps Taken  
1. Created a Resource Group and Virtual Network in Microsoft Azure to organize and connect all resources  
2. Deployed a Virtual Machine named **DC-1** using Windows Server 2025 Datacenter and configured the server settings  
4. Set the Domain Controller’s private IP address to static to ensure reliable communication and DNS functionality  
5. Installed Active Directory Domain Services and promoted DC-1 to a Domain Controller by creating a new domain  
6. Created a Client VM (Client-1), connected it to the same network, configured DNS, and verified communication between both machines  

![Resource Group](images/ResourceGroup.png)
![VM Setup](images/VM.png)  
![Server Configuration](images/Server.png)
![Static IP](images/Static.png)
![Domain Controller Setup](images/domaincontrollerinstall.png)*
---
