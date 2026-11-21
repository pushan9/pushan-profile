# Pushan Shukla — Profile

A responsive, multi-tab professional profile built as a single static HTML page. It uses no external libraries, fonts, images, or build step.

## Run locally

Open `index.html` in a browser.

## GitHub Pages

The workflow in `.github/workflows/deploy-pages.yml` deploys the page after changes are pushed and checks for profile-page changes every Saturday at 03:15 UTC. The scheduled deployment is skipped if `index.html` has not changed in the previous seven days.

The repository is intended to remain private for now. GitHub Pages availability and visibility for private repositories depend on the GitHub plan and repository settings. To avoid unintentionally publishing the profile, the workflow runs its deployment job only when the repository is public; make the repository public when you are ready for deployment.

Before the first deployment, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**. The workflow does not change repository visibility or Pages settings.

## Profile content

The page summarizes experience and achievements from the supplied resumes. Personal email and phone details are intentionally not included.
