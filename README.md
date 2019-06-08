# RedHunt Linux Distribution (VM)
[<img src="https://redhuntlabs.com/assets/images/target-audience-512-512x512.png" align="right" width="100">](https://redhuntlabs.com/)
Virtual Machine for Adversary Emulation and Threat Hunting by [RedHunt Labs](https://redhuntlabs.com/)

RedHunt OS aims to be a one stop shop for all your threat emulation and threat hunting needs by integrating attacker's arsenal as well as defender's toolkit to actively identify the threats in your environment.



## Base Machine: 
* Lubuntu-18.04 x64

## Tool Setup
#### Attack Emulation:
* [Caldera](https://github.com/mitre/caldera)
* [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team)
* [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire)
* [Metta](https://github.com/uber-common/metta)
* [RTA](https://github.com/endgameinc/RTA)
* [Nmap](https://nmap.org/download.html)
* [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec)
* [Metasploit](https://github.com/rapid7/metasploit-framework)
* [Responder](https://github.com/lgandx/Responder)
* [Zap](https://www.zaproxy.org/)

#### Logging and Monitoring:
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

## VM Download Link: 
* Release v1: http://bit.ly/RedHUNTv1. All feedback is welcome.

*Changelog*
* System Updates
* Tool Updates
* New Categories added: Open Source Intelligence & Threat Intelligence
* Base OS Updated to 18.04
* Metasploit Framework Installed

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
Password: caldera 

## Checksums: 
**Version 1**
* MD5: 49b14e98b0b7d0276fe90da3f98608b0
* SHA1: 1963cdccc31349699226a3741bc5d1825ab70a61

## Sneak Peek:
<img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Login.jpg" width="35%"> <img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Caldera.jpg" width="35%"> <img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Kolide.jpg" width="35%">
<img src="https://github.com/redhuntlabs/RedHunt-OS/blob/master/Yeti.jpg" width="35%">

## To-Do:
- [ ] Integrate Memory Forensics and Analysis Framework
- [x] Integrate Threat Intelligence Frameworks
- [x] Integrate OSINT Frameworks

## Website:
* https://redhuntlabs.com

## Twitter:
* https://twitter.com/redhuntlabs

## Facebook:
* https://www.facebook.com/redhunt.labs.7

## References:
* https://cyberwardog.blogspot.in/2017/02/setting-up-pentesting-i-mean-threat_98.html
* https://jordanpotti.com/2018/02/16/elk-osquery-kolide-fleet-love/
