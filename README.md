# Kassora — Webseiten

Quelle der Seite https://kassora.craftec.ch (Startseite DE/EN, Datenschutz, Support). Statisches HTML/CSS ohne externe Aufrufe — kein CDN, keine Google Fonts, kein Analytics.

- `site/` = ausgelieferte Seite (Cloudflare Pages, Projekt `kassora`, ohne Git-Anbindung; Deploy von Hand: `npx wrangler pages deploy site --project-name kassora --branch main`).
- Die Dateien im Wurzelordner (`index.html`, `datenschutz.html`, `support.html`) sind nur Weiterleitungen der alten GitHub-Pages-Adresse auf die neue Domain.
- `docs/RECHERCHE_REGISTER.md` hält fest, was vor dem Bauen geprüft wurde.
