# kevinqhv.github.io

Personal research site of Kévin Quénéhervé, built with [Hugo](https://gohugo.io) — no theme, just the files in `layouts/` and `assets/`.

## Edit the content

Almost everything lives in four YAML files:

| File | What it holds |
| --- | --- |
| `data/profile.yaml` | Name, short statement, links, thesis, supervisors, topics |
| `data/publications.yaml` | Papers, posters and talks (`kind: paper / poster / talk / journal`) |
| `data/projects.yaml` | Projects on the home page (the first one is shown large with its image) |
| `data/cv.yaml` | Experience, education and course projects |

Adding a publication:

```yaml
- kind: paper
  title: My new paper
  authors: [Kévin Quénéhervé, Philippe Tanguy, Rachid Dafali, Vianney Lapôtre]
  venue: Full conference name
  venue_short: CONF 2026
  place: City, Country
  date: "2026-06"
  featured: true          # also show it on the home page
  links:
    - { label: "PDF", url: "https://..." }
    - { label: "DOI", url: "https://doi.org/..." }
  abstract: >-
    One paragraph.
```

## Run locally

```bash
hugo server        # Hugo extended ≥ 0.128
```

## Deploy

Pushing to `main` builds and publishes the site through `.github/workflows/hugo.yaml`
(GitHub → Settings → Pages → Source must be set to **GitHub Actions**).
