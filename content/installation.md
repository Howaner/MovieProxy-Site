---
title: Installation
type: page
layout: single
class: page-installation
---

1. Java 8 auf dem System installieren  
	```apt-get install openjdk-8-jre-headless```
2. Die [aktuellste Version](https://ci.howaner.de/job/MovieProxy/) der Software herunterladen  
	```wget https://ci.howaner.de/job/MovieProxy/lastSuccessfulBuild/artifact/target/MovieProxy.jar```
3. Einen Storage Ordner mit mindestens einem Unterordner anlegen  
	```mkdir storage && mkdir storage/Filme```
3. Die MovieProxy.jar mit Java ausführen  
	```java -jar MovieProxy.jar```
4. Der MovieProxy ist jetzt über http://die-ip-des-servers:8080 erreichbar.

# Verwendete Ordner

| Ordner    | Verwendung                                                 |
|-----------|------------------------------------------------------------|
| storage/  | Speicherort für heruntergeladene Videos                    |
| cache/    | Speicherort für Videos, die gerade heruntergeladen werden  |
| logs/     | Log4j speichert die Konsolen-Ausgabe hier in Dateiform ab. |
