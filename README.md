# ⚙️ Tech Environment Setup – Mini Project

This project is the first practical task in the Darey.io DevOps learning path. It focuses on preparing and configuring a personal development environment using essential tools and accounts required throughout the DevOps program.

---

## 🎯 Objective

To install, configure, and validate a working DevOps environment that includes:
- Git
- Visual Studio Code (VS Code)
- Ubuntu/Linux environment (via AWS EC2, Vagrant, or VirtualBox)
- GitHub account
- AWS account
- SSH setup

---

## 🧰 Tools Installed

| Tool           | Purpose                              |
|----------------|--------------------------------------|
| **Git**        | Version control system               |
| **VS Code**    | Code editor for development          |
| **Ubuntu 20.04**| Development environment              |
| **AWS EC2**    | (or VirtualBox + Vagrant) for hosting the environment |
| **GitHub**     | For source code management           |
| **SSH**        | Secure access to remote environments |

---

## 📥 Setup Steps

### ✅ Git Installation
```bash
sudo apt update
sudo apt install git -y
git --version



✅ Visual Studio Code
Downloaded from: https://code.visualstudio.com

Installed essential extensions:

GitLens

Remote - SSH

✅ Ubuntu/Linux Environment
Launched Ubuntu 20.04 instance on AWS EC2
or

Created Ubuntu box using Vagrant + VirtualBox

✅ SSH Access
Connected to remote Ubuntu machine using:

bash
Copy
Edit
chmod 400 my-key.pem
ssh -i "my-key.pem" ubuntu@<EC2-IP>
✅ GitHub Setup
Created GitHub account: github.com/piusjohn

Configured Git with:

bash
Copy
Edit
git config --global user.name "Pius John"
git config --global user.email "your-email@example.com"
📸 Screenshots (Attached Separately)
Terminal running Ubuntu environment

Git version output

VS Code connected to the machine

SSH terminal connection

AWS EC2 instance dashboard

GitHub profile and repository

🧾 Outcome
✅ All tools installed and configured

✅ Environment ready for DevOps projects

✅ First milestone completed on Darey.io

✍️ Author
Pius John
Corporate Student – Darey.io PBL
GitHub: @piusjohn
