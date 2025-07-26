# 🐧 Linux Commands Cheatsheet

A curated collection of essential Linux commands every beginner, DevOps engineer, or system admin should know. Designed for ease of use on any Linux system – whether you're working on a local machine or an EC2 instance.

---

## 🔧 System & Info Commands

| Command | Description |
|--------|-------------|
| `uname -a` | Show system/kernel information |
| `cat /etc/os-release` | Display OS version |
| `uptime` | Show how long the system has been running |
| `top` / `htop` | View CPU & memory usage |
| `free -m` | Show memory in MB |
| `df -h` | Show disk usage |
| `lsblk` | List block storage devices |
| `hostname -f` | Show full hostname |

---

## 👥 User & Group Management

| Command | Description |
|--------|-------------|
| `sudo useradd <username>` | Add new user |
| `sudo passwd <username>` | Set user password |
| `usermod -aG sudo <username>` | Add user to sudo group |
| `sudo groupadd <groupname>` | Create new group |
| `sudo usermod -g <groupname> <username>` | Set primary group |
| `sudo userdel <username>` | Delete user |
| `id <username>` | Show user details |
| `whoami` | Show current logged-in user |

---

## 📁 File & Directory Operations

| Command | Description |
|--------|-------------|
| `ls -la` | List files with permissions |
| `cd /path/` | Change directory |
| `mkdir folder` | Create new folder |
| `rm -rf folder/` | Delete folder recursively |
| `cp fileA fileB` | Copy file |
| `mv fileA fileB` | Rename or move |
| `touch file.txt` | Create empty file |
| `cat file.txt` | View file contents |

---

## 🔍 Text Processing & Searching

| Command | Description |
|--------|-------------|
| `cat -n file` | Add line numbers |
| `grep "word" file` | Find word in file |
| `grep -i word` | Case-insensitive search |
| `grep -v word` | Show lines that do not match |
| `sort file` | Sort lines alphabetically |
| `sort -n` | Sort numerically |
| `chmod 777 file` | Full permission to file |

---

## 🌐 Networking

| Command | Description |
|--------|-------------|
| `ping google.com` | Test connectivity |
| `ifconfig` / `ip a` | Show network info |
| `ssh-keygen -t rsa` | Generate SSH key |
| `curl ifconfig.me` | Get public IP |
| `netstat -tuln` | Show listening ports |

---

## 🛠️ System Tools

| Command | Description |
|--------|-------------|
| `ps aux` | Show all processes |
| `kill <pid>` | Kill process |
| `history` | Show command history |
| `cal` / `date` | Calendar and system time |
| `df -h` / `du -sh` | Disk space details |

---

## 📦 Archiving & Compression

| Command | Description |
|--------|-------------|
| `tar cf file.tar files/` | Create tar |
| `tar xf file.tar` | Extract tar |
| `gzip file` / `gzip -d file.gz` | Compress / decompress |

---

## 🧠 Helpful Shortcuts

| Shortcut | Description |
|----------|-------------|
| `Ctrl + C` | Stop current command |
| `Ctrl + Z` | Pause current command |
| `Ctrl + D` | Logout or EOF |
| `!!` | Run last command again |
| `Ctrl + R` | Search recent command |

---

## 🙌 Author & Credits

Cheatsheet created for quick access to must-know Linux commands.  
Follow **Shivam Agnihotri** on [LinkedIn](https://www.linkedin.com/in/shivamagnihotri) for real-world DevOps content.

