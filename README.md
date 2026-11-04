# Privacy-Preserving Trajectory Intelligence — Call for Book Chapters

A responsive, static landing page based on the supplied one-page call for book chapters PDF.

## Preview locally

Open `index.html` in a browser, or run a local static server from this folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to Vercel

1. Extract this ZIP file.
2. Create a new GitHub repository and upload the contents of this folder (keep `index.html` at the repository root).
3. In Vercel, select **Add New → Project** and import the repository.
4. Framework preset: **Other**. Build command: leave blank. Output directory: `.`.
5. Deploy. The site is static and does not require environment variables or a build step.

You can also use Vercel CLI from this folder: `vercel`.

## Content and assets

- `index.html`, `styles.css`, `script.js`: website source.
- `assets/`: editor portrait crops and the supplied call-for-chapters PDF.

The Google Form, CMT portal, editor names, affiliations, contact addresses, publisher description, topic areas, and dates are transcribed from the supplied PDF. Please verify the form URL and all submission details before public launch.
