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
because it stores all the companies data and systems and should not be compromised at any circumstances. 

### Which devices should normal employees be allowed to access? ###
All normal employees should be able to access 
- The printer,So that employees can print work related documentation and important reports.
  
- The employee PC, So that employees can work on work related projects and communicate with teams access essential software, and remain productive.
  

### Which device should have the strongest access controls? ###
-   Router
-   File server
-   Admin PC

These devices are somewhat of a powerhouse to the company and its infrastructure and if one of these are risked it could be fatal for the company and its data and so to prevent such risk it is important for these devices to have the strongest access controls.

### What could happen if an attacker gained access to the employee PC? ###
If an attacker had gained acces to an employees PC the attacker could be able to see the companies projects and gain access to essential software and compromise the companies data.

### Identify 5 potential security risks in this network. ###
- Poor passwords
- Outdated software
- Poor management protocols
- Access control
- Lack of propper training

### Suggest one security control for each risk. ###
- Poor passwords: Use a strong password policy that enforces multi-factor authentication (MFA) on all user accounts.
- Outdated software: Set up an automated patch management system to apply security updates as soon as they launch.
- Poor management protocols: Create and enforce clear governance frameworks with documented standard operating procedures.
- Access control: Implement the principle of least privilege so users only access files they truly need.
-  Run regular, engaging cybersecurity awareness training and phishing simulations for all staff.

  ### Design 3 firewall rules that would improve security. ###
  - Secure Remote Management (Inbound Control Plane Hardening)
  - Restrict Outbound Unencrypted/High-Risk Ports (Egress Filtering)
  -  Explicit Implicit Deny (Default-Deny Rule)


## Network Segmaentation ##
Internet
   ↓
Router / Firewall
   ↓
Switch
   ├── Admin PC
   ├── Employee PCs
   ├── File Server
   ├── Web Server
   └── Printer

  
