# BUCKEYE — Design & Consulting Website

Static website for **BUCKEYE Design & Consulting**, a creative strategy, advertising and brand advisory studio based in Bengaluru, India.

Built with plain **HTML, CSS and vanilla JavaScript** — no frameworks, no build step, no dependencies.

## Pages

| File               | Purpose                                            |
| ------------------ | -------------------------------------------------- |
| `index.html`       | Home / hero                                        |
| `about.html`       | Studio profile                                     |
| `services.html`    | Advertising, branding & digital service offerings   |
| `clients.html`     | Client list / case work                            |
| `workshops.html`   | Workshops & training programmes                    |
| `contact.html`     | Contact details and enquiry form                   |

## Features

- Fully static — works on any hosting provider or locally in a browser
- Responsive layout with mobile navigation menu
- Live Bengaluru (IST) clock in the top bar
- "Initiate Project Brief" modal enquiry form with category selection
- Enquiry form submits via **WhatsApp** (`wa.me` deep link) — there is no backend

## Project Structure

```
├── index.html
├── about.html
├── services.html
├── clients.html
├── workshops.html
├── contact.html
├── styles.css      # all styling
├── script.js       # navigation, clock, enquiry form logic
└── README.md
```

## Run Locally

No installation or build required. Just open `index.html` in a browser:

```
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

## Deployment

Upload all files in this directory to your hosting provider's document root (e.g. Netlify, Vercel, cPanel `public_html`, or GitHub Pages). There is nothing to compile.

### GitHub Pages

1. Go to **Settings → Pages** on this repository
2. Set **Source** to `main` branch, root (`/`)
3. The site will be published at `https://<username>.github.io/buckeye-website/`

## Notes

- The enquiry form composes a WhatsApp message from the entered details and opens it in a new tab — no data is stored or sent to a server.
- Unused source imagery and deliverable PDFs are kept out of the repository via `.gitignore`.
