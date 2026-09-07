# karthik-strikes.github.io

Personal research site for Sai Karthik Kosuri. Plain static HTML and CSS, no build step,
no framework, no runtime dependencies beyond a Google Fonts stylesheet.

```
index.html                 the whole site
favicon.svg
robots.txt / sitemap.xml
.nojekyll                  tells GitHub Pages to serve files verbatim
assets/
  headshot.jpg             EXIF stripped
  iadr-2026-poster.jpg
  kosuri-cv.pdf
  evistreams-emnlp-2026.pdf
  loneliness-arxiv-2609.02606.pdf
```

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to `main`. GitHub Pages (Settings -> Pages -> Deploy from branch -> `main` / `root`)
publishes to https://karthik-strikes.github.io within a minute or two.

## Custom domain

Add a `CNAME` file containing the bare domain (e.g. `karthikkosuri.com`), point the
registrar's DNS at GitHub Pages, then set the domain under Settings -> Pages.
