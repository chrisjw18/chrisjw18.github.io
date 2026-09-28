# FieldApp Notebook website

Static website for [fieldapp.org](https://fieldapp.org), published by GitHub Pages from `main` at `/`.

The September 2026 refresh uses the approved terrain artwork, bright app icon, authentic iPhone/iPad screenshots and a 20-second promotional film. All media is hosted locally. The site has no analytics, external font services or third-party video embeds. Video is click-to-play, starts muted and does not preload; captions and a written description are included.

## Release wording

Version 1.2 is publicly available. Its release was verified on the public UK App Store listing on 26 September 2026, including the updated description and version history. The site now presents the screenshots, film and features as part of the released app.

The release notice, hero availability note, version-1.2 section, screenshot/video labels, search/share descriptions and availability FAQ in `index.html` were updated together. For future releases, verify public availability before changing these claims; approval alone is not public release. Keep screenshots and the privacy policy aligned with the released app. No automatic release-status monitor is installed.

## Development

Serve this directory using any static HTTP server. There is no build step. Test `index.html`, `privacy.html` and all pages under `guides/` at desktop, tablet and phone widths, check local links, and test the native video player when changing its implementation before publishing. Keep the existing `CNAME` and privacy-policy substance intact when changing the presentation.

## Fieldwork guides and search

The homepage links to three practical guides: offline field data collection, custom survey forms, and CSV/media export to Excel. Instructions and screenshots describe public version 1.2; do not advertise unreleased beta features. Each guide has its own title, description, canonical URL, social metadata and links to related workflows. The sitemap lists the homepage, privacy policy and all three guides. Update `lastmod` only for substantive page changes.

Search Console setup is managed separately from visitor analytics; no analytics script or tracking cookie is required for these guides. Account ownership/verification and indexing status must be confirmed in Search Console, not inferred from the presence of the sitemap. Public availability of a page is not proof that Google has indexed or ranked it. Do not publish private account details, search-performance reports or working notes in this repository.
