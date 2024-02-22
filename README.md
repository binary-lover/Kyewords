<h1 align = "center">Cyber Security Keywords</h1>
<p align="center"><img align="center" src = "https://kasi.asia/wp-content/uploads/2022/06/CyberSecurity-iStock-1296650655_1900x600_acf_cropped.jpg"></p>



- **Cybersecurity Careers**
    <p align="center"><img align="center" src = "cybersecurity careers.png"></p>


- **MX record:**
    - A DNS 'mail exchange' (MX) record directs email to a mail server. The MX record indicates how email messages should be routed in accordance with the Simple Mail Transfer Protocol (SMTP, the standard protocol for all email).



- **AXFR:**
  - AXFR (global Asynchronous Transfer Full Range) is a protocol for “zone transfers” for replication of DNS data across multiple DNS servers. Unlike normal DNS queries that require the user to know some DNS information ahead of time, AXFR queries reveal resource records, including subdomain names.


- **Reverse lookup:**
    - In computer networks, a reverse DNS lookup or reverse DNS resolution (rDNS) is the querying technique of the Domain Name System (DNS) to determine the domain name associated with an IP address – the reverse of the usual "forward" DNS lookup of an IP address from a domain name.



- **Brute force:**
    - A brute-force attack is a trial-and-error method used by application programs to decode login information and encryption keys to use them to gain unauthorized access to systems.



- **Subdomain:**
    - A subdomain is a separate part of your website that operates under the same primary domain name.



- **Network Classes:**
    - Class A: 10.0.0.0 to 10.255.255.255
    - Class B: 172.16.0.0 to 172.31.255.255
    - Class C: 192.168.0.0 to 192.168.255.255



