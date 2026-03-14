# Tribal View Website

Static marketing site for the Tribal View app overview.

## Files

- `index.html`: main landing page
- `styles.css`: styles for the landing page
- `.gitlab-ci.yml`: GitLab Pages deployment pipeline

## Hosting

### GitHub Pages

1. Create a GitHub repository from this folder.
2. Push the files.
3. In repository settings, enable GitHub Pages and deploy from the root branch.

### GitLab Pages

1. Create a GitLab repository from this folder.
2. Push the files to the `main` branch.
3. GitLab Pages will publish the `public/` artifact from `.gitlab-ci.yml`.

## Replace before publishing

- Google Play link in `index.html`
- support email and website
- privacy policy URL
- app-specific copy and screenshots
