# camilosalgar.github.io

One-page site built with Quarto. Every commit to `main` rebuilds and publishes it automatically (see the Actions tab).

## Add a new piece

Open `index.qmd`, click the pencil icon, and copy one of the existing lines inside the Writing or Projects list. Each line has three parts: the date, the link, and where it was published.

```html
<li><span class="d">DATE</span><span><a href="LINK">TITLE</a><span class="v">WHERE PUBLISHED</span></span></li>
```

- `LINK` is a web address for published work, or a file path like `essays/my-paper.pdf` for a PDF.
- Keep the list in order, newest at the top.

To add a PDF: open the `essays` or `research` folder, click **Add file → Upload files**, drag it in, and commit. Then add its line to `index.qmd`.

## Edit the rest

- Name, intro, lists, contacts: `index.qmd`
- Fonts, colors, spacing: `styles.scss`
- Site title and favicon: `_quarto.yml`
