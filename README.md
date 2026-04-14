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

## Geplant

- Monitoring mit Grafana + Prometheus
- Ansible Playbooks für automatisches Server-Setup
- Weitere Sicherheitstests mit Kali Linux (Metasploit, Nikto)
- VPN-Server aufsetzen (WireGuard)
- Zweiter Ubuntu Server als Test-Ziel
