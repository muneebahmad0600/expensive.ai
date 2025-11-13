# GitHub Pages Setup Instructions

To enable GitHub Pages for this repository, please follow these steps:

## Steps to Enable GitHub Pages:

1. **Navigate to Repository Settings:**
   - Go to https://github.com/muneebahmad0600/expensive.ai
   - Click on "Settings" tab (requires repository admin access)

2. **Access Pages Settings:**
   - In the left sidebar, scroll down and click on "Pages"

3. **Configure Source:**
   - Under "Build and deployment" section
   - Select "Source": Deploy from a branch
   - Select "Branch": Choose `main` (or your default branch)
   - Select folder: `/ (root)`
   - Click "Save"

4. **Wait for Deployment:**
   - GitHub will automatically deploy your site
   - The site will be available at: `https://muneebahmad0600.github.io/expensive.ai/`
   - Initial deployment may take a few minutes

5. **Verify Deployment:**
   - A green checkmark will appear once deployed
   - Visit the URL to see your privacy policy page

## Current Status:

✅ `index.html` file created with comprehensive privacy policy content
⏳ GitHub Pages needs to be enabled (requires repository admin access)

## Alternative: Using GitHub Actions

If you prefer more control, you can also set up GitHub Pages with GitHub Actions:
1. Go to Settings > Pages
2. Select "GitHub Actions" as the source
3. Use the static HTML workflow

## Note:

The `index.html` file has been created in the root directory, which is the standard location for GitHub Pages. Once enabled, it will be automatically served as the homepage of your site.

## File Structure:

```
expensive.ai/
├── README.md
├── index.html (privacy policy page)
└── GITHUB_PAGES_SETUP.md (this file)
```
