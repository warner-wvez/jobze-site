# jobze-site

The marketing landing page and private beta waitlist for JOBZE. Live at [jobze.io](https://jobze.io).

JOBZE is a job search command center for students and recent grads. It reads your resume, scores it against real peer benchmarks, learns your preferences, researches companies in real time, and handles the parts of the job search that eat your entire week. The free scorer is the onramp: paste a job description, paste your resume, get a deterministic score, a verdict, and three concrete fixes. No signup, no card.

This repository is the public-facing site only. The scoring engine and the product app live in separate repositories.

## Contents

- `index.html`: desktop landing page with the embedded scorer demo and the waitlist form
- `mobile.html`: mobile-optimized variant
- `profile.html`: deep profile form for waitlist signups
- `site.webmanifest`, `favicon.*`, `apple-touch-icon.png`, `android-chrome-*.png`: PWA manifest and app icons
- `CNAME`: binds the custom domain jobze.io

## Stack

Vanilla HTML, CSS, and JavaScript. No build step. Type stack: Inter, IBM Plex Mono, and Syne. Hosted on GitHub Pages, served from `main`.

## Status

Live. Private beta for students and recent grads. Waitlist open.

Part of [WVEZ Solutions](https://wvez.org).
