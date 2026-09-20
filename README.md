# Personal homepage

A static personal homepage inspired by Colin Raffel's native HTML site:
https://colinraffel.com/

Uses browser-default monospace, native blue links and a centered text column.
No framework, external fonts, JavaScript, analytics, or build step.
On small screens the body type increases to 16px for readability.

## Edit

Edit `index.html` directly. Content was adapted from `MyCV/main.tex` on
2026-09-20; review affiliations and publication information before publishing.
The CV PDF is a snapshot and should be replaced whenever your CV changes.
To add a portrait, place your own `portrait.jpg` beside `index.html` and
uncomment the image element. No placeholder or third-party portrait is shown.

## GitHub Pages

Copy `index.html`, `.nojekyll` and `Zhihang_Yi_CV.pdf` to the root of your
`<username>.github.io` repository. In Settings → Pages select
Deploy from a branch, then the branch containing these files and /(root).
There is no custom domain configuration to remove.

## Local preview

From this folder run:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765/ in your browser.
