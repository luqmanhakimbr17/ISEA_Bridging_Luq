# ISEA_Bridging_Luq

1. Linux Installation

<img width="300" height="250" alt="Screenshot 2025-11-16 171259" src="https://github.com/user-attachments/assets/c0916352-5390-4fc0-90a8-cd520315b507" />

2. Total Cost of Ownership

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


 

 

 

 

MU BRG-ISEA: Introduction to Server Environments and Architectures 

Reflective Learning Journal 

 

 

 

 


Introduction: 

This journal documents my practical learning journey throughout the bridging module. The objective was to transition from theoretical concepts to hands-on proficiency in managing server infrastructures, spanning from local virtualized environments to cloud-based deployments. This reflection will detail my discovery process, problem-solving approaches, tools utilised, and the insights gained from each lab and the relevance to contemporary IT roles. 

Installing a Linux Environment on Your PC 

The first step involved setting up a Linux environment using VMware Workstation Pro. The process required downloading the VMware Workstation Pro, Ubuntu 22.04.3 LTS iso disc image file, creation of a new virtual machine and configuring the virtual machine parameters such as RAM, CPU cores, and disk size. 

  

This lab introduced the systemd service manager, the default in modern Ubuntu systems. This underscores the importance of persistent service configuration in maintaining reliable uptime, a critical concern for any system administrator responsible for production systems. 

 

 

 

 

 

 

 

 

 

Difference when apache2 is installed is port 80 being used/allowed, however earlier commands have port 80 allowed, hence, shows no difference. 

 

 

 

 

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

Total Cost of Ownership (TCO) in Printers 

Based on TCO which printer is the “best”? 

For determining which printer is "best" based on TCO, the answer depends significantly on the usage context. Traditional inkjet printers typically have lower initial costs but higher ongoing expenses for consumables. Laser printers involve greater upfront investment but usually offer lower long-term operational costs. The most economical choice emerges from analyzing the total expenses over the intended usage period rather than simply comparing purchase prices. 

Would your answer be the same for a home user who prints 5 pages per week? 

When considering a home user with minimal printing needs, the TCO comparison shifts considerably. For someone printing only occasionally, the lower initial cost of basic printers might outweigh the long-term savings of more efficient models. The specific usage pattern and volume requirements are crucial factors that can change which option proves most cost-effective. 

What other factors could/should we have considered apart from the TCO? 

Beyond direct financial considerations, several non-monetary factors deserve attention. Print quality requirements, speed needs, reliability, and environmental impact all influence the suitability of different printer types. For document-intensive environments, durability and maintenance requirements become significant, while for creative work, color accuracy and media compatibility may take priority. 

Knowing something about the cost structure of printers, what would you look for in a large workgroup printer? 

For workgroup printers serving multiple users, different considerations come into play. High-volume capabilities, network integration, and robust construction become more important than for individual use. The ability to handle heavy usage patterns while maintaining performance and minimizing downtime becomes a key differentiator. 

What is the time period where both printers will cost the same? 

The point where different printers reach cost parity depends on their specific cost structures and usage patterns. This breakeven analysis helps determine when the long-term savings of a more expensive model offset its higher initial price, which varies based on individual circumstances and printing habits. 

7. Provisioning and Securing a Cloud VM (AWS EC2) 

Unable to attempt as I do not access to AWS. 

Reading was done and this is what i have learnt. Provisioning a cloud VM involves selecting an appropriate instance type, operating system image, and region. A critical security practice is the configuration of security groups, which act as a built-in firewall. The use of key pairs for SSH authentication, rather than passwords, is a fundamental security measure in the cloud. The core concepts of provisioning and securing a server are consistent across platforms, even if the specific management interface differs. This is a fundamental skill for cloud administration. 

8. Writing Bash Scripts and Using Regular Expressions 

Automation is a cornerstone of efficient IT operations. In this lab, I wrote bash scripts to automate routine tasks, such as a script that updates the system packages and checks disk space. Understanding scripting and regex is what separates a junior administrator from a senior one, enabling the automation of complex deployment and monitoring tasks, a core principle of DevOps. 

 

 

 

 

 

 

 

 

 

 

 

Why do we use the shebang (#!/bin/bash) at the beginning of scripts? 

The shebang (#!/bin/bash) serves as an interpreter directive that tells the system which program should be used to execute the script. When you run an executable script, the operating system reads the first line starting with #! and uses the specified interpreter to run the rest of the script. This is important because it ensures the script runs with the correct interpreter bash vs. sh vs. python, etc., it allows the script to be executed directly without specifying the interpreter and makes the script more portable and self-documenting. 

 

9. Configuring DNS and Testing Domain Resolution  

The Domain Name System (DNS) is fundamentally the phonebook of the internet. It translates human-friendly domain names (like www.example.com) into machine-readable IP addresses (like 192.0.2.1) that computers use to identify each other on the network. Without DNS, we would have to memorize complex numerical IP addresses for every website we wish to visit. Configuring DNS involves creating records that map domain names to IP addresses. Understanding DNS is crucial because it is the directory of the internet; misconfiguration can render services inaccessible. This skill is vital for network and web service management. 

Domain Resolution Process: This is the sequence of steps taken to translate a domain name into an IP address. It often involves querying multiple servers: 

The user's computer first checks its local cache. 

If not found, it queries a Recursive Resolver (usually provided by the ISP or a service like Google DNS). 

The resolver then queries the Root Nameserver, which directs it to the Top-Level Domain (TLD) nameserver (e.g., for .com). 

The TLD server points to the Authoritative Nameserver for the specific domain, which holds the actual DNS records and returns the final IP address. 

 

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

 
