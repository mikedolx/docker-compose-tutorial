# Über
Dieses Repository ist ein Tutorial für einen kurzen Einstieg in das Thema "Betrieb von Serveranwendungen" mit `docker compose`.

Es soll die Server-Anwendung [Rocket-Chat](https://www.rocket.chat/) unter zu Hilfenahme von `docker-compose.yml` aufgesetzt werden.

# Fähigkeiten
Mit diesem Tutorial erlenst Du folgende Fähigkeiten
- Du lernst die Grundlagen in `YAML`
- Du lernst die Grundlagen in `docker`
- Du startest deine eigene Server-Anwendung

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

## Einführung in docker mit compose

Schaue Dir die folgenden Videos an:
- [YouTube - Docker in 90s](https://www.youtube.com/watch?v=X10T1SXFA_M)
- [YouTube - Was ist Docker 15m](https://www.youtube.com/watch?v=sokNzEFt_k0)

### Fragen
- Was sind die Besonderheiten bei Docker?

## Installation von docker mit compose
Für den Betrieb einer Server-Anwendung mit `docker-compose` müssen wir zunächst Docker mit dem Compose plugin auf dem PC installieren.

- Kannst Du identifizieren, ob docker bereits auf dem PC installiert ist?

<details>
  <summary>Lösung</summary>
  ```shell
  docker --version
  ```
</details>

Wenn Du feststellst, dass docker noch nicht auf dem PC installiert ist, dann installiere es mit folgendem Befehl. Lese Dir dazu die folgende Anleitung durch:

https://docs.docker.com/desktop/install/mac-install/

## Über die Anwendung
- Informiere dich kurz über Rocket.chat
- [Rocket.chat](https://www.rocket.chat)
- [Anleitung: Rocket-Chat mit docker-compose](https://docs.rocket.chat/deploy/deploy-rocket.chat/deploy-with-docker-and-docker-compose)

### Fragen
- Was ist Rocket.chat?
- was kann ich damit machen?

## Starten der Anwendung
Über den Befehl `docker compose up` kannst Du die Anwendung starten. 

- Was siehst du im Terminal?
- Wo ist der unterschied, wenn du die Anwendung mit `docker-compose  up -d` startest?
- Wie kannst Du die Anwendung aufrufen?

## Links
- [YouTube - Docker in 90s](https://www.youtube.com/watch?v=X10T1SXFA_M)
- [YouTube - Was ist Docker 15m](https://www.youtube.com/watch?v=sokNzEFt_k0)
- [YouTube - Grundlagen in YAML](https://www.youtube.com/watch?v=eKq7hDIbcjs)
- Rocket-Chat mit docker-compose
	- [Anleitung: Rocket-Chat mit docker-compose](https://docs.rocket.chat/deploy/deploy-rocket.chat/deploy-with-docker-and-docker-compose)
	- [Beispiel .env-Datei](https://github.com/RocketChat/Docker.Official.Image/blob/master/env.example)
