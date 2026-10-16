# Gettysburg Mold Guide - Render Static Site

This is **one static informational webpage**: `index.html`. No Node.js, framework, images, build dependencies, header, footer, or navigation menu.

## Deploy through Render (browser and GitHub, no VS Code needed)

1. Download and extract the ZIP archive.
2. On GitHub create a repository, e.g. `gettysburg-mold-guide-render`.
3. Open the repository, choose **Add file -> Upload files**, and upload `index.html` to the **repository root** (not a nested folder).
4. Commit changes.
5. On Render choose **New -> Static Site** and connect this repository.
6. Configure:
   - Branch: `main`
   - Root Directory: blank
   - Build Command: `mkdir -p dist && cp index.html dist/`
   - Publish Directory: `dist`
7. Deploy. Render will assign an `.onrender.com` address.

## Content

- Topic: How to Spot Hidden Mold Under Kitchen Sinks and Bathroom Vanities in Gettysburg
- The second paragraph contains the exact anchor `Bathroom & Kitchen Mold Removal Gettysburg, PA` pointing to:
  `https://gettysburgmoldremediationpros.com/bathroom-kitchen-mold-removal-gettysburg-pa/`
- Google Maps embed: 129 Chambersburg St, Gettysburg, PA 17325
- All nine supplied business/social links: Houzz, Manta, Yelp, Facebook, YouTube, X, Pinterest, TikTok, Quora
- Source references: EPA and CDC
- The page is independently informative. Hosting it does not guarantee indexing or backlink value.

No `render.yaml` needed; use the Render dashboard settings above. Do not use the Web Service deployment type for this site.
