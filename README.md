# CARAT GitHub Pages Kit

This folder is a ready-to-publish static GitHub Pages package for the public-facing CARAT GitHub site.

## What it is for

Use this as the **public product face** of CARAT on GitHub:

- project overview
- trust and methodology summaries
- official links
- Chrome extension install area
- roadmap and public docs links

Do **not** use this page for:

- VPS or deployment secrets
- internal endpoints
- infrastructure notes
- admin documentation
- anything operationally sensitive

## Recommended GitHub structure

For an organization page, GitHub Pages expects a repository named:

`CARATProtocol.github.io`

GitHub Docs reference:

- https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages

## Suggested public links

- Main website: `https://caratprotocol.com`
- Engine: `https://caratprotocol.com/carat/engine`
- Extension privacy: `https://caratprotocol.com/carat/extension-privacy`
- GitHub org: `https://github.com/CARATProtocol`

## Updating the Add to Chrome button later

When the Chrome Web Store listing is approved:

1. Open `index.html`
2. Find the button text:
   - `Add to Chrome (coming soon)`
3. Replace the placeholder `href="javascript:void(0)"`
4. Use the real Chrome Web Store URL
5. Remove the `button-disabled` class

