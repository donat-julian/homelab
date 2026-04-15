# Homelab

Persönliches Homelab-Projekt zur Übung von Sysadmin- und Netzwerkadministration.

## Umgebung

- Host: Windows 11
- Virtualisierung: VirtualBox
- OS: Ubuntu Server 24.04 LTS

## Was bisher eingerichtet wurde

- SSH-Server (openssh)
- Statische IP-Konfiguration (Netplan)
- Firewall (ufw) - default deny, nur SSH und HTTP erlaubt
- Webserver (nginx)
- Konfigurationsdateien dokumentiert (nginx, firewall, netplan)
- Nmap Security Scan durchgeführt
- Kali Linux VM aufgesetzt für Penetration Testing
- Monitoring Stack: Prometheus + Grafana (Dashboard: Node Exporter Full)
- ✅ VPN-Server (WireGuard) - Windows Client verbunden
- Ansible Playbooks für automatisches Server-Setup

## Geplant

- Weitere Sicherheitstests mit Kali Linux (Metasploit, Nikto)
- Zweiter Ubuntu Server als Test-Ziel

## Screenshots

### Grafana Monitoring Dashboard
![Grafana Dashboard](docs/screenshots/Grafana_Dashboard.png)

### Nginx Webserver
![Nginx](docs/screenshots/Nginx.png)

### Grafana Datenquelle
![Grafana Datenquelle](docs/screenshots/Grafana_Datenquelle.png)

### WireGuard
![WireGuard](docs/screenshots/Wireguard.png)

### Ping_WireGuard
![Ping_WireGuard](docs/screenshots/Ping_Wireguard.png)

### Ansible Playbook
![Ansible Playbook](docs/screenshots/Ansible_Playbook.png)
