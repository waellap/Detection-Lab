# Detection-Lab


## Objective
Detecting Malware using Splunk and Sysmon

The Detection Lab project aimed to establish a controlled environment for simulating and detecting reverse tcp payload. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
Detecting malware and understanding logs 

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
Splunk, Nmap, Sysmon windows 10, and kali linux

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network scanning tools (such as nmap) for Scanning newtowrk and looking into the open ports.
- Sysmon Collect detailed system events
- Windows 10 Target machine generating logs
- Kali Linux Simulate attacks.

## Steps
Lab photo demonstration.

Example below.

*Ref 1: Network Diagram*
-Creating the Malware using msfvenom.
<img src="https://imgur.com/ncgqRFW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


-After creating the malware in this step, we will exploit.

<img src="https://imgur.com/qHgRqD3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


-Creating the HTTP.Server.

<img src="https://imgur.com/8LWykK9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


-Turning down the malware detector in Windows Defender.


<img src="https://imgur.com/zxRYS7f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


-Connecting to the server and choosing the exe file, aka (malware folder).


<img src="https://imgur.com/loAu4PC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


-Download the exe file (Resume.pdf.exe) and run it


<img src="https://imgur.com/bcXDOsy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


-After running the malware folder, checking it through the cmd by running Netstat -anob to see if the 
connection is established

<img src="https://imgur.com/L6SZByZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />





<img src="https://imgur.com/ncgqRFW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />





<img src="https://imgur.com/ncgqRFW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />





<img src="https://imgur.com/ncgqRFW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



