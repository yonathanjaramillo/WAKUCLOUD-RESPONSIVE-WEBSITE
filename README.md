# WAKUCLOUD-RESPONSIVE-WEBSITE
RESPONSIVE WEBSITE FOR AWS CONSULTING AGENCY[README.md](https://github.com/user-attachments/files/29639723/README.md)

# Waku Cloud — Official Website

> Unlimited AWS, AI & Software Engineering. One monthly membership. Avg. 48-hour delivery.

🌐 **Live site:** [wakucloud.com](https://wakucloud.com)

---

## What This Is

The official marketing website for **Waku Cloud** — a subscription-based cloud engineering service offering unlimited AWS, AI, and software builds for one flat monthly fee.

Built as a single HTML file with zero dependencies, zero frameworks, and zero build steps. Designed to feel like a premium SaaS product, inspired by the DesignJoy membership model.

---

## Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Pure HTML5 + CSS3 + Vanilla JavaScript |
| **Fonts** | Inter (Google Fonts) |
| **Animations** | CSS keyframes + JS |
| **Calendar** | Calendly inline embed |
| **Payments** | Stripe Payment Links |
| **Hosting** | Netlify |
| **Domain** | Namecheap → wakucloud.com |

No React. No Node. No build process. One file.

---

## Project Structure

```
waku-cloud/
│
├── index.html          # The entire website (single file)
├── README.md           # This file
├── .gitignore          # Files to exclude from Git
└── netlify.toml        # Netlify deployment config
```

---

## Features

- **Blue freckled mascot** brand system used throughout
- **3D tilt membership card** in hero section
- **Animated mascot** in pricing section (cursor-following eyes, blink, wave)
- **Calendly inline embed** for booking calls
- **Stripe payment links** on all purchase buttons
- **Scrolling ticker** with service tags
- **Infinite scrolling benefit cards**
- **Animated how-it-works icons** (CSS + JS)
- **FAQ accordion**
- **Mobile responsive**
- **Scroll reveal animations**

---

## Sections

1. **Nav** — Sticky with mascot logo
2. **Hero** — Headline + 3D tilting membership card
3. **Ticker** — Infinite scrolling service tags
4. **How It Works** — 3 animated line icons (Subscribe → Receive → Yours)
5. **About** — Centered quote box
6. **Services** — Colored pill cloud
7. **Benefits** — Infinite scrolling feature cards
8. **Pull Quotes** — Editorial testimonials
9. **Testimonials** — 3-column masonry grid
10. **Founder** — Dark panel with animated mascot
11. **Pricing** — Left mascot panel + right dark pricing card
12. **FAQ** — Accordion + booking card
13. **Calendly** — Full inline calendar embed
14. **CTA** — Floating mascot cluster
15. **Footer**

---

## External Integrations

### Stripe
- Payment link: `https://buy.stripe.com/00waEP11q0u0fdO0WW3oA00`
- All "Join today" and "Get started" buttons route here
- Monthly subscription: **$4,990/month**

### Calendly
- Booking link: `https://calendly.com/yonathanmlb/new-meeting`
- Embedded inline in the booking section (dark theme)
- All "Book a call" buttons scroll to this embed

### Google Fonts
- Inter (400, 500, 600, 700, 800, 900 + italic variants)
- Loaded via CDN — no local font files needed

---

## Deployment

### Netlify (current)

The site is deployed on Netlify via drag-and-drop. To update:

1. Make changes to `index.html`
2. Go to [app.netlify.com](https://app.netlify.com)
3. Open your site → **Deploys** tab
4. Drag `index.html` onto the deploy dropzone
5. Live in ~10 seconds

### Netlify via GitHub (recommended for ongoing updates)

1. Push this repo to GitHub
2. In Netlify → **Add new site → Import an existing project**
3. Connect your GitHub repo
4. Set **Publish directory** to `/` (root)
5. Set **Build command** to *(leave empty)*
6. Deploy

After that, every `git push` to `main` automatically deploys to `wakucloud.com`.

---

## Local Development

No build tools needed. Just open the file:

```bash
# Option 1 — Open directly
open index.html

# Option 2 — Serve locally (optional, for Calendly embed to work)
npx serve .
# or
python3 -m http.server 8080
```

Then visit `http://localhost:8080`

---

## Updating Content

All content is in `index.html`. Use **Find & Replace** (Ctrl+H / Cmd+H) in any text editor:

| To change | Search for |
|---|---|
| Price | `$4,990` |
| Original price | `$7,890` |
| Email | `hello@wakucloud.com` |
| Calendly link | `calendly.com/yonathanmlb/new-meeting` |
| Stripe link | `buy.stripe.com/00waEP11q0u0fdO0WW3oA00` |
| Any headline | Copy exact text from the live site |

---

## Brand System

### Colors
| Token | Hex | Usage |
|---|---|---|
| Background | `#F2EDEB` | Page background (warm cream) |
| Ink | `#0D0D0D` | Primary text |
| Blue (primary) | `#4169E1` | Mascot, links, accents |
| Blue light | `#6B8FFF` | Mascot gradient top |
| Pink | `#FF6B9D` | Freckles |
| Orange | `#FF6B00` | CTA buttons, How it works card |
| Yellow | `#fbbf24` | Subscribe card |
| Electric blue | `#4169E1` | Request card |
| Dark | `#0D0D0D` | CTA sections, pricing right |

### Mascot
The blue freckled smiley is the central brand element. Variations used:
- **Nav** — 30px logo mark
- **Hero card** — Cluster of 4 colored mascots
- **Pricing panel** — Large animated 220px mascot (cursor eyes, blink, wave)
- **FAQ panel** — Inside gradient booking card
- **CTA** — Cluster of 5 floating mascots
- **Footer** — Small logo mark

---

## Contact

- **Website:** [wakucloud.com](https://wakucloud.com)
- **Email:** hello@wakucloud.com
- **LinkedIn:** [linkedin.com/company/waku-cloud](https://linkedin.com/company/waku-cloud)
- **Calendly:** [calendly.com/yonathanmlb/new-meeting](https://calendly.com/yonathanmlb/new-meeting)

---

## License

© 2026 Waku Cloud. All rights reserved.

This codebase is proprietary. Do not copy, distribute, or reuse without written permission from Waku Cloud.
