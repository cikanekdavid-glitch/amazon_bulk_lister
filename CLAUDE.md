# Amazon Bulk Listing Generator

## Overview
A single-page HTML app for generating Amazon bulk listing flat files using AI (Claude API). Users paste ASINs, configure settings, and get a ready-to-upload flat file.

## Project Structure
- `index.html` — The entire app (HTML + CSS + JS in one file)
- `Amazon Bulk Listing Generátor.html` — Original file (kept for reference)

## Development
This is a static HTML site deployed on Vercel. No build step needed.

To preview locally, just open `index.html` in a browser.

## Deployment
The project auto-deploys to Vercel on push to `main`.
- **Live URL**: https://amazon-bulk-lister.vercel.app
- Push changes to `main` branch to deploy

## Making Changes
Edit `index.html` directly. The app is self-contained — all HTML, CSS, and JavaScript are in that single file.

After making changes, commit and push to `main`:
```bash
git add index.html
git commit -m "description of changes"
git push origin main
```
Vercel will auto-deploy within ~30 seconds.
