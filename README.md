## Security Analyst - Trojan Mirage Training

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/34a9cfaacc16b47910a901afa91181ee384e1ffd/Introduction.png)

Not every signal is a threat, and not every threat announces itself.  No two runs play out the same. The network shifts, the traps evolve. 
Only the sharpest eyes see through the attack !!! 

## Scenario Prompt

A user reported that his computer was locked in fullscreen browser mode, displaying a list of infected files, and persistent notification pop-ups about 
the infections.  The desktop wallpaper was altered to show a message claiming some files were infected.

## Infected Files Information

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/84e83d04f401e85a119846ba58ab038d4fbf4f6a/files.png)

## Warning message

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/8b6e5b5c46b3dbc1ff0cac90e9d99809597c6451/warning%20message.png)

## Analyzed the network topology to find IP address connections

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/f41027e289bc982a06bf814b09777dbf15356420/network%20topology.png)

## Searched for message details in the local user computer

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/6556924010b2920279f3042d1c9d80cc3ce369c3/message.png)

Reviewed the process of investigating a potential compromise on John Smith's workstation, by checking recent downloads and system changes. Identified that the incident appeared to involve an email and a Word document download, documented my findings and cross-referenced timestamps to understand the timing of the incident.

## Project Objective

Investigated a simulated ransomware attack on John Smith's workstation. Analyzed network topology, examined log files in Splunk and Security Onion tools, and identified indicators of compromise including external IP addresses and malicious files. Learned how to trace the attack vector from a macro-enabled Word document downloaded through reverse TCP connections to a Remote Access Trojan (RAT) that displayed full-screen warning messages and altered desktop wallpaper. The investigation revealed that the attack started with spear phishing targeting specific user John Smith, with the malicious chain involving email attachments, disabled macros, and multiple executable files masquerading as legitimate system processes. In addition, identified and executed the key remediation steps, which are blocking the external IP addresses, removing malicious files, documenting the incident, and implementing user training to prevent future attacks.

## Used Security Onions, Splunk, Palo Alto Netwoks to run further investigation

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/25eec4daa446fc7dcca89b5dae4e844b65e80665/splunk.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/2b87d4d5ed8055935ddcc9bfed427ccfd701321d/Splunk%202.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/faa4f0ce6e78b01e344a168870f439940a7dd013/Security%20onion.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/e2ab2c8b38a03533790eca02da9c3fa8066d4bc8/Security%20onion2.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/e28ebb9745664e165ac1754dac58867ac8fe2040/palo%20alto%20network.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/8b650c2223a1eb627635269647a54084aab06dde/palo%20alto%202.png)

## Malware Analysis Investigation

This project mainly focused on analyzing a potential malware incident involving a Word document with macros that could download and execute malicious files. Identified that the document contained a reverse TCP connection that would download cmd.exe and a Splunk forwarder (malicious executable file), which would then spawn other processes including a virus scanner. 

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/28dd3b716075fd931fc3bcb0a9890686467ce93a/information%20-%20finding.png)

##  Conclusion

The focus of this project was to investigate a security incident involving a Remote Access Trojan (RAT) disguised as a Splunk forwarder. Additional findings involved the chain of events from the initial email attachment with a macro to start the execution of malicious files. Examined the firewall logs to verify lateral movement and confirmed limited external network activity, with no further internal compromise detected. Documented and reviewed two suspicious executables and implemented immediate remediation steps to prevent future incidents.
Furthermore, blocked two malicious IP addresses through Palo Alto Networks firewall, removed malicious files including a Remote Access Trojan and Word document, and conducted thorough documentation of the incident timeline. To prevent this situation from happening again user training about avoiding downloads from untrusted sources was recommended and to attend lessons learned meeting to discuss improved security policies and proactive measures.

## Certificate earned

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/64996298843c64ca9e423d0d9e75d8601901e372/certificate%20earned%20.png)


