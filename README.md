# 🦷 Pottbrock ZFA Recruiting Dashboard

Bewerber-Management für die kieferorthopädische Praxis Dr. Pottbrock.

## Features

- **Passwortschutz** – Zugang nur mit Passwort, wird im Browser gespeichert
- **Kanban-Board** – 6 Spalten: Neu → Kontaktiert → Nicht erreicht → VG → Zusage → Absage
- **Swipe-Navigation** – Zwischen Spalten swipen (iPhone optimiert)
- **Klickbare Status-Leiste** – Direkt zu jeder Spalte springen
- **E-Mail Import** – Bewerbungs-Mails von finanzerfahrungen.de einfügen & auto-parsen
- **Quick Actions** – Direkt Anrufen, WhatsApp, E-Mail von jeder Karte
- **Notizen** – Pro Bewerber Notizen hinterlegen
- **Offline-fähig** – Alle Daten im localStorage, kein Server nötig
- **Apple Liquid Glass Design** – Glasmorphismus UI

## Deployment auf GitHub Pages

### 1. GitHub Repository erstellen

```bash
# Im Terminal:
git init
git add .
git commit -m "Initial commit: Pottbrock Recruiting Dashboard"
git branch -M main
git remote add origin https://github.com/DEIN-USERNAME/pottbrock-recruiting.git
git push -u origin main
```

### 2. GitHub Pages aktivieren

1. Gehe zu **Settings** → **Pages** im Repository
2. Source: **Deploy from a branch**
3. Branch: **main** / Folder: **/ (root)**
4. Save

### 3. Fertig!

Nach 1-2 Minuten erreichbar unter:
```
https://DEIN-USERNAME.github.io/pottbrock-recruiting/
```

## Passwort

Das Passwort wird einmalig eingegeben und dann im Browser gespeichert.
Abmelden über das 🔒 Icon oben rechts.

## Technologie

- Vanilla HTML/CSS/JavaScript (kein Build-Step, kein Framework)
- localStorage für Datenpersistenz
- CSS backdrop-filter für Glaseffekte
- Touch-Events für Swipe-Navigation
