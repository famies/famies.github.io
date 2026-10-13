# Famies Enterprises website

Website for Famies Enterprises, Ifeanyi's real-estate business in Enugu (land banking, site-and-service plots, physical verification of property). Mike Agu is building it for him.

## Where things stand
* `index.html` is the first draft: one page, Tailwind from the CDN, a contact form written for Netlify Forms. It has not been published anywhere.
* This is a separate project from Spotter (`../geoai-land-speculator`). Spotter is Mike's private land-research tool and has no agent or seller features; do not add listings or Famies branding there, and do not copy Spotter's data or maps into this site. Ifeanyi uses Spotter as an invited member, like anyone else.

## Rules for the copy
* Do not say "verified", "clear title" or "secure" about land unless the page says exactly what was checked, by whom and when. A buyer who relies on those words and loses money has a claim against the business.
* No prices, plot numbers or owners' names on the public page without Ifeanyi's say-so.
* Confirm the business name, phone, email and office address with Ifeanyi before publishing.

## Standards
* Keep it a static site unless there is a reason to add a build step.
* Never hardcode API keys; use `.env` files.
