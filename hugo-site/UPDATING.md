# Updating This Website

This site is designed so most updates happen by editing Markdown files in `hugo-site/content/`.

## Add a Paper

1. Create a folder under `content/publication/`, using a stable lowercase slug.
2. Add `index.md` with title, date, authors, publication type, venue, abstract, tags, and links.
3. Put PDFs in `static/files/` and link them as `files/name.pdf`.
4. If you have a thumbnail or cover, put `featured.jpg` beside `index.md`.

## Update Bio or Contact

Edit `content/bio/_index.md` and `content/contact/_index.md`.

## Add a Talk or Software Project

Use the examples in `content/talk/placeholder-talk/` and `content/software/placeholder-software/`.

## Before Publishing

Replace every `[PLACEHOLDER]`, add the real bio/photo/contact details, run the Hugo build, then review the preview in a browser.
