# SammleRSS 🥗

Ein simpler, browser-basierter RSS-Reader.

## Features

- 🇩🇪 Deutsche Gaming-News-Feeds
- 🎨 Verschiedene Themes (Lila, Blau, Grün, etc.)
- ⚡ Phasenbasiertes Laden für schnelle Vorschau
- 🔄 Automatische Aktualisierung
- 💾 Lese-Status wird gespeichert
- 🎬 Shorts-Modus für schnelles Durchscrollen
- ☁️ Infinite Scroll

## Direkt nutzen

1. Öffne: **https://DEIN-NAME.github.io/SammleRSS/**
2. Feeds werden automatisch geladen

## Lokal nutzen (mit Python)

```bash
cd /pfad/zu/SammleRSS
python -m http.server 8000
# Dann: http://localhost:8000/SammleRSS.html
```

Oder doppelklick auf `Start SammleRSS.bat`

## Technische Details

- Kein Server nötig (Client-seitig)
- Proxies für CORS-Umbegung
- Phase 1: Schnellvorschau (neueste Items)
- Phase 2: Alle verfügbaren Items

## Für Entwickler

```bash
# Repository klonen
git clone https://github.com/DEIN-NAME/SammleRSS.git

# Änderungen pushen
git add .
git commit -m "Update"
git push
```

## Lizenz

MIT
