# tryhackme.com 

 Lernen Part 1
--------------------------------

1. **Offensive security** 
- identify and exploit system vulnerabilities to enhance security measures 
- exploiting software bugs, leveraging insecure setups, taking advantage of unenforced access control policies, ect
- Red teams + penetration testers specialize in these offensive techniques

2. **Defensive Security**
- preventing intrusions from occuring
- detecting intrusions when they occur and responding properly
- User cyber security awareness, documenting and managing assets, updating and patching systems, setting up intrusion preventation security devices (**IPS**), setting up logging and monitoring devices
- IPS blocks any network traffic that matches present rules and attack signatures
- Blue teams are part of the defensive security landscape

3. **more defensive security**
- Security Operations Center (SOC)
- Threat Intelligence
- Digital Forensics and Incident Response (DFIR)
- Malware Analysis


## Two main topics related to defensive security

- Security Operations Center (SOC), where we cover Threat Intelligence
- Digital Forensics and Incident Response (DFIR), where we also cover Malware Analysis

#### **Security Operations Center (SOC)**

1. **Tasks of SOC**
- Vulnerabilities       : system vulnerability, proper update or patch
- Policy violations     : set of rules required to protect the network and systems, as example: **upload confidential company data to an online storage service**
- Unauthorized activity : case where a user’s login name and password are stolen, and the attacker uses them to log into the network **--> SOC must detect and block it**
- Network intrusions    : user clicks on a malicious link or when an attacker exploits a public server --> **SOC must detect it as soon as possible to prevent further damage** 


**Security operations cover various tasks to ensure protection; one such task is threat intelligence.**

**Forensics is the application of science to investigate crimes and establish facts.**



#### **Threat Intelligence**


**Intelligence needs data --> Data has to be collected, processed, and analyzed**

**collected from local sources such as --> network logs and public sources such as forums**

**Data processing arranges it into a format suitable for analysis** 

**analysis phase seeks to find more information about the attackers and their motives; moreover, it aims to create a list of recommendations and actionable steps** 

**--> learn about your enemy --> create strategies, tactics, techniques and procedures against it** 



#### **Digital Forensics and Incident Response (DFIR)**


**application of science to investigate crimes and establish facts**

- File System   : Analyzing digital forensics image (low-level copy) of a system’s storage reveals much information (installed programs, created files, partially overwritten files, and deleted files)
- System memory : attacker runs their malicious program in memory without saving it to the disk, taking forensic image (low-level copy) of the system memory is best way to analyze its contents and learn about attack
- System logs   : each client and server maintain different log files -> provide plenty info about what happened on system, **even if attacker tries to clear --> leaves traces**
- Network logs  : Logs of the network packets that have traversed a network help answer more questions about whether an attack is occurring and what it entails


#### **Incident Response**


**An incident usually refers to a data breach or cyber attack**
**less critical, such as a misconfiguration, an intrusion attempt, or a policy violation**

- Preparation                             : Ideally, various measures are put in place to prevent incidents from happening in first place
- Detection and Analysis                  : team has the necessary resources to detect any incident; moreover, it is essential to analyze any detected incident further to learn about its severity
- Containment, Eradication, and Recovery  : Once incident detected, crucial to stop it affecting other systems, eliminate it, and recover affected systems
- Post-Incident Activity                  : After a successful recovery, a report is produced, and the lesson learned is shared to prevent similar future incidents



#### **Malware Analysis**


**Malware stands for malicious software. Software refers to programs, documents, and files you can save on a disk or send over the network**

- **virus** is a piece of code (part of a program) attaches itself to a program, designed to spread from one computer to another and works by altering, overwriting, and deleting files once it infects a computer
- **Trojan Horse** is a program that shows one desirable function but hides a malicious function underneath
- **Ransomware** is a malicious program that encrypts the user’s files. Encryption makes the files unreadable without knowing the encryption password --> Ransom for encryption of the files 


**Extra:**

- open-source databases out there, like **AbuseIPDB**, and **Cisco Talos Intelligence**, where you can perform a **reputation** and location check for the IP address
