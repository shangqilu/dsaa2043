# DSAA 2043 Course Website

Public course website for **DSAA 2043 — Design and Analysis of Algorithms,
Fall 2026**.

Live site: <https://shangqilu.github.io/dsaa2043/>

Canvas remains the official source for course information. This repository is
the more accessible public mirror maintained by the course teaching team.

## Local preview

Serve the `site/` directory with any static web server. For example:

```sh
python3 -m http.server 8000 --directory site
```

Then open <http://localhost:8000/>.

## Updating the site

Use a pull request for student-facing changes. See [CONTRIBUTING.md](CONTRIBUTING.md)
and complete the pull request checklist before requesting instructor review.

Material placeholders and links are maintained in `site/index.html`. Keep an
unreleased item visible with a clear “coming soon” label; replace that label
with a link only when the material is ready for public release.

Published lecture PDFs are stored in `site/`. When replacing a published file,
update its version query in `site/index.html` so students do not receive an
older cached copy. Lab materials are available on Canvas and are not published
in this repository.
