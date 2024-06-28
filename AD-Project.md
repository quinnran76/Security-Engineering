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

- Splunk Enterprise
- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
- Kali Linux
- Crowbar (Brute Force Tool)
- Atomic Red Team to test and search Technique frameworks
- Sysmon to monitor  and log system activity to the Windows event log.

## Steps

Example(s) below.

*Ref 1: Network Diagram*
*  Designed a logical diagram for the project
![Active Directory Project-2024](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/031ea7e9-5114-4823-a1c4-77b740ec0d27)



*  Built the home lab environment, including installing and configuring virual machines, setting the NAT network according to the diagram, and promoting a Domain Controller
![Screenshot 2024-05-23 160743](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/9c9fa566-5912-4c46-aea1-b0d21abb52f1)
![Screenshot 2024-05-23 161118](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/5840b289-67b4-43ce-8a0b-29e14fea94c9)




*  Installed and configured Splunk Enterprise on an Ubuntu Server as the SIEM solution
![Screenshot 2024-05-23 170017](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/448bb87c-7a41-414f-925b-4f415b08a257)




*  Setup a "Target PC" (Windows10) and joined it to the domain
![Screenshot 2024-05-23 170321](https://github.com/quinnran76/Detection-Lab/assets/58571908/b99ea284-fae8-4b5d-9b3c-d25f75561e77)



*  Configured Splunk Universal Forwarder and Sysmon on the Target-PC to collect and forward logs to the Splunk server
![Screenshot 2024-05-23 172305](https://github.com/quinnran76/Detection-Lab/assets/58571908/b9eb89ed-9cfe-412d-9b4a-7393e62d8f16)



*  Perfomed a Brute-Force attack using Kali Linux and the Crowbar tool, targeting the "Target PC"
![Screenshot 2024-05-23 170321](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/2cb95bd6-a629-4139-834a-8cba4e1ef4f2)





*  Analyzed the generated telemetry and logs in Splunk to detect and investigate the Brute-Force attack
![Screenshot 2024-05-23 172305](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/c87c041f-3dda-40fb-8b77-0f87abd4ad77)
![Screenshot 2024-05-23 173219](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/24f1122a-3143-4567-b829-09b8139f3cdf)
![Screenshot 2024-05-23 173741](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/0f2b517c-eaf7-4bec-9ef5-c613c041a5e9)
![Screenshot 2024-05-23 173909](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/a37d92bd-0f3c-4a55-8975-64244f348eb2)





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








 

