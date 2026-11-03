# Famies Enterprises website

Website for Famies Enterprises, Ifeanyi's real-estate business in Enugu (land banking, site-and-service plots, physical verification of property). Mike Agu is building it for him.

## Where things stand
* `index.html` is one page, Tailwind from the CDN. Contact is by WhatsApp and email links (no form; GitHub Pages cannot process one). It is to be published on GitHub Pages as `famies/web` (https://famies.github.io/web/) once the `famies` org exists.
* `print/business-cards.html` is a 10-up US Letter sheet for Gartner Studios 65517 card stock (2 x 3.5 in, 2 columns x 5 rows, 0.5 in top and 0.75 in side margins). Render it with headless Chrome to `print/business-cards.pdf`; `?guides=1` adds dashed outlines for a plain-paper test print.
* Spotter is not named or linked on the site. The "We look before you buy" section describes the screening (satellite imagery, building growth, terrain) without naming the tool, because Spotter is private and not open to invitation; Ifeanyi shares screenshots with clients, nobody else gets access.
* This is a separate project from Spotter (`../geoai-land-speculator`). Spotter is Mike's private land-research tool and has no agent or seller features; do not add listings or Famies branding there, and do not copy Spotter's data or maps into this site. Ifeanyi uses Spotter as an invited member, like anyone else.

## Rules for the copy
* Do not say "verified", "clear title" or "secure" about land unless the page says exactly what was checked, by whom and when. A buyer who relies on those words and loses money has a claim against the business.
* No prices, plot numbers or owners' names on the public page without Ifeanyi's say-so.
* Confirm the business name, phone, email and office address with Ifeanyi before publishing.

## Standards
* Keep it a static site unless there is a reason to add a build step.
* Never hardcode API keys; use `.env` files.
