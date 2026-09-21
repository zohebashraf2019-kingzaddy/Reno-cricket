# Reno Cricket Club Official Website

Complete static website package for Reno Cricket Club, prepared for GitHub and Vercel.

## Included
- `index.html` - complete responsive website
- `assets/rcc-logo.jpeg` - RCC logo
- `assets/committee/` - all seven standardized 2026 committee portraits
- About RCC
- 2026 committee profiles and biographies
- Tournament section
- Sponsors and partners
- Join RCC contact form
- Instagram, Facebook, YouTube and CricClubs links
- Optional YouTube live-match banner

## Deploy to GitHub
Upload the CONTENTS of this folder to the root of a new GitHub repository:
- index.html
- README.md
- assets/

Do not upload the parent ZIP itself as the website root.

## Vercel
Import the GitHub repository into Vercel. This is a static site and does not require a build command.

## Turn on the LIVE MATCH banner
Open `index.html`, find:

`const LIVE_MATCH = false;`

Change it to:

`const LIVE_MATCH = true;`

Then change `LIVE_URL` to the exact RCC YouTube livestream URL.

## Committee portraits
All portraits are standardized at 1200 x 1500 pixels and already connected to the committee cards.

## Important
The Join RCC form currently uses `mailto:`. For a production form that submits without opening the visitor's email client, connect it to a form service or backend endpoint.
