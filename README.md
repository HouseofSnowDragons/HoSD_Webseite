# No Risk Inferno x House of Snow Dragons Webseite

Diese Vorlage ist direkt für GitHub Pages vorbereitet.

## Dateien

- `index.html` = Hauptseite
- `assets/logo.png` = Logo
- `assets/hero-bg.png` = Hintergrundbild
- `assets/character.png` = Charakterbild
- `.nojekyll` = verhindert GitHub-Jekyll-Probleme

## GitHub Pages Anleitung

1. Erstelle auf GitHub ein neues Repository, z. B. `hosd-webseite`.
2. Lade alle Dateien aus diesem Ordner in das Repository hoch.
3. Gehe in GitHub auf `Settings`.
4. Öffne links `Pages`.
5. Bei `Build and deployment` wähle:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Speichern.
7. Nach kurzer Zeit ist die Webseite online.

## Wichtig

Die Datei `index.html` muss im Hauptordner liegen, nicht in einem Unterordner.
Die Bilder müssen im Ordner `assets` bleiben, weil die Webseite diese Pfade verwendet:

- `assets/logo.png`
- `assets/hero-bg.png`
- `assets/character.png`
