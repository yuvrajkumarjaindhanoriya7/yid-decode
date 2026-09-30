# YJD decode

A lightweight browser-based web code debugger by Yuvraj Jain.

## Features

- JavaScript, HTML, and CSS modes
- Syntax and common-error checks
- File upload and drag-and-drop support
- Safe sandboxed preview
- JavaScript console capture
- Download edited code
- No build step required

## Run locally

Open `index.html` directly in a browser, or run a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload all files while keeping the `src` folder structure.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save and wait for GitHub Pages to publish the site.

## Security note

This demo runs JavaScript inside a sandboxed iframe. For production support for other programming languages, execute code in isolated server-side containers with strict resource limits.
