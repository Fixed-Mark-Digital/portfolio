# Portfolio

A single-page portfolio. Plain HTML and CSS, no build step, no JavaScript.

## Files

```
index.html     The whole page (styles are in the <style> block)
assets/        Project screenshots (WebP)
.nojekyll      Tells GitHub Pages to serve the files as they are
```

## Publishing on GitHub Pages

1. Create a new public repository (for example `portfolio`).
2. Upload these files to the root of the repository, keeping the `assets` folder.
3. In the repository, go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute or two the page is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Rules for this page

Keep it neutral so it can be linked from freelance platforms.

- No email, phone number, booking link, form or social links.
- No link to any business site of mine.
- No domain, email or phone number visible inside screenshots.
- Get permission before adding a client.

## Adding a project

Copy an existing `<article class="card">` block and change the text. Images should be WebP at about double their display width, with `width`, `height` and real alt text.
