# 📦 M347 – Projekt LB02: Containerisierte Applikationen

## 🧑‍💻 Projektteam

- Praewphan Jamnongnok
- Arvin Mercado

## 🎯 Ziel

Dieses Projekt wurde im Rahmen des Moduls 347 durchgeführt. Ziel war es, verschiedene Applikationen (WordPress, MediaWiki, Jira) als containerisierte Microservices in einer Cloud-ähnlichen Umgebung bereitzustellen. Zusätzlich wird ein Monitoring-Service via Portainer integriert.

## 🧱 Verwendete Technologien

- Docker & Docker Compose
- Git & GitHub
- Portainer (für Monitoring)
- draw.io (für Architekturdiagramme)

## ⚙️ Services

| Service   | Beschreibung                      | Port |
| --------- | --------------------------------- | ---- |
| WordPress | CMS zum Erstellen von Webseiten   | 8080 |
| MediaWiki | Wiki-System                       | 8081 |
| Jira      | Ticket-/Projektmanagement-System  | 8082 |
| Portainer | Container-Monitoring & Verwaltung | 9000 |

## 🚀 Startanleitung

### Voraussetzungen

- Docker Desktop installiert
- WSL 2 aktiviert (unter Windows)
- Git installiert (für Quellcodeverwaltung)

### Starten des Projekts

```bash
cd Projekt/wordpress
docker compose up -d

### 📂 Projektstruktur
Projekt/
├── wordpress/
│   └── docker-compose.yml
├── mediawiki/
│   └── docker-compose.yml
├── jira/
│   └── docker-compose.yml
├── monitoring-portainer/
│   └── docker-compose.yml
└── install/
    └── optionales Installationsskript
```
