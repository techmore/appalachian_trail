# AT Near 18947

A camping guide to Appalachian Trail access points and overnight spots near Pipersville, PA (zip 18947), written for couples and first-time campers. It covers eight nearby campgrounds and parks, a map of all spots, and a short beginner guide.

**Live site:** https://techmore.github.io/appalachian_trail/

## Run locally

The site is built with Jekyll. With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

GitHub Pages builds the site from the root of `main`.

## Layout

| Path | What it is |
|---|---|
| `index.html` | Home page with the top picks |
| `spots/` | One page per campground or park, plus an index |
| `newbie-guide/` | Trip planning, gear checklist, and what to expect |
| `map.html` | All spots on one map |
| `about.html` | About page |
| `_layouts/default.html` | Shared page layout |
| `assets/css/style.css` | Stylesheet |
| `_config.yml`, `Gemfile` | Jekyll configuration and gems |

Part of [Techmore](https://techmore.github.io/pages/repos/).
