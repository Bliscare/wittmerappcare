# Wittmer AppCare Website

Statische Website für `wittmerappcare.ch`, veröffentlicht über Cloudflare Pages.

## Cloudflare Pages

- Projekt: `wittmerappcare`
- Produktionsbranch: `main`
- Build command: leer
- Build output directory: `.`
- Root directory: Repository-Root

Für diese Website ist kein separater Cloudflare Worker nötig. Das Pages-Projekt
übernimmt Deployment, benutzerdefinierte Domains, Weiterleitungen und Header.

## Domains und E-Mail

- `wittmerappcare.ch` und `www.wittmerappcare.ch` dem Pages-Projekt zuweisen.
- `www.wittmerappcare.ch` dauerhaft auf `https://wittmerappcare.ch` umleiten.
- Cloudflare Email Routing für `kontakt@wittmerappcare.ch` aktivieren.
- Die Zieladresse muss in Cloudflare bestätigt sein.
