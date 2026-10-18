# Athkanda Lihiniya – website

Static site, no build step. Everything GitHub Pages needs is in this folder.

## 1. Set your address (once)
Replace the placeholder in `index.html`, `robots.txt` and `sitemap.xml`
(use your GitHub username and repo name):

    sed -i '' 's|https://YOUR-USERNAME.github.io/athkanda-lihiniya/|https://USERNAME.github.io/REPO/|g' index.html robots.txt sitemap.xml

## 2. Optional settings (end of `index.html`)
- `GA_ID` – Google Analytics 4 Measurement ID (G-XXXXXXXXXX). Empty = no tracking.
- `CONTACT_EMAIL` – shows the "Help us restore it" button in the Restoration section.

## 3. Publish
1. Create a new public repo on github.com.
2. Upload the *contents* of this folder (drag & drop works; largest file is `promo.mp4`, ~20 MB).
3. Settings → Pages → Deploy from branch → `main` / root.
4. Site goes live at `https://USERNAME.github.io/REPO/` within a minute or two.

## 4. After it is live
Submit `sitemap.xml` in Google Search Console.
