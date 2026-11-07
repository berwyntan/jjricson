# The Complete Furnisher

Single-page interior design landing page — off-white linen and walnut brown palette. Static HTML/CSS/JS, ready for free Vercel hosting.

## Local preview

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

Open [http://127.0.0.1:4173](http://127.0.0.1:4173).

## Deploy on Vercel (free)

1. Push this repo to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Leave **Framework Preset** as Other / no build command — this is a static site.
4. Click **Deploy**. You get a free `*.vercel.app` URL.

Or with the Vercel CLI:

```bash
npx vercel
```

## Customise

- Brand name and copy: `index.html`
- Colours and type: `styles.css` (`--linen`, `--walnut`, `--bark`)
- Photos: drop your files into `images/` using the names in `images/README.md`
- Connect the enquire form to Formspree, Basin, or your own endpoint in `script.js`
