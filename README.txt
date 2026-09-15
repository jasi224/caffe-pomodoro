# Caffè Pomodoro – iPhone Web-App

Diese Version ist als Progressive Web App (PWA) vorbereitet.

## Auf dem iPhone
1. Die Dateien müssen einmal über eine HTTPS-Adresse erreichbar sein.
2. Die Seite in **Safari** öffnen.
3. **Teilen** → **Zum Home-Bildschirm** → **Hinzufügen**.
4. Danach startet Caffè Pomodoro wie eine eigene App.

## Wichtig
Die App nutzt weiterhin einige externe Bibliotheken/Fonts. Nach dem ersten Laden können diese vom Service Worker zwischengespeichert werden. KI-Funktionen benötigen weiterhin Internetzugang.

## Dateien
- `index.html` – die App
- `manifest.json` – App-Definition
- `service-worker.js` – Offline-/Caching-Unterstützung
- `icons/` – App-Icons
