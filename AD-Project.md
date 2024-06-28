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

* Network diagram for the project
  
![Active Directory Project-2024](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/031ea7e9-5114-4823-a1c4-77b740ec0d27)



* Built the home lab environment, including installing and configuring virual machines, setting the NAT network according to the diagram, and promoting a Domain Controller
![Screenshot 2024-05-23 160743](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/9c9fa566-5912-4c46-aea1-b0d21abb52f1)
![Screenshot 2024-05-23 161118](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/5840b289-67b4-43ce-8a0b-29e14fea94c9)




* Installed and configured Splunk Enterprise on an Ubuntu Server as the SIEM solution
![Screenshot 2024-05-23 170017](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/448bb87c-7a41-414f-925b-4f415b08a257)




* Setup a "Target PC" (Windows10) and joined it to the domain
![Screenshot 2024-05-23 170321](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/2cb95bd6-a629-4139-834a-8cba4e1ef4f2)



* Configured Splunk Universal Forwarder and Sysmon on the Target-PC to collect and forward logs to the Splunk server
![Screenshot 2024-05-23 172305](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/c87c041f-3dda-40fb-8b77-0f87abd4ad77)



* Perfomed a Brute-Force attack using Kali Linux and the Crowbar tool, targeting the "Target PC"
![Screenshot 2024-05-23 173219](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/24f1122a-3143-4567-b829-09b8139f3cdf)





* Analyzed the generated telemetry and logs in Splunk to detect and investigate the Brute-Force attack
![Screenshot 2024-05-23 173741](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/0f2b517c-eaf7-4bec-9ef5-c613c041a5e9)
![Screenshot 2024-05-23 173909](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/a37d92bd-0f3c-4a55-8975-64244f348eb2)
![Screenshot 2024-05-23 173940](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/b62b412f-60f3-489d-8495-28a439a441c9)
![Screenshot 2024-05-23 174247](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/0d9e3ec2-f014-4161-8435-077c7a0b51c6)





*  Executed Atomic Red Team tests on the "Target PC" to simulate various attack techniques | Utilized the MITRE ATT&CK framework website to reference the listed Techniques
![Screenshot 2024-05-23 181459](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/3aac4911-a2aa-47b9-a023-cd2955ffbe54)
![Screenshot 2024-05-23 181334](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/eda5384c-dad1-4c5c-8b43-b6aec886e22c)
![Screenshot 2024-05-23 184819](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/7ec30129-c9a2-4ba7-aa48-040c574e386e)
![Screenshot 2024-05-23 193015](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/dd1f9029-393d-4269-827b-8a5214592a63)
![Screenshot 2024-05-23 184547](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/b4407794-8b92-408c-86d2-d229f900b86d)
![Screenshot 2024-05-23 185526](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/83975dba-d100-4b44-9a0e-32e0c97c9402)



*  Analyzed the generated telemetry in Splunk (SIEM)
![Screenshot 2024-05-23 193252](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/45d6c642-8a03-48fd-a0f1-529960e17a9e)
![Screenshot 2024-05-23 193155](https://github.com/quinnran76/Security-Engineering-Labs/assets/58571908/bb5d1fb9-47f8-45d5-9e23-5acf43aa96a5)










 

