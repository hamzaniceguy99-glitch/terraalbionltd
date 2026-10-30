# Terra Albion — terra albion ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `terraalbionltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/terraalbionltd.mjs`).
> To change the content, edit that file and run `node build.mjs terraalbionltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@terraalbionltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Referred) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Terra Albion Ltd is a management consultancy based near Tewkesbury, working since 2018. We take on strategy and planning, operations and process work, programme delivery and ongoing advisory support for owner-managed and mid-sized businesses. There is a British complication worth raising before an engagement rather than during it. Under the off-payroll working rules, a medium or large private sector client is responsible for determining whether a contractor's engagement is inside or outside IR35, must give a reasoned status determination statement, and can be liable for the income tax and National Insurance if it gets that wrong without taking reasonable care. A blanket determination made without looking is not compliance. So we scope work around defined deliverables and our own methods, which makes an honest determination straightforward. Site: terraalbionltd.shop
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
