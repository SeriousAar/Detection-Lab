# Detection-Lab & SOC Automation Project

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Security Information and Event Management system for log ingestion and analysis.
- Network analysis tools for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps

### 1. Representation of Labor
![image](https://github.com/SeriousAar/Detection-Lab/assets/164546782/2728272e-dd8d-492f-8fca-dc99ef815811)

##### Pic. 1: Workflow Labor

Here you can see how I set up the lab and the entire project.
You can see my Windows 10 client, which runs on Oracle VirtualBox. In addition, I have 2 cloud providers, Wazuh and TheHive, which communicate with me here.

### 2. Workflow
![image](https://github.com/SeriousAar/Detection-Lab/assets/164546782/52c2649f-abfa-4cce-bb19-a19606161092)

##### Pic. 2: Functionality 

Here you can see how the whole thing is structured. When I open the "file" the Wazuh alert hits. This communicates using SHA256 and shows the errors. From here we continue to 
VirusTotal, where the whole thing is analyzed and looked at in more detail. This provides more detailed information such as where the error came from, which user, which computer, 
etc. I then receive a message on my email distribution list that a malicious file has been accessed. At the same time, the whole thing is systematically presented in TheHive, which 
file it is and what the origin is.






