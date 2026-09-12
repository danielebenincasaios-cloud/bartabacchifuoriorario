# Bar-Tabacchi Fuori Orario

Sito statico (HTML/CSS/JS, nessuna build necessaria) per il Bar-Tabacchi Fuori Orario di Sant'Antonio, Porto Mantovano (MN).

## Deploy su Vercel

1. Importa questo repository su [vercel.com/new](https://vercel.com/new).
2. Framework preset: **Other** (sito statico) — nessuna build command, nessuna output directory da configurare, Vercel serve direttamente `index.html`.
3. Deploy.

## Da fare prima di andare online

Le immagini in `uploads/` sono **placeholder** (SVG generati), perché le foto reali non erano disponibili come file durante l'implementazione:

- `uploads/logo.svg` → sostituire con il vero logo (es. `uploads/LOGO.jpeg`)
- `uploads/team.svg` → sostituire con la vera foto di Antonio e Gaetano (es. `uploads/ANTONIOeGAETANO.jpeg`)

Dopo aver caricato i file reali, aggiorna i riferimenti `src` in `index.html` (cerca `uploads/logo.svg` e `uploads/team.svg`).

Sono presenti anche alcuni contenuti segnaposto da confermare con i titolari:
- Prezzi del menu (`[PREZZO]`)
- Servizi di tabaccheria (`[DA CONFERMARE]`)
- Info parcheggio (`[DA CONFERMARE]`)
