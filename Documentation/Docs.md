| Hostname      | Role           | IP Address    | Network        | Operating System            | Open Ports      |
| ------------- | -------------- | ------------- | -------------- | --------------------------- | --------------- |
| kali-attacker | Attacker       | 172.16.50.100 | 172.16.50.0/24 | Kali Linux                  | -               |
| web-target    | Target Server  | 172.16.50.10  | 172.16.50.0/24 | Ubuntu Server 22.04 + Nginx | 80/tcp, 22/tcp  |
| sec-onion     | IDS / Defender | 172.16.50.200 | 172.16.50.0/24 | Security Onion              | Monitoring Mode |

Network ID  : 172.16.50.0/24
Subnet Mask : 255.255.255.0
Topology    : Internal Network (VirtualBox - PBL-LAB)
Gateway     : None (Isolated Lab Environment)
