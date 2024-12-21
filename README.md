# SOC-Automation-Lab
Objective


In this SOC automation project, the primary goal was to enhance security operations using a suite of powerful tools. The system was built on Windows, with integration across several security platforms to streamline threat detection and incident response. Shuffle was used to automate workflows between tools such as Shuffle,  Wazuh, TheHive, and Cassandra. VirusTotal was employed for malware analysis by submitting suspicious files and URLs, providing detailed insights into potential threats. Security events were visualized and analyzed through Shuffle, while Wazuh monitored endpoints, collecting and analyzing security data. TheHive managed security incidents, enabling efficient tracking and response. Cassandra acted as a distributed database for securely storing extensive log data. Automated email notifications were set up to alert the security team about critical incidents, ensuring rapid response. This integrated system improved efficiency in detecting and managing security threats.

As part of the testing phase, Mimikatz was executed directly from the command line on the Windows machine to simulate attacks and validate the detection capabilities of the system.
The integrated tools, including Wazuh and TheHive, successfully flagged the malicious behavior, triggering alerts that were visualized . The system’s effectiveness was further confirmed through automated email notifications sent to the security team in real time. This comprehensive testing demonstrated that the SOC automation system was capable of detecting and responding to advanced threats like those posed by Mimikatz.

To enhance the scalability and resilience of the project, TheHive and Wazuh were hosted on DigitalOcean droplets. This cloud-based infrastructure provided a reliable platform for managing security operations, enabling centralized log collection, incident tracking, and efficient data processing. Hosting these tools on DigitalOcean allowed for seamless integration, ensuring that security events were consistently managed and analyzed in real time. The cloud deployment, combined with automated workflows and real-time alerting, ensured that the system could scale effectively to handle growing security demands


Skills Learned


Tools Used

Mimikatz

Kali Linux 

Vitual Box 

Windows 10

Kibana

Cassandra

Shuffle 

Digital Ocean Droplets( host The Hive and Wazuh Servers)

Firewall



References

#configuring the hive 

<img width="652" alt="Screenshot 2024-11-14 at 6 45 57 PM" src="https://github.com/user-attachments/assets/ed927420-1458-45ad-a013-75e16b2b4986" />
<img width="906" alt="Screenshot 2024-11-14 at 6 52 50 PM" src="https://github.com/user-attachments/assets/1fc81c23-d572-45b2-bbc3-faffecf6b773" />
<img width="714" alt="Screenshot 2024-11-14 at 6 59 11 PM" src="https://github.com/user-attachments/assets/9f73c58d-1f39-42be-998b-5236747c6c33" />

#installing wazuh on client

![Screenshot 2024-11-18 at 8 18 02 PM](https://github.com/user-attachments/assets/bc3d4444-2a88-4d88-8c46-ce6ece4ff184)


# testing mimikat event (changed name to mikat to see if mimikat detection still works under a different name )
<img width="688" alt="Screenshot 2024-11-20 at 2 35 45 PM" src="https://github.com/user-attachments/assets/e72bd90e-2b70-4f37-a536-e4aeabae1c49" />
<img width="1018" alt="Screenshot 2024-11-20 at 2 24 56 PM" src="https://github.com/user-attachments/assets/69b658cb-ab30-4d6e-9e41-0561d4532aa4" />
<img width="1389" alt="Screenshot 2024-11-20 at 2 33 23 PM" src="https://github.com/user-attachments/assets/7150c732-c48e-4720-834f-ec4fb1c10749" />
<img width="721" alt="Screenshot 2024-11-20 at 2 37 51 PM" src="https://github.com/user-attachments/assets/5f57f3f8-d84b-406a-86f5-ee683323e01f" />
<img width="721" alt="Screenshot 2024-11-20 at 2 38 36 PM" src="https://github.com/user-attachments/assets/21b518a9-eaae-47f7-a63c-83521112cc0a" />

# integrating with shuffle
<img width="774" alt="Screenshot 2024-11-24 at 1 59 07 PM" src="https://github.com/user-attachments/assets/8b65a2e8-875f-4ae5-ab55-d6c3c152c2de" />

<img width="326" alt="Screenshot 2024-11-24 at 2 05 33 PM" src="https://github.com/user-attachments/assets/1308cfe8-c907-4d89-8287-059c3de6446c" />

#email notification for mimkatz detection
<img width="1094" alt="Screenshot 2024-12-20 at 6 46 07 PM" src="https://github.com/user-attachments/assets/16a9d8f2-56fc-472f-9382-d3f708283e28" />

