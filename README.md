# The Unfiltered Records Brand Guidelines & Assets Site

This is the self-contained production bundle for the official brand guidelines and asset download portal.

## Folder Structure

- `index.html`: The main brand identity system guidelines page.
- `download-assets.html`: The asset download portal containing SVGs, badges, and color tokens.
- `nameless-prodigy-badge.png`: The signature brand/creator lockup image asset used on both pages.

## How to Host on GitHub Pages

1. **Initialize a Git repository**:
   Open a terminal in this folder and run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of brand guidelines and asset portal"
   ```

2. **Publish to GitHub**:
   - Create a new public repository on GitHub (do not initialize with README).
   - Link the local repository to your GitHub repository:
     ```bash
     git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
     git branch -M main
     git push -u origin main
     ```

3. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub.
   - Click on the **Pages** section in the left sidebar.
   - Under **Build and deployment**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and `/ (root)` folder, then click **Save**.
   - Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/` in a few minutes!
