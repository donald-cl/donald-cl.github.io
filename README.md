# donald-cl.github.io

This site exists **only** to satisfy Google's OAuth branding requirements for the
personal Cloud project "vibecoder": a Google-verifiable home page, a privacy
policy, and an authorised domain, so the OAuth app can be published to "In
production" instead of expiring its login every 7 days.

- `index.html` — what vibecoder is (a single-user personal tool).
- `privacy.html` — privacy policy, including the Google API Services User Data
  Policy **Limited Use** statement and how to revoke access.
- `terms.html` — short terms of use.

Plain static HTML: no JavaScript, no analytics, no trackers, no build step, and
no code from any other repository. Served by GitHub Pages from `main`, root.

Search Console verification (HTML file or meta tag) is added by
`tools/site-verify` in the vibe-projects queue repo; the meta-tag variant
replaces the `<!-- site-verification -->` line in `index.html`.

Google Branding settings this site backs:

| Field             | Value                                       |
|-------------------|---------------------------------------------|
| Home page         | https://donald-cl.github.io/                |
| Privacy policy    | https://donald-cl.github.io/privacy.html    |
| Authorised domain | donald-cl.github.io                         |
