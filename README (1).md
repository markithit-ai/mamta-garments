# Mamta Garments Website

This is a simple, single-file GitHub Pages website.

## Files

Keep these two files together in the same GitHub repository:

```text
mamta-garments/
├── index.html
└── logo.png
```

There is NO React, Vite, npm, build step, `src` folder, `public` folder, or GitHub Actions workflow.

## How to publish on GitHub Pages

1. Create an empty GitHub repository named `mamta-garments`.
2. Upload:
   - `index.html`
   - `logo.png`
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Save.
6. Your site will be available at:

`https://YOUR-USERNAME.github.io/mamta-garments/`

## How to change the logo

Replace `logo.png` with the new logo.

IMPORTANT:
- Keep the filename exactly `logo.png`, OR
- if you use another filename, edit this line in `index.html`:

```html
<img class="logoImage" src="logo.png" alt="Mamta Garments logo">
```

## How to change website text

Open `index.html` in VS Code, Notepad++, or another text editor.

Use **Ctrl + F** to search for the text you want to change.

Examples:

- `WE DON'T JUST`
- `WE SELL VIBES`
- `10+ YEARS`
- `RAUNAK SINGH`
- `949K`
- `60+ GOOGLE REVIEWS`
- `Haripur Road`
- `Cuttack, Odisha 753001`

Edit the wording and save the file.

Then upload the updated `index.html` to GitHub and choose **Replace file**.

## How to change the Google Maps location

The main Google Maps buttons currently use:

`https://maps.app.goo.gl/4qfGpnfPuTNM85xa6`

Search for that URL in `index.html` and replace it with the new Google Maps link whenever the store location changes.

The visible map preview uses a Google Maps search embed. If the store moves, also search for:

```text
https://www.google.com/maps?q=Mamta%20Garments%2C%20Haripur%20Road%2C%20Cuttack%2C%20Odisha&output=embed
```

and change the address after `q=`.

## How to change Instagram

Search for:

`https://www.instagram.com/mamtaagarments/`

Replace it with the correct Instagram URL.

## How to change WhatsApp

Search for:

`https://whatsapp.com/channel/0029VbBQXxl2kNFotrRpRt02`

Replace it with the new WhatsApp Channel URL.

The floating WhatsApp button is intentionally GREEN.

## How to change the founder information

Search for:

`RAUNAK SINGH`

and edit the nearby text.

The follower count is currently shown as:

`949K`

because that was the count visible in the supplied Instagram screenshot. Update it whenever needed.

## How to change the Google rating/review count

Search for:

`5.0`

and:

`60+ GOOGLE REVIEWS`

Update these when the Google listing changes.

Do not invent individual customer reviews. The website uses general review themes from the supplied Google review summary.

## How to replace the category/hero images

The current website uses temporary online fashion images.

Search for:

```text
images.unsplash.com
```

Each URL belongs to one visual.

To replace one:

1. Upload your new image to the same GitHub repository.
2. Change the corresponding `src="..."` URL in `index.html`.

For example:

```html
<img src="YOUR-IMAGE-URL-HERE" alt="Jeans">
```

### Recommended image sizes

Hero:
- 1200 × 1500 px or similar portrait

Category images:
- 800 × 1000 px or similar portrait

Store:
- 1400 × 900 px or similar landscape

Founder:
- 900 × 1100 px or similar portrait

Use compressed JPG/WebP images where possible.

## Important: do not upload secrets

Do NOT put:
- Google API keys
- passwords
- private tokens
- `.env` files containing secrets

into this repository.

## Troubleshooting

### Website is blank

Check that the repository root contains:

```text
index.html
logo.png
```

and that `index.html` is NOT inside another folder.

### Logo is missing

Make sure:

```text
logo.png
```

is in the same folder as:

```text
index.html
```

### Changes are not visible

Wait 1–2 minutes after the GitHub Pages deployment.

Then hard-refresh the browser:

Windows Chrome:
`Ctrl + Shift + R`

## Current business links

Instagram:
https://www.instagram.com/mamtaagarments/

WhatsApp Channel:
https://whatsapp.com/channel/0029VbBQXxl2kNFotrRpRt02

Google Maps:
https://maps.app.goo.gl/4qfGpnfPuTNM85xa6

Founder Instagram:
https://www.instagram.com/raunaksingh_sa/
