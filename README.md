# Password-generator

Live Demo: https://password-generator-five-xi-69.vercel.app/

A lightweight, client-side Password Generator built with plain HTML, CSS and JavaScript.

## Overview

This small project generates secure, customizable passwords directly in the browser. It requires no backend — just open `index.html` or deploy the folder as a static site.

## Features

- Generate passwords with configurable length
- Include/exclude lowercase, uppercase, numbers and symbols
- One-click copy to clipboard
- Small, dependency-free static site (HTML/CSS/JS)

## Usage

1. Open `index.html` in your browser.
2. Choose the password length and character options.
3. Click the generate button and use the copy button to copy the result.

Run a local static server for testing (optional):

```bash
# Python
python -m http.server 5500

# Node (http-server)
npx http-server -p 5500
```

## Deploy

This project is ready for static hosting. Example deployment options:

- Vercel: Connect the GitHub repository and import the project — Vercel auto-detects static sites.
- GitHub Pages: Enable Pages for the repository and serve from the `main` branch.
