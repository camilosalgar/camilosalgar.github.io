# camilosalgar.github.io

Personal website built with Quarto. Every commit to `main` rebuilds and publishes the site automatically (see the Actions tab).

## Add a new piece

1. Open the folder: `essays/`, `research/`, or `creative/`.
2. Click **Add file → Create new file**. Name it something like `my-new-essay.qmd` (lowercase, hyphens, no spaces).
3. Copy the contents of `_template.qmd` from that folder, fill in the title/description/date/categories, and write below the `---` line.
4. Click **Commit changes**. The site updates in about 2 minutes.

Images and PDFs: upload them into the same folder and link them with `![Caption](image.png)` or `[PDF](file.pdf)`.

## Edit pages

- Bio: `about.qmd`
- Home page intro: `index.qmd`
- Site name, menu, footer: `_quarto.yml`
- Colors and fonts: `styles.scss`
