<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-unicode-normalize/brand/main/social/go-ruby-unicode-normalize.png" alt="go-ruby-unicode-normalize/go-ruby-unicode-normalize.github.io" width="720"></p>

# go-ruby-unicode-normalize.github.io

The organization's institutional landing page, served at
<https://go-ruby-unicode-normalize.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-ruby-unicode-normalize/docs](https://github.com/go-ruby-unicode-normalize/docs), served at
<https://go-ruby-unicode-normalize.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
