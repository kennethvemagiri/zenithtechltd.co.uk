# Zenith Tech — Landing Page

A black & white landing page for Zenith Tech. No build step required.

## Run locally

Open `index.html` in a browser, or use a simple server:

```bash
# Python
python3 -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Adding your logo later

In `index.html`, find the logo block:

```html
<a href="#" class="logo" aria-label="Zenith Tech home">
  <!-- Logo placeholder: replace with <img> when ready -->
  <span class="logo-wordmark">Zenith Tech</span>
</a>
```

Replace the inner content with your image, for example:

```html
<a href="#" class="logo" aria-label="Zenith Tech home">
  <img src="logo.svg" alt="Zenith Tech" width="140" height="32" />
</a>
```

Adjust `.logo` in `styles.css` if you need different logo sizing.
