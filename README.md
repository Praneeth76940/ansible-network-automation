# 🚀 Network Automation with Ansible + GNS3


This project automates Cisco router configuration using *Ansible* in a *GNS3 lab*. It pushes configs, backs up running configs, and simulates real-world automation from a control node (Ubuntu VM).
---

## 🔧 Tools Used
- Ansible
- GNS3 with Cisco IOSv
- Ubuntu (Control Node)
- GitHub

---

## 📁 Project Structure

├── playbooks/           # Ansible YAML files
├── inventory/           # Host IPs & credentials
├── topology/            # GNS3 file + diagram
├── outputs/             # Config backups
└── README.md


---

## ▶ How to Run

1. *Clone Repo*
bash
git clone https://github.com/YourUser/NetworkAutomationProject.git


2. *Run Playbook*
bash
ansible-playbook playbooks/push_config.yml -i inventory/inventory.ini


---

## 📷 Topology
![Topology](topology/topology.png)

---

## ✅ Highlights
- SSH-based config push
- Real Cisco CLI commands
- Full backup of configs
- Ready for Jenkins/GitOps CI/CD

---

## 🙋‍♂ Author

Praneeth Reddy – Network Engineer  
🔗 [GitHub](https://github.com/Praneeth76940) | [LinkedIn](www.linkedin.com/in/praneeth-reddy-ab4673a3)
