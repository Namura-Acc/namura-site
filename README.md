# Namura Static Website

Namura is a clean static website for a non-commercial indie software lab. It is built with plain HTML, CSS, and JavaScript only.

## Files

- `index.html` - homepage
- `projects.html` - project list
- `about.html` - about page
- `support.html` - support and FAQ
- `privacy.html` - privacy policy
- `terms.html` - terms and disclaimer
- `assets/styles.css` - shared design system and responsive styling
- `assets/site.js` - small mobile navigation toggle
- `assets/logo.svg` - local SVG logo

## Run Locally

Open `index.html` directly in a browser. No install step, build command, or package manager is required.

## Deploy to Netlify

1. Create a new site from the repository.
2. Leave the build command empty.
3. Set the publish directory to the repository root.
4. Deploy.

## Deploy to Vercel

1. Import the repository as a new project.
2. Use the static site defaults.
3. Leave the build command empty.
4. Set the output directory to the repository root if Vercel asks for one.
5. Deploy.

## Deploy to GitHub Pages

1. Push the files to a GitHub repository.
2. Open the repository settings.
3. Go to Pages.
4. Choose the branch that contains the site, usually `main`.
5. Select the repository root as the publishing source.
6. Save and wait for GitHub Pages to publish the site.

## Notes

The site uses no external dependencies, fonts, analytics, or client-side frameworks. Internal links are relative, so the pages can be hosted from a root domain or opened directly from the filesystem.
