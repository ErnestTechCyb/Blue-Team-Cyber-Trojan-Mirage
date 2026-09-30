## Blue-Team-Cyber-Trojan-Mirage

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

## Use Security Onions, Splunk, Palo Alto to run further investigation

![Image Alt](

![Image Alt](

![Image Alt](

![Image Alt](

![Image Alt](

![Image Alt](


