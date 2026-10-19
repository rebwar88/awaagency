AWA Agency — static bilingual website

DEPLOYMENT
1. Back up any existing website files first.
2. Open the file manager for awaagency.net in your hosting account.
3. Upload and extract this ZIP into the domain's web root (usually public_html).
4. index.html, style.css, app.js and assets/ must sit directly in that root,
   not inside an extra awa-site folder. Remove or rename a hosting placeholder
   index file only after backing it up.
5. Open https://awaagency.net and check both languages and mobile layout.
   The domain must point to your hosting and SSL must be enabled.

No WordPress, database, npm, build step or API key is required.
All assets are local. Language preference is stored in the visitor's browser.
The project logos have no outgoing links, as requested.
Email, WhatsApp and telephone buttons open the visitor's corresponding apps.
There is no contact form or collection of personal information on this site.

EDITING
Main bilingual copy: index.html (data-ku and data-en).
Services and project names: app.js.
Colors, layout, animations and responsive rules: style.css.
Logo images: assets/.
Reduced-motion preferences are respected.
After editing style.css or app.js, change the ?v= number after their names in index.html
so visitors' browsers download the new files instead of using a cached copy.

CONTACT
contact@awaagency.net
+964 770 0065765
Careers: jobs@awaagency.net

VERIFICATION
JavaScript syntax and local asset references were checked.
A live browser visual check and deployment to your Hostinger account were
not performed in this environment. Please review the site after upload.
