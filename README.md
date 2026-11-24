# Shadowxtoolkit

A lightweight, automated installer for essential cybersecurity and bug bounty tools on Termux (Android arm64). Built for educational purposes and authorized security testing only.

## Features

*   **Reconnaissance:** `nmap`, `dnsutils`, `whois`, `wafw00f`
*   **Bug Bounty Arsenal:** `subfinder`, `httpx`, `nuclei`
*   **Exploitation & Web Testing:** `sqlmap`, `hydra`, `CMSeeK`
*   **Custom Modules:** Includes integration for `php2shell` (by aarsaputra).
*   **Secret Scanning:** `gitleaks`

## Installation

1.  Open Termux on your Android device.
2.  Clone this repository and run the installer:

```bash
git clone https://github.com/USERNAME/REPO_NAME.git
cd REPO_NAME
chmod +x install.sh
./install.sh
