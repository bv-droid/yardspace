# YARD — Open in July · Semey

Cinematic scroll-driven launch site for **YARD**, a multifunctional loft space on the Irtysh river in Semey, Kazakhstan.

Open the film: **Earth → Kazakhstan → Semey → the building** — then `Войти →` to step inside.

- **Landing** — `index.html` — bilingual ҚАЗ/РУС, animated logo, 3 marketing headlines, 4 scroll-scrubbed films, "Открытие в июле".
- **Inside** — `inside.html` — 1F YARD Café + Academy (interactive), 2F anti-café with 8 zones (interactive), contacts + map.

## Stack
Static HTML/CSS/JS. No build, no framework. Static hosting only.

- Cormorant Garamond · Inter · JetBrains Mono (Google Fonts)
- 4 H.264 mp4 films in `video/` (~29 MB total, 720p)
- Floor renders `floor1.png` / `floor2.png` with click-tooltip hotspots
- OG share image: `og.png`

## Run locally
```bash
python3 -m http.server 4178
# open http://localhost:4178/
```

## Deploy
Drop the repo onto any static host: **GitHub Pages, Netlify, Vercel, Cloudflare Pages**, or plain S3/Nginx. No env vars, no build step.

For GitHub Pages: Settings → Pages → Source: `main` branch, `/ (root)`.

## Contacts
- admin@yardspace.kz
- Instagram [@yardspace](https://instagram.com/yardspace)
- ул. К. Мухамедханова 36г, Семей, Қазақстан

---
© 2026 YARD · Designed by eDesign Interactive
