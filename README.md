# SOC Analyst Lab: Threat Detection & Response with LimaCharlie EDR

## Objective

This hands-on lab establishes a functional SOC environment using LimaCharlie EDR to simulate real-world cyber attacks, engineer custom detection rules, and implement automated response mechanisms. The lab focuses on developing practical skills in threat detection, behavioral analysis, and incident response through hands-on adversary emulation.

⚠️ All lab activities were conducted in a safe, isolated environment for educational purposes only. 

### Skills Learned
- Deployed and configured LimaCharlie EDR with Sysmon log ingestion for comprehensive endpoint monitoring and telemetry collection
- Enabled and applied Sigma detection rules to enhance threat visibility
- Operated Sliver C2 framework by launching the client, configuring HTTP listeners, generating custom implants, and managing remote sessions to simulate adversary tactics
- Conducted endpoint investigations using EDR telemetry, analyzing process trees, network connections, file system artifacts, and event timelines to identify malicious activity
- Executed privilege escalation to SYSTEM level and performed credential dumping using Living-off-the-Land Binary (LOLBin) techniques (rundll32.exe, comsvcs.dll) to extract passwords from LSASS memory
- Created and tested Detection & Response (D&R) rules to identify credential dumping by monitoring sensitive LSASS process access
- Implemented and validated automated response rules to block ransomware behaviors (VSS deletion) and terminated attack chains in real-time
- Created custom YARA rules and automated malware scanning workflows to proactively detect threats at download and execution stages

## Tools & Technologies Used

- **LimaCharlie EDR** (sensor, telemetry, rules)  
- **Sysmon** (event logging)  
- **Sigma rules** (detections)  
- **Sliver C2** (adversary emulation)  
- **YARA** (malware scanning)  
- **Windows Event Logs, PowerShell**  

## Lab Walkthrough
### Step 1 – Environment Setup
### Step 2 – 
### Step 3 -
### Step 4 – 
### Step 5 – 
### Step 6 – 
### Step 7 –

## References
- Based on [So You Want to be a SOC Analyst?](https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro) by Eric Capuano
