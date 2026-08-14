# network-recon.md
Hands-on cybersecurity project documenting the design and security assessment of a small business network, including threats, vulnerabilities, network segmentation, and security controls.

## Mission: Act like a junior security analyst investigating a small company's network ##

## Company ##
Apex Digital

## Employees ##
15

## Network ##
192.168.10.0/24


## Devices informarion ##

| Device | IP Address | Role |
|---|---|---|
| Router | `192.168.10.1` | Gateway |
| File Server | `192.168.10.10` | Stores company files |
| Web Server | `192.168.10.20` | Hosts company website |
| Admin PC | `192.168.10.50` | IT administrator |
| Employee PC | `192.168.10.51` | Normal employee |
| Printer | `192.168.10.60` | Network printer |


## Security levels on devices ##

| Device | IP Address | Role | Security Level |
|---|---|---|---|
| Router | `192.168.10.1` | Gateway | High |
| File Server | `192.168.10.10` | File storage | Critical |
| Web Server | `192.168.10.20` | Website | High |
| Admin PC | `192.168.10.50` | IT administrator | High |
| Employee PC | `192.168.10.51` | Normal employee | Medium |
| Printer | `192.168.10.60` | Network printer | Low |


## Network Security Assessment ##

### What is the most valuable device on this network? Why? ###
The file server 
because it stores all the companies data and systems 

### Which devices should normal employees be allowed to access? ###
All normal employees should be able to access 
- The printer
and 
- The employee PC
  

### Which device should have the strongest access controls? ###
-   Router
-   File server
-   Admin PC

  
