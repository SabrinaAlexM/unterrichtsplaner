# MI Planer – Lehrplan 21

Eine webbasierte App für Studierende und Lehrpersonen, die den Modullehrplan **Medien und Informatik (Lehrplan 21)** übersichtlich aufbereitet und Lehrmittel kompetenzbasiert erschliesst.

---

## Funktionen

### Lehrplan
- Alle Kompetenzen des Modullehrplans MI (Kanton Thurgau) nach offiziellem LP21-Dokument
- Bereiche: **MI.1 Medien**, **MI.2 Informatik**, **Anwendungskompetenzen**
- Abgedeckt: **Kindergarten bis 3. Sekundar** (Zyklus 1, 2 und 3)
- Filterfunktion nach Zyklus
- Aufklappbare Kompetenzkarten mit zyklus-spezifischen Grundansprüchen
- Farbleitsystem nach LP21: Orange (Z1), Blau (Z2), Grün (Z3)

### Lehrmittel
Zwei Navigationsrichtungen:

**◈ Kompetenz → Kapitel**
Kompetenz wählen → alle Lehrmittel mit passenden Kapiteln werden angezeigt, Treffer hervorgehoben.

**⊞ Kapitel → Kompetenzen**
Kapitel wählen → alle enthaltenen Kompetenzen mit Kompetenzstufen werden detailliert dargestellt.

Aktuell enthaltene Lehrmittel:
- **connected 1** – 5. Klasse
- **connected 2** – 6. Klasse
- **connected 3** – 7. Klasse
- **connected 4** – 8./9. Klasse

*(Lehrmittelverlag Zürich, 2026)*

---

## Technologie

- Reine HTML/CSS/JavaScript-Datei – keine Abhängigkeiten, kein Build-Schritt
- Läuft im Browser, funktioniert offline
- Deploybar auf Vercel, GitHub Pages oder jedem statischen Hosting

---

## Deployment

### GitHub
1. Repository erstellen
2. `index.html` hochladen
3. Commit

### Vercel
1. Vercel mit GitHub-Konto verbinden
2. Repository auswählen
3. «Deploy» klicken – fertig

### GitHub Pages
1. Repository-Einstellungen → Pages
2. Branch `main`, Ordner `/root` wählen
3. Speichern – die App ist unter `https://[username].github.io/[repo]` erreichbar

---

## Datenquellen

- Lehrplan 21 Modul Medien und Informatik, Kanton Thurgau (Dezember 2016)
- connected 1–4, Lehrmittelverlag Zürich (Januar 2026)

---

## Lizenz

Dieses Projekt ist ein Bildungswerkzeug für die Lehrerinnen- und Lehrerbildung.  
Die Inhalte des Lehrplans 21 sind Eigentum der jeweiligen Kantone.  
Die Lehrmittelinhalte (connected) sind Eigentum des Lehrmittelverlags Zürich.
