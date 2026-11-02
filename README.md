# CEEL Portfolio — editing guide

This is a plain HTML, CSS, and JavaScript portfolio. You do not need a framework to update the content.

## Change the content

Open `script.js`. The editable content is at the top of the file in three arrays:

- `PROJECTS` controls the project cards and the project portion of the homepage carousel.
- `CERTIFICATES` controls the certificates and the certificate portion of the homepage carousel.
- `SKILLS` controls the separate Skills page.

To add an image, place it in `images/projects`, `images/certs`, or `images/profile`, then use its website path such as `/images/projects/my-image.jpg` in the matching array.

## Change the look

Open `styles.css` to update colors, typography, spacing, responsive breakpoints, and component styles. The main colors are near the top in `:root`.

## Run locally

If Node.js is installed, run `npm run dev:static` or `pnpm dev:static` from the website folder, then open the local URL shown by Vite. The pages are `index.html`, `about.html`, `projects.html`, `certificates.html`, and `skills.html`.
