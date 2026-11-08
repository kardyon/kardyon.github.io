# Kardyon Therapeutics website

A responsive, static one-page website built for GitHub Pages. It uses plain HTML, CSS, and JavaScript with no build step.

## Preview locally

Open `index.html` in a browser, or serve this directory with any local static server.

## Publish on GitHub Pages

1. Add these files to the root of a GitHub repository.
2. In **Settings → Pages**, select **Deploy from a branch**.
3. Choose the publishing branch and `/ (root)` folder, then save.
4. GitHub Pages will publish the site at the repository's Pages URL.

## Before publishing

- In `script.js`, replace `YOUR_EMAIL@example.com` with the verified company inquiry address. The contact form uses the visitor's email app; it does not store or transmit data to a server.
- Add the CEO's name and confirm all affiliations, titles, and bios.
- Add dated news and complete publication citations when available.
- Confirm therapeutic program descriptions and any regulatory or clinical-stage statements with the scientific and legal teams.
- Confirm permission to publish the founder and leadership portraits supplied in the Word documents. The Board of Advisers document did not contain portraits.
- The Nature article is cited, but no figures from the paper are reproduced. Obtain permission before adding publisher figures.
- The site loads DM Sans and Manrope from Google Fonts. If you prefer no third-party requests, remove the font links in `index.html`; the CSS includes system fallbacks.

## Files

- `index.html` — site content and structure
- `styles.css` — responsive design
- `script.js` — mobile navigation, current year, and mailto contact form
- `assets/home.jpg` — home-page research pathway figure
- `assets/founder-*.{png,jpg}` — scientific founder portraits from the supplied Word file
- `assets/leadership-ceo.jpg` — leadership portrait from the supplied Word file
