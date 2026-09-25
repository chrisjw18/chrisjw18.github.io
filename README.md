# FieldApp Notebook website

Static website for [fieldapp.org](https://fieldapp.org), published by GitHub Pages from `main` at `/`.

The September 2026 refresh uses the approved terrain artwork, bright app icon, authentic iPhone/iPad screenshots and a 20-second promotional film. All media is hosted locally. The site has no analytics, external font services or third-party video embeds. Video is click-to-play, starts muted and does not preload; captions and a written description are included.

## Release wording

Version 1.2 is awaiting App Store review. The site explicitly identifies the new interface and features as previews; the App Store link currently offers version 1.1. Do not switch to “available now” merely because Apple approves the update: wait for the public release to be verified.

At launch, update the release notice, hero availability note, version-1.2 section, screenshot/video labels and availability FAQ in `index.html`. Keep screenshots and the privacy policy aligned with the released app. No automatic release-status monitor is installed.

## Development

Serve this directory using any static HTTP server. There is no build step. Test `index.html` and `privacy.html` at desktop, tablet and phone widths, check local links, and test the native video player before publishing. Keep the existing `CNAME` and privacy-policy substance intact when changing the presentation.
