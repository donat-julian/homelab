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
- ✅ Docker - Nginx und Grafana als Container

## Voraussetzungen

- Windows 10/11
- VirtualBox (https://virtualbox.org)
- Ubuntu Server 24.04 LTS ISO
- Kali Linux VirtualBox Image

## Setup

1. VirtualBox installieren
2. Ubuntu Server VM erstellen (8GB RAM, 4 CPU, 50GB HDD)
3. Netzwerkbrücke in VirtualBox einstellen
4. SSH installieren: `sudo apt install openssh-server -y`
5. Statische IP setzen via Netplan (`192.168.2.100`)
6. Firewall aktivieren: `sudo ufw enable`
7. Nginx installieren: `sudo apt install nginx -y`
8. Prometheus + Grafana installieren
9. WireGuard VPN einrichten
10. Ansible Playbook ausführen: `ansible-playbook -i inventory.ini playbook.yml`

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

### Netzwerkdiagramm
![Netzerkdiagramm](docs/screenshots/Netzwerkdiagramm.png)