- **TCP:**
    - Transmission Control Protocol (TCP) is a standard that defines how to establish and maintain a network conversation by which applications can exchange data.
    - **3 Way Handshake:**
        1. First PC sends a random sequence number and sets SYN flag = 1 (syn = 1 for connection request).
        2. Second PC replies for the sequence with Acknowledgement no (sequence no + 1) and sends ACK no = 1 (1 for confirmation) in reply to the SYN flag and also requests a connection back with SYN flag = 1 to the first PC.
        3. When ACK & SYN and a sequence no are received by the first PC, it replies back in response to SYN with ACK no (sequence + 1) and ACK flag = 1.
        So this is how the 3 Way Handshake Happens In TCP.

    - **TCP Header**
        ![TCP Header](https://media.geeksforgeeks.org/wp-content/uploads/TCPSegmentHeader-1.png)
        - **Sequence Number** – A 32-bit field that holds the sequence number, i.e., the byte number of the first byte that is sent in that particular segment. It is used to reassemble the message at the receiving end of the segments that are received out of order.
        - **Acknowledgement Number** – A 32-bit field that holds the acknowledgment number, i.e., the byte number that the receiver expects to receive next. It is an acknowledgment for the previous bytes being received successfully.
        - **Control flags –** These are 6 1-bit control bits that control connection establishment, connection termination, connection abortion, flow control, mode of transfer, etc. Their function is:
            - URG: Urgent pointer is valid
            - ACK: Acknowledgment number is valid( used in case of cumulative acknowledgment)
            - PSH: Request for push
            - RST: Reset the connection
            - SYN: Synchronize sequence numbers
            - FIN: Terminate the connection



- **Reverse engineering:**
    - The process of taking a piece of software or hardware and analyzing its functions and information flow so that its functionality and behavior can be understood.



- **Bash:**
    - Bourne-again shell, is a command-line shell and scripting language used on Linux, macOS, and other Unix-like operating systems



- **Vulnerability:**
    - A vulnerability is a weakness that can be exploited by cybercriminals to gain unauthorized access to a computer system.



- **Bind Shell vs Reverse shell:**
    - **Bind Shell:**
        - When a vulnerable machine listens for a connection.
    - **Reverse Shell:**
        - When a vulnerable machine tries to connect.



- **Traffic Smuggling**
- **Native Windows API**
- **White-listed Domain Abuse**



- **CAP Theorem:**
    - Consistency, Availability, Partition tolerance
    - It is impossible to distribute a system to simultaneously provide more than two of the three of the guarantees.



- **ASIC:**
    - Application Service Integrated Circuit, used for bitcoin mining.

- **ICMP:**    - Internet Control Message Protocol (ICMP) is a network layer protocol that is used to diagnose communication errors. `ICMP` is used for diagnostics and network management. For example, the `ping` utility uses an `ICMP` request and `ICMP` reply message.


- **Footprinting:**
    - The process of cybersecurity footprinting involves profiling an organization and collecting data about the network, host, employee, and third-party partners, like which OS is used, which services used and its versions, firewall protocols, IPs, DNS.

- **Fuzzing :** - Fuzzing is a technique used to find vulnerabilities in software, operating systems, and networks. It's also known as fuzz testing.
    - **The steps for fuzz testing are**: 
        - Identify the target system
        - Identify inputs
        - Generate fuzzed data
        - Execute the test using fuzzy data

- **Enumeration:**
    - It's nothing but gathering information about the


* **Cyber Security threats**
    - **Malware :** - It's an malicious software intended to harm or exploit any programmable devices, service or network.
    - **Ransomware** - Ransomware is a type of malware that encrypts a victim's files or device and demands a ransom for the decryption key
    - **Social Engineering** - Social engineering is the manipulation of individuals to extract sensitive information. For example, phishing, Emails.
    - **Denial of Service (DoS):** It's a cyber attack aimed at disrupting the normal functioning of a computer system, network, or service by overwhelming it with a flood of illegitimate requests or traffic, making it temporarily or indefinitely unavailable to users. The goal is to exhaust the target's resources, such as bandwidth, processing power, or memory, causing a disruption in services.
    - **DDoS:** (Distributed Denial of Service) attacks involve multiple systems coordinating the attack, making them more potent and challenging to mitigate.



- **Payloads :** - Payload in the context of malware refers to malicious code that causes harm to the targeted victim. Malware payloads can be distributed by methods such as worms and phishing emails. 
  - Payloads can be delivered to your computer through: Email attachments, Malicious websites, USB drives. 
  - Today, malware authors typically encrypt the payload to hide the malicious code from antimalware detection and remediation tools


- **Trojan :** - A Trojan is a type of malware disguised as legitimate software that trick users into loading and executing it on their systems. Once activated, Trojans can enable cyber-criminals to spy on you, steal your sensitive data, and gain backdoor access to your system.



- **Ransomware :** - Ransomware is a type of malware that encrypts a victim's files or device and demands a ransom for the decryption key. 


- **IOC :** - Indicators of Compromise (IOCs) are pieces of forensic data, such as data found in system log entries or files, that identify potentially malicious activity on a system or network.


- **Reconnaissance :** - Reconnaissance is the information-gathering stage of ethical hacking, where you collect data about the target system.


- **Hack Value :** - Perceived value or worth of a targate as seen by the attacker

- **Zero-Day Attack / O day attack :** - An attack that occurs before a vendor is aware of flaw or is able to provide a patch for the flaw.

- **Daisy Chaining / Pivoting :** - Using a sucsessfull attack immediately launch another attack.

- **Doxing :** - publishing personally idenfiable information (PII) about an individual usually with malicious intent.

- **Non-repudiation :** - The inability to deny that you did something, usually accomplished through requirement authentication andd digital signature on documents.

- **Mitigation :** - Any action or control used to minimize Damage in the event of negative event.

- **inetial Access :** - The first step in the cyber kill chain/mitre att&ck, where the attacker gains access to the target system.

- **Parsistence:**: - The ability of malware to survive a reboot.

- **Spear Phishing :** - A phishing attack that is targeted at a specific individual or group.

- **Control :** - Planting a backdoor or other malware on a system to maintain access.

### Hacker Classes

![alt text](hackerClass.png)

* **Testing Types**

    - **White Box :**
        - internal team will perform it, have complete visiblity
        - risk: Teams already familiar with a system will overlook the vulnerabilities
    - **Grey Box :**
        - The tester has some visibility into the system they are testing
    - **Black Box :**
        - No visibility to the tester
        - Most closely resemble actual attack
    

* **SIEM** (Security Information and Event Management)

    - **SIEM** stands for Security Information and Event Management. It is a comprehensive approach to cybersecurity that involves the integration of security information management (SIM) and security event management (SEM) functions into a single security management system.

    - **Some key features of SIEM include:**
        - **Log Management:** SIEM systems collect, aggregate, and store log data from a wide range of sources, including security devices, servers, and applications.
        - **Real-Time Monitoring:** SIEM systems provide real-time monitoring of security events, allowing security teams to detect and respond to threats as they occur.
        - **Threat Detection:** SIEM systems use advanced analytics and machine learning to detect and respond to security threats.
        - **Incident Response:** SIEM systems provide incident response capabilities, allowing security teams to investigate and respond to security incidents.

- **UEBA** **U**ser and **E**ntity **B**ehavior **A**nalytics

- UEBA is a cybersecurity technology that focuses on analyzing and understanding the behavior of users and entities (such as devices, applications, and servers) within an organization's network. The goal of UEBA is to detect and respond to abnormal or anomalous behavior that may indicate potential security threats.

### SOAR 

- **SOAR** Securonix provides SOAR solutions that enable organizations to automate and orchestrate their response to security incidents. This can enhance the efficiency and effectiveness of incident response workflows.