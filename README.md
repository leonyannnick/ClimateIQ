# ClimateIQ
This repository will contain all files for the project. 
**Please be patient until I have uploaded all files. This repository is under construction**

CLimaIQ
CLimaIQ ist ein Projekt zur intelligenten Steuerung eines Heizstabs mithilfe von Überschuss-Photovoltaikstrom (PV). Es kombiniert die Flexibilität eines Raspberry Pi mit der Zuverlässigkeit einer Siemens LOGO! SPS, um eine effiziente und kostensparende Lösung für die Nutzung von überschüssiger Solarenergie zu bieten.

📖 Projektübersicht
Das Ziel dieses Projekts ist es, überschüssige PV-Leistung zur Erwärmung von Wasser oder anderen Anwendungen zu nutzen, indem der Heizstab intelligent geregelt wird.

Raspberry Pi: Übernimmt die Datenverarbeitung, Steuerungslogik und Kommunikation mit externen Systemen.
Siemens LOGO! SPS: Steuert die physikalische Regelung des Heizstabs und sorgt für die Ausführung der Sicherheitslogik.
Hauptfunktionen
PV-Überschusssteuerung: Automatische Regelung des Heizstabs, abhängig von der verfügbaren PV-Leistung.
Datenlogging: Aufzeichnung von Leistungsdaten zur späteren Analyse.
Flexibilität: Einfache Anpassung an verschiedene Systemkonfigurationen.
Zuverlässigkeit: Robuste Sicherheitsmechanismen durch die SPS.
🚀 Anforderungen
Hardware
Raspberry Pi (z. B. Raspberry Pi 4 oder vergleichbares Modell)
Siemens LOGO! SPS (ab 8. Generation empfohlen)
Heizstab kompatibel mit der Ausgangsleistung.
Photovoltaik-Anlage mit Überschussmessung.
Software
Raspberry Pi:
Betriebssystem: Raspberry Pi OS (empfohlen)
Python 3.x
Siemens LOGO! Soft Comfort: Für die SPS-Programmierung.
📂 Repository-Inhalt
/raspberry_pi/: Enthält den Python-Code und Skripte für den Raspberry Pi.
/siemens_logo/: Enthält die LOGO!-Projektdateien (.lsc) und Dokumentation.
/docs/: Enthält Anleitungen und Dokumentationen zur Einrichtung und Nutzung des Systems.
README.md: Diese Datei, die eine Übersicht über das Projekt bietet.
🔧 Einrichtung
Raspberry Pi
Raspberry Pi OS installieren und aktualisieren.
Python und die notwendigen Bibliotheken installieren:
bash
Code kopieren
sudo apt update
sudo apt install python3 python3-pip
pip3 install -r raspberry_pi/requirements.txt
Skripte aus dem Ordner raspberry_pi anpassen und ausführen.
Siemens LOGO!
Projektdateien (siemens_logo/*.lsc) in Siemens LOGO! Soft Comfort importieren.
Konfiguration für die spezifische Hardware anpassen.
Projekt auf die SPS hochladen.
📊 Datenvisualisierung (optional)
Integration mit Tools wie Grafana oder InfluxDB für Echtzeit-Dashboards und historische Datenanalyse wird unterstützt.

💡 Ideen & Weiterentwicklung
Unterstützung weiterer SPS-Modelle und Controller.
Integration mit Smart-Home-Systemen.
Verbesserung der Steuerungsalgorithmen für maximale Effizienz.
📝 Lizenz
Dieses Projekt steht unter der MIT-Lizenz. Weitere Informationen finden Sie in der Datei LICENSE.

📩 Kontakt
Wenn Sie Fragen, Feedback oder Vorschläge haben, können Sie sich gerne melden:

Autor: [Dein Name oder Organisation]
E-Mail: [Deine E-Mail-Adresse]
GitHub Issues: Nutzen Sie das Issue-Tracking.
