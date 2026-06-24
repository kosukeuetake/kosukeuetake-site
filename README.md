# Kosuke Uetake Academic Website

This repository contains a draft academic website for Kosuke Uetake.

The intended production source is in `hugo-site/` and follows the intake prompt's requested Hugo
Blox + Pagefind + GitHub Pages structure. The root `index.html` is a local browser preview fallback
because Hugo, Go, Node, and Pagefind are not currently installed in this shell.

No changes have been pushed or published from this workspace.

## Local Preview

Open the local preview server at <http://127.0.0.1:4173/> once it is running.

## Production Build

After installing Hugo Extended, Go, and Node:

```powershell
cd hugo-site
hugo mod vendor
hugo --gc --minify
npx pagefind --site public
```
