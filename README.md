# Blog Deployment

This directory contains your static blog files ready for deployment to GitHub Pages.

## Deployment Instructions

1. Create a new repository on GitHub
2. Configure your Git identity:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

3. Link and push to your GitHub repository:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main --force
   ```

4. Enable GitHub Pages:
   - Go to your repository settings on GitHub
   - Navigate to the "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

Your blog will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Updating the Blog

1. Make your changes to the blog content
2. Run the export script again
3. Commit and push the changes:
   ```bash
   git add .
   git commit -m "Update blog content"
   git push origin main
   ```
