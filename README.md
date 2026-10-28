# DN360 Visuals — dn360visuals llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `dn360visualsllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/dn360visualsllc.mjs`).
> To change the content, edit that file and run `node build.mjs dn360visualsllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@dn360visualsllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
DN360 Visuals LLC is a Florida limited liability company producing 360 virtual tours, photography, video and aerial imagery, formed in 2019. Two things we settle before a shoot, both of which clients are usually surprised by. Aerial work for commercial purposes requires an FAA remote pilot certificate and, in controlled airspace, an authorization obtained before the flight — and a client who hires an uncertificated operator has exposure of their own, not just the pilot. We fly certificated or we do not fly. Second, under US copyright law the person who takes a photograph owns it unless there is a written assignment or a written work-made-for-hire agreement, so paying for images does not by itself give you the right to use them however you like. We put the licence or the assignment in writing. Site: dn360visualsllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
