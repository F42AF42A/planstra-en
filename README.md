# Planstra

**Brand strategy builder** — 45 slides, from PESTLE and SWOT through
positioning and mission to a blue ocean strategy canvas.

Open beta: **https://planstra.pro** · Russian edition: **https://planstra.ru**

## What it is

A single-page app with no server. Everything you type stays in your own
browser (localStorage) and is never sent anywhere. Every slide carries a
"learn more" note and a worked example; Markdown import/export and PDF export
are built in — only the slides you light up go into the PDF.

## Running it locally

Download `index.html` and open it in a browser. Nothing else is needed.

| File | What it is |
|---|---|
| `index.html` | the whole app |
| `favicon.svg` | tab icon |
| `og.png` | social preview image |
| `.nojekyll` | turns off Jekyll processing on GitHub Pages |

## How this file is produced

This edition is generated from the Russian source by `build.py` in the
[planstra](https://github.com/F42AF42A/planstra) repository: strings are
spliced in by exact source position from a translation dictionary, so a change
made once in the source reaches both editions.
