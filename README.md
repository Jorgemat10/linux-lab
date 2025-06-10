# 🐧 Linux Lab with Ubuntu and Kali

This lab demonstrates basic and essential Linux commands using Ubuntu and Kali Linux. It's designed for beginners, especially those learning cybersecurity or system administration.

> ⚠️ NOTE: All sensitive information such as IP addresses and usernames has been sanitized for privacy.

## 🧪 Lab Objectives
- Navigate and manage the file system
- View system and network information
- Use common commands for package management and user control

## 📸 Screenshots
See the `screenshots/` folder for visuals of the commands in action.

## 📋 Commands Covered

`bash
# Update the system (Debian-based)
sudo apt update && sudo apt upgrade -y

# Create a file and directory
mkdir test_directory
touch test_directory/example.txt

# Navigate directories
cd test_directory
ls -la

# Show current user and hostname
whoami
hostname

# Display IP address (sanitize before posting!)
ip a

# Check system info
uname -a
lsb_release -a

# List open ports (useful for security)
ss -tuln

# View running processes
top

