# Isaac Onyeani — Portfolio Website

A responsive, animated portfolio website for Isaac Onyeani, Social Media Manager and Digital Growth Strategist.

## Included
- `index.html` — portfolio content and page structure
- `style.css` — blue visual theme, responsive layout, animations
- `script.js` — mobile navigation, scroll reveal effects, current year
- `assets/isaac-onyeani.png` — profile portrait
- `assets/client-feedback-page.png` — client feedback screenshot about page management
- `assets/client-feedback-ads.png` — client feedback screenshot about ad conversions

## Publish on GitHub Pages
1. Extract this ZIP file.
2. Create a new repository on GitHub (for example, `isaac-onyeani-portfolio`).
3. Upload **all the files and the `assets` folder**, preserving the folder structure.
4. Open the repository's **Settings → Pages**.
5. Under build and deployment, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`, then save.
7. Wait for GitHub Pages to publish your site. The published URL will appear in the Pages settings.

## Before publishing
- Confirm that the WhatsApp number and email in `index.html` are correct.
- Replace or add work samples if you have more approved client examples.
- The website uses Google Fonts; if a visitor is offline, it falls back to system sans-serif fonts.
- The feedback screenshots are included locally in `assets/`, so they remain available when the site is uploaded with the full folder structure.

## Accuracy note
Project outcomes and follower figures are based on the information in the supplied CV. Do not add unsupported performance claims; update the case studies if you have verified analytics or permission to share additional details.


## Vercel image troubleshooting
This project expects these files to exist at the deployed paths:
- `/assets/isaac-onyeani.png`
- `/assets/client-feedback-page.png`
- `/assets/client-feedback-ads.png`

Keep the `assets` folder at the same level as `index.html` in the repository. Upload the entire project, not just `index.html`. In Vercel, check **Project → Settings → Build and Deployment**: set the Root Directory to the folder containing `index.html`; for a plain HTML site, use no build command and ensure the output directory includes `index.html` and `assets/`. Redeploy after committing the image files. You can test each image by opening its URL on your domain; if it returns 404, the image file is missing from the deployed output or the path/capitalization does not match.
