# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

# Checking the Port using ifconfig:


<img width="747" height="421" alt="Screenshot 2025-09-22 082656" src="https://github.com/user-attachments/assets/c824bb64-bc0f-49f1-b03d-9d70701f5542" />

The ifconfig command is used to display network interface details in Linux systems. In this output, eth0 represents the active Ethernet network interface with the IPv4 address 10.170.96.39 and subnet mask 255.255.255.0. It also shows the MAC address, broadcast address, and IPv6 address of the system. The RX and TX packet information indicates the amount of data received and transmitted through the network. The lo interface represents the loopback or localhost connection with IP address 127.0.0.1, which is used for internal system communication. The output confirms that the network interfaces are active and functioning properly without errors.

# Get into The MsfConsole :

<img width="900" height="427" alt="Screenshot 2025-09-22 082758" src="https://github.com/user-attachments/assets/89f298f1-970b-453f-8775-6252035d6ea7" />

The output shows the successful launch of the msfconsole, which is the command-line interface of the Metasploit Framework used for penetration testing and security analysis. It displays the Metasploit version (v6.4.84-dev) along with the number of exploits, auxiliary modules, payloads, encoders, and evasion tools available in the framework. The ASCII art logo confirms that the framework has started correctly. The message also mentions that Metasploit is an open-source project developed by Rapid7. Finally, the prompt msf > indicates that the console is ready to accept commands for scanning, exploitation, and security testing activities.

# Using Help Command :

<img width="940" height="756" alt="Screenshot 2025-09-22 082847" src="https://github.com/user-attachments/assets/37c07c0f-5c68-4dd9-b719-22006f10cb0e" />

The output shows the result of the help command in the Metasploit Framework (msfconsole). It displays a list of available commands along with their descriptions to assist users in operating the framework. The commands are divided into sections such as Core Commands and Module Commands. Core commands include functions like connect, sessions, set, history, and exit, which are used for navigation and configuration. Module commands help users interact with exploits, payloads, and scanning modules. This help menu acts as a quick reference guide for beginners and security professionals while working in Metasploit.

# Nmap :

<img width="726" height="673" alt="Screenshot 2025-09-22 083659" src="https://github.com/user-attachments/assets/290f2308-5fcf-4df8-9fde-80208af10473" />

The output shows the result of an Nmap TCP SYN scan (-sT) performed on the network range 10.170.96.39/24 through the Metasploit console. Nmap scanned 256 IP addresses and identified 5 active hosts in the network. The scan detected several open ports and services such as 135/msrpc, 139/netbios-ssn, 445/microsoft-ds, 3306/mysql, and 53/domain, which indicate services running on those systems. Some hosts showed filtered or closed ports, meaning the ports are protected by a firewall or not accepting connections. The output also displays MAC addresses and device vendor information for discovered hosts. Overall, the scan helps identify active devices and available network services for security analysis and penetration testing.

# DB_Nmap :
<img width="736" height="475" alt="Screenshot 2025-09-22 091802" src="https://github.com/user-attachments/assets/224bb14b-4efc-480f-afeb-d1c64f19d7ba" />

The output shows the result of the db_nmap command executed inside the Metasploit Framework to scan the network range 192.168.64.39/24. Unlike normal nmap, db_nmap stores the scan results directly into the Metasploit database for later analysis and exploitation. The scan identified 4 active hosts and detected several open ports such as 135/msrpc, 139/netbios-ssn, 445/microsoft-ds, 3306/mysql, and 53/domain. Some systems had filtered or closed ports, indicating firewall protection or inactive services. The output also includes MAC addresses and latency information for each discovered device. This command helps penetration testers efficiently collect and manage network reconnaissance data within Metasploit.


# Viewing the metasploit framework on root:

<img width="732" height="397" alt="Screenshot 2025-09-22 092723" src="https://github.com/user-attachments/assets/cfc69af2-bb31-443d-a1e6-d4eefcdb9515" />






## RESULT :
The Metasploit framework for reconnaissance is  examined successfully
