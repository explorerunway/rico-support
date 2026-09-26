# Rico public support site

Published on 26 September 2026 in the separate public [`explorerunway/rico-support`](https://github.com/explorerunway/rico-support) repository. GitHub Pages publishes the root of `main`, with HTTPS enforced. The Rico app source repository stays private.

Public URLs:

- `https://explorerunway.github.io/rico-support/`
- `https://explorerunway.github.io/rico-support/support.html`
- `https://explorerunway.github.io/rico-support/privacy.html`

The support and privacy pages returned HTTP 200 over HTTPS after publication, with the configured support email present and no placeholder contact text.

## Support mail

`rico-support@vishranabuilds.com` uses an enabled Cloudflare Email Routing rule forwarding to the user-selected verified destination. Domain mail settings are ready and synced. Actual inbox delivery has not been tested; routing configuration alone is not evidence of receipt.

## Maintaining the site

Keep the local `public-site` copy and the public repository in sync. Publish only these static site files. If hosting changes, update the website-hosting paragraph in `privacy.html`. Keep the public policy date and content aligned with the policy in Rico.

Use the privacy and support URLs in App Store Connect. The in-app policy links to the public privacy page.

The site contains no scripts, analytics, forms, or external assets. Its links are relative so the pages work under the GitHub Pages project path or a custom domain.
