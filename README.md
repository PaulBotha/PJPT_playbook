# PJPT_playbook

Possible commands, tools and outputs that I migth be looking for.

Recon 

NMAP 
sudo nmap -p445 ip/24 --open  (search for smb in subnet that are open)

sudo nmap  -A -T4 -p- ip  (big search for all ports) 

sudo nmap --script smb-security-mode -p445 ip/24  (looking for not require SMB signing, DC requires & Domain member doesn't require) - Lab1

sudo nmap --script smb_protocols -p445 ip/24  (looks for SMB version) - Lab1
