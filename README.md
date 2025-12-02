# understories.github.io

Landing page for Understories - seeding light in the dark forest.

## Setup for GitHub Pages

This repository is configured to work with GitHub Pages. To enable your site:

1. **Repository Settings**: 
   - Go to your repository on GitHub
   - Click on **Settings** tab
   - In the left sidebar, select **Pages**
   - Under "Build and deployment", select **Deploy from a branch**
   - Under "Branch", select **main** (or your default branch)
   - Select **/ (root)** as the folder
   - Click **Save**

2. **Wait for Deployment**:
   - GitHub will build and deploy your site
   - This usually takes 1-2 minutes
   - Your site will be available at `https://understories.github.io/`

3. **Verify**:
   - The `.nojekyll` file is included to ensure GitHub Pages serves the site as-is without Jekyll processing
   - Your `index.html` is in the root directory, which is the correct location

## Local Development

To run the site locally:

```bash
npm start
# or
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.