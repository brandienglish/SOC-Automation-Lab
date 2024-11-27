# SOC-Automation-Lab
Objective


In this SOC automation project, the primary goal was to enhance security operations using a suite of powerful tools. The system was built on Windows, with integration across several security platforms to streamline threat detection and incident response. Shuffle was used to automate workflows between tools such as VirusTotal, Kibana, Wazuh, TheHive, and Cassandra. VirusTotal was employed for malware analysis by submitting suspicious files and URLs, providing detailed insights into potential threats. Security events were visualized and analyzed through Kibana, while Wazuh monitored endpoints, collecting and analyzing security data. TheHive managed security incidents, enabling efficient tracking and response. Cassandra acted as a distributed database for securely storing extensive log data. Automated email notifications were set up to alert the security team about critical incidents, ensuring rapid response. This integrated system improved efficiency in detecting and managing security threats.

As part of the testing phase, Mimikatz was executed directly from the command line on the Windows machine to simulate attacks and validate the detection capabilities of the system.
The integrated tools, including Wazuh and TheHive, successfully flagged the malicious behavior, triggering alerts that were visualized in Kibana. The system’s effectiveness was further confirmed through automated email notifications sent to the security team in real time. This comprehensive testing demonstrated that the SOC automation system was capable of detecting and responding to advanced threats like those posed by Mimikatz.

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
Virus Total


References
