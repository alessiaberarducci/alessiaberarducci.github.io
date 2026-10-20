# Alessia Berarducci — academic homepage

A buildless, responsive website for GitHub Pages. No package installation is needed.

## Update content

Edit `content.js`. The three lists are `papers`, `events`, and `courses`. Copy an existing entry to add another. Keep newest entries first.

- Papers: title, authors, year, venue, description, article URL and PDF URL.
- Events: date, type (`Talk`, `Poster`, `Conference`, or `Summer school`), optional `categories` array for multiple filters, title, venue, location, optional URL. Only add talks or attendance that actually happened or are confirmed.
- Courses: title, degree level, term, role, optional responsibilities in `details`, course URL. Instructor names are not displayed.

Edit biography, social links, and interests in `index.html`. Replace `assets/Alessia-Berarducci-CV.pdf` when updating your CV.

## Preview

Run `python3 -m http.server 8000` in this directory and open http://localhost:8000.

## Publish on the existing GitHub Pages site

Put these files in the root of `alessiaberarducci/alessiaberarducci.github.io`, preserving any existing repository configuration you need. Commit and push. In GitHub Settings → Pages, select the appropriate branch and root directory if not already configured. `.nojekyll` enables direct static-file delivery.

This local workspace was empty; these files have not been pushed to the existing public repository.

## Content sources

- Existing homepage: https://alessiaberarducci.github.io/ (biography, interests, March 2026 Bern talk).
- https://proceedings.mlr.press/v350/berarducci26a.html
- https://arxiv.org/abs/2604.27011
- https://search.usi.ch/en/people/ad40d80b1fce47930042270403691e36/berarducci-alessia/courses
- Teaching assistant roles confirmed by Alessia in chat and her supplied LinkedIn screenshot (Graphical Models and Network Science, February–June 2025; Probability & Statistics, September 2024–January 2025). Mentoring role omitted at her request.

Scholar could not be read directly. The two publication records were verified using PMLR and arXiv; both concern FairMind and are labeled separately as a conference paper and preprint. No conference attendance is inferred from authorship.

The canvas animation supports pause, reduced-motion preferences, cursor interaction, and suspends rendering offscreen. Google Fonts are optional: local font fallbacks remain usable offline.
