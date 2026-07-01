# Echiterm Site

Landing page static pentru Echiterm, publicata prin Cloudflare Pages.

## Domenii

- https://echiterm.ro
- https://www.echiterm.ro

## Structura

- `index.html` - pagina principala
- `assets/styles.css` - stiluri CSS

## Flux de actualizare

1. Modifica fisierele local.
2. Verifica pagina in browser local.
3. Commit:
   - `git add .`
   - `git commit -m "Update landing page"`
4. Push:
   - `git push`
5. Cloudflare Pages publica automat din branch-ul `main`.

## Deploy

Cloudflare Pages este conectat la repo-ul GitHub:
`danucj/echiterm-site`

- Production branch: `main`
- Build command: gol
- Build output directory: `/` sau `.`

## Observatie

Pentru site-ul static nu este nevoie de VPS. VPS-ul va fi util mai tarziu pentru aplicatia reala, cu backend FastAPI, baza de date, autentificare si licentiere.
