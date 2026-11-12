BMVU MARKET WEBSITE STARTER

FILES
- index.html: complete responsive storefront (HTML, CSS and JavaScript in one file)
- assets/hero-art.webp: locally stored hero artwork crop

FEATURES
- Home page displays Featured Products first, then Shop by Category.
- The six category cards and the top-right three-dot menu open category-specific listings.
- Each product has a detail page with its own SEO title, meta description, keywords, image alt text, short description, full description, features, requirements, delivery and warranty notes.
- Product pages emit Product JSON-LD structured data; home and category pages emit Store/CollectionPage structured data.
- Search, sorting and a browser-local cart are included.
- USD pricing and responsive mobile/desktop layouts.

EDIT PRODUCTS
Open index.html in a code editor and edit the PRODUCTS array near the beginning of the JavaScript section. For every product, set a unique id, name, category, price, image, short description, full description, features, requirements, delivery, warranty, seoTitle, meta and keywords.

IMAGE QUALITY
Product cards use high-resolution image URLs from Unsplash with width=1200 and q=90. Replace these URLs with your own licensed product photography or optimized WebP images for a consistent brand look. Do not use images you do not have rights to use.

DEPLOY
For ordinary static hosting, upload index.html and the assets folder into the site's public_html/root folder. Keep the assets folder beside index.html.
For WordPress, this is a standalone static storefront, not a WordPress theme/plugin. It can be hosted in a separate folder/subdomain or integrated into a custom page/template by a developer.

IMPORTANT LIMITATIONS TO FINISH BEFORE SELLING
- Cart is local/browser-only. No payment gateway, order database, email automation, user accounts or admin dashboard is connected.
- Replace demo catalog details, prices, product images, warranty wording and delivery claims with verified current information before publishing.
- Add your actual WhatsApp/live-chat URLs and a real checkout/payment provider.
- Add a sitemap.xml and robots.txt, verify the domain in Google Search Console, submit the sitemap, and ensure each product URL is crawlable. Query-string URLs may need server-side SEO routing for best canonical/indexing control.
- SEO implementation does not guarantee Google rankings. Content accuracy, original product images, performance, links, competition and indexing all affect results.
