# Docker Setup

## Installierte Container

### Nginx
docker run -d -p 80:80 --name nginx-container nginx

### Grafana
docker run -d -p 3000:3000 --name grafana-container grafana/grafana

## Nützliche Befehle

- Container anzeigen: docker ps
- Container stoppen: docker stop <name>
- Container starten: docker start <name>
- Logs anzeigen: docker logs <name>

