# QR Security User Study Static Site

<!-- RESEARCH CLASSIFICATION: MIXED (BENIGN + RISKY PAGES) -->

This repository contains a fully static GitHub Pages website for a QR-code security user study.

## Included Files

- `index.html`
- `styles.css`
- `menu/oak-street-bistro.html` (BENIGN)
- `parking/conference-center.html` (BENIGN)
- `wifi/guest-access.html` (BENIGN)
- `events/art-walk.html` (BENIGN)
- `reward/claim-free-lunch.html` (RISKY)
- `account/session-check.html` (RISKY)
- `security/update-qr-viewer.html` (RISKY)
- `redirect/short-link-preview.html` (RISKY)

## Safety Constraints Implemented

- No backend or server-side processing
- No credential submission or payment collection
- No external scripts, analytics, or trackers
- No file downloads
- No real brands
- No links to real malicious or third-party destinations
- Any risky-page form is client-side only and shows a mock alert instead of submitting

## Publish With GitHub Pages (Repo Root)

1. Push this repository to GitHub.
2. Open repository **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch), folder `/ (root)`
5. Save, then open the generated Pages URL.
