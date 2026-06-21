# Cyber Shack — 90's Retro Demo Site

A hand-coded, 90's-style mock-up website. Plain HTML + CSS, no build tools,
no dependencies — ready to upload straight to GitHub Pages.

## Files

```
index.html       Home page
about.html       About page
links.html       Links page
guestbook.html   Demo guestbook (form is not wired to a server)
style.css        Shared stylesheet
images/          All site graphics (banner, buttons, backgrounds, etc.)
```

## How to publish on GitHub Pages

1. Create a new GitHub repository (e.g. `cyber-shack`).
2. Upload all the files in this folder, **keeping the `images` folder
   structure intact** (don't rename or flatten it — the CSS and HTML
   reference `images/...` paths).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch".
5. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
6. Wait a minute or two — GitHub will give you a live URL like
   `https://yourusername.github.io/cyber-shack/`.

That's it — no build step required, since it's all static HTML/CSS.

## Customizing

- Swap the banner/buttons by re-running `gen_images.py`-style edits, or
  just drop in your own images with the same filenames.
- Edit the text directly in the `.html` files — it's plain, readable markup.
- All colors and fonts live in `style.css` if you want to retheme it.
