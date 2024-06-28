# Active Directory Project

## Objective

The Active Directory and Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Setting up and configuring an Active Directory (AD) environment
- Understanding the role of Domain Controllers and AD components
- Implementing and configuring Splunk as a SIEM solution
- Generating and analyzing security logs and telemetry
- Simulating cyber attacks using tools like Kali Linux and Atomic Red Team
- Detecting and responding to security incidents using a SIEM
- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

![Splunk Enterprise](https://img.shields.io/badge/Splunk_Enterprise-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Atomic Red Team](https://img.shields.io/badge/Atomic_Red_Team-B22222?style=for-the-badge&logo=atom&logoColor=white)
![Sysinternals](https://img.shields.io/badge/Sysinternals-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
- Crowbar (Brute Force Tool)
- Atomic Red Team to test to simulate various attack techniques and analyzed the generated telemetry in Splunk.
- Sysmon to monitor  and log system activity to the Windows event log.

## Steps

Example(s) below.

*Ref 1: Network Diagram*
*  Designed a logical diagram for the project
![Active Directory Project-2024](https://github.com/quinnran76/Detection-Lab/assets/58571908/048f3cef-cd1f-4853-936a-9b450f9caab1)



*  Built the home lab environment, including installing and configuring virual machines, setting the NAT network according to the diagram, and promoting a Domain Controller
![Screenshot 2024-05-23 161118](https://github.com/quinnran76/Detection-Lab/assets/58571908/0911104c-9878-4d54-a7d7-d7b87cc105ff)
![Screenshot 2024-05-23 160743](https://github.com/quinnran76/Detection-Lab/assets/58571908/620ad46c-56e0-484a-8bf9-4cc0e544bf83)



*  Installed and configured Splunk Enterprise on an Ubuntu Server as the SIEM solution
![Screenshot 2024-05-23 170017](https://github.com/quinnran76/Detection-Lab/assets/58571908/a70588fb-6c8a-47d9-9c71-68a23c96bc2d)



*  Setup a "Target PC" (Windows10) and joined it to the domain
![Screenshot 2024-05-23 170321](https://github.com/quinnran76/Detection-Lab/assets/58571908/b99ea284-fae8-4b5d-9b3c-d25f75561e77)



*  Configured Splunk Universal Forwarder and Sysmon on the Target-PC to collect and forward logs to the Splunk server
![Screenshot 2024-05-23 172305](https://github.com/quinnran76/Detection-Lab/assets/58571908/b9eb89ed-9cfe-412d-9b4a-7393e62d8f16)



*  Perfomed a Brute-Force attack using Kali Linux and the Crowbar tool, targeting the "Target PC"
![Screenshot 2024-05-23 173219](https://github.com/quinnran76/Detection-Lab/assets/58571908/69553083-b7b4-43fd-8b1a-615ded77a56f)




*  Analyzed the generated telemetry and logs in Splunk to detect and investigate the Brute-Force attack
![Screenshot 2024-05-23 173741](https://github.com/quinnran76/Detection-Lab/assets/58571908/a391f554-5667-4db0-8019-428afa2e92b6)
![Screenshot 2024-05-23 173909](https://github.com/quinnran76/Detection-Lab/assets/58571908/2dca5762-3425-4cd2-bb3c-fce4155a5a48)
![Screenshot 2024-05-23 173940](https://github.com/quinnran76/Detection-Lab/assets/58571908/553d6e98-c569-403b-a928-5c380589a9b2)
![Screenshot 2024-05-23 174247](https://github.com/quinnran76/Detection-Lab/assets/58571908/338183ec-b6e4-432a-b89c-1e1c04e3f047)



*  Executed Atomic Red Team tests on the "Target PC" to simulate various attack techniques | Utilized the MITRE ATT&CK framework website to reference the listed Techniques
![Screenshot 2024-05-23 181459](https://github.com/quinnran76/Detection-Lab/assets/58571908/e2360df4-05b9-4ac6-882c-74e56094cfe9)
![Screenshot 2024-05-23 181334](https://github.com/quinnran76/Detection-Lab/assets/58571908/e0708fe1-bf9f-4b72-81d8-99590660e095)
![Screenshot 2024-05-23 184819](https://github.com/quinnran76/Detection-Lab/assets/58571908/33a3cb4d-e077-40e5-80dd-16d3c2421925)
![Screenshot 2024-05-23 184819](https://github.com/quinnran76/Detection-Lab/assets/58571908/e91a40c2-e3c4-4332-8ee4-d71837c2df43)
![Screenshot 2024-05-23 184547](https://github.com/quinnran76/Detection-Lab/assets/58571908/49614ea8-5f3c-4de8-97cc-e6c91b9f9db2)


*  Analyzed the generated telemetry in Splunk (SIEM)
![Screenshot 2024-05-23 185526](https://github.com/quinnran76/Detection-Lab/assets/58571908/5b44a512-c658-48c6-a366-8ab68dc85602)
![Screenshot 2024-05-23 193015](https://github.com/quinnran76/Detection-Lab/assets/58571908/073e6441-18f2-484e-a7bd-7f0167931395)
![Screenshot 2024-05-23 193155](https://github.com/quinnran76/Detection-Lab/assets/58571908/18939f32-f92d-4094-bb21-8a8b72c886c2)








 

