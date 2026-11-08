# abrioso.github.io

Personal website of André Kakoo Brioso, published with GitHub Pages at
<https://abrioso.github.io>.

## Structure

| File         | Purpose                                                  |
|--------------|----------------------------------------------------------|
| `index.html` | The site: a single page with inline CSS and no JavaScript |
| `404.html`   | Page GitHub Pages serves for unknown paths               |

There is no build step and no dependencies. The site makes no third-party
requests: fonts come from the visitor's system and the favicon is an inline
SVG.

## Local preview

Any static file server works, for example:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>. Local servers do not use the custom error
page, so preview it directly at <http://localhost:8000/404.html>.

## Deployment

GitHub Pages publishes the site from the branch set under
*Settings → Pages* (normally `main`) on every push. Changes go through a pull
request; once merged, the site usually updates within a few minutes.

## Content

Keep the job title, background and interests consistent with the profile
README in [abrioso/abrioso](https://github.com/abrioso/abrioso).
