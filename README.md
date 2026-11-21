# Network & Technology Profile

A responsive, multi-tab professional profile built as a single static HTML page. It uses no external libraries, fonts, images, or build step.

## Run locally

Open `index.html` in a browser.

## GitHub Pages

The workflow in `.github/workflows/deploy-pages.yml` deploys after changes are pushed and checks for repository changes every Saturday at 03:15 UTC. The scheduled deployment is skipped if no non-workflow repository files changed during the previous seven days.

This repository is public. GitHub Pages is configured to deploy through the `Update profile site` GitHub Actions workflow. The workflow runs on pushes, checks for non-workflow repository changes every Saturday at 03:15 UTC, and deploys when the repository is public.

GitHub Pages publishes the profile site publicly. Personal email and phone details are intentionally not included.

## Profile content

The page summarizes experience and achievements from the supplied resumes. Personal email and phone details are intentionally not included.

Use **Download PDF** on the page and choose **Save as PDF** in the browser's print dialog. The print layout includes every profile section, not just the currently selected tab.
