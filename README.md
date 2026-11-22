# ChargeKaro website

Marketing website for ChargeKaro: find verified EV charging stations, pre-book a charging slot, and partner with us as a station owner.

A single static page with no build step: `index.html` plus `assets/`.

## Hosting on Netlify
- Publish directory: the repo root. There is no build command.
- The partner form in "For charging station owners" does two things in the background:
  1. Saves the request in ChargeKaro's Supabase database (`submit_partner_request`), shown on the Admin panel's "Partner requests" page.
  2. Emails it to chargekaroo@gmail.com through FormSubmit (formsubmit.co).
  The visitor sees "Thank you" right away and is warned only if both fail.

## Contact
chargekaroo@gmail.com · +91 83095 15062
