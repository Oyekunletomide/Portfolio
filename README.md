# Tomide Oyekunle Portfolio Website

This is a complete static portfolio package for a UX/UI, Product Design, Shopify CRO, and landing page designer.

## What is included

- `index.html` - main portfolio homepage
- `case-studies/` - 4 detailed case study pages
- `assets/styles.css` - all styling
- `assets/script.js` - theme toggle, mobile menu, filters, and reveal animations
- `assets/*.svg` - placeholder project and profile images
- `assets/og-image.png` - social sharing preview image
- `assets/favicon.svg` - browser icon
- `assets/resume-template.pdf` - downloadable resume placeholder
- `thank-you.html` - contact form success page
- `404.html` - error page
- `robots.txt` and `sitemap.xml` - basic SEO files

## First things to edit

1. Open `index.html`.
2. Replace:
   - `Tomide Oyekunle`
   - `oyekunletomide@gmail.com`
   - `linkedin.com/in/yourname`
   - all placeholder metrics
   - all placeholder testimonials
   - all placeholder case study copy
3. Replace project images inside `assets/` with your real screenshots.
4. Replace `assets/profile-placeholder.svg` with your real profile image.
5. Replace `assets/resume-template.pdf` with your real resume PDF.

## How to replace images

Keep the same file names for the easiest update:

- `assets/project-shopify-homepage.svg`
- `assets/project-product-page.svg`
- `assets/project-saas-dashboard.svg`
- `assets/project-mobile-app.svg`
- `assets/project-landing-page.svg`
- `assets/profile-placeholder.svg`

You can replace SVG files with PNG or JPG, but update the image paths in the HTML if the file extension changes.

## Contact form setup

The form is prepared for Netlify Forms:

```html
<form name="portfolio-contact" method="POST" action="thank-you.html" data-netlify="true">
```

To make it work:

1. Upload/deploy the whole folder to Netlify.
2. Netlify should detect the form automatically.
3. Test the form after deployment.

For other hosting platforms, connect the form to Formspree or your own backend.

## How to deploy fast

### Netlify
1. Go to Netlify.
2. Drag and drop the full portfolio folder.
3. Set your custom domain if you have one.

### GitHub Pages
1. Create a GitHub repository.
2. Upload all files.
3. Enable GitHub Pages from repository settings.
4. The contact form will need Formspree or another backend.

### Vercel
1. Upload the project to GitHub.
2. Import the repository into Vercel.
3. Deploy as a static site.
4. Use Formspree or another backend for the form.

## Best portfolio content order

Use this order inside every real case study:

1. Project overview
2. Problem
3. Your role
4. Goal
5. Research or audit findings
6. User flow or wireframes
7. Design decisions
8. Final UI
9. Results or expected impact
10. Lessons learned

## Important

Do not publish fake metrics as real results. If a number is not real, label it as:

- design hypothesis
- expected impact
- placeholder metric
- internal estimate

Your strongest portfolio will come from real screenshots, clear thinking, and honest results.
