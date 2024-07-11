# Daniel Livingston - Personal Website & Blog

[![Netlify Status](https://api.netlify.com/api/v1/badges/3f4370c5-b2cd-47d0-8f06-ff33593fe33f/deploy-status)](https://app.netlify.com/sites/www-livingston/deploys)

These are the source files for my personal website and blog.

## Tech Stack

| Tech | Name | URL |
|------|------|-----|
| Static site generator | Hugo | https://gohugo.io/ |
| Theme | Codex | https://github.com/jakewies/hugo-theme-codex |
| Deployment | Netlify | https://app.netlify.com/sites/personal-site-drl/deploys |

## Getting Started

This website requires Hugo, which [you can install from the gohugo.io website](https://gohugo.io/installation/).

### Cloning

The [Hugo theme](https://github.com/jakewies/hugo-theme-codex) is referenced as a Git submodule. Clone this repo with the `--recurse-submodules` flag, or run `git submodule update --init --recursive`.

### Running a Development Server

To launch a live development server which refreshes on file changes, run:

```bash
hugo --logLevel info server -D
```

The default server address is <http://localhost:1313/>.
