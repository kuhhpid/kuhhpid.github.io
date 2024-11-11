# Mathe-Quiz mit Countdown und Punktesystem

## Aufgabenstellung

Erstelle ein HTML/JavaScript-Programm für ein einfaches Mathe-Quiz mit folgender Funktionalität:

### 1. Fragen-Generator:
- Das Programm soll dem Benutzer einfache Mathe-Aufgaben stellen.
- Der Benutzer kann den Zahlenbereich der Aufgaben über einen Schieberegler (Slider) einstellen.
- Der Benutzer kann mehrere Operationen (Addition, Subtraktion, Multiplikation, Division) per Checkbox auswählen. Es können auch mehrere Operationen gleichzeitig aktiv sein.
- Jede Aufgabe verwendet eine zufällig ausgewählte aktive Operation.

### 2. Countdown und Progress-Bar:
- Nach einer einstellbaren Zeit (Schieberegler für Timeout in Sekunden) zeigt das Programm das richtige Ergebnis an, wenn der Benutzer keine Antwort gibt.
- Der Countdown soll grafisch durch eine Fortschrittsanzeige (Progress-Bar) dargestellt werden.

### 3. Antwortmöglichkeiten und Feedback:
- Das Programm soll zu jeder Aufgabe fünf Antwortoptionen generieren, darunter die richtige Antwort sowie vier zufällige falsche Antworten.
- Der Benutzer klickt auf eine Antwortoption. Bei einer richtigen Antwort färbt sich die Schaltfläche grün, bei einer falschen Antwort rot.
- Die Antwortmöglichkeiten sollen gemischt angezeigt werden.

### 4. Automatische nächste Frage:
- Nach jeder Antwort oder bei Zeitablauf soll das Programm automatisch zur nächsten Frage übergehen.

### 5. Punktesystem:
- Ein Punktestand wird im Interface angezeigt und aktualisiert sich mit jeder richtigen Antwort.
- Die Punktevergabe basiert auf der gewählten Operation:
  - **Addition**: 1 Punkt
  - **Subtraktion**: 2 Punkte
  - **Multiplikation**: 3 Punkte
  - **Division**: 4 Punkte

### 6. Visuelle Anforderungen:
- Die Benutzeroberfläche soll einfach und übersichtlich gestaltet sein, mit klaren Hinweisen auf die aktuelle Frage, Antwortoptionen und den Punktestand.
- Verwende HTML und CSS für das Design und JavaScript für die Logik.

## Hinweise
- Das Programm soll als interaktive Webanwendung ausgeführt werden, die in einem modernen Browser funktioniert.
- Du kannst dieses Projekt als Grundlage für deine eigenen Aufgaben verwenden oder es anpassen, um weitere Funktionen hinzuzufügen.

## Installation
- Klone dieses Repository oder lade die Dateien herunter, um das Quiz lokal auszuführen.
- Öffne die `index.html`-Datei in deinem Browser, um das Quiz zu starten.
