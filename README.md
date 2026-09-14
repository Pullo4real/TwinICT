# Twin Technologies website (v4)

Static multi-page site for Twin Technologies. Deployed on Netlify with a Progressive Web App manifest/service worker.

## What's in this build
- New header: Language Services / Academy / Services dropdown tabs, a separate Careers button, and a "languages we cover" strip under the header on the homepage and Language Services pages.
- New footer: 3 lean columns (social, brand, contact) with no links duplicated from the hamburger menu.
- New pages: `careers.html`, `language-services.html` (+ 7 service pages), `academy.html` (+ 2 listing + 11 course pages, replacing `curriculum.html`), `services.html` rebuilt (+ 5 offering pages), `404.html`.
- 4 separate Netlify forms for dashboard sorting: `career-application`, `service-request`, `general-inquiry`, `academy-enrollment`.
- The floating chat button now opens a written FAQ panel instead of a live chat.
- `netlify.toml` 301-redirects the old page URLs (`curriculum.html`, the old `services/*.html` pages) to their new locations, so old links/bookmarks/search results still resolve.
- Images compressed; two unused legacy images removed.

## Still open — decide with Buuba before/at launch
- Real social media links (LinkedIn/YouTube/TikTok/Facebook/Instagram) — footer currently uses `#` placeholders.
- A real demo video for the video-thumbnail placeholder in the gallery.
- Whether to build the "translation request tracker" proof-of-skill feature (idea only, not built).
- A free Google Business Profile for local search (not part of the site itself).

## Deploy
Upload the contents of this folder to the GitHub repository connected to Netlify (GitHub mobile web UI → "Add file → Create new file", full folder paths, e.g. `academy/vibe-coding.html`). Netlify auto-deploys the root directory. `netlify.toml` handles redirects and headers automatically — no manual Netlify dashboard configuration needed.

## Replace later
- Gallery visual slots in `gallery.html` can be replaced with more photographs as they come in.
- `#` social links with live URLs when available.
- Video cards can be linked to the final video URL(s).
