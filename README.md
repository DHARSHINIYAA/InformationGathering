# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### History of the website :
<img width="1817" height="966" alt="Screenshot 2025-08-30 093152" src="https://github.com/user-attachments/assets/8dabdc99-9cae-4fd6-bc50-22847a4d6657" />

### ping command :
# Windows OS
<img width="1026" height="343" alt="Screenshot 2025-08-30 232125" src="https://github.com/user-attachments/assets/ae11d4b7-4b14-43c3-8ee7-f9dd96ed1469" />

### Liux OS:
<img width="820" height="389" alt="Screenshot 2025-08-30 231948" src="https://github.com/user-attachments/assets/2b302b76-3675-4aca-9cc8-1dd718cb2f80" />
### Whois
<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/a421b5c7-d403-4d06-a3c6-dff780c1d2ef" />

### Finding Hosting Company :
<img width="1824" height="881" alt="Screenshot 2025-08-30 092908" src="https://github.com/user-attachments/assets/91df735c-6c1e-429a-affa-1dd21e93c756" />

<img width="1822" height="877" alt="Screenshot 2025-08-30 092925" src="https://github.com/user-attachments/assets/172c6cf5-a476-430e-9112-9fe96f0de360" />

##  whois :
<img width="796" height="455" alt="Screenshot 2025-08-30 232159" src="https://github.com/user-attachments/assets/0fb79208-ca5f-4b53-a529-daa5bc0d1111" />

### netcat :
<img width="790" height="296" alt="Screenshot 2025-08-30 232529" src="https://github.com/user-attachments/assets/b323a33c-480d-4543-8c81-a7a41b53ae52" />

### nmap :
<img width="758" height="223" alt="Screenshot 2025-08-30 232911" src="https://github.com/user-attachments/assets/cb8fcc90-ecea-46b8-884b-3914fa80c3fe" />

### whatweb :
<img width="932" height="248" alt="Screenshot 2025-08-30 233059" src="https://github.com/user-attachments/assets/3181ef06-d03a-4939-a53e-d9b33af1c3cb" />

### httprint :
<img width="710" height="813" alt="Screenshot 2025-08-30 233141" src="https://github.com/user-attachments/assets/d9b90237-6317-4ebc-9ad0-c2db9d7cbf1e" />

### TCP traceroute :
<img width="700" height="166" alt="Screenshot 2025-08-30 234221" src="https://github.com/user-attachments/assets/d2ae16e0-c67b-4436-ac76-09bac1b0cc92" />

### UDP traceroute :

<img width="633" height="550" alt="Screenshot 2025-08-30 233730" src="https://github.com/user-attachments/assets/3d46ffcd-6f1a-447c-9e60-8d9288d81a16" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
