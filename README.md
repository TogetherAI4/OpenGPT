```md
---
title: OpenGPT
emoji: 🚀
colorFrom: blue
colorTo: yellow
sdk: docker
sdk_version: 1.24.0
app_file: run.py
pinned: true
app_port: 1338
---

# OpenGPT
## Entwickler: N.Achyuth Reddy
### GPT 3.5/4

<strong>KEIN API-SCHLÜSSEL ERFORDERLICH</strong> ❌🔑 

Dieses Projekt nutzt die [G4F-API](https://github.com/xtekky/gpt4free). <br>
Erleben Sie die Leistungsfähigkeit von ChatGPT mit einer benutzerfreundlichen Oberfläche, verbesserten Jailbreaks und komplett kostenlos.

## Bekannte Fehler 🚧
- Stream-Modus funktioniert nicht ordnungsgemäß.

## Neuigkeiten 📢
Ich habe eine neue Version von OpenGPT unter Verwendung der [OpenGPT-API](https://chimeragpt.adventblocks.cc/) erstellt. 
<br>
<br>
Diese kostenlose API ermöglicht die Verwendung verschiedener KI-Chat-Modelle, einschließlich <strong>GPT-4, GPT-4-32k, Claude-2, Claude-2-100k und mehr.</strong> <br>
Schauen Sie sich das Projekt hier an: [OpenGPT - Chimera Version](https://github.com/ramonvc/OpenGPT/tree/chimeragpt-version).

## Projekt-Hosting und Demonstration 🌐🚀
Das Projekt ist auf mehreren Plattformen gehostet, um getestet und modifiziert zu werden.
|Plattform|Status|API-Schlüssel|Kostenlos|Repo|Demo|
|--|--|--|--|--|--|
|[replit](https://replit.com/)|![Aktiv](https://img.shields.io/badge/Aktiv-hellgrün)|◼️|☑️|[OpenGPT](https://replit.com/@ramonvc/OpenGPT)|[Chat](https://achyuthgamer-OpenGPT.hf.space/chat/)
|[hugging face](https://huggingface.co)|![Aktiv](https://img.shields.io/badge/Aktiv-hellgrün)|◼️|☑️|[OpenGPT](https://huggingface.co/spaces/monra/OpenGPT/tree/main)|[Chat](https://huggingface.co/spaces/achyuth5/OpenGPT)
|[replit](https://replit.com/)|![Aktiv](https://img.shields.io/badge/Aktiv-hellgrün)|☑️|☑️|[OpenGPT - Chimera Version](https://replit.com/achyuth5/OpenGPT-chimera)|[Chat](https://achyuthgamer-OpenGPT.hf.space/chat/)

## Hinweis ℹ️ 
<p>
  OpenGPT ist ein Projekt, das verschiedene kostenlose KI-Konversations-API-Anbieter nutzt. Jeder Anbieter ist eine API, die von verschiedenen KI-Modellen generierte Antworten bereitstellt. Der Quellcode im Zusammenhang mit diesen Diensten ist im <a href="https://github.com/achyuth4/OpenGPT/tree/main/g4f">G4F-Ordner</a> verfügbar.

Es ist wichtig zu beachten, dass aufgrund der umfangreichen Reichweite dieses Projekts die hier registrierten kostenlosen Dienste eine erhebliche Anzahl von Anfragen erhalten können, was zu vorübergehender Nichtverfügbarkeit oder Zugangsbeschränkungen führen kann. Daher ist es üblich, auf diese Dienste offline oder instabil zu stoßen.

Wir empfehlen, dass Sie nach eigenen Anbietern suchen und sie Ihren persönlichen Projekten hinzufügen, um Instabilität und Nichtverfügbarkeit der Dienste zu vermeiden. Innerhalb des Projekts, im <a href="https://github.com/achyuth4/OpenGPT/tree/main/g4f/Provider/Providers">Anbieter-Ordner</a>, finden Sie mehrere Beispiele für Anbieter, die in der Vergangenheit funktioniert haben oder noch funktionieren. Es ist einfach, der Logik dieser Beispiele zu folgen, um kostenlose GPT-Dienste zu finden und die Anfragen in Ihr spezifisches OpenGPT-Projekt zu integrieren.

Bitte beachten Sie, dass die Auswahl und Integration zusätzlicher Anbieter in der Verantwortung des Benutzers liegen und nicht direkt mit dem OpenGPT-Projekt zusammenhängen, da das Projekt als Beispiel dafür dient, wie die <a href="https://github.com/xtekky/gpt4free">G4F-API</a> mit einer Web-Benutzeroberfläche kombiniert werden kann.
</p>

## Inhaltsverzeichnis  
- [To-Do-Liste](#to-do-liste-%EF%B8%8F)  
- [Erste Schritte](#erste-schritte-white_check_mark)  
  - [Repository klonen](#repository-klonen-inbox_tray)  
  - [Abhängigkeiten installieren](#abhängigkeiten-installieren-wrench)  
- [Anwendung ausführen](#anwendung-ausführen-rocket)  
- [Docker](#docker-)  
  - [Voraussetzungen](#voraussetzungen)  
  - [Docker ausführen](#docker-ausführen)
- [Eingegliederte Projekte](#eingegliederte-projekte-busts_in_silhouette)
  - (#) 
  - [API OpenGPT](#api-g4f)
- [Sternhistorie](#sternhistorie)
- [Rechtlicher Hinweis](#rechtlicher-hinweis) 

##

## To-Do-Liste ✔️

- [x] Integriere die kostenlose GPT-API in das
- [x] Erstelle Docker-Unterstützung
- [x] Verbessere die Jailbreak-Funktionalität
- [x] Füge das GPT-4-Modell hinzu
- [x] Verbessere die Benutzeroberfläche
- [ ] Status der API-Anbieter überprüfen (online/offline)
- [ ] Bearbeiten und Erstellen von Jailbreaks/Rollen aktivieren in der
- [ ] Refaktorisieren des Webclients

## Erste Schritte :white_check_mark:  
Um mit diesem Projekt zu beginnen, müssen Sie das Repository klonen und [Python](https://www.python.org/downloads/) auf Ihrem System installiert haben.  
  
### Repository klonen :inbox_tray:
Führen Sie den folgenden Befehl aus, um das Repository zu klonen:  

```
git clone https://github

