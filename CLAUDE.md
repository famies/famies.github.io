# Famies Enterprises website

Website for Famies Enterprises, Ifeanyi's real-estate business in Enugu (land banking, site-and-service plots, physical inspection of property). Mike Agu is building it for him.

## Where things stand
* `index.html` is one page, Tailwind from the CDN. Contact is by WhatsApp and email links (no form; GitHub Pages cannot process one). It is published on GitHub Pages from `famies/famies.github.io` at https://famies.github.io/. The repo is public, so nothing private goes in it.
* `print/business-cards.html` is a 10-up US Letter sheet for Gartner Studios 65517 card stock (2 x 3.5 in, 2 columns x 5 rows, 0.5 in top and 0.75 in side margins), front only, with a QR code to the site. Render it with headless Chrome to `print/business-cards.pdf`; `?guides=1` adds dashed outlines for a plain-paper test print.
* Spotter is not named or linked on the site. The "We look before you buy" section describes the screening (satellite imagery, building growth, terrain) without naming the tool, because Spotter is private and not open to invitation; Ifeanyi shares screenshots with clients, nobody else gets access.
* This is a separate project from Spotter (`../geoai-land-speculator`). Spotter is Mike's private land-research tool and has no agent or seller features; do not add listings or Famies branding there, and do not copy Spotter's data or maps into this site.
* Private facts about the business (what Ifeanyi has confirmed, applications and mandates in progress, things to add later) live in the private studio23 repo at `../studio23/clients/famies/PRIVATE.md`. Read it before changing the copy, update it there, and never copy its contents into this public repo.

## Rules for the copy
* Do not say "verified", "clear title" or "secure" about land unless the page says exactly what was checked, by whom and when. A buyer who relies on those words and loses money has a claim against the business.
* Say only what a document supports, as a statement about the record with a date: "applied in August 2026", "accredited on ...", never "authorised" or "official" on its own.
* No prices, plot numbers or owners' names on the public page without Ifeanyi's say-so.
* Contact details, the CAC number and any accreditation go on the page only once Ifeanyi has confirmed them (see the private notes).

## Standards
* Keep it a static site unless there is a reason to add a build step.
* Never hardcode API keys; use `.env` files.
* `main` is protected by a global git hook; Mike pushes with `OBILABS_ALLOW_MAIN_PUSH=1`. Commit messages carry no AI attribution line.
