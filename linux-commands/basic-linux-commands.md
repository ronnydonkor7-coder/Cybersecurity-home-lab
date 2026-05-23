# Important Linux Commands for Cybersecurity

## File & Directory Commands
```bash
ls              # Lists files and directories
ls -la          # Lists all files including hidden files with details
pwd             # Shows current directory location
cd              # Changes directory
mkdir           # Creates a new directory
rm              # Removes files
rm -rf          # Force removes files/directories recursively
cp              # Copies files or directories
mv              # Moves or renames files
touch           # Creates a new empty file
cat             # Displays file contents
nano            # Opens nano text editor
clear           # Clears terminal screen
history         # Shows command history
```

---

## Permission & User Commands
```bash
chmod           # Changes file permissions
chown           # Changes file ownership
sudo            # Runs command as administrator
whoami          # Displays current logged-in user
passwd          # Changes user password
id              # Shows user and group IDs
useradd         # Creates a new user
usermod         # Modifies user account
```

---

## Networking Commands
```bash
ping            # Tests network connectivity
ifconfig        # Displays network interface configuration
ip a            # Shows IP address information
netstat -an     # Displays active network connections
ss -tulnp       # Shows listening ports and services
traceroute      # Tracks route packets take across network
nslookup        # Queries DNS records
dig             # Retrieves DNS information
arp -a          # Displays ARP table
route           # Shows routing table
hostname        # Displays system hostname
```

---

## Process & System Monitoring Commands
```bash
top             # Displays running processes in real-time
htop            # Interactive process viewer
ps aux          # Lists running processes
kill            # Terminates a process
killall         # Terminates processes by name
df -h           # Shows disk space usage
free -m         # Displays memory usage
uptime          # Shows system uptime
uname -a        # Displays system information
```

---

## Security & Log Commands
```bash
grep            # Searches text patterns in files
find            # Searches for files/directories
tail            # Displays last lines of a file
tail -f         # Monitors file updates live
head            # Displays first lines of a file
journalctl      # Views system logs
dmesg           # Displays kernel/system boot messages
last            # Shows login history
who             # Displays logged-in users
w               # Shows active users and activity
```

---

## Package Management Commands
```bash
sudo apt update     # Updates package lists
sudo apt upgrade    # Upgrades installed packages
sudo apt install    # Installs packages
sudo apt remove     # Removes packages
```

---

## File Compression Commands
```bash
zip             # Compresses files into ZIP format
unzip           # Extracts ZIP files
tar -cvf        # Creates TAR archive
tar -xvf        # Extracts TAR archive
```

---

## SSH & Remote Access Commands
```bash
ssh             # Securely connects to remote systems
scp             # Securely copies files between systems
sftp            # Secure file transfer protocol
```

---

## Cybersecurity & Networking Tools
```bash
nmap            # Network scanning and discovery tool
wireshark       # Packet capture and traffic analysis tool
tcpdump         # Command-line packet analyzer
nikto           # Web server vulnerability scanner
hydra           # Password brute-force testing tool
aircrack-ng     # Wireless security testing suite
sqlmap          # SQL injection testing tool
```
