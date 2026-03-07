# GitHub Upload Anleitung

## Schritt 1: Neues Repository erstellen

1. Gehe auf https://github.com
2. Klick auf "New repository"
3. Name: `SammleRSS`
4. Public auswählen
5. Klick auf "Create repository"

## Schritt 2: Dateien hochladen

### Option A: Per Drag & Drop (einfach)
1. Auf der Repository-Seite: "uploading an existing file" klicken
2. Diese Dateien auswählen und hochladen:
   - `SammleRSS.html`
   - `feeds.json` (falls vorhanden)
   - `favicon.ico` (optional)
   - `logo.png` (optional)

### Option B: Per Git (fortgeschritten)

```bash
# Repository klonen
git clone https://github.com/DEIN-USERNAME/SammleRSS.git

# Dateien rein kopieren
cp SammleRSS.html SammleRSS/

# Pushen
cd SammleRSS
git add .
git commit -m "Initial commit"
git push
```

## Schritt 3: GitHub Pages aktivieren

1. Im Repository auf "Settings" klicken
2. Links auf "Pages" klicken
3. Bei "Source": "Deploy from a branch"
4. Branch: "main" auswählen
5. "/ (root)" auswählen
6. Save klicken

## Schritt 4: URL finden

- Nach ~1-2 Minuten erscheint die URL unter "Pages"
- Format: `https://DEIN-USERNAME.github.io/SammleRSS/`

## Fertig! ✓

Teile die URL mit allen - sie können die App sofort nutzen!
