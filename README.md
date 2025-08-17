# Loyalty Card Registration System

This project is a **Loyalty Card Registration System** built using HTML, TailwindCSS, and JavaScript.  
It provides two main parts:
- **Registration Form** for users to register and upload their information, photo, and signature.
- **Admin Portal** to view, manage, print, and delete loyalty card applications.

## Files

- `online_viewer_net.htm` → Original bundled file (HTML + CSS + JS inline)
- `styles.css` → Extracted CSS from <style> blocks
- `scripts.js` → Extracted JavaScript from <script> blocks
- `README.md` → Documentation

## Features

- Multi-step registration form (Details → Photo → Signature → Submit)
- Automatic ZIP code & gender detection
- Signature pad with mouse/touch support
- Claim stub generation, print, and download
- Admin portal for managing applications (status, print, delete)
- Data stored in browser `localStorage`

## Usage

1. Open `online_viewer_net.htm` directly in a browser.  
2. If you want to use external files:
   - Link `styles.css` in the `<head>`
   - Link `scripts.js` before the closing `</body>` tag
