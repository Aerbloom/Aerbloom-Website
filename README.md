# Aerbloom multi-page static site

## Included
- `index.html` — homepage
- `basil.html`
- `rosemary.html`
- `jalapeno.html`
- `lavender.html`
- `cucumber.html`
- `styles.css`
- `script.js`
- `assets/` — logo, lineup image, basil render, and flavor crops

## Fastest deployment
This is a plain static site. No framework or build step.

### Option 1: Netlify
1. Create a free Netlify account.
2. Drag the whole folder into Netlify Drop.
3. Netlify publishes the site immediately.
4. In GoDaddy DNS, point your domain to Netlify.

### Option 2: GitHub Pages
1. Create a GitHub repo.
2. Upload all files.
3. Turn on GitHub Pages.
4. Add your custom domain in the Pages settings.
5. Point GoDaddy DNS to GitHub Pages.

### Option 3: Traditional hosting
If you buy basic hosting with GoDaddy or another provider, upload the files into the web root with cPanel File Manager or FTP.

## Can this be used with WordPress?
Yes, but with an important distinction:

### Easiest
Use this site as-is on static hosting. This is the cheapest and simplest route.

### With WordPress
You can use these files in WordPress in three ways:
1. **Custom theme or child theme**  
   Best long-term WordPress route. A developer can split the HTML into `header.php`, `footer.php`, `page templates`, and enqueue `styles.css` and `script.js`.
2. **Custom HTML blocks / page builder embeds**  
   Possible, but not ideal for a full multi-page site. Better for sections, not whole site architecture.
3. **Convert to Shopify or WordPress later**  
   Often the cleanest path: launch static first, then port into the CMS once copy and product data are final.

### What WordPress requires
A domain alone is not enough. WordPress needs hosting that supports PHP and a database, plus a WordPress install.

## What to customize next
- Replace the placeholder email address
- Add real pricing and pack sizes
- Add ingredients / nutrition facts
- Connect order buttons to Shopify, Faire, or a contact form
- Add a stockist page when distribution begins
