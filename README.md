# CCSA104 – Security Policy Management Lab

## Project Overview

This repository documents my practical work for **CCSA104 – Security Policy Management**, completed as part of the Certified Cybersecurity Security Analyst (CCSA) training programme.

The lab focused on understanding and configuring security policies using Check Point SmartConsole. It covered Access Control policy management, firewall rule organisation, Network Address Translation (NAT), rule ordering, and basic policy troubleshooting.

The project includes the practical report, supporting screenshots, configuration observations, and theoretical explanations of key security policy management concepts.

## Student Information

| Field | Details |
|---|---|
| **Name** | Mukaram Oladega |
| **Student ID** | C11/26/CCSA/17114 |
| **Course** | CCSA104 – Security Policy Management |
| **Platform** | Check Point SmartConsole |
| **Project Type** | Cybersecurity Practical Lab |
| **Date** | November 2026 |

## Lab Objectives

The objectives of this lab were to:

- Explore the default security policy and understand its components.
- Create and organise Access Control rules.
- Understand the purpose and placement of the Stealth and Cleanup rules.
- Configure rulebase sections for better policy organisation.
- Explore automatic Hide NAT configuration.
- Understand the relationship between policy saving, publishing, and installation.
- Examine policy installation history and identify configuration limitations.

## Technologies and Concepts

- Check Point SmartConsole
- Security Management Server (SMS)
- Access Control Policy
- Firewall Rulebase Management
- Network Address Translation (NAT)
- Hide NAT / Port Address Translation (PAT)
- Security Zones
- Firewall Rule Ordering
- Security Policy Troubleshooting

## Practical Tasks Completed

### 1. Default Security Policy Exploration

Explored the default policy package and examined its components, including the Cleanup rule, Hits, Track, and Install On columns, Global Properties, and policy management options.

### 2. Access Control Policy Configuration

Created and organised network objects and Access Control rules using the lab's example network environment.

The configuration covered:

- Administrative access to the gateway.
- Stealth rule protection.
- Inbound access to DMZ services.
- DNS outbound access.
- Internal web access.
- Outbound SMTP access.
- Cleanup rule configuration.

### 3. Rulebase Organisation

Organised the policy into logical sections:

- Management and Protection
- DMZ Services
- Outbound Access
- Cleanup

These sections were used for administrative organisation and readability; they do not independently determine traffic enforcement.

### 4. Network Address Translation

Explored automatic Hide NAT configuration for the Internal LAN network.

The exercise covered how multiple internal hosts can share a translated external address and how port translation helps distinguish their connections.

### 5. Policy Installation and Troubleshooting

Reviewed policy installation attempts and Installation History. The installation process could not be completed successfully because the required Security Gateway components were not available in the local lab environment.

## Lab Environment and Limitations

The local environment provided access to the **A-SMS (Security Management Server)** only.

The Gateway Cluster and A-SME components were not installed locally. The instructor approved proceeding with the available A-SMS environment.

Consequently:

- Policy objects and rulebase configurations could be explored and documented.
- Gateway policy enforcement could not be validated.
- Policy installation attempts failed because the required gateway components were unavailable.
- End-to-end traffic testing and successful enforcement were not demonstrated.

Tasks or test cases not provided by the instructor were excluded from the report. No successful gateway deployment or traffic enforcement is claimed.

## Repository Contents

The repository is organised into the following sections:

- `docs/` – Completed practical and theoretical report.
- `evidence/screenshots/` – Screenshots captured during the lab exercises.
- `README.md` – Project overview and documentation.

See the repository files for the detailed practical steps, observations, screenshots, and theoretical answers.

## Key Learning Outcomes

Through this exercise, I developed a better understanding of:

1. How firewall Access Control policies are structured and managed.
2. Why rule ordering is important in firewall policy enforcement.
3. The security purpose of Stealth and Cleanup rules.
4. How NAT enables private network hosts to access external networks.
5. The distinction between saving, publishing, and installing security policies.
6. Why policy installation and enforcement must be validated in an environment with the required gateway components.

## Conclusion

This lab provided practical exposure to Check Point security policy management, particularly Access Control rule creation, rulebase organisation, and NAT configuration.

Although the absence of a locally available Security Gateway prevented successful policy installation and end-to-end enforcement testing, the exercise strengthened my understanding of firewall policy administration and the importance of validating configurations in an operational environment.

---

**Author:** Mukaram Oladega  
**Course:** CCSA104 – Security Policy Management  
**Student ID:** C11/26/CCSA/17114
