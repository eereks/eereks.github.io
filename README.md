# eereks.github.io

Source for my personal blog at **<https://eereks.github.io>** — notes, writeups, and study material on cybersecurity, with a focus on Active Directory attack paths & hardening, identity (Entra ID), PKI / ADCS, and threat detection.

Built with [Jekyll](https://jekyllrb.com/) and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Site is then available at <http://127.0.0.1:4000>. Drafts (in `_drafts/`) are included with `--drafts`:

```bash
bundle exec jekyll serve --drafts
```

## Writing a post

Posts live in `_posts/` and follow the filename `YYYY-MM-DD-title.md`. Minimal front matter:

```yaml
---
title: Post title
date: 2026-06-05 12:00:00 +0200
categories: [Active Directory]
tags: [kerberos, hardening]
---
```

Work-in-progress posts go in `_drafts/` (no date prefix needed) and are excluded from the build until moved to `_posts/`.

## License

Content © Eslam Rashed. Theme released under the [MIT License](LICENSE).
