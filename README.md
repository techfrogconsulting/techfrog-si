# TechFrog.SI — TechFrog.AI mirror

Marketing website for Tech Frog’s custom offline AI systems for homes and businesses.

## Run locally

No package dependencies or build step are required. From the repository root:

```sh
python3 -m http.server 4173
```

Open http://127.0.0.1:4173.

## Files

- `index.html`: page content, metadata, FAQ, process, and inquiry links.
- `styles.css`: responsive layouts, typography, aqua accent, logo framing, and reduced-motion support.
- `script.js`: mobile navigation and email copying.
- `assets/`: owner-supplied TechFrog.AI logo and self-hosted fonts.
- `CNAME`: `techfrog.si` custom-domain declaration.
- `.nojekyll`: existing marker for direct static publication.

## Publishing

This repository uses GitHub Pages with `main` and the repository root. Keep the existing `CNAME` and `.nojekyll` files when updating the website. The page, styles, JavaScript, fonts, logo, inquiry links, and commercial terms are identical to https://github.com/techfrogconsulting/techfrog-ai. The canonical and social URLs remain https://techfrog.ai/ as the primary version.

To update the mirror, copy the current website files from the source repository, retain this repository’s `CNAME`, and push to `main`.

## Contact and engagement

All inquiries go to `chat@techfrog.ai` with subject `Offline AI System Inquiry` and the agreed three-line inquiry template. The introductory conversation is free, and confidential information is reserved until after an NDA.

The paid assessment is **The AI Design Brief — $1,500**. Its full scope and terms appear on the page.

## Brand assets

The supplied silver/aqua TechFrog.AI logo is retained unchanged. CSS frames display the complete lockup or frog symbol. Fonts are hosted locally.
