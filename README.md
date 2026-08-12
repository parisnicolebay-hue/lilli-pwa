# lilli-pwa

**Lilli — standalone synthetic demonstration.**
SYNTHETIC DEMONSTRATION — no real patient data.

An installable, fully static demo of the Lilli patient conversation for
**lilli.vanillios.com**, hosted on GitHub Pages in the same deployment style
as the other public demo apps on this account.

## What it is

Scripted synthetic patient journeys — choice buttons only, no free-text
clinical entry — through concern, safety screening, symptom questions,
urgency, and a simulated "send" that issues an unmistakably synthetic
reference such as `TEST-PERSON-001`. Emergency answers stop the ordinary
conversation and show a `role="alert"` panel with 911 guidance.

## What it is not

- **No backend.** Nothing is transmitted anywhere; everything happens in the
  browser. There is no API, database, analytics, or tracking of any kind.
- **No personal data.** The demo never asks for names, phone numbers, email,
  photographs, or any real patient information.
- **Not a care service.** The page says so at all times.

## Files

`index.html` · `app.css` · `app.js` · `i18n.js` · `manifest.webmanifest` ·
`service-worker.js` · `icons/` (192, 512, apple-touch, avatar, marks) ·
`robots.txt` · `CNAME`

All paths are relative, so the app runs identically from a local static
server and from the custom-domain root. The service worker caches only the
enumerated static shell — never anything else.
