# Carnelian Community Newsletter Starter

This is a static HTML/CSS site designed for GitHub Pages.

## Recommended publishing setup
1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub: Settings → Pages.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then Save.
6. GitHub will publish the site at the Pages URL shown in Settings → Pages.

GitHub's current documentation supports publishing directly from a branch, which is the simplest approach for this static site.

## Monthly workflow
1. Duplicate the previous month's folder under `/newsletters/YYYY/month/`.
2. Edit the title, President's message, updates, reminders, and contact details.
3. Add optimized JPG/WebP images to `/assets/images/`.
4. Replace placeholder image paths in the issue.
5. Add the new issue to `/archive.html`.
6. Update the homepage's "latest issue" link and headline.
7. Commit/push changes. GitHub Pages republishes automatically.

## Image guidance
- Wide hero/rendering: 1800–2200 px wide, JPG/WebP.
- Content images: 1200–1600 px wide.
- Keep text out of images whenever possible.
- Use actual HTML for titles, dates, captions, body copy and links.
- Compress images before upload.

## Privacy
Treat the site as public. Do not publish:
- Gate/access codes or detailed security procedures
- Homeowner account or violation information
- Private meeting material
- Non-public financial data
- Personal contact information unless intended for publication

## Custom domain
Once the site is live and stable, add a custom domain in GitHub Pages settings and configure the required DNS records with your domain provider.

## Files
- `index.html` — homepage / current issue
- `archive.html` — newsletter archive
- `assets/site.css` — all site styling
- `assets/images/` — photos and generated renderings
- `newsletters/YYYY/month/index.html` — each monthly issue