.com/ramonvc/OpenGPT.git
```

### Abhängigkeiten installieren :wrench: 
Navigieren Sie zum Projektverzeichnis:
```
cd OpenGPT
```

Installieren Sie die Abhängigkeiten:
```
pip install -r requirements.txt
```
## Anwendung ausführen :rocket:
Um die Anwendung auszuführen, führen Sie den folgenden Befehl aus:
```
python run.py
```

Greifen Sie über die URL in Ihrem Browser auf die Anwendung zu:
```
http://127.0.0.1:1338
```
oder
```
http://localhost:1338
```


## Docker 🐳
### Voraussetzungen
Stellen Sie sicher, dass Sie [Docker](https://www.docker.com/get-started) auf Ihrem Computer installiert haben, bevor Sie beginnen.

### Docker ausführen
Holen Sie das Docker-Image von Docker Hub:
```
docker pull ramonvc/OpenGPT
```

Führen Sie die Anwendung mit Docker aus:
```
docker run -p 1338:1338 ramonvc/OpenGPT
```

Greifen Sie über die URL in Ihrem Browser auf die Anwendung zu:
```
http://127.0.0.1:1338
```
oder
```
http://localhost:1338
```

Wenn Sie die Anwendung beendet haben, stoppen Sie die Docker-Container mit folgendem Befehl:
```
docker stop <container-id>
```

## Eingegliederte Projekte :busts_in_silhouette:
Ich empfehle dringend, beide Projekte zu besuchen und zu unterstützen.

###
Die Anwendungsschnittstelle wurde aus dem [chatgpt-clone](https://github.com/xtekky/chatgpt-clone)-Repository übernommen.

### API G4F
Die kostenlose GPT-4-API wurde aus dem [GPT4Free](https://github.com/xtekky/gpt4free)-Repository übernommen.

<br>

## Sternhistorie
[![Sternhistorie-Diagramm](https://api.star-history.com/svg?repos=ramonvc/OpenGPT&type=Timeline)](https://star-history.com/#achyuth4/OpenGPT&Timeline)

<br>""""""""""""
```
