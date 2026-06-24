# Agent Notes

## Project

This repository is the static website for EscPlay. It currently deploys plain HTML, CSS, and assets from the repository root through the Pages workflow.

## Local Workflow

- Preview the site by opening `index.html` directly in a browser; there is no build step yet.
- Keep the site dependency-free unless a future game build requires tooling.
- Keep custom domain configuration in the host settings. Do not add a `CNAME` file while deployment uses the current workflow.
- Check desktop and mobile layout before publishing visible UI changes.

## Git Policy

- Keep the branch history to exactly one commit.
- For every new change, stage only the intended files, amend the existing commit, and push with `--force-with-lease`.
- Do not create follow-up commits on this repository unless the user explicitly changes this policy.
