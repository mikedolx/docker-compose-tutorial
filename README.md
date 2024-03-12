# Über
Dieses Repository ist ein Tutorial für einen kurzen Einstieg in das Thema "Betrieb von Serveranwendungen" mit `docker compose`.

Es soll die Server-Anwendung [Rocket-Chat](https://www.rocket.chat/) unter zu Hilfenahme von `docker-compose.yml` aufgesetzt werden.

# Fähigkeiten
Mit diesem Tutorial erlenst Du folgende Fähigkeiten
- Du lernst die Grundlagen in `YAML`
- Du lernst die Grundlagen in `docker`
- Du erstellst deine eigene Server-Anwendung

# Aufgaben

## Grundlegende Themen
Die folgenden Fragen kannst Du vor ab recherchieren, um ein paar grundlegende Skills zum Thema zu erlangen.

- Was ist eine Domaine?
- Was ist eine IP-Adresse?
- Was ist eine Portnummer?
- Was ist der Unterschied zwischen IP-Adresse und Domaine?

## Einführung in YAML (Siehe Links)
Schaue Dir das Video zum Thema [YouTube - Grundlagen in YAML](https://www.youtube.com/watch?v=eKq7hDIbcjs) an.

- Welche Datei kannst du als YAML-Datei identifizieren?
- Welche Grundlegenden "Objekte" kannst Du in der Datei 

## Installation von docker mit compose
Für den Betrieb einer Server-Anwendung mit `docker-compose` müssen wir zunächst Docker mit dem Compose plugin auf dem PC installieren.

- Kannst Du identifizieren, ob docker bereits auf dem PC installiert ist?

Wenn Du feststellst, dass docker noch nicht auf dem PC installiert ist, dann installiere es mit folgendem Befehl. Lese Dir dazu die folgende Anleitung durch:

https://docs.docker.com/desktop/install/mac-install/

## Ersteinrichtung der `docker-compose.yml`
Lade die  
- Ersteinrichtung einer `.env`-Datei
- Starten der Anwendungen
- Einrichtung von Rocket-Chat
	- Admin-Benutzer
		- Name: 
		- E-Mail: 
	- Organization Infos
		- Name: TBS 902022
		- Organization Industry: Technology Services
		- Organization Size: 501-1000
		- Country: Germany

## Links
- [YouTube - Docker in 90s](https://www.youtube.com/watch?v=X10T1SXFA_M)
- [YouTube - Was ist Docker 15m](https://www.youtube.com/watch?v=sokNzEFt_k0)
- [YouTube - Grundlagen in YAML](https://www.youtube.com/watch?v=eKq7hDIbcjs)
- Rocket-Chat mit docker-compose
	- [Anleitung: Rocket-Chat mit docker-compose](https://docs.rocket.chat/deploy/deploy-rocket.chat/deploy-with-docker-and-docker-compose)
	- [Beispiel .env-Datei](https://github.com/RocketChat/Docker.Official.Image/blob/master/env.example)
