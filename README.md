# JhannKahhh Print Services

A responsive business website for a print-services project. It uses PyScript and Python event handlers for a filterable service catalog, live print estimates, a multi-item quote builder, and quote form validation.

The site also includes a project walkthrough and an FAQ explaining the limits of this front-end demo.

## PyScript events

- Filter the service catalog by business, marketing, or everyday printing, then configure a service directly from its card.
- Choose a finish and turnaround to calculate sample pricing, add multiple print types to a quote, and remove or clear items.
- Upload an image for a local-only artwork preview (up to 5 MB); the file is not uploaded or stored.
- Sample bulk discounts apply to the quote: 5% for 100+ items and 10% for 500+ items.
- Submit the form to validate the required fields and display an on-page estimate preview.
- Use **Print / save as PDF** to print the quote or save it as a PDF from the browser.
- The interactions run in Python in the browser; no JavaScript application code or backend is required.

## Run the website

Open `index.html` in a modern browser while connected to the internet. PyScript and the web fonts load from their CDNs, so the first page load needs an internet connection. If opening the file directly does not load PyScript in your browser, serve this folder with a local static web server and open its local URL.

## Project notes

- The listed PHP prices and rush surcharge are sample values. Update them to match the business before using the site as a real price list.
- The estimate form is a front-end demonstration only. It does not send email, upload artwork, or save submitted information; quotes and previews remain in browser memory until the page is refreshed.
- The website is ready to publish as a static GitHub Pages site from the repository root.
- For the group-contribution requirement, each member should make and push their own meaningful changes with clear commit messages.

## Publish with GitHub Pages

In the GitHub repository, open **Settings → Pages**, choose **Deploy from a branch**, select the `main` branch and `/ (root)` folder, then save. GitHub Pages will publish `index.html` after deployment completes.
