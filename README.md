# Giri Manigandan — Portfolio

A static site (HTML, CSS and JS) with no build step. It is ready for Vercel.

## Deploy on Vercel
**Option A: drag and drop**
1. Unzip, then go to https://vercel.com/new.
2. Drag the `giri-portfolio` folder onto the page.
3. When asked for a framework preset, choose **Other**. Leave the build and output settings empty, then click **Deploy**.

**Option B: GitHub**
1. Push this folder to a GitHub repository.
2. Import the repository on https://vercel.com/new.
3. Set Framework to **Other**, then click **Deploy**.

**Option C: Vercel CLI**
```
npm i -g vercel
cd giri-portfolio
vercel --prod
```

## Notes
- `vercel.json` sets the caching and security headers. `404.html` is the custom not-found page.
- The canonical URL, share card, `sitemap.xml` and `robots.txt` all point to https://girimanigandan.vercel.app. If you deploy under a different domain, find and replace that address.
- The contact form posts to Web3Forms. Its access key is already in `contact.html`.
- The resume PDF is at `assets/Giri-Manigandan-Resume.pdf`.
- Phones (screens up to 760px wide) get their own layout: the photo sits on the right and slides in, projects and thoughts show in two columns, and images show a shimmer while loading. Desktop is unaffected.
