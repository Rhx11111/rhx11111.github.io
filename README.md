# Haoxiang Ren — academic homepage

An English academic homepage made from static HTML and CSS. No installation or build step is required.

## Publish with GitHub Pages

The address is **https://rhx11111.github.io/**, published from the GitHub account `Rhx11111`.

1. In that account, create a public repository named `rhx11111.github.io`.
2. Upload **the contents of this folder** to the repository's `main` branch. Keep `index.html` at the repository root and preserve the `assets/` folder. Include `.nojekyll` when uploading; it marks this as a plain static site.
3. Open **Settings → Pages**. Choose **Deploy from a branch**, then **main** and **/ (root)**, and save.
4. Wait for the Pages deployment to finish, then open the address above. Leave the custom-domain field empty.

If the GitHub account has a different name, the user-site repository and address must use that name. Also update the canonical link and `og:url` in `index.html` to match the actual published address.

## Edit the homepage

- `index.html`: biography, contact links, publication authors and summaries. Each publication is an `<article class="entry">`.
- `style.css`: custom typography, colors, spacing and responsive layout.
- `template-base.css`: base template styles.
- `assets/`: publication illustrations. Preserve image proportions when replacing figures.

Commit edits to `main`; GitHub Pages will publish the updated files. You can also open `index.html` locally to review changes.

The homepage currently contains six papers. The `*` author markers indicate equal contribution, not correspondence.

## Attribution

The layout adapts the MIT-licensed [leonidk.github.io template](https://github.com/leonidk/leonidk.github.io), inspired by [Yihao Sun's homepage](https://www.yihaosun.cn/). Retain `template-license.txt` and the template credit in the footer.

Publication figure sources, licenses, and contribution-marker evidence are documented in [ATTRIBUTION.md](ATTRIBUTION.md). Figure rights remain with their respective authors.
