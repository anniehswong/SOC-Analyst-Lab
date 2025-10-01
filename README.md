# SOC Analyst Lab: Threat Detection & Response with LimaCharlie EDR

## Objective

This hands-on lab establishes a functional SOC environment using LimaCharlie EDR to simulate real-world cyber attacks, engineer custom detection rules, and implement automated response mechanisms. The lab focuses on developing practical skills in threat detection, behavioral analysis, and incident response through hands-on adversary emulation.

The lab was performed on cloud-hosted virtual machines in a controlled, isolated environment to ensure safety and reproducibility.

Attack VM: Linux
Target VM: Windows

## Skills Learned

* Deployed and configured LimaCharlie EDR with Sysmon log ingestion for comprehensive endpoint monitoring and telemetry collection
* Enabled and applied Sigma detection rules to enhance threat visibility
* Operated Sliver C2 framework by launching the client, configuring HTTP listeners, generating custom implants, and managing remote sessions to simulate adversary tactics
* Conducted endpoint investigations using EDR telemetry, analyzing process trees, network connections, file system artifacts, and event timelines to identify malicious activity



* Created and tested Detection & Response (D&R) rules to identify credential dumping by monitoring sensitive LSASS process access
* Simulated ransomware behavior by executing VSS shadow-copy deletion, then built and validated a Detection & Response (D&R) rule to automatically terminate the C2 implant's parent process in real-time
* Created custom YARA signatures for Sliver C2 malware and implemented automated scanning workflows using D&R rules to detect threats at download (file-based) and execution (memory-based) stages, validating detection through manual and automated testing

## Tools & Technologies Used

- LimaCharlie
- Sysmon
- Sigma EDR Ruleset
- Sliver C2
- YARA 

## Lab Walkthrough
[Work in progress]

## References
- Based on [So You Want to be a SOC Analyst?](https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro) by Eric Capuano
