# Homesmade Recipe Blog

Static recipe blog for GitHub Pages, served at https://yassinemrx.github.io/Homesmade/.

## Deploy
1. Download and extract the ZIP.
2. In your existing GitHub repository `yassinemrx/Homesmade`, upload **the contents** of `homesmade_site`, not the enclosing folder.
3. Replace `index.html` and commit all files to `main`.
4. Confirm Settings > Pages > Deploy from a branch > main > /(root).
5. Wait for Actions > pages build and deployment to finish.

## Add a recipe
- Create `recipes/your-recipe-slug/index.html` using an existing recipe page as a template.
- Add the recipe record to `recipes.json`.
- Add its canonical URL to `sitemap.xml`.
- Replace sample content and images with your own verified recipe and licensed images before production use.

## Notes
- This is a static website; search and category filters run in the browser.
- Unsplash image URLs are illustrative external assets and may change; host your own properly licensed images for production.
- Paths use `/Homesmade/`. If the repository name changes, update paths in HTML, JS, and metadata.
- Review GitHub Pages terms and limits before commercial/high-volume usage.
