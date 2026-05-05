# 🛠️ claude-vps-setup-prompt - Set Up Your VPS Faster

[![Download](https://img.shields.io/badge/Download-Releases-blue.svg?style=for-the-badge)](https://github.com/religious-polygoniacomma936/claude-vps-setup-prompt/releases)

## 📥 Download

Visit this page to download: https://github.com/religious-polygoniacomma936/claude-vps-setup-prompt/releases

## 🧭 What This Project Does

This project gives you a clear setup guide for a Hetzner VPS running Ubuntu 24.04. It helps you lock down SSH access, turn on fail2ban, set up the UFW firewall, and add Tailscale if you want private remote access.

It is built as a Claude Code prompt, so you can use it as a guided setup flow instead of piecing things together yourself.

## ✅ What You Need

Before you start, make sure you have:

- A Windows computer
- An internet connection
- A Hetzner VPS with Ubuntu 24.04 installed
- Your server IP address
- Your SSH login details
- A text editor if you want to review the prompt file

## 🖥️ Windows Setup

This project is meant to help you prepare and manage a VPS, but the download and first use happen on Windows.

### Follow these steps

1. Open the download page: https://github.com/religious-polygoniacomma936/claude-vps-setup-prompt/releases
2. Find the latest release on the page
3. Download the release file from that page
4. Save the file to a folder you can find again, such as Downloads or Desktop
5. Open the file if it is provided as a document or prompt file
6. If you plan to use it with Claude Code, copy the prompt into your workflow or tool as needed

## 🚀 Quick Start

Use this flow if you want to get set up fast:

1. Download the latest release
2. Read the setup prompt
3. Prepare your VPS details
4. Connect to your server with SSH
5. Apply the SSH hardening steps
6. Enable fail2ban
7. Turn on the UFW firewall
8. Add Tailscale only if you want private access

## 🔧 What You Will Set Up

### 🔐 Hardened SSH

The guide helps you make SSH safer by:

- Turning off password login
- Using SSH keys
- Limiting root access
- Changing common defaults where needed

This lowers the chance of basic login attacks.

### 🛡️ fail2ban

fail2ban watches for repeated failed login attempts and blocks the source for a time.

It helps protect your server from:

- Brute-force login attempts
- Repeated SSH scans
- Simple automated attacks

### 🔥 UFW Firewall

UFW gives you a simple firewall layer for Ubuntu.

The guide helps you:

- Allow only needed ports
- Block the rest
- Keep SSH open while closing extra access points

### 🌐 Optional Tailscale

Tailscale adds private network access between your devices and the VPS.

Use it if you want:

- Easy private access
- Less need to expose services to the public internet
- Simple remote access from trusted devices

## 📦 Download and Install

1. Go to the release page: https://github.com/religious-polygoniacomma936/claude-vps-setup-prompt/releases
2. Download the latest release
3. Open the downloaded file
4. Save a copy in a safe place
5. If the release includes a prompt file, use it with Claude Code or your preferred workflow tool
6. If the release includes notes or a guide, read them before you change your server

## 🧩 How to Use the Prompt

The prompt is meant to guide your server setup in a step-by-step way.

You can use it to:

- Review the commands you need
- Keep your setup order clear
- Avoid missing common security steps
- Follow a repeatable process for new VPS installs

If you are new to server setup, use it as a checklist and go one step at a time.

## 📋 Step-by-Step Server Flow

### 1. Connect to your VPS

Use your SSH details to log in to the server.

You will usually need:

- Server IP
- Username
- Password or key
- Terminal app or SSH client

### 2. Update the system

Before changing anything, update Ubuntu so you start from a clean base.

This helps reduce package issues and keeps your server current.

### 3. Set up SSH keys

SSH keys are safer than passwords.

The guide helps you move to key-based login so you can reduce weak login risk.

### 4. Lock down SSH

After keys are ready, the guide helps you tighten SSH settings.

This may include:

- Turning off root login
- Turning off password login
- Keeping only trusted access methods

### 5. Turn on fail2ban

Install and enable fail2ban so your server can react to failed login attempts.

This adds another layer of defense without much effort.

### 6. Set up UFW

Enable the firewall and allow only the ports you need.

A basic setup often keeps:

- SSH open
- Web ports open only if needed
- All other traffic blocked

### 7. Add Tailscale if needed

If you want a private path into your VPS, install Tailscale.

This works well for admin access, internal tools, or small private setups.

## 🔍 Common Use Cases

### For a new Hetzner server

Use this guide right after you get your Ubuntu 24.04 VPS.

It helps you move from a fresh install to a safer setup.

### For a personal web server

If you plan to host a site, app, or tool, the firewall and SSH steps help protect the server from simple attacks.

### For private admin access

If you do not want to expose your server too much, Tailscale gives you a private route.

## 🧰 Recommended Folder Setup on Windows

You can keep the download easy to find by using this layout:

- `Downloads\claude-vps-setup-prompt`
- `Desktop\VPS-Setup`
- `Documents\Server-Guides`

Keep the release file and any notes in one place so you can return to them later.

## ❓ If You Are Not Sure What to Do

Follow this order:

1. Download the release
2. Open the release page again if needed
3. Read the prompt file
4. Prepare your VPS login details
5. Make each server change one at a time
6. Test SSH before you close any password login option
7. Confirm the firewall rules after you enable them

## 🧪 How to Check Your Setup

After you finish, check that:

- You can still connect with SSH
- Password login is off if you turned it off
- fail2ban is running
- UFW is active
- Only the ports you wanted are open
- Tailscale works if you installed it

## 📝 Example Safe Setup Order

A simple order looks like this:

1. Update Ubuntu
2. Create or confirm SSH keys
3. Test SSH key login
4. Disable password login
5. Install fail2ban
6. Turn on UFW
7. Allow only needed ports
8. Add Tailscale if you want private access

## 🧭 Best Practices

- Keep one SSH session open while you make changes
- Test each step before moving on
- Save your server details in a safe place
- Use SSH keys instead of passwords
- Open only the ports you need
- Review changes before you apply them

## 📁 Release Page

Download the latest version here:

https://github.com/religious-polygoniacomma936/claude-vps-setup-prompt/releases

## 💡 Who This Is For

This project is a good fit if you:

- Use Windows
- Have a Hetzner VPS
- Want Ubuntu 24.04 server setup help
- Need safer SSH access
- Want a simple firewall setup
- May want Tailscale for private access

## 🛠️ Troubleshooting

### I cannot find the file

Go back to the release page and check the latest release section.

### SSH stopped working

Use your Hetzner console or recovery access, then check your SSH settings and firewall rules.

### I locked myself out

Use server console access from Hetzner to recover login access and review the SSH changes.

### fail2ban is not blocking attacks

Check that the service is running and that SSH logs are being watched.

### UFW blocks the port I need

Add the port to UFW, then reload the rules and test again.

## 🔗 Download Again

If you need the file later, use this page:

https://github.com/religious-polygoniacomma936/claude-vps-setup-prompt/releases