# Kelly Ann Design

Interior design studio site for [kellyanndesign.com](https://kellyanndesign.com).

Pure static HTML/CSS/JS — no build step.

## Preview locally

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 5173
```

Then visit `http://localhost:5173`.

## Cheapest hosting (recommended)

Keep the domain at GoDaddy. Host the site for **$0**.

You do **not** need GoDaddy Website Builder or paid GoDaddy hosting.

### Cloudflare Pages (good default)

1. Push this repo to GitHub.
2. In [Cloudflare Pages](https://pages.cloudflare.com/), create a project from the repo.
3. Build settings:
   - Framework preset: None
   - Build command: _(leave empty)_
   - Output directory: `/` (root)
4. Add custom domain `kellyanndesign.com` in Cloudflare, then either:
   - Switch GoDaddy nameservers to Cloudflare, or
   - Add the DNS records Cloudflare shows (usually an A/CNAME for the root and `www`).

### Netlify

Connect the repo, publish the site root (no build command). The contact form already includes Netlify form attributes so submissions work once deployed there.

## What’s next

- Drop branding / project photos into an `images/` folder and wire them into the Studio section.
- Point a link from [noreliuspartners.com](https://noreliuspartners.com) to this site.
