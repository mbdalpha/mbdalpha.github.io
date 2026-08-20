# mbdalpha

Personal site. Static HTML, no build step.

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

This tree is the site root. Paths are relative, so it works as a user site or a project site.

1. Create a repo (`mbdalpha.github.io` for `https://mbdalpha.github.io/`, or any repo for `https://mbdalpha.github.io/<repo>/`).
2. Push this directory to `main`.
3. In the repo: Settings → Pages → Deploy from a branch → `main` / `/ (root)`.

`.nojekyll` is present so GitHub does not run Jekyll.
