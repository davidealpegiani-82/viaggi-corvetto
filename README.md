# Tabella Viaggi — Corvetto

App PWA per la gestione dei **viaggi, trasferimenti e ritiri** della filiale Centroedile di Corvetto.

## Repo correlati
- [turni-corvetto](https://github.com/davidealpegiani-82/turni-corvetto) — Gestione Turni
- [matrice-versamenti-corvetto](https://github.com/davidealpegiani-82/matrice-versamenti-corvetto) — Matrice Versamenti Casse

## Pubblicazione su Netlify

### Opzione A — Drag & drop
1. Vai su https://app.netlify.com/drop (o Deploys del sito esistente)
2. Trascina lo zip / cartella di deploy
3. Apri l’URL HTTPS dal telefono o PC

### Opzione B — Collegamento Git (consigliato)
1. Su Netlify: **Add new site → Import an existing project** (o collega questo repo al sito già esistente)
2. Build command: *vuoto*
3. Publish directory: `.`
4. Deploy

Sito attuale: https://bejewelled-shortbread-65b56c.netlify.app/

### Dopo il deploy
- Usa sempre il link Netlify (non il file locale) per lo sync Firebase
- Sul telefono: “Aggiungi a Home” / Installa app
- In caso di aggiornamento: popup in-app oppure rimuovi e reinstalla la scorciatoia

## Contenuto
- `index.html` — app completa (viaggi, trasferimenti, ritiri, PDF, email, PWA)
- `manifest.webmanifest` + `icon-*.png` — icona e installazione app
- `sw.js` — service worker / cache versionata
- `version.json` — versione per avviso aggiornamento
- `netlify.toml` — header e fallback SPA
