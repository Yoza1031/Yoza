# YOZA — Portfolio & Commissions

A warm, responsive artist portfolio built with plain HTML, CSS and JavaScript. No framework, build step, paid builder or subscription required.

## Pages
- `index.html` — Home and artist introduction
- `gallery.html` — Artwork gallery
- `shop.html` — Commission types and enquiry details
- `contact.html` — Email, Instagram and YouTube
- `style.css` — Shared design and responsive navigation

## Publish free with GitHub Pages
1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then Save.
5. Wait for GitHub to publish the site. The Pages section will show the website URL.

## Website assets\nUpload these two image files into an `images` folder in the repository, keeping their filenames exactly as shown:\n- `yoza-oc.png` — your transparent OC header portrait.\n- `yoza-meadow.jpg` — the soft meadow background.\n\nThe background is styled with a warm overlay and approximately 25% opacity. The OC image is already transparent; no black background removal is needed.\n\n## Add artwork to the gallery
1. Create a folder named `images` in the repository.
2. Upload your artwork there as JPG, PNG or WebP, for example `portrait-study.webp`.
3. Open `gallery.html` and find a card inside `gallery-grid`.
4. Replace that card's placeholder `<div class="gallery-image">...</div>` with:
   `<div class="gallery-image"><img src="images/portrait-study.webp" alt="Portrait study"></div>`
5. Change the title and category below the image.
6. To add another artwork, copy one complete `gallery-card` block and update its image path, alt text, title and category.

The image styling is already included in `style.css`.

## Personalise
Contact email and social links are currently set in `contact.html` and the commission button in `shop.html`. Update those files if your public contact details change.

## Shop / commissions
The Shop is an enquiry menu, not an online checkout. Visitors contact you to discuss the brief, quote, deadline and payment details. This keeps the first version free and simple; payment processing can be added later if needed.
