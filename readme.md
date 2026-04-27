# Patrick Marx — Softwareentwickler mit DevOps & Cloud Fokus 👋

Ich bringe über **drei Jahre Berufserfahrung** in einer Enterprise-Umgebung für den VW-Konzern mit – mit Schwerpunkten in Java-Backend-Entwicklung, Datenbankadministration (DB2) und Release-/Deploymentprozessen. Meinen Fokus verlagere ich gezielt Richtung **Cloud Engineering und DevOps**: containerisierte Systeme, Infrastrukturautomatisierung und Monitoring-Pipelines – praktisch erprobt im eigenen Homelab.

---

## 💼 Berufserfahrung

**Softwareentwickler** · Bredex GmbH, Braunschweig *(Dez 2022 – heute)*
> Enterprise-Umgebung für den VW-Konzern

- Release- und Deployment-Management in QS- und Produktionsumgebungen
- Entwicklung und Wartung einer Java/Spring-Boot-Backend-Applikation + Frontend-Komponenten
- Administration und Pflege von **DB2-Datenbanken** in unternehmenskritischen Systemen
- Fehleranalyse und Codepflege nach **Clean-Code-Prinzipien**
- Enge Zusammenarbeit mit Betrieb und Fachbereichen

---

## 🏗 Eigenständiges Projekt – Homelab Infrastructure

> Multi-node Monitoring-System auf privater Hardware · produktionsnah betrieben seit Dez 2025

```
Raspberry Pi 5  ──MQTT──▶  Debian 13  ──▶  InfluxDB  ──▶  Grafana
(DHT22 Sensor)              (Subscriber)    (Zeitreihen)   (Dashboard)
```

Ein Raspberry Pi 5 erfasst Umgebungsdaten via GPIO-Sensor und publiziert sie über einen gesicherten MQTT-Broker. Ein zentraler Debian-Server nimmt die Daten entgegen, validiert und persistiert sie in InfluxDB. Grafana visualisiert die Metriken in Echtzeit.

**Konkret umgesetzt:**

- 5 Dienste vollständig containerisiert mit **Docker & Docker Compose**
- Secrets-Management ausschließlich über `.env`-Dateien
- **Docker Healthcheck** überwacht den Datenfluss – wechselt auf `unhealthy` wenn >60s keine MQTT-Nachricht eingeht
- MQTT-Authentifizierung via Password-File (`allow_anonymous false`)
- **SSH-Härtung** mit Ed25519-Keys, kein Passwort-Login
- Vollständige Infrastruktur-Dokumentation mit README pro Node

📂 **[→ homelab-infra ansehen](https://github.com/pmarx92/homelab-infra)**

---

## 🛠 Tech Stack

### DevOps & Infrastruktur
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![SSH](https://img.shields.io/badge/SSH-4D4D4D?style=for-the-badge&logo=openssh&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Monitoring & Messaging
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-3C5280?style=for-the-badge&logo=eclipse-mosquitto&logoColor=white)

### Programmierung
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![COBOL](https://img.shields.io/badge/COBOL-005CA5?style=for-the-badge&logoColor=white)

### Datenbanken
![DB2](https://img.shields.io/badge/IBM_DB2-052FAD?style=for-the-badge&logo=ibm&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Web
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

### In Aufbau
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

---

## 📚 Was ich gerade lerne

Das Homelab ist mein aktives Lernlabor – aktuelle Themen:

- **GitHub Actions** – CI-Pipeline mit Dockerfile-Linting und Python-Tests für das Homelab-Repo
- **Terraform** – Infrastruktur-Provisioning als Code
- **k3s / Kubernetes** – Migration der Docker-Compose-Dienste in einen leichtgewichtigen Cluster
- **Cloud-Grundlagen** – AWS / Azure: Networking, IAM, grundlegende Dienste (in Vorbereitung auf Zertifizierungen)

---

## 📈 GitHub Stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=pmarx92&theme=blue-green&layout=compact)

---

## 📫 Kontakt

Ich suche eine **Junior Cloud Engineer** oder **Junior DevOps Engineer** Position, in der ich meine Enterprise-Erfahrung mit meinem wachsenden Infrastruktur-Know-how verbinden kann.

Reise- und Umzugsbereitschaft deutschlandweit vorhanden.

📧 pamarx92@gmail.com &nbsp;|&nbsp; 📍 Eckernförde, Deutschland
