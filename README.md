# Images — Logos & Backgrounds

Drop your **logos** and **background images** in this folder. When the app is published
(e.g. to GitHub Pages), every file here is served at the URL:

```
/images/<filename>
```

For example, `public/images/logo.png` becomes `/images/logo.png` in the running app.

## Why this folder?

- It lives outside the bundled source, so you can swap logos/backgrounds **without touching code**.
- Reference them from your project HTML/CSS as `/images/logo.png` or `/images/bg.jpg`.
- When pushing to GitHub, commit this folder so the published site picks up your assets.

## Suggested structure

```
public/images/
  logos/      <- brand logos, icons
  backgrounds/ <- full-screen background images
```

The Asset Manager page (inside the app) also stores uploads in your browser's local
storage for quick reuse — but files placed here are the ones that ship with the build.
