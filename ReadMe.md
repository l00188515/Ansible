# **ReadMe** 

## **What is this Repo?**
This is my **Ansible** repo which is part of my CA for Infrastructure as A Code module in the PGDip in Cloud Technology.


# **Contents**
1. **Build** 
- Configuration information on the Ansible servers in my lab.
2. **Security**
- Ansible Manger configuration around provisioning account, SSH and RSA keys
3. **Ansible Manager**
- Adding Ansible PPA to the repository
- Installation of Ansible
- Editing the Ansible Inventory file
- Ping test to all servers
- df -h to all servers
4. **Ansible Playbooks**
- Apply updates
- Install Appache webserver
- Install MariaDB

## **Servers**
| Server Name | Function | OS | IP | Mask | DG |
|----------- | ------- | ---- |------ | ------- | ----- |
|AnsibleManager|Ansible Server|Ubuntu Desktop|192.168.0.67|255.255.255.0|192.168.0.1
| AnsibleServer1|Ansible Server| Ubuntu Server 24.04|192.168.0.69|255.255.255.0|192.168.0.1|
|AnsibleServer2|Ansible Server|Ubuntu Server 24.04|192.168.0.70|255.255.255.0|192.168.0.1|

