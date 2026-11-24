# Voltlogik UG – Website

Schlanke statische Website (reines HTML/CSS, kein WordPress, kein JavaScript, keine externen Dienste) für voltlogik.de, gehostet bei Hetzner.

## Seiten
- `index.html` – Start
- `leistungen.html`, `referenzen.html`, `ueber-uns.html`, `kontakt.html`
- `impressum.html`, `datenschutz.html` – Entwürfe, Angaben in [ ] ausfüllen

## Sicherheit
`.htaccess` erzwingt HTTPS, setzt Security-Header (HSTS, CSP, X-Frame-Options usw.) und sperrt alte WordPress-Pfade.

## Deployment
Alle Dateien per SFTP in das Web-Verzeichnis des Hetzner-Webhostings laden (vorher Backup der alten WordPress-Seite).
