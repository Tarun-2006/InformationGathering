# NAME : Tarun S
# REG NO : 212223040226

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
<img width="1919" height="921" alt="Screenshot 2025-09-01 052949" src="https://github.com/user-attachments/assets/7470ae85-e3e6-4577-8ea5-4de09d25f387" />


### Finding Hosting Company :
<img width="1871" height="900" alt="Screenshot 2025-09-01 063623" src="https://github.com/user-attachments/assets/e0f46145-6af4-4dce-b1ed-388752850e40" />


### History of the website :
<img width="1907" height="895" alt="Screenshot 2025-09-01 063712" src="https://github.com/user-attachments/assets/ee01e310-2a28-44cc-a0ce-101ff42fba1e" />


### ping command :
<img width="850" height="260" alt="Screenshot 2025-09-01 064402" src="https://github.com/user-attachments/assets/8620e4ed-d57c-4e84-be7d-ed8d5ce41f0e" />

### netcat :
<img width="728" height="99" alt="Screenshot 2025-09-01 065620" src="https://github.com/user-attachments/assets/0d9d4293-9763-457b-a22d-668fa2870dd2" />


### nmap :
<img width="780" height="234" alt="Screenshot 2025-09-01 064348" src="https://github.com/user-attachments/assets/7f8d029a-15c4-49a5-bf87-4b9a9bc473e5" />


### whatweb :
<img width="939" height="137" alt="Screenshot 2025-09-01 064636" src="https://github.com/user-attachments/assets/0dfb03f8-27c6-484f-bb39-3aa4e93c2038" />


### TCP traceroute :
<img width="753" height="81" alt="Screenshot 2025-09-01 064905" src="https://github.com/user-attachments/assets/efdca8b1-12e2-467c-854b-05a9a25cd307" />


### UDP traceroute :
<img width="652" height="514" alt="Screenshot 2025-09-01 065045" src="https://github.com/user-attachments/assets/78d32047-1bc4-407a-a116-4fe5c1937b30" />

## ICMP traceroute:
<img width="862" height="546" alt="Screenshot 2025-09-01 065256" src="https://github.com/user-attachments/assets/95d3bd6a-04ea-48fc-966f-adefd927d155" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
