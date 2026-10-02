# ElSalvadorwedding.com

A GitHub Pages–ready static website for **El Salvador Wedding**, based on the structure and visual direction of the referenced Firecracker Weddings site, redesigned with a more modern editorial/luxury look.

## Included
- Home / hero with featured YouTube film
- Photo portfolio using the referenced Wix portfolio image sources
- Film section using YouTube embeds/thumbnails from the referenced channel
- About / approach section
- Blog / journal index based on the existing blog topics
- Contact section with `hi@davidrj.com`
- "Based in El Salvador & London"
- 50% promotion banner: weddings in El Salvador until November 2027
- Fully responsive layout
- No build system or dependencies required

## GitHub Pages
1. Create a GitHub repository, e.g. `elsalvadorwedding`.
2. Upload `index.html` and the `assets` folder.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`.
5. Save. GitHub will publish the site.

## Important: featured showreel
The supplied YouTube channel was accessible, but the exact video ID for **"Luxury Wedding Showreel"** could not be reliably resolved from the available indexed page data. The hero currently uses a known film from the channel and is labelled for the requested showreel.

When the exact YouTube video URL is available, replace `ARpPdgYCyaY` in the hero iframe with the ID from:
`https://www.youtube.com/watch?v=VIDEO_ID`

The site is otherwise ready to upload.

## Contact form
The form uses a simple `mailto:` action so it works on a static GitHub Pages site without a backend. For a more reliable production enquiry form, connect it to Formspree, Netlify Forms, or another form endpoint later.
