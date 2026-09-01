# Pediatric Hospital World — MAX REAL v4

Isolated iPhone-first pediatric cardiology hospital environment.

## Safety boundary

This repository is intentionally standalone. It does **not** modify or depend on the existing `stevetodman.com`, `3dworld`, or other simulator repositories.

## Launch

Open the hosted site. On iPhone, use Safari in landscape. For an app-like icon: **Share → Add to Home Screen**.

## Hosting

The included GitHub Actions workflow deploys the repository root as a static GitHub Pages site after Pages is enabled for this repository with **GitHub Actions** as the source.

## Privacy/discoverability

The app includes `noindex, nofollow, noarchive` metadata. This reduces accidental search-engine discovery but is **not authentication**. Do not add real patient data, PHI, API secrets, or private credentials to this repository or browser app.

## Architecture

- Static single-page Three.js hospital world
- PWA manifest + service worker
- iPhone touch controls and landscape layout
- No backend and no API keys
