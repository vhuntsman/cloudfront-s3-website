# Mock WordPress Static Site

This is a small mock of a WordPress site that has already been exported/generated as static HTML.

Structure:
- `index.html` — homepage
- `blog/index.html` — blog archive
- `blog/*.html` — individual posts
- `about.html`, `contact.html` — static pages
- `assets/style.css` — shared stylesheet

It intentionally contains only static files so you can practice migrating it to:
S3 + CloudFront + HTTPS + DNS.

There is no PHP, WordPress runtime, database, or server-side functionality.
