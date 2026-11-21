# Pushan Shukla — Profile

A responsive, multi-tab professional profile built as a single static HTML page. It uses no external libraries, fonts, images, or build step.

## Run locally

Open `index.html` in a browser.

## GitHub Pages

The workflow in `.github/workflows/deploy-pages.yml` deploys the page after changes are pushed and checks for profile-page changes every Saturday at 03:15 UTC. The scheduled deployment is skipped if `index.html` has not changed in the previous seven days.

This repository is public. GitHub Pages is configured to deploy through the `Update profile site` GitHub Actions workflow. The workflow runs on pushes, checks for profile-page changes every Saturday at 03:15 UTC, and deploys when the repository is public.

GitHub Pages publishes the profile site publicly. Personal email and phone details are intentionally not included.

## Profile content

The page summarizes experience and achievements from the supplied resumes. Personal email and phone details are intentionally not included.
