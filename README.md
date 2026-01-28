🛠️ System Security Control Demonstration Script


==========================================================
:: ██╗    ██╗███████╗██╗   ██╗██╗████████╗███████╗ ██████╗ 
:: ██║    ██║██╔════╝██║   ██║██║╚══██╔══╝██╔════╝██╔════╝ 
:: ██║ █╗ ██║███████╗██║   ██║██║   ██║   ███████╗███████╗ 
:: ██║███╗██║╚════██║██║   ██║██║   ██║   ╚════██║██╔═══██╗
:: ╚███╔███╔╝███████║╚██████╔╝██║   ██║   ███████║╚██████╔╝
::  ╚══╝╚══╝ ╚══════╝ ╚═════╝ ╚═╝   ╚═╝   ╚══════╝ ╚═════╝ 

===========================================================
📌 Overview

This Windows batch script demonstrates how system security controls can be queried and modified during a penetration testing engagement or controlled lab environment.

It is intended for educational purposes, red team simulations, and understanding how endpoint protections behave under administrative access.

This is not meant for casual use, production systems, or machines you do not explicitly own or have permission to test.

⚠️ Important Warning

This script requires Administrator privileges

It interacts with Windows Defender, Firewall, and security-related services

Running it on a real system can reduce security

Use only in labs, VMs, or authorized testing environments

If you don’t understand what each action does, don’t run it. Curiosity is fine. Carelessness is expensive.

🧠 What the Script Does

Checks for Administrator privileges

Attempts to modify Windows Defender configuration

Stops or disables certain security-related services

Turns off Windows Firewall profiles

Terminates commonly known antivirus processes (if present)

The goal is to demonstrate attacker techniques, not to recommend them.

🧪 Intended Use Cases

Penetration testing labs

Red team training environments

Malware analysis sandboxes

Defensive research and awareness

Educational content creation

❌ Not Intended For

Production systems

Daily-use machines

Unauthorized environments

“Just testing it real quick” scenarios

If that’s your plan, stop here.

🛡️ Responsibility

You are responsible for how you use this script.
Authorization matters. Ethics matter. Logs exist.

Use knowledge to understand systems, not to burn bridges.

✍️ Author

Wsuits6
Security tooling, research, and controlled chaos.