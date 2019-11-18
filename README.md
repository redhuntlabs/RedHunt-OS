# RedHunt Linux Distribution (VM) v2
[<img src="https://redhuntlabs.com/assets/images/target-audience-512-512x512.png" align="right" width="100">](https://redhuntlabs.com/)
Virtual Machine for Adversary Emulation and Threat Hunting by [RedHunt Labs](https://redhuntlabs.com/)

RedHunt OS aims to be a one stop shop for all your threat emulation and threat hunting needs by integrating attacker's arsenal as well as defender's toolkit to actively identify the threats in your environment.

**[`To know more about our asset discovery and perimeter security offering, check out nVadr.`](https://redhuntlabs.com/nvadr.html)**

## Base Machine: 
* Lubuntu-18.04 x64

## Tool Setup
#### Attack Emulation:
* [Caldera](https://github.com/mitre/caldera)
* [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team)
* [Nmap](https://nmap.org/download.html)
* [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec)
* [Metasploit](https://github.com/rapid7/metasploit-framework)
* [Responder](https://github.com/lgandx/Responder)
* [Zap](https://www.zaproxy.org/)
* [ADRecon](https://github.com/adrecon/ADRecon)

#### Threat HUNTing:
* [Kolide Fleet](https://github.com/kolide/fleet)
* [ELK (Elasticsearch, Logstash, and Kibana) Stack](https://www.elastic.co/elk-stack)

#### Open Source Intelligence (OSINT):
* [Maltego](https://www.paterva.com/web7/buy/maltego-clients/maltego-ce.php)
* [Recon-ng](https://bitbucket.org/LaNMaSteR53/recon-ng)
* [Datasploit](https://github.com/DataSploit/datasploit)
* [theHarvestor](https://github.com/laramies/theHarvester)

#### Threat Intelligence:
* [Yeti](https://github.com/yeti-platform/yeti)
* [Harpoon](https://github.com/Te-k/harpoon)

#### Reporting:
* [Asciinema](https://asciinema.org)
* [Flameshot](https://github.com/lupoDharkael/flameshot)
* [CherryTree](https://www.giuspen.com/cherrytree/)

## VM Download Link: 
* Release v2: http://bit.ly/RedHunt-OS-v2. All feedback is welcome.

*Changelog*
* System Updates
* Tool Updates
* New Categories added: Reporting
* Outdated tools removed
* Base OS Updated to 18.04

**Setup:**
* Download the latest OVA file from https://github.com/redhuntlabs/RedHunt-OS.
* Import the OVA in VirtualBox.
* Login using the credentials hunter:hunter.
* Update the distribution ‘sudo apt-get update && sudo apt-get upgrade’.
* Configure/Use the tools.

**VM Credentials:**
Username: hunter
Password: hunter

**Caldera Credentials:**
Username: admin 
Password: admin 

## Checksums: 
**Version 1**
* MD5: f8d433140f7e2b370b81c8b6ed3c951f
* SHA1: 66b6a9bdbd2c6f029de9d17a2e086166a1ab7fd3

## Sneak Peek:
<img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Login.jpg" width="35%"> <img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Caldera.jpg" width="35%"> <img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Kolide.jpg" width="35%">
<img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Yeti.jpg" width="35%">

## To-Do:
- [ ] Integrate Memory Forensics and Analysis Framework
- [x] Integrate Reporting Tools
- [x] Integrate Threat Intelligence Frameworks
- [x] Integrate OSINT Frameworks

## Website:
* https://redhuntlabs.com

## Twitter:
* https://twitter.com/redhuntlabs

## References:
* https://cyberwardog.blogspot.in/2017/02/setting-up-pentesting-i-mean-threat_98.html
* https://jordanpotti.com/2018/02/16/elk-osquery-kolide-fleet-love/
