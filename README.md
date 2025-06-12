# -Computer-Security-System-Project-1
##MITM Attack using Kali Linux, Ettercap, Metasploitable and DVWA, Windows Machine, Wireshark

#Creating a multi-VM environment using Oracle VirtualBox Manager involves several steps to set up and configure the virtual machines to interact with each other on a secure host-only network. Here are the processes involved in creating the multi-VM environment – 

1.	Installing Oracle VirtualBox Manager: The first step is to download and install Oracle VirtualBox Manager on the host machine. This software allows the user to create and manage virtual machines.

2.	Creating Virtual Machines (VMs): Once VirtualBox is installed, users can create multiple virtual machines. For this scenario, two VMs would be created, one for Kali Linux and another for another operating system like Damn Vulnerable Web Application (DVWA).

3.	Configuring VM Settings: Each VM needs to be configured with appropriate settings such as memory allocation, processor settings, storage, and network settings. In this case, users would configure the VMs to use a host-only network for communication between them.

4.	Installing Kali Linux: Kali Linux would be installed on one of the VMs. Kali Linux is a popular distribution for penetration testing and security auditing. Once installed, users can explore the features and tools provided by Kali Linux for security testing and analysis.

5.	Exploration of Kali Linux: After installation, users can explore the Kali Linux environment, including its pre-installed tools for network scanning, vulnerability assessment, and penetration testing. This might include tools like Nmap for network scanning, Metasploit for exploitation, Wireshark for packet analysis, etc.

6.	Inclusion of Additional Operating System (e.g., DVWA): Optionally, another operating system such as Damn Vulnerable Web Application (DVWA) can be included on the second VM. DVWA is intentionally vulnerable web application used for practicing web application security testing techniques. This provides a target for testing the security tools and techniques available in Kali Linux.

7.	Network Configuration: Ensure that both VMs are configured to use a host-only network in VirtualBox. This allows communication between the VMs while isolating them from the external network, providing a secure testing environment.

8.	Testing and Experimentation: With the VMs configured and running, users can begin testing and experimenting with different security tools and techniques provided by Kali Linux. This might include scanning the DVWA instance for vulnerabilities, exploiting them, and then securing the system.
