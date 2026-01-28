# Robert Laurella - Personal Website

A minimal personal portfolio site hosted on GitHub Pages.

Visit: [robertlaurella.ca](https://robertlaurella.ca)

## Local Development

This is a static HTML site (no build tools required).

To preview locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

Push to `main` branch and GitHub Pages will automatically deploy.

## Structure

- `index.html` - Main landing page
- `404.html` - Custom error page
- `CNAME` - Custom domain configuration
- `.nojekyll` - Tells GitHub Pages to skip Jekyll processing
