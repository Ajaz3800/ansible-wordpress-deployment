# 🚀 Ansible WordPress Production Deployment

Automated **production-ready WordPress deployment using Ansible**.

This project provisions a complete **LEMP stack** including **Nginx, PHP-FPM, MySQL, and WordPress** using **Infrastructure as Code (IaC)** principles.

The goal of this project is to demonstrate **DevOps automation skills using Ansible roles, modular playbooks, and repeatable infrastructure deployment**.

---

# 🏗 Basic WordPress Hosting Architecture in AWS


![Basic WordPress Hosting Architecture in AWS](assets/demo.gif)


---
# 🏗 High Availability WordPress Hosting Architecture on AWS


![High Availability WordPress Hosting Architecture on AWS](assets/demo-1.gif)

---
# 🏗 Secure High Availability Multi-Region WordPress Hosting Architecture on AWS


![Secure High Availability Multi-Region WordPress Hosting Architecture on AWS](assets/demo-2.gif)

---
# ⚙️ Tech Stack

| Component      | Technology           |
| -------------- | -------------------- |
| Automation     | Ansible              |
| Web Server     | Nginx                |
| Application    | WordPress            |
| Database       | MySQL                |
| Runtime        | PHP-FPM              |
| OS Support     | Ubuntu / Debian      |
| Infrastructure | EC2 / VPS / Cloud VM |

---

# 📂 Project Structure

```
ansible-wordpress-deployment
│
├── inventory
│   └── hosts.ini
│
├── group_vars
│   └── all.yml
│
├── roles
│   ├── common
│   │   └── tasks
│   │
│   ├── security
│   │   └── tasks
│   │
│   ├── mysql
│   │   └── tasks
│   │
│   ├── php
│   │   └── tasks
│   │
│   ├── wordpress
│   │   └── tasks
│   │
│   ├── nginx
│   │   ├── tasks
│   │   └── templates
│   │
│   └── ssl
│       └── tasks
│
├── playbook.yml
└── README.md
```

---

# 🚀 Features

✔ Automated **WordPress deployment**

✔ **Nginx web server configuration**

✔ **PHP-FPM runtime setup**

✔ **MySQL database provisioning**

✔ **WordPress database and user creation**

✔ **Role-based Ansible architecture**

✔ Ready for **cloud deployment (EC2 / VPS / Cloud VM)**

---

# 🖥 Supported Infrastructure

This playbook can deploy WordPress on:

* AWS EC2
* DigitalOcean Droplets
* Google Cloud Compute Engine
* Azure Virtual Machines
* Any **Ubuntu/Debian VPS**

---

# 📦 Configure Inventory

Edit the `inventory/hosts.ini` file with your server details.

Example:

```
[wordpress]
wordpress-server ansible_host=SERVER_IP ansible_user=ubuntu ansible_ssh_private_key_file=~/.ssh/id_rsa
```

Example for EC2:

```
[wordpress]
wordpress-server ansible_host=54.210.xx.xx ansible_user=ubuntu ansible_ssh_private_key_file=~/.ssh/aws-key.pem
```

---

# ▶️ Run the Playbook

Deploy the complete WordPress stack:

```
ansible-playbook playbook.yml
```

This playbook will automatically install and configure:

* Nginx
* PHP-FPM
* MySQL
* WordPress

---

# 🔍 Verify Installation

After deployment, open your browser:

```
http://<server-ip>
```

You should see the **WordPress installation page**.

---

# 🔐 Security Best Practices

This project implements several best practices:

* Dedicated **database user**
* **Service separation** (Nginx + PHP-FPM)
* Proper **file permissions**
* **Idempotent configuration management**
* Role-based **Ansible architecture**

---

# 📊 Automation Workflow

```
Provision Server
       │
       ▼
Install System Packages
       │
       ▼
Configure MySQL Database
       │
       ▼
Install PHP-FPM
       │
       ▼
Deploy WordPress
       │
       ▼
Configure Nginx
       │
       ▼
Start Services
```

---

## 📸 Screenshots

<p align="center">
  <img src="assets/screenshot.png" width="33%" />
  <img src="assets/screenshot-2.png" width="33%" />
  <img src="assets/screenshot-3.png" width="33%" />
</p>

<p align="center">
  <img src="assets/screenshot-4.png" width="33%" />
  <img src="assets/screenshot-5.png" width="33%" />
  <img src="assets/screenshot-6.png" width="33%" />
</p>

<p align="center">
  <img src="assets/screenshot-7.png" width="33%" />
  <img src="assets/screenshot-8.png" width="33%" />
  <img src="assets/screenshot-9.png" width="33%" />
</p>

---

# 📚 Learning Outcomes

This project demonstrates practical experience with:

* **Ansible configuration management**
* **Infrastructure as Code (IaC)**
* Automated **LEMP stack deployment**
* Modular **Ansible roles architecture**
* Cloud-ready **infrastructure automation**

---

## ⭐ Support

If you find this project helpful, please give it a star ⭐ on GitHub.

---

## 🌐 Connect With Me

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shaikh-muhammad-ajaz)
[![Email](https://img.shields.io/badge/Email-shaikhajaz38000@gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shaikhajaz38000@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-red?style=for-the-badge\&logo=youtube\&logoColor=white)](https://www.youtube.com/@devopswithajaz)
</div>

<div align="center">

[![Upwork](https://img.shields.io/badge/Upwork-Hire%20Me-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://upwork.com/freelancers/muhammadajaz)
[![Fiverr](https://img.shields.io/badge/Fiverr-Order%20Now-1DBF73?style=for-the-badge&logo=fiverr&logoColor=white)](https://www.fiverr.com/ajazshaikh3800)
</div>

---

<div align="center">
  
### 💡 "Turning ideas into production-ready systems."

![Profile Views](https://komarev.com/ghpvc/?username=Ajaz3800&color=brightgreen&style=flat-square)
[![GitHub followers](https://img.shields.io/github/followers/Ajaz3800?label=Follow&style=social)](https://github.com/Ajaz3800)

</div>
