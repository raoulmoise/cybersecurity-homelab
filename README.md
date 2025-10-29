# 🛢️ Homelab

This repository contains all the configurations and documentation for my homelab.  
As a systems engineer passionate about automation, networks, and cybersecurity, the goal of this environment is to **learn, test, and document real infrastructure setups** on physical hardware using open-source tools.

---

## 🧠 Goals
 
- Build a hybrid **DevOps + Blue Team** environment for hands-on learning  
- Maintain a **public “living resume”** through project documentation  
- Simulate a realistic enterprise infrastructure with monitoring and SIEM  

---

## 💻 Hardware Used

### Main Server – HP Z420 Workstation  
- **CPU:** Intel Xeon E5-1620 (4 cores / 8 threads, 3.8 GHz)  
- **RAM:** 32 GB DDR3 ECC  
- **Storage:** 480 GB SSD (OS)  +  2 × 1 TB HDD  +  500 GB HDD   (for VMs, backups, logging)  
- **GPU:** NVIDIA Quadro 2000 (1 GB GDDR5)  
- **Network:** 1 × Intel NIC (VLAN capable)  
- **Operating System:** Proxmox VE 9.0 (virtualization host)

### Laptop – Lenovo ThinkPad T470  
- **OS:** Kali Linux (Blue Team / offensive testing)  
- **Usage:** remote administration, attack simulation, and analysis

---

## 📚 Learning Themes

- Infrastructure as Code (IaC) & automation  
- Network segmentation, logging, and detection  
- SIEM & observability pipelines  
- Containerized self-hosting  
- Incident response and forensics practice  
- Continuous documentation & reproducibility

---

## 🔗 Useful Sites

<img width="50" height="50" alt="linuxserver-io" src="https://github.com/user-attachments/assets/f7932651-946b-4670-bfe4-1f9322dfb07f" /> | [LinuxServer.io](https://www.linuxserver.io/)  
<img width="50" height="50" alt="github" src="https://github.com/user-attachments/assets/3ffb7dd8-6df2-4545-9369-816f47ac8335" /> | [DashboardIcons](https://dashboardicons.com/)

---

## 🔄 Homelab Update (Oct 2025)

A new lab has been created to run **Proxmox VE 9** on the HP Z420 workstation.  
This new setup enables the full virtualization of Blue Team components (Windows AD, Wazuh, Sysmon) and DevOps automation tools (Ansible, Docker, K3s) on a single platform.  

---

## 🚧 Status

🟢 Actively maintained as part of my [`cybersecurity-homelab`](https://github.com/raoulmoise/cybersecurity-homelab) project.  
This environment will evolve to integrate **Cybersecurity** components.
