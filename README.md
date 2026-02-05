## NAME:Ragul M
## REG. NO.: 212224100048
## DATE: 05/02/2026

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
### Whois

<img width="1919" height="1150" alt="image" src="https://github.com/user-attachments/assets/097225b9-c158-4ad0-973f-9bcead924489" />

### Finding Hosting Company :
<img width="1919" height="1144" alt="image" src="https://github.com/user-attachments/assets/0be075d3-ba1d-48c1-8f1c-034d06d2fe78" />

### History of the website :
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/38c78859-b757-4e89-a320-e381918b4545" />


### ping command :
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/79428971-17b1-4679-8258-75c6867edf65" />

### whois :
<img width="1917" height="1079" alt="Screenshot 2026-01-30 095700" src="https://github.com/user-attachments/assets/a3d9b7aa-db7a-4141-bdbd-5fd34fa2e10d" />

<img width="1915" height="1077" alt="image" src="https://github.com/user-attachments/assets/66d0a059-05ad-4209-9d5e-0a1e5951e145" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/cfb5e59e-01ee-4909-b735-18f9719677a3" />

### netcat :
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/5f9e469c-9d9e-4ff9-9f8b-d796aa07d953" />


### nmap :
<img width="1900" height="1078" alt="image" src="https://github.com/user-attachments/assets/49a3a227-3cfa-4df7-bdf3-e61397c5c95a" />


### whatweb :
<img width="1919" height="1079" alt="Screenshot 2026-01-30 100057" src="https://github.com/user-attachments/assets/84433862-ab22-4417-905a-81a522ed101a" />


### httprint :
<img width="1919" height="1079" alt="Screenshot 2026-01-30 100322" src="https://github.com/user-attachments/assets/8f7cba26-4fb7-49e7-8d1d-35513ee2cb36" />


### TCP traceroute :
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8c082fdb-8f53-4bf7-9c87-7915f991940d" />


### UDP traceroute :
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/1c5f604a-a7df-436a-b0c2-f058af432432" />


## RESULT:

The information gathering techniques tools/procedure were identified successfully.
