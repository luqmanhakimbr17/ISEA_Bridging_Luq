# ISEA_Bridging_Luq

1. Linux Installation

Installation and running of the virtual machine was successful and ran smoothly

<img width="300" height="250" alt="Screenshot 2025-11-16 171259" src="https://github.com/user-attachments/assets/c0916352-5390-4fc0-90a8-cd520315b507" />

<img width="300" height="250" alt="Screenshot 2025-11-16 171438" src="https://github.com/user-attachments/assets/8aca6d2a-8928-4e9f-9886-1513325fcb0e" />






 

 

 

Some useful and frequent commands used were: 

Sudo – superuser do, written at the start of a command to run it as the root user. Some users do not have access to run certain commands 

Ip a – Shows IP address 

Nano – text editor for files 

Cat – displays file in the terminal 

 

Understanding and Applying Linux Permissions 

Linux permissions, based on the concepts of Read, Write, and Execute for Owner, Group, and Others, are fundamental to multi-user system security. This lab demonstrated that incorrect permissions can lead to severe security vulnerabilities (e.g., a world-writable system file) or application failures. This knowledge is indispensable for security hardening and is a daily consideration for system administrators and security analysts. 

Searching and Navigating the Linux File System 

The find and grep commands were explored for efficient file system navigation and content searching.  

 

These tools are critical for troubleshooting and log analysis, allowing administrators to quickly pinpoint issues without manually inspecting numerous files. This skill directly translates to roles in technical support and DevOps, where rapid problem identification is key. 

# 6. Total Cost of Ownership

Printer A – Inkjet
Purchase cost: $120
Ink cartridge cost: $25
Pages per cartridge: 200 pages
Cost per page: $0.125

Printer B – Laser
Purchase cost: $300
Toner cost: $80
Pages per toner: 2,000 pages
Cost per page: $0.04

We assume a typical office prints 500 pages per month.

Over Three Years Comparison:

| Cost Component            | Inkjet (Printer A)       | Laser (Printer B)       |
| ------------------------- | ------------------------ | ----------------------- |
|   Upfront cost            | $120                     | $300                    |
|   Monthly print volume    | 500 pages                | 500 pages               |
|   Cost per page           | $0.125                   | $0.04                   |
|   Monthly running cost    | 500 × 0.125 =   $62.50   | 500 × 0.04 =   $20.00   |
|   Yearly operating cost   | $750                     | $240                    |
|   3-year operating cost   | $2,250                   | $720                    |
|   3-year TCO              |   $2,370                 |   $1,020                |

The laser printer has a much lower TCO over 3 years:
Inkjet TCO: $2,370
Laser TCO: $1,020

Even though the laser printer costs more upfront, its lower cost per page results in significant long-term savings.
Therefore, a laser printer is clearly the “best” choice based on TCO. For low printing volume, Inkjet printer is the better choice

Beyond cost, several critical factors affect printer selection:
Print quality (text vs photo printing)
Inkjet: better for photos
Laser: better for office documents

Print speed
Laser printers are significantly faster.

Reliability and duty cycle
Work environments require robust printers capable of high monthly page volumes.

Maintenance and downtime
Laser printers generally require less frequent maintenance
Ink may dry out in low-usage scenarios

Energy consumption
Laser printers use more power when heating toner drums.

Environmental impact
Cartridge recycling
Waste toner
Energy use

Network connectivity
Important for workgroups or shared office environments.

These factors may outweigh pure cost in certain use cases.


# 7. Provisioning and Securing a Cloud VM (Azure)

Creating a Cloud VM using Azure CLI.

Reading was done and this is what i have learnt. Provisioning a cloud VM involves selecting an appropriate instance type, operating system image, and region. A critical security practice is the configuration of security groups, which act as a built-in firewall. The use of key pairs for SSH authentication, rather than passwords, is a fundamental security measure in the cloud. The core concepts of provisioning and securing a server are consistent across platforms, even if the specific management interface differs. This is a fundamental skill for cloud administration. 

SSH using Azure CLI

<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/8ea656d7-4eb2-4c54-b51c-af0077c5940b" />

<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/455f59ed-bac0-43c4-a7c1-f4b6c9af2bb8" />

<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/37f7e7ed-f8e3-4792-9f00-13d57351488b" />

<img width="350" height="300" alt="image" src="https://github.com/user-attachments/assets/13c83a77-9264-418b-96e1-79fd49df086b" />

8. Writing Bash Scripts and Using Regular Expressions 

Automation is a cornerstone of efficient IT operations. In this lab, I wrote bash scripts to automate routine tasks, such as a script that updates the system packages and checks disk space. Understanding scripting and regex is what separates a junior administrator from a senior one, enabling the automation of complex deployment and monitoring tasks, a core principle of DevOps. 

