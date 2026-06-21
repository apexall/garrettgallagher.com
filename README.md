# Garrett's Page — 90's Retro Homepage

A hand-coded, 90's-style personal homepage for Garrett: bass guitar,
ponies, record collecting, and his band Nebuladrag (nebuladrag.com).
Plain HTML + CSS, no build tools, no dependencies — ready to upload
straight to GitHub Pages.

## Files

```
index.html       Home page
about.html       About Garrett (bass, the band, records, ponies)
ponies.html      Pony page
records.html     Record collection
guestbook.html   Demo guestbook (form is not wired to a server)
style.css        Shared stylesheet
images/          All site graphics (banner, buttons, icons, backgrounds)
```

The nav bar also links out to **nebuladrag.com** (Garrett's band) via the
"THE BAND" button on every page.

## How to publish on GitHub Pages

1. Create a new GitHub repository (e.g. `garretts-page`).
2. Upload all the files in this folder, **keeping the `images` folder
   structure intact** (don't rename or flatten it — the CSS and HTML
   reference `images/...` paths).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch".
5. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
6. Wait a minute or two — GitHub will give you a live URL like
   `https://yourusername.github.io/garretts-page/`.

That's it — no build step required, since it's all static HTML/CSS.

## Customizing

- Swap the banner/buttons by re-running `gen_images.py`-style edits, or
  just drop in your own images with the same filenames.
- Edit the text directly in the `.html` files — it's plain, readable markup.
- All colors and fonts live in `style.css` if you want to retheme it.
