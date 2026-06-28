# suziyan.com

Suziyan is a reflective editorial-style website about human emotions. This repository currently contains a lightweight static site with no build step.

## Project Files

- `index.html` - page structure and content
- `styles.css` - visual design and responsive layout
- `script.js` - scroll reveal interaction
- `CNAME` - custom domain for static hosting

## Local Preview

Open `index.html` directly in a browser, or serve the folder with any static file server.

## Suggested Hosting

This project is well suited for:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

## GitHub Pages Setup

1. Create a new GitHub repository.
2. Push the contents of this folder to the default branch.
3. In GitHub, open `Settings > Pages`.
4. Set the source to `Deploy from a branch`.
5. Select the default branch and `/ (root)`.
6. After the site is live, keep the `CNAME` file as `suziyan.com`.
7. In your domain registrar, point the apex domain to GitHub Pages using the required DNS records.

## Domain Note

The `CNAME` file assumes the final production domain will be `suziyan.com`. Only connect it after the domain is purchased and DNS is under your control.