<img width="350" height="300" alt="Screenshot 2025-11-16 015142" src="https://github.com/user-attachments/assets/a3dd45cc-7f14-46f7-9a4f-1ddc9cd7c2b7" />
<img width="350" height="300" alt="Screenshot 2025-11-16 015335" src="https://github.com/user-attachments/assets/e2784dda-2974-4cbe-b4e5-41b4d00b2fd9" />
<img width="350" height="300" alt="Screenshot 2025-11-16 015403" src="https://github.com/user-attachments/assets/cc717d53-865c-45a9-87dc-4459ff9e6f2a" />
<img width="350" height="300" alt="Screenshot 2025-11-16 015547" src="https://github.com/user-attachments/assets/0419a2c8-e695-4645-b97d-c69984a26fec" />
<img width="350" height="300" alt="Screenshot 2025-11-16 015719" src="https://github.com/user-attachments/assets/82bea4ab-9d89-474a-928a-5557892d4497" />
<img width="350" height="300" alt="Screenshot 2025-11-16 015755" src="https://github.com/user-attachments/assets/e60a3011-b4de-44b2-80f7-29c79fe62bc1" />
<img width="350" height="300" alt="Screenshot 2025-11-16 021956" src="https://github.com/user-attachments/assets/d58f1dbc-b329-47f9-b0de-135becd05e81" />
<img width="350" height="300" alt="Screenshot 2025-11-16 022101" src="https://github.com/user-attachments/assets/aa519288-ec59-4733-880f-939d188f4c20" />
<img width="350" height="300" alt="Screenshot 2025-11-16 022459" src="https://github.com/user-attachments/assets/39628604-46b8-4d22-98e2-b8e4381a7417" />
<img width="350" height="300" alt="Screenshot 2025-11-16 022601" src="https://github.com/user-attachments/assets/804dc279-bf02-4d57-adb2-5faaae961701" />

Why do we use the shebang (#!/bin/bash) at the beginning of scripts? 

The shebang (#!/bin/bash) serves as an interpreter directive that tells the system which program should be used to execute the script. When you run an executable script, the operating system reads the first line starting with #! and uses the specified interpreter to run the rest of the script. This is important because it ensures the script runs with the correct interpreter bash vs. sh vs. python, etc., it allows the script to be executed directly without specifying the interpreter and makes the script more portable and self-documenting. 

 

9. Configuring DNS and Testing Domain Resolution  

The Domain Name System (DNS) is fundamentally the phonebook of the internet. It translates human-friendly domain names (like www.example.com) into machine-readable IP addresses (like 192.0.2.1) that computers use to identify each other on the network. Without DNS, we would have to memorize complex numerical IP addresses for every website we wish to visit. Configuring DNS involves creating records that map domain names to IP addresses. Understanding DNS is crucial because it is the directory of the internet; misconfiguration can render services inaccessible. This skill is vital for network and web service management. 

Domain Resolution Process: This is the sequence of steps taken to translate a domain name into an IP address. It often involves querying multiple servers: 

The user's computer first checks its local cache. 

If not found, it queries a Recursive Resolver (usually provided by the ISP or a service like Google DNS). 

The resolver then queries the Root Nameserver, which directs it to the Top-Level Domain (TLD) nameserver (e.g., for .com). 

The TLD server points to the Authoritative Nameserver for the specific domain, which holds the actual DNS records and returns the final IP address. 

<img width="2738" height="898" alt="image" src="https://github.com/user-attachments/assets/a1e2d423-0c73-4f73-88c8-6eb4d0e5dda9" />


 

10.  Obtaining and Managing Digital Certificates 

SSL (Secure Sockets Layer) and its successor, TLS (Transport Layer Security), are cryptographic protocols designed to provide secure communication over a computer network. They are most commonly recognized as the 'S' in HTTPS, which secures data transferred between a web browser and a server. 

SSL/TLS Certificate: This is a digital certificate that authenticates a website's identity and enables an encrypted connection. It acts as a digital passport, containing key information such as the domain name it is issued for, the person, organization, or device it was issued to, the Certificate Authority (CA) that issued it, the CA's digital signature, associated subdomains and issue date and expiration date. 

11. Scripting Linux Server Functions for Automation 

Building on the earlier bash scripting lab, this involved creating more sophisticated scripts. For example, I developed a script that automated the backup of a website's directory and database to a specified backup directory. [Screenshot of the backup script and its successful execution log] This required error handling and logging. Such automation scripts are the building blocks of Infrastructure as Code (IaC) and Continuous Integration/Continuous Deployment (CI/CD) pipelines, central to modern DevOps practices. 

Why is automating system monitoring beneficial for administrators? 

Automating system monitoring provides several key benefits: 

  

Proactive Problem Detection: Identifies issues before they become critical problems 

Time Efficiency: Eliminates manual checks, saving administrative time 

Consistency: Provides regular, standardized monitoring intervals 

Historical Data: Enables trend analysis and capacity planning 

Rapid Response: Immediate alerts for critical conditions 

Performance Optimization: Identifies bottlenecks and resource hogs 

Capacity Planning: Helps predict when upgrades are needed 

Documentation: Creates audit trails for compliance and analysis 

24/7 Coverage: Continuous monitoring without human intervention 

Resource Optimization: Ensures efficient use of system resource 

 

12. Additional Server Service MariaDB Database Server 

To expand my learning, I selected MariaDB, a popular open-source database server. The installation was straightforward using sudo apt install mariadb-server. [Screenshot of the installation command and successful setup message] The challenge was securing the installation using sudo mysql_secure_installation, which involved setting a root password and removing anonymous users. [Screenshot of the secure installation process] I then created a test database and user, [Screenshot of SQL commands to create a database and user], understanding how databases serve as the backend for most web applications. This experience connects web server administration (Apache/PHP) with data management, a common combination in LAMP/LEMP stacks, and is highly relevant for full-stack developers and system administrators. 

 

 

 

 

 

 

 

 

 

 

Conclusion: 

The intensive BRG-ISEA module provided a holistic, hands-on immersion into server environments. The journey from setting up a local Ubuntu VM to provisioning secure cloud instances and automating tasks highlighted the interconnectivity of modern IT infrastructure. Key takeaways include the critical importance of security hardening, the financial implications of cloud architecture, and the necessity of automation for scalability and reliability. These skills are directly transferable to roles such as System Administrator, Cloud Engineer, and DevOps Practitioner, forming a solid foundation for a career in modern IT operations. 

 
