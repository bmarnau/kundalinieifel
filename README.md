# Eifel Kundalini Yoga Festival

Responsive, statische Landingpage für das Eifel Kundalini Yoga Festival 2026 auf Haus Bollheim. Die Seite besteht aus HTML und CSS sowie dem bereits vorhandenen JavaScript-Countdown. Es gibt keine Abhängigkeiten und keinen Build-Schritt. Der Originalflyer steht einmalig und unverzerrt im Programmbereich; das semantische HTML-Programm folgt darunter.

## Aufbau

- `index.html`: semantische Seitenstruktur, alle veröffentlichten Inhalte und Countdown
- `impressum.html`: veröffentlichungsbereites Impressum der Veranstalterin
- `datenschutz.html`: technische Datenschutzerklärung mit deutlich markierten Betreiber- und Hostingplatzhaltern
- `css/style.css`: Layout, Gestaltung, responsive Breakpoints und reduzierte Bewegung
- `bilder/`: unveränderte lokale Flyer- und Personenbilder
- `docs/`: unveränderte Textquellen

Die stabilen Navigationsziele sind `festival`, `programm`, `gestaltende` und `ort`.

## Veröffentlichungshinweis

`impressum.html` und `datenschutz.html` sind mit den bestätigten Angaben veröffentlichungsbereit. In der Datenschutzerklärung sind Sabine Montag als verantwortliche Stelle, DomainFactory GmbH als Hostinganbieter und die LDI NRW als Aufsichtsbehörde genannt. Laut bestätigter Hostingkonfiguration werden keine Server-Logdateien gespeichert; die beim Seitenaufruf technisch notwendige Verarbeitung ist entsprechend dokumentiert.

Externe Google-Font-Aufrufe wurden entfernt. Die Website lädt nun nur lokale Website-Ressourcen; der Link zur offiziellen Website von Haus Bollheim wird erst durch aktives Anklicken aufgerufen.

## Quellen und Zuordnung

- Programm, Eckdaten, Hinweise und Anmeldung: `bilder/Flyer-Programm-2026.png`
- Semantischer Programmtext: `docs/programm.txt`
- Personenbeschreibungen: `docs/Texte website Eifel-Festival.docx`
- Mela: `bilder/Mela.jpeg`
- Silvio: `bilder/Silvio.jpeg`
- Jens Freiwald: `bilder/jens.png`
- Judith Maria Günzl: `bilder/judith.jpeg`
- Anette Prabhudaya und Rani Jaskanwal: `bilder/anette.jpeg`; Beschreibungstext direkt für die Website bereitgestellt
- JAP: `bilder/japa.jpg`; Band- und Konzerttext direkt für die Website bereitgestellt
- Veranstaltungsort: lokal vorhandene Angabe „Haus Bollheim · Zülpich“; die Website verlinkt deutlich gekennzeichnet auf die offizielle externe Seite von Haus Bollheim.

### Nicht veröffentlichte bzw. uneindeutige Zuordnungen

- Für Mela enthält die DOCX-Quelle sowohl eine Ich-Fassung als auch eine mit „Oder in der 3. Person:“ bezeichnete Fassung. Beide Fassungen werden vollständig und unverändert wiedergegeben.

## Lokale Vorschau

`index.html` kann direkt im Browser geöffnet werden. Alternativ im Projektordner einen beliebigen statischen Webserver starten, zum Beispiel:

```powershell
python -m http.server 8000
```

Danach `http://localhost:8000/` öffnen. Die GitHub-Pages-Auslieferung funktioniert direkt aus dem Repository und benötigt keinen Build-Schritt.

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Einzelheiten stehen in `LICENSE`.
