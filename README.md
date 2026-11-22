# PULP — Digital Magazine Starter

A responsive, static website starter for PULP, an independent digital magazine about art, music, technology, news, alternative models, gonzo writing and digital culture.

## What's included

- `index.html` — the full homepage and section structure
- `styles.css` — responsive visual system (neon pink, cyan, black, retro-digital / MySpace-inspired details)
- `script.js` — mobile navigation
- `assets/pulp-concept-cover.png` — original concept artwork used as the hero image

## Preview locally

Open `index.html` in a browser. No build tools or package installation are required.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository named `pulp-magazine` (or another name you prefer).
2. Upload every file and folder in this project. Keep `index.html` at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. GitHub will provide the public website URL after deployment finishes.

## Add articles later

The homepage currently contains clearly marked placeholder content. To publish your first articles, duplicate a `<article class="feed-card">...</article>` block in `index.html`, update its title, summary and category, and add your image under `assets/`. Then point the image element to that file, for example:

```html
<img src="assets/my-article-cover.jpg" alt="Short description of the image">
```

For a larger publication, the next development step should be a content system (such as a lightweight CMS) so editors can publish without editing HTML.

## Sections

Live skeleton: Art, Music, Tech, News, Models, Blog, About.

Marked as under construction: Podcast / PULP Radio, Video / PULP TV, YouTube channel.

## Before launch

- Replace the placeholder social links (`href="#"`) with official PULP profiles.
- Set up a real editorial email address and update `hello@pulpzine.com` if needed.
- Confirm the final domain and publication contact details.
- Add an age-appropriate access notice and clear content labels before publishing erotic/adult material; use platform-specific rules for each social network.
- Only publish images and stories with documented permission and consent from adult contributors.
- Add privacy, terms, copyright and submission pages before collecting user data or accepting submissions.

PULP is a working title/brand concept; check name, domain and trademark availability before investing in the identity.

### Signature cursor
The site includes a custom SVG orange-slice cursor (`assets/pulp-orange-cursor.svg`) to match the PULP name. It is enabled on mouse/trackpad devices and falls back to the normal cursor on touchscreens.
