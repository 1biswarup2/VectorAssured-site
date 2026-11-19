# VectorAssured Site

Static "Coming Soon" landing page for VectorAssured. No build step.

## Files
- `index.html`: page markup
- `styles.css`: styles
- `favicon.svg`: site icon
- `vercel.json`: Vercel config (clean URLs, security headers)

## Local preview
```bash
python3 -m http.server 3000
# open http://localhost:3000
```

## Deploy to Vercel
1. Go to https://vercel.com/new and import this GitHub repo.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Click **Deploy**. Every push to `main` redeploys automatically.

Or with the CLI: `npx vercel --prod`
