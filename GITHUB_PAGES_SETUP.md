# GitHub Pages Setup Instructions

This repository has been configured with a GitHub Actions workflow to automatically deploy the HTML files to GitHub Pages.

## What was added:
- `.github/workflows/pages.yml` - GitHub Actions workflow for automatic deployment

## How to complete the setup:

1. **Enable GitHub Pages in repository settings:**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "GitHub Actions"
   - Save the changes

2. **Trigger the deployment:**
   - The workflow will automatically run on the next push to the `main` branch
   - You can also manually trigger it from the "Actions" tab → "Deploy to GitHub Pages" → "Run workflow"

3. **Access your site:**
   - Once deployed, your site will be available at:
   - `https://feierlord.github.io/adm1nabuse/`

## Files that will be deployed:
- `index.html` - Main landing page
- `rules.html` - Rules page
- `styles.css` - Stylesheet
- `README.md` - Repository documentation

## How the workflow works:
- Automatically deploys on every push to the `main` branch
- Can be manually triggered via the Actions tab
- Uses the latest GitHub Actions v4 for deployment
- Deploys all files from the repository root

## Troubleshooting:
- If the workflow doesn't run automatically, check that:
  1. GitHub Pages is set to "GitHub Actions" as the source
  2. The workflow has the necessary permissions
  3. GitHub Pages is enabled for the repository
