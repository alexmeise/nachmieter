# nachmieter

Hosts my home in search of a nachmieter.

Statische Seite für ein Nachmieter-Inserat, gebaut mit Jekyll und dem `minima`-Theme,
deploybar über GitHub Pages.

## Inhalt anpassen

- `_config.yml` — Titel, Beschreibung, Name/E-Mail, `repository`.
- `index.md` — Eckdaten, Miete, Beschreibung (alle `PLATZHALTER` ersetzen).
- `galerie.md` — Fotos; Dateien in `assets/images/` ablegen und `src`-Pfade anpassen.
- `kontakt.md` — Kontaktangaben.

## Lokal bauen (fish shell)

```fish
bundle install
bundle exec jekyll serve
```

Dann im Browser: http://localhost:4000

## Deployment auf GitHub Pages

1. Repo auf GitHub pushen (Branch `main`).
2. In **Settings → Pages → Build and deployment → Source** auf **GitHub Actions** stellen.
3. Der Workflow unter `.github/workflows/pages.yml` baut und deployt automatisch bei jedem Push auf `main`.
