# ⚠️All the Tools are run on the my machine are are directed at my own machine⚠️
# Elevate_Labs_Internship_Task_1
## Task 1 of Elevate Labs Internship



### **Objective:** Learn to discover open ports on devices in your local network to understand network exposure.

## Tools Used
- Wireshark
- nmap

## Open ports found 
    
    PORT     STATE   SERVICE
    53/tcp   open    domain
# ⬇️ Steps performed to complete the Objective ⬇️


- **Step- 1:** Setup Kali Linux VM Lab in VMware Workstation

- **Step- 2:** Opened the Kali VM and then open the terminal and wrote the following command to check my IP

        ip a 

- **Step- 3:** Using nmap in terminal to perform TCP SYN scan and analysing Open ports by running

        nmap -sS <target ip>
  
        example:

        To save the output in a file:

        nmap -sS <target ip> -oN <filename>
        
        

- **Step- 4:**  Open Wireshark and start analyising live traffic and ports


- **Step- 5:** Finally save the wireshark output in a file


- **Step- 6:** Studied Common services running on the ports for example:

    - HTTP (Hypertext Transfer Protocol) - Port 80:

    - NetBIOS/SMB (Server Message Block) - Ports 139, 445:

    - FTP (File Transfer Protocol) - Ports 20, 21:

    - DNS (Domain Name System) - Port 53:

    - SMTP (Simple Mail Transfer Protocol) - Port 25:

- **Step- 7:** Risks of Open ports:

  - Entry Points: Open ports act as potential entry points for attackers to access your system or network.


  - Backdoors: Misconfigured or unprotected ports can create backdoors, allowing unauthorized individuals to bypass firewalls and other security measures.


  - Exposure of Services: Open ports can reveal the services and applications running, which attackers can use to plan further attacks.


  - Weak Credentials: If services listening on open ports use weak or default credentials, attackers can use brute force attacks to gain access


