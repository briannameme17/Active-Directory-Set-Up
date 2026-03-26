# Active Directory Setup in Microsoft Azure  
**Domain Controller (DC-1) + Client VM (Client-1)**  

## Overview  
This project demonstrates how to deploy a basic Active Directory environment in Microsoft Azure by creating a Domain Controller (DC-1) using Windows Server 2025 Datacenter and a client machine (Client-1). The setup includes configuring networking, assigning a static IP, installing Active Directory Domain Services, and validating connectivity between systems.  

## Steps Taken  

1. Created a Resource Group and Virtual Network in Microsoft Azure to organize and connect all resources  

![Resource Group](images/Resource%20Group.png)

2. Deployed a Virtual Machine named **DC-1** using Windows Server 2025 Datacenter and configured the server settings  

![VM Setup](images/VM.png)  
![Server Configuration](images/Server.png)

3. Set the Domain Controller’s private IP address to static to ensure reliable communication and DNS functionality  

![Static IP](images/Static.png)

4. Installed Active Directory Domain Services and promoted DC-1 to a Domain Controller by creating a new domain  

![Domain Controller Setup](images/domain%20controller%20install.png)

5. Created a Client VM (Client-1), connected it to the same network, configured DNS, and verified communication between both machines  


---

- Validated communication between systems  

---
