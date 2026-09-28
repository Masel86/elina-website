# Elina Bindze – Website mit Live-Editor

Statische Landingpage (Tailwind CDN) für die mobile Fuß- und Handpflege,
erweitert um einen In-Place-Editor mit Admin-Login.

## Dateien
- `index.html` – die komplette Seite inkl. Editor und Login.

## Bearbeiten (Admin)

Login öffnen:
- Tastenkürzel `Strg` + `Shift` + `E`, oder
- URL um `#admin` ergänzen: `index.html#admin`

Standard-Zugangsdaten (im `<script data-purpose="admin-editor">` in `index.html` änderbar):
- Name: `elina`
- Passwort: `elina2024`

Nach dem Login erscheint unten die Admin-Leiste:
- **Bearbeiten starten** – Texte werden direkt editierbar; Klick auf ein Bild
  erlaubt Datei-Upload oder Eingabe einer Bild-URL.
- **Als HTML exportieren** – lädt `elina-bearbeitet.html` mit allen Änderungen
  herunter (ohne Editor-Code). Diese Datei online stellen.
- **Änderungen verwerfen** – zurück zum Original.
- **Abmelden** – Sitzung beenden.

## Wichtige Hinweise
- **Kein echter Schutz:** Der Login läuft nur im Browser. Wer die HTML-Datei
  öffnet, kann Name/Passwort im Quelltext sehen. Für echten Schutz ist ein
  Server-Backend nötig. Zugangsdaten trotzdem auf eigene Werte ändern.
- **Speicherung:** Änderungen liegen im `localStorage` des jeweiligen Browsers,
  nicht für andere Besucher. Damit alle die neue Version sehen: exportieren und
  die exportierte Datei beim Hoster hochladen.
