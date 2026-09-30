## Blue Team Cyber Trojan Mirage

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/dd39adda8fb811f26efe3a1a8b35740e945df47f/Trojan%20image.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/34a9cfaacc16b47910a901afa91181ee384e1ffd/Introduction.png)

Not every signal is a threat, and not every threat announces itself.  No two runs play out the same. The network shifts, the traps evolve. 
Only the sharpest eyes see through the illusion.  

## Scenario Prompt:

A user reported that their computer is locked in fullscreen browser mode, displaying a list of infected files, while persistent notifications pop up about 
the infections.  The desktop wallpaper has been altered to show a message claiming the files are infected, along with contact instructions for supported
remediation.

## Infected Files Information

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/84e83d04f401e85a119846ba58ab038d4fbf4f6a/files.png)

## Warning message

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/8b6e5b5c46b3dbc1ff0cac90e9d99809597c6451/warning%20message.png)

## Analyze the network topology to find IP address connections

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/f41027e289bc982a06bf814b09777dbf15356420/network%20topology.png)

## Searched for message details in the local user computer

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/6556924010b2920279f3042d1c9d80cc3ce369c3/message.png)

I reviewed the process of investigating a potential compromise on Safina's workstation, by checking recent downloads and system changes. I identified that the incident appeared to involve an email and a Word document download, I started documenting my findings and cross-referencing timestamps to understand the extent of the incident.

## Project feedback

The goal of the blue team were  to investigate a simulated ransomware attack on Zafina Young's workstation. The session involved analyzing network topology, examining log files in Splunk and Security Onion tools, and identifying indicators of compromise including external IP addresses and malicious files. Through the process I learned to trace the attack vector from a macro-enabled Word document download through reverse TCP connections to a remote access Trojan (RAT) that displayed full-screen warning messages and altered desktop wallpaper. The investigation revealed that the attack started with spear phishing targeting specific user Zafina Young, with the malicious chain involving email attachments, disabled macros, and multiple executable files masquerading as legitimate system processes. In addition, I identified and executed the key remediation steps including blocking the external IP addresses, removing malicious files, documenting the incident, and implementing user training to prevent future attacks.

## Use Security Onions, Splunk, Palo Alto Netwoks to run further investigation

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/25eec4daa446fc7dcca89b5dae4e844b65e80665/splunk.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/2b87d4d5ed8055935ddcc9bfed427ccfd701321d/Splunk%202.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/faa4f0ce6e78b01e344a168870f439940a7dd013/Security%20onion.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/e2ab2c8b38a03533790eca02da9c3fa8066d4bc8/Security%20onion2.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/e28ebb9745664e165ac1754dac58867ac8fe2040/palo%20alto%20network.png)

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/8b650c2223a1eb627635269647a54084aab06dde/palo%20alto%202.png)

## Malware Analysis Investigation

Main focused was on analyzing a potential malware incident involving a Word document with macros that could download and execute malicious files. I identified that the document contained a reverse TCP connection that would download cmd.exe and a Splunk forwarder, which would then spawn other processes including a virus scanner. 

![Image Alt](https://github.com/ErnestTechCyb/Blue-Team-Cyber-Trojan-Mirage/blob/28dd3b716075fd931fc3bcb0a9890686467ce93a/information%20-%20finding.png)


