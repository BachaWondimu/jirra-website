# JIRRA Website Prototype

Open `index.html` for the public site and `admin.html` for the content-management demo.

## What works in this prototype
- Responsive cinematic JIRRA homepage
- Culture / community / football positioning
- Real supplied JIRRA photography
- Latest-content cards
- Admin demo for Blog, Poster, Event, Culture, Football and Community content
- Image preview, publish and delete using browser localStorage

## Before production
The admin page is intentionally a front-end prototype, not real security. For deployment, connect it to authenticated admin accounts, a CMS/database and cloud image storage. Do not rely on a hidden `/admin` URL or client-side password for security.

A practical production stack is Netlify for hosting plus a headless CMS or database/auth/storage provider. The public design can remain the same while the content source is replaced.
