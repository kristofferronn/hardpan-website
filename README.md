# hardpangames.com: landing page

A single static page: `index.html`, `images/village-day-one.jpg` and `images/running-spiral.svg`. No build step.

## Before publishing

1. **Email sign-up (KR-06):** create an account with an email service (Buttondown is simple and cheap; Mailchimp has a free tier). Copy the form address it gives you into `SIGNUP_ACTION` near the bottom of `index.html`. Until then, the form shows "Sign-up opens in a few days".
2. **Contact address:** the footer links to hello@hardpangames.com; set that address up with your domain provider, or change it.
3. **Image:** replace `images/village-day-one.jpg` whenever you have a better screenshot (keep the name, or update the `img` tag and its width and height).

## Publishing with GitHub Pages (free)

1. Create a new public repository, e.g. `hardpan-website`, and push these files to it.
2. In the repository: Settings → Pages → Deploy from branch → `main`, folder `/ (root)`.
3. Under "Custom domain" enter `hardpangames.com` and tick "Enforce HTTPS".
4. At your domain provider, point the domain to GitHub Pages (GitHub shows the exact DNS records to add on the Pages settings screen).

Netlify or Cloudflare Pages work the same way: drag the folder in, then connect the domain.

## Design notes

Colours come from Minoan fresco palettes (fresco blue, saffron, madder red, lime plaster). The band between the hero and the content is a running-spiral border, the classic Minoan fresco motif. Type: Young Serif for headings, Instrument Sans for text (Google Fonts).
