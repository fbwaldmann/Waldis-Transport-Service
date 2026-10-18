# Waldis Transportservice – Website

Statische Website für Waldis Transportservice (Oerlenbach), gehostet mit GitHub Pages.

## Aufbau

- `index.html` – Startseite
- `impressum.html`, `datenschutz.html` – Rechtstexte
- `css/style.css` – Styles
- `img/` – Fotos
- `.github/workflows/pages.yml` – Veröffentlichung auf GitHub Pages

## Veröffentlichen

1. Im Repository unter **Settings → Pages** bei *Source* **GitHub Actions** auswählen.
2. Änderungen auf den Branch `main` pushen – die Seite wird automatisch veröffentlicht
   (oder unter **Actions → GitHub Pages → Run workflow** manuell starten).
3. Die Adresse lautet dann `https://fbwaldmann.github.io/Waldis-Transport-Service/`.

Eigene Domain: unter **Settings → Pages → Custom domain** eintragen und beim Domain-Anbieter
einen CNAME-Eintrag auf `fbwaldmann.github.io` setzen.

## Lokal ansehen

```sh
python3 -m http.server 8000
```

Dann <http://localhost:8000> öffnen.
