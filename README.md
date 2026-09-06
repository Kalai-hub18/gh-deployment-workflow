# GitHub Deployment Workflow

This project demonstrates how to automatically deploy a simple HTML website to GitHub Pages using GitHub Actions.

## Project Structure

- `index.html` - The website's main HTML page.
- `.github/workflows/deploy.yml` - GitHub Actions workflow responsible for deploying the website.
- `README.md` - Project documentation.

## How It Works

Whenever changes to `index.html` are pushed to the `main` branch, GitHub Actions automatically runs the deployment workflow.

The workflow:

1. Checks out the repository.
2. Configures GitHub Pages.
3. Uploads the website files as a Pages artifact.
4. Deploys the artifact to GitHub Pages.

## Website

After deployment, the website will be available at:

https://<username>.github.io/gh-deployment-workflow/