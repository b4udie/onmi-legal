# Onmi — legal documents

Published documents for the Onmi iOS app by Valentyn Bratkevych:

- **Privacy Policy** — https://b4udie.github.io/onmi-legal/privacy-policy.html
- **Terms of Use** — https://b4udie.github.io/onmi-legal/terms-of-service.html

These are the URLs referenced from App Store Connect and opened inside the app, so they must
keep working: do not rename the files, do not rename this repository, and do not disable
GitHub Pages.

## Updating

1. Edit the HTML directly, or re-run the `legal-docs` skill in the app repository.
2. Update the `Effective date` and `Last updated` lines in the file you changed.
3. Commit and push to `main` — GitHub Pages redeploys automatically within a minute or two.

Announce material changes inside the app before they take effect.

## When these documents must be revisited

- a new SDK, analytics or crash reporting tool is added;
- accounts, subscriptions or user-generated content appear in the app;
- data starts leaving the device, or starts going to a new third party (including AI providers);
- the app changes its audience (for example, becomes directed to children).

The answers in App Store Connect → App Privacy must always match what the Privacy Policy says;
a mismatch is a rejection.

## Layout

```
index.html              landing page linking both documents
privacy-policy.html     Privacy Policy
terms-of-service.html   Terms of Use (EULA)
styles.css              shared styles, no external dependencies
.nojekyll               serve files as-is, without Jekyll processing
```

---

Generated from a template and populated with this app's actual data practices. **Not legal
advice** — have a lawyer review both documents before release. Questions:
[bratkevychv@proton.me](mailto:bratkevychv@proton.me) · Last updated: 26 September 2026
