# Infinite Horizon Website

A simple GitHub Pages website for Infinite Horizon.

## Files

- `index.html` - Main website
- `style.css` - Website appearance
- `script.js` - Small interactive features
- `images/` - Put your logo and screenshots here

## Publishing with GitHub Pages

1. Create a GitHub repository.
2. Upload all of these files to the repository root.
3. Open the repository's **Settings**.
4. Open **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`.
7. Save.

## Adding your game download

Open `index.html`.

Find:

```html
href="#"
```

on the **Download for Windows** button and replace the `#` with the URL
of your GitHub Release or release asset.

Example:

```html
href="https://github.com/YOUR-NAME/YOUR-REPO/releases/latest"
```

## Adding screenshots

Put screenshot files into the `images` folder.

For example:

- `images/screenshot1.jpg`
- `images/screenshot2.jpg`
- `images/screenshot3.jpg`

Then replace a placeholder:

```html
<div class="screenshot placeholder">
  <span>Screenshot 1</span>
</div>
```

with:

```html
<div class="screenshot">
  <img src="images/screenshot1.jpg" alt="Infinite Horizon gameplay screenshot">
</div>
```

## Changing the version

Search `index.html` for:

`Alpha v0.1.0`

and replace it with your current version number.
