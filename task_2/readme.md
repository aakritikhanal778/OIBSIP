# Task 2 – Basic Firewall Configuration with UFW

## Objective
Set up a basic firewall using **UFW** (Uncomplicated Firewall) on a Linux system to allow and deny specific network traffic.

## Tools Used
- **UFW** (Uncomplicated Firewall)
- Ubuntu / Debian-based Linux system

## Steps Performed
1. Checked if UFW was installed, and installed it if necessary.
2. Enabled UFW to start managing firewall rules.
3. Allowed essential services (e.g., SSH, HTTP, HTTPS).
4. Denied unnecessary ports to enhance security.
5. Verified rules and firewall status.
6. Documented commands, outputs, and their purposes.

## Common Commands Used
- `sudo apt install ufw` – Install UFW
- `sudo ufw enable` – Enable firewall
- `sudo ufw allow 22` – Allow SSH
- `sudo ufw allow 80` – Allow HTTP
- `sudo ufw allow 443` – Allow HTTPS
- `sudo ufw deny <port>` – Block a specific port
- `sudo ufw status numbered` – View firewall rules

## Files in This Folder
- **ufw_configuration_report.pdf** – Step-by-step guide with screenshots and command explanations.
- **screenshots/** – Folder containing screenshots of terminal outputs.
- **demo-video-link.txt** – Google Drive link to the demonstration video.

## Summary of Results
- Configured a secure firewall allowing only necessary traffic.
- Successfully blocked unwanted ports.
- Verified firewall status to confirm security settings.

## Demo Video
📹 [Click here to watch the demonstration](https://drive.google.com/file/d/1jpA8Bbm2ddvG_qYQmCtq5PM86bOnSxYC/view?usp=sharing)
