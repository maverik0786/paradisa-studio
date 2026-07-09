# Paradisa Studio — Project Info

## Brand
- Brand: PARADISA
- Nome pubblico: Paradisa Studio
- Dominio: paradisa.studio
- Email pubblica: hello@paradisa.studio

## Hosting & Deploy
- Hosting: Cloudflare Pages
- URL Pages: paradisa-studio.pages.dev
- Dominio custom: https://paradisa.studio
- Repository GitHub: maverik0786/paradisa-studio
- Branch produzione: main
- Deploy automatico da push su main

## Stack
- Stack: HTML, CSS, JavaScript vanilla
- Build command: nessuno
- Build output directory: .

## Email
- Incoming email: Cloudflare Email Routing
- Email in uscita: Brevo SMTP
- Dominio autenticato su Brevo con DKIM e DMARC

## Google Play Console
- Developer name: Paradisa Studio
- Email pubblica Play Store: hello@paradisa.studio
- Sito pubblico Play Store: https://paradisa.studio

## Sviluppo locale
- Preview locale: `python3 -m http.server 8000`
- Workflow: modifica locale → test → commit → push main → deploy automatico

## SECURITY NOTES
- Non salvare password nel repo
- Non salvare SMTP key nel repo
- Non salvare token/API key nel repo
- Le credenziali vanno conservate in un password manager
- PROJECT_INFO.md non deve mai contenere segreti
