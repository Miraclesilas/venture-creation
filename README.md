# GST 321 Venture Creation CBT Practice App

A responsive Bootstrap 5 CBT practice application for GST 321 – Venture Creation, University of Uyo.

## Features
- Username login/sign-up using browser localStorage
- Selectable question count: 20, 40, 60, 100, or all available
- Selectable timer: 30, 60, 90 minutes, or no timer
- Randomized question order
- Randomized answer options
- Question navigator
- Answered status and flagging
- Automatic scoring
- Answer review with hints
- Local attempt history and average score
- Mobile-responsive Bootstrap 5 interface
- GitHub Pages compatible static files
- Footer credit: Miracle Silas, University of Uyo, educational purposes

## Files
- `index.html` – application interface and logic
- `questions.json` – question bank
- `README.md` – publishing instructions
- `LICENSE` – MIT license

## GitHub Pages publishing
1. Create a GitHub repository, for example `gst321-venture-creation-cbt`.
2. Upload `index.html`, `questions.json`, `README.md`, and `LICENSE` to the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` and `/root`, then save.
7. Wait for GitHub Pages to publish the site.
8. Open the generated Pages URL.

## Important notes
- This is a static educational practice app. GitHub Pages does not provide a backend database.
- Usernames, history, and scores are stored only in the visitor's browser.
- Do not use this app for collecting passwords, sensitive personal information, or official examination credentials.
- The question bank is original revision material based on broad venture-creation study themes; verify it against the official University of Uyo GST 321 textbook and lecturer's course outline.
- Bootstrap and Bootstrap Icons are loaded from CDN, so the default version requires internet access.
