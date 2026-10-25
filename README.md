# Renovare website

Static site: plain HTML and CSS, no build step.

## Structure
- index.html, about.html, donate.html, contact.html
- css/style.css (all styling; change colours in the :root block)

## Before publishing
Replace every highlighted [placeholder] with real details.
Replace [project email] in contact.html.

## Hosting on GitHub and Cloudflare Pages (free)
1. Create a GitHub account if needed, then a new public repository called "renovare-site".
2. Upload these files (Add file > Upload files) and commit.
3. In Cloudflare, go to Workers & Pages > Create > Pages > Connect to Git, and select the repository.
4. Build command: leave empty. Build output directory: / (root). Save and deploy.
5. Your site will be live at renovare-site.pages.dev. Add a custom domain later if you buy one.

## Notes
- The contact form uses a mailto link, which opens the visitor's email app. For a form that works without that, a free form service can be connected later.
- Keep the repository public only if you're happy for the code to be visible; the content is visible anyway once published.
