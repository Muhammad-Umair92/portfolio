# Portfolio

Static site for Vercel. There is no build step and no backend.

## Local preview

From this directory:

```bash
python3 -m http.server 4173
```

Open `http://127.0.0.1:4173`.

## Vercel

1. Import this repository.
2. Framework preset: **Other**.
3. Leave the build command empty.
4. Leave the output directory empty so Vercel serves the repository root.

`index.html` is the site entry. Styles, fonts, and `favicon.svg` are static files next to it.
