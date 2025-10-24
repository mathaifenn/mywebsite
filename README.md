# Web Starter — Vimeo Hero (Static HTML)

This bundle is ready to unzip into your deployment folder (GitHub → Vercel).

## 1) Replace the Vimeo video
- Upload your Canva export to Vimeo (Free plan is fine).
- Get the **numeric VIDEO_ID** from the video URL, e.g. `https://vimeo.com/123456789` → `123456789`.
- Open `index.html` and replace `VIDEO_ID` in the iframe `src`.

## 2) Optional: Blogger
- In `index.html`, replace `https://YOURBLOG.blogspot.com` with your blog URL.
- Later, we can embed the live feed.

## 3) Deploy
If your repo is already linked to Vercel:
```bash
git add .
git commit -m "Add Vimeo hero starter site"
git push
```
Vercel will build and deploy automatically.

## Files
- `index.html` — landing page with Vimeo hero, services section, and footer
- `assets/css/styles.css` — theme (Georgia, dark blue palette)
- `assets/img/` — place any images here

## Notes
- Autoplay: works because video is muted and uses Vimeo background mode.
- Performance: keep the video short (≤20–30s) for a smooth load.
