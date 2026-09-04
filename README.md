# Multimodal Cognitive Neuroscience Lab website

This repository contains the Quarto source for the Multimodal Cognitive Neuroscience Lab website at Washington University in St. Louis.

Published site: <https://crn2022.github.io/mmclab-washu.github.io/>

## Preview locally

Install [Quarto](https://quarto.org/docs/get-started/), clone this repository, and run:

```bash
quarto preview
```

## Publish

Before committing, verify the entire site locally:

```bash
quarto render
```

Commit and push changes to `main`. The workflow in `.github/workflows/publish.yml` will render the site and deploy it to GitHub Pages automatically.

## Routine maintenance

Keep the personnel, publications, news, and opportunities pages current. Before each update, verify external links and run a complete local render when Quarto is available.
