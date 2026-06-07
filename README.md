# Folio

A single-page library for free reading. Browse and download 40+ public-domain
classics as EPUB (via [Project Gutenberg](https://www.gutenberg.org)), or switch
tabs to a handpicked shelf of iconic fan fiction linked from
[Archive of Our Own](https://archiveofourown.org).

No build step, no dependencies, no backend — the whole site is one static
`index.html`.

## Features

- **Classics** — instant free EPUB downloads, filterable by genre, with a live
  search across title, author, and subject.
- **Fan favourites** — curated fics that open on AO3, filterable by fandom.
- **Procedural covers** — each cover is generated from the title and genre as an
  inline SVG, so there are no image assets to host.
- **Responsive & accessible** — works on touch and desktop, keyboard-navigable,
  with visible focus states.

## Running locally

It's a static file, so just open it:

```sh
# any static server works, e.g.
python -m http.server 8000
# then visit http://localhost:8000
```

Or simply double-click `index.html`.

## Credits

Classic books from [Project Gutenberg](https://www.gutenberg.org). Fan fiction
linked from [Archive of Our Own](https://archiveofourown.org). Folio hosts no
copyrighted content — it links to the original sources.
