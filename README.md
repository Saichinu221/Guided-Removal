# Reversal Dashboard

Client-side dashboard for Reversal processing — With-L21 / Without-L21 / Aging70 / HAZ / HRV tabs.

Everything runs in the browser (SheetJS, PapaParse, JSZip via CDN). No server, no backend — uploaded files are parsed locally and never sent anywhere.

## Note on Master Data

The original internal copy of this tool ships with a built-in site/warehouse lookup table baked into the page. That table has been **removed** in this public version (it contained real Amazon site codes and hub mappings, not appropriate for a public repo).

This means the "Master Data" is now empty by default. To use any tab, either:
- Upload a `Master_File.xlsx` each time (the file input marked optional), or
- Use the **"Edit Master Data"** button in the header to type in rows for the current session, then **Download XLSX** to save your own copy for next time.

## Running locally

Just open `index.html` in a browser. No build step, no install.

## Hosting on GitHub Pages

1. Push this folder to a GitHub repo.
2. Repo Settings -> Pages -> Source: `main` branch, `/ (root)` folder -> Save.
3. GitHub gives you a URL like `https://<username>.github.io/<repo>/` after a minute or two.

## Author

Sai Ram Chandupatla - GR Tech
