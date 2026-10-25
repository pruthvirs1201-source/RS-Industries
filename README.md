# RS Industries Website

A responsive, single-page company website for RS Industries, focused on technical consumables and industrial supply.

## Website features

- Responsive desktop and mobile layout
- Company introduction and service approach
- Product-category enquiry links
- Quotation enquiry form
- No external JavaScript or CSS dependencies

## Run locally

Open `index.html` in a modern web browser. The site is static HTML, CSS, and JavaScript, so no build step is required.

## Publish with GitHub Pages

1. Open the repository: https://github.com/pruthvirs1201-source/RS-Industries
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Wait for GitHub Pages to publish the site. The published URL will be shown in the Pages settings.

## Important before going live

- The enquiry form currently opens the visitor's default email app using a `mailto:` link. It does not submit to a server or store enquiries.
- The recipient email is intentionally not hard-coded because the official RS Industries contact email has not yet been provided. Update the form's JavaScript mailto target in `index.html` to the correct business email before launch.
- Add the official phone number, business address, confirmed product range, and any verified certifications or supplier brands before publishing.
- Product categories are presented as indicative sourcing categories; confirm actual availability and scope before making specific claims.

## Main file

- `index.html` — complete website, styling, and client-side interaction.
