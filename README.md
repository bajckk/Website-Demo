# Spotify – Login and Registration (School Demo)

A Spotify-style login and registration page made for school. It is a demo only: **no real authentication, no server, no stored accounts**. Not affiliated with Spotify. The interface is in Slovenian.

## Features

- Dark, responsive layout
- Login/Registration tabs switched with CSS only
- Form validation with [SweetAlert2](https://sweetalert2.github.io/) alerts listing every error, with invalid fields highlighted in red
- Falls back to a plain `alert()` if SweetAlert2 can't load

## Validation

- **Email:** required, valid format
- **Password:** required, at least 6 characters
- **Name** (registration): required, at least 2 characters
- **Confirm password** (registration): required, must match the password

## Run

No build step. Open `index.html` in a browser. An internet connection is needed for SweetAlert2 (loaded from a CDN).

## Files

- `index.html` – markup and validation script
- `style.css` – styles, including the alert theme
