# Safr landing page (Hallmark rebuild)

A from-scratch rebuild of https://safr-embassy-ready-travel.lovable.app as one static page. Open `index.html` in a browser; there is no build step.

- `index.html`: the page
- `styles.css`: page styles (starts with the Hallmark stamp)
- `tokens.css`, `base.css`: the Wayfind theme tokens and base rules
- `images/`: screenshots taken from the live Safr demo workspace (sample data only)

## Check before going live

These claims came over from the old site as they were. Confirm each one or remove it:

- 500+ UAE travel agencies, 180+ countries, 99.9% embassy compliance, under 2 hours average processing
- 214 consular rules in Atlas
- The quote from Ahmed Al Mansoori, Head of Operations, Emirates Travel Group. The old site used the same name for its sample applicant and demo user, so check that this is a real client.
- "Trusted by" Emirates, dnata, flydubai, Qatar Airways, Turkish Airlines and Air Canada (only list them with permission)
- GDPR compliant, UAE PDPL, ISO 27001

## Still to wire up

- **Request access form:** `form#access` has an empty `data-endpoint`. Set it to a URL that accepts a POST; until then the page says nothing was sent.
- **Privacy policy, Terms of service, Contact:** these link to `#`, as they did on the old site.
- **Agent sign in:** links to the live Lovable app's `/login`.

## Not carried over

- The Dubai skyline and jet photos, and the portrait beside the quote. They didn't show anything about the product.
- The "Run sample passport" simulator. Real screenshots of the workspace replace it.
- The old footer's social icons, which linked nowhere.

## Changed wording

- "Visa Management Platform" label above the headline: removed
- Hero line: shortened to "Client paperwork in, embassy-ready visa packs out in 90 seconds."
- "Watch 90s Demo": became "See the route" (it only ever scrolled to the workflow)
- "Ready to revolutionize your visa operations?": became "Join 500+ UAE agencies on Safr"
- "180+ Countries. One Platform.": became "Every line leaves from DXB"
- Destination tabs: shortened to UK, US and GCC; the full names stay in each panel
