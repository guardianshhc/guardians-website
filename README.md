# Guardians Home Healthcare Website

This repository contains the public website for Guardians Home Healthcare.

## What this is
- A static website (HTML + CSS + JavaScript)
- No database
- No login
- The contact form must be connected to a backend endpoint to actually send messages

## File structure
- `index.html` — Main page content
- `css/styles.css` — Styling
- `js/main.js` — Navigation + form logic
- `images/` — Logo and service images

## Common edits (non-technical)
**Update phone numbers / emails / address**
- Open `index.html`
- Use search (Ctrl+F) for the phone number or email and replace it

**Update images**
- Replace files in `images/` using the same filename  
  (example: replace `logo.png` but keep the name `logo.png`)

## Contact form note
The contact form on the site should **not** collect medical details.
A short notice is included on the form asking users not to submit PHI.

## Hosting
This site can be hosted using:
- GitHub Pages (free), or
- Cloudflare Pages (recommended when using Cloudflare DNS)

If you want help with hosting or connecting the form securely, contact the site admin.


