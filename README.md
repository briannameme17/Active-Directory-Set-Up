# Active Directory Domain Setup in Microsoft Azure  
This project demonstrates how to deploy a basic Active Directory environment in Microsoft Azure by creating a Domain Controller (DC-1) using Windows Server 2025 Datacenter and a client machine (Client-1). The setup includes configuring networking, assigning a static IP, installing Active Directory Domain Services, and validating connectivity between systems.  

## Steps Taken  
1. Created a Resource Group and Virtual Network in Microsoft Azure to organize and connect all resources  
3. Set the Domain Controller’s private IP address to static to ensure reliable communication and DNS functionality  
4. Installed Active Directory Domain Services and promoted DC-1 to a Domain Controller by creating a new domain  

![Resource Group](Images/resource.png)
![VM Setup](Images/VM.png)  
![Virtual Network](Images/vn.png)
![Server Configuration](Images/Server.png)
![Static IP](Images/Static.png)

-

---
