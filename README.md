# CV

Portfolio repository for **https://bluesangg.github.io/CV/**.

## Purpose

This repo is the **portfolio/detail layer** of the site.
It should hold the pages that go deeper than the root landing page.

## What this repo is for

Use this repo for:
- portfolio homepage
- artifact pages
- coursework portfolio content
- resume-style portfolio pages
- supporting pages tied to the portfolio

Do **not** treat this repo as the main root homepage for `https://bluesangg.github.io/`.
That role belongs to the separate `BlueSaNGG.github.io` repo.

## Main pages

- `/CV/` → repo GitHub Pages root
- `/CV/ml-portfolio.html` → professional portfolio page
- `/CV/artifact-leadership-growth.html` → Artifact 1
- `/CV/artifact-ml-vs-deep-learning.html` → Artifact 2
- `/CV/training-methods-artifact.html` → Artifact 3
- `/CV/artifact-communication-clarity.html` → Artifact 4

## Relationship to other site repos

This repo works together with:
- `BlueSaNGG/BlueSaNGG.github.io` → publishes to `https://bluesangg.github.io/`

Recommended division of responsibility:
- `BlueSaNGG.github.io` = landing page / personal-site front door
- `CV` = detailed portfolio and artifact hosting

## Recommended long-term structure

Keep only **two site repos** unless a future need is strong enough to justify a third:

1. **BlueSaNGG.github.io**
   - root landing page
   - interactive resume
   - lightweight personal-site navigation

2. **CV**
   - professional portfolio
   - coursework portfolio
   - artifact pages
   - supporting detail pages

This two-repo setup is enough right now and is not too messy as long as the division stays clear.

## Assets

- `css/`, `images/`, `favicon.ico` → supporting assets for pages inside this repo

## Notes

- If a page is mainly a destination users reach *from* the homepage, it likely belongs here.
- If GitHub Pages content looks stale, wait for deployment/cache refresh before assuming the push failed.
