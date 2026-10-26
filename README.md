<picture>
  <source media="(prefers-color-scheme: dark)" srcset="hero.svg">
  <source media="(prefers-color-scheme: light)" srcset="hero-light.svg">
  <img src="hero.svg" alt="Rayan Aldossary, Network and Cybersecurity, CCNA, Saudi Arabia" width="100%">
</picture>

<img src="about.svg" alt="Console: show version and show interfaces status, listing networking and security skills as connected ports, including SIEM with Wazuh and Splunk" width="100%">

### Labs in numbers

<img src="labs.svg" alt="Across my labs: 5 network devices, 6 virtual machines, 4 VLANs, 5 endpoints, 4 security tools, 5 log sources monitored" width="100%">

### Detection pipeline

<img src="detection-pipeline.svg" alt="The Cisco network, OPNsense and Suricata, the Windows domain servers, the Proxmox and Docker hosts, and UniFi send logs to Wazuh, which decodes, correlates and responds, then forwards to Splunk. A brute force attempt on SWAGGER-DC-01 becomes a level 10 alert and the source is blocked." width="100%">

<a href="https://github.com/Rayan-Aldossary/Home-DataCenter">
  <img src="project-home-datacenter.svg" alt="Home-DataCenter: view repository" width="100%">
</a>

### Tools I work with

<p>
  <img alt="Cisco IOS XE" src="https://img.shields.io/badge/Cisco%20IOS%20XE-111317?style=for-the-badge&logo=cisco&logoColor=1BA0D7">
  <img alt="OPNsense" src="https://img.shields.io/badge/OPNsense-111317?style=for-the-badge&logo=opnsense&logoColor=D94F00">
  <img alt="Proxmox VE" src="https://img.shields.io/badge/Proxmox%20VE-111317?style=for-the-badge&logo=proxmox&logoColor=E57000">
  <img alt="Windows Server" src="https://img.shields.io/badge/Windows%20Server-111317?style=for-the-badge&logo=windows&logoColor=0078D4">
  <img alt="Suricata" src="https://img.shields.io/badge/Suricata%20IDS-111317?style=for-the-badge&logo=suricata&logoColor=EF6C00">
  <img alt="Wazuh" src="https://img.shields.io/badge/Wazuh-111317?style=for-the-badge&logo=wazuh&logoColor=3595F9">
  <img alt="Splunk" src="https://img.shields.io/badge/Splunk-111317?style=for-the-badge&logo=splunk&logoColor=65A637">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-111317?style=for-the-badge&logo=docker&logoColor=2496ED">
  <img alt="Ansible" src="https://img.shields.io/badge/Ansible-111317?style=for-the-badge&logo=ansible&logoColor=EE0000">
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-111317?style=for-the-badge&logo=ubuntu&logoColor=E95420">
  <img alt="UniFi" src="https://img.shields.io/badge/UniFi-111317?style=for-the-badge&logo=ubiquiti&logoColor=006FFF">
  <img alt="Python" src="https://img.shields.io/badge/Python-111317?style=for-the-badge&logo=python&logoColor=FFD43B">
  <img alt="Power BI" src="https://img.shields.io/badge/Power%20BI-111317?style=for-the-badge&logo=powerbi&logoColor=F2C811">
</p>

<details>
<summary><code>RAYAN-01# show running-config</code></summary>

```text
hostname Rayan-Aldossary
!
service password-encryption
no ip http server
ip ssh version 2
login block-for 120 attempts 3 within 60
!
logging trap informational
logging host wazuh.swagger.lab
!
snmp-server location Saudi Arabia
snmp-server contact linkedin.com/in/rayanaldossary
!
vlan 10
 name networking
vlan 20
 name infrastructure
vlan 30
 name cybersecurity
!
interface Port-channel1
 description Home-DataCenter, 2x10G LACP
!
banner motd ^
 Authorized access only.
 Built, broken, fixed, documented.
^
!
end
```

</details>

<br>

<p align="center">
  <a href="https://sa.linkedin.com/in/rayanaldossary"><img src="connect.svg" alt="Connect on LinkedIn" height="56"></a>
</p>
