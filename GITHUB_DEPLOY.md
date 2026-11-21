# Publish to GitHub Pages

The repository is configured to publish its static site with GitHub Actions.

1. Push this repository to the `main` branch.
2. Open **Settings > Pages** in the GitHub repository.
3. Set **Source** to **GitHub Actions**.
4. Open the **Actions** tab and run or wait for **Deploy to GitHub Pages**.
5. When deployment completes, open the URL shown by the workflow environment.

The entry point is `index.html`. `.nojekyll` prevents GitHub Pages from applying Jekyll processing.
