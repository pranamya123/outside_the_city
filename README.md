# Outside The City — Wireframes (team review)

Hi-fi wireframes for an `outsidethecity.org` refresh. Five static pages wired with a shared header/footer, warm earthy design system, and lightweight interactivity.

## Review locally

Open `index.html` in any browser — no build step, no server needed. All pages link to each other.

```bash
# macOS
open index.html
```

## Pages

| File | What's on it |
|---|---|
| [`index.html`](index.html) | Home — hero, "We Create Firsts", 4-way Engage grid, sponsors, "Hope Begins Outside" testimonial, 501(c)(3) strip |
| [`about.html`](about.html) | Mission · DOJ gang stats · Life Resume Experiences · gallery · team bios |
| [`involved.html`](involved.html) | 3 paths · 5 volunteer roles · corporate CSR deep dive · sponsors |
| [`donate.html`](donate.html) | Monetary/Product track switcher · amount tiers · Classy.org CTA · product workflow |
| [`contact.html`](contact.html) | 5-intent picker with per-intent form · SoCal map · FAQ |
| [`styles.css`](styles.css) | Shared design tokens (earth palette, DM Serif + Instrument Sans, pill buttons) |

## What the design pulls from the live site

- Audience: formerly gang-involved and previously incarcerated **adult** men & women
- Tagline: **"Adventure. Healing. Second chances."**
- Signature phrases: **"We. Create. Firsts."** / **"Hope. Begins. Outside."**
- Coverage: Orange · San Diego · LA Counties (and beyond)
- Parent org: Teen Health, Inc. · 501(c)(3) · EIN 87-4628884 · founded 2022
- Contact: `info@outsidethecity.org`
- "Life Resume Experiences" coined-term callout
- DOJ gang stats (21,500+ gangs, 731,000 members, ages 12–24, age 15 median)
- Five volunteer roles: Wilderness Guides, Team Builders, Endurance Athletes, Seniors, Lifeguards
- Real team bios: Scott Swift (Founder), Darren Porter, Corey Swift, Stephen Chee (Advisory)
- Current sponsors: Orgain, TMR, Carlson, Outward Bound, PE Partners
- Two donation tracks: Monetary (Classy.org campaign 628076) + Product donation

## What this design adds vs. the live site

- Four-way **Engage grid** on Home
- **Amount tiers** on Donate with impact labels ($25 → $2,500)
- **5-intent Contact form** with fields that adapt per intent
- **4-step product donation workflow**
- Deep **Corporate CSR section** (6 engagement modes)
- **Newsletter subscribe** in footer
- **FAQ** on Contact (placeholder answers — needs org sign-off)
- **SoCal map** with service-area pins on Contact

## Still open

- Stories page (nav placeholder — decision deferred)
- Real testimonial copy (Marcus quote on Home is a placeholder)
- FAQ answers on Contact need org sign-off
- Imagery is Unsplash placeholders — needs real outing photography

## Notes on implementation

- No framework — vanilla HTML/CSS + ~20 lines of JS per interactive page
- Fonts loaded from Google Fonts (DM Serif Display, Instrument Sans, JetBrains Mono)
- Design tokens live as CSS custom properties at the top of `styles.css`
