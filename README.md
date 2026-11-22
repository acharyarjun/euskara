# Euskara Batua

Curso de euskera batua de A1 a C2, de [Arjun Acharya](mailto:acharyarjun@gmx.com) (Bilbao).

**Web:** [https://acharyarjun.github.io/euskara/](https://acharyarjun.github.io/euskara/)

This repository publishes the Euskara Batua **web app** on GitHub Pages. It is not uploaded to Hostinger.

## What’s here

Version **1.1.1** of the production web build, with asset and router paths rewritten for the Pages base `/euskara/`.

The original application source lived in a Cursor Origin repository created by a cloud agent. That Origin repo was not accessible when this GitHub repository was created, so this tree contains the published web app (HTML, CSS, JS, icons and legal pages), not the full TypeScript/Vite source. A later commit can add the source if it becomes available.

No keystores, `.env` files or signing secrets are in this repository.

## Pages

The site is served from the `gh-pages` branch at:

- App: https://acharyarjun.github.io/euskara/
- Sign in: https://acharyarjun.github.io/euskara/entrar
- Privacy (ES + EN): https://acharyarjun.github.io/euskara/privacy/
- Data deletion (ES + EN): https://acharyarjun.github.io/euskara/data-deletion/

SPA deep links are handled by `404.html` (a copy of `index.html`). `/euskara/entrar` is also a real folder so that URL returns HTTP 200.

## Auth (Supabase)

In the Supabase project dashboard, set:

- **Site URL:** `https://acharyarjun.github.io/euskara/`
- **Redirect URLs:** `https://acharyarjun.github.io/euskara/**` and `com.arjunacharya.euskera://auth`

Those settings can only be changed in the dashboard.

## Licence / contact

The course content and the app are © Arjun Acharya. Contact: acharyarjun@gmx.com.
