# How to Enable GitHub Pages for This Repository

This repository contains an HTML website (`index.html`) that can be rendered as a live website using GitHub Pages.

## Setup Instructions

### Step 1: Enable GitHub Pages
1. Navigate to this repository on GitHub: https://github.com/danmeissner/sheepshead-signup
2. Click on **Settings** (top right)
3. In the left sidebar, click **Pages**
4. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
5. Click **Save** if prompted

### Step 2: Wait for Deployment
- Once enabled, the GitHub Actions workflow will automatically deploy the site
- The deployment typically takes 1-2 minutes
- You can check the progress in the **Actions** tab

### Step 3: Access Your Site
After deployment completes, your site will be available at:
**https://danmeissner.github.io/sheepshead-signup/**

## Automatic Updates
Once GitHub Pages is enabled, every time you push changes to the `main` branch:
1. The GitHub Actions workflow automatically runs
2. Your site is rebuilt and redeployed
3. Changes appear live within 1-2 minutes

## Viewing Locally
To view the site locally without GitHub Pages:
1. Clone or download this repository
2. Open `index.html` directly in a web browser
3. The site will work with full functionality (requires internet for Firebase)

## Troubleshooting
- **Site not loading?** Wait a few minutes after enabling Pages
- **Changes not appearing?** Check the Actions tab for deployment status
- **404 error?** Verify Pages is enabled in Settings > Pages
