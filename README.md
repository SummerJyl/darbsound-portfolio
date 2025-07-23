# Darbsound Portfolio — Tech Stack & Project Structure

## 1. Frontend Framework: React
- Component-based, reusable, with a great ecosystem.
- Fits well with modular components.
- Enables future expansion (e.g., Podcast page with dynamic content).

## 2. Static Site Generator / Framework: Next.js
- Built on React, offers file-based routing (easy creation of pages like `/about`, `/contact`).
- Supports Static Site Generation (SSG) for fast load times and SEO.
- Can add Server-Side Rendering (SSR) or API routes later if needed.
- Easy deployment to Vercel, Netlify, or GitHub Pages (with some config).

## 3. Styling
- CSS Modules or Styled Components for scoped, maintainable styles.
- Tailwind CSS for utility-first and rapid styling (optional).

## 4. Content Management
- Start with Markdown or JSON files for About, Credits, etc. — easy to maintain.
- Later, add a headless CMS like Contentful, Sanity, or Netlify CMS for easy content editing.

## 5. Hosting & Deployment
- GitHub Pages (for static sites, simple portfolios).
- Vercel or Netlify (best support for Next.js, automatic builds from GitHub).
- Keep Bluehost for domain registration and redirect/proxy if desired.

## 6. Additional Tools & Features
- Podcast embedding (Spotify, Apple Podcasts widgets).
- IMDb and movie links — manual or API integration if desired.

---

## Suggested Project Structure (Next.js)

/pages
index.js # Home page
about.js # About page/component
contact.js # Contact page/form
credits.js # Credits page
podcast.js # Podcast page (future)
/components
Header.js
Footer.js
ProjectCard.js # Component to show projects/credits
/public
assets/ # Images and media files
/styles
globals.css
components.module.css

/index.html # Home / Work page
/about.html # About page
/credits.html # Credits page
/contact.html (removed) # Contact replaced by modal popup on all pages
/css/
style.css # Main stylesheet
/images/ # Images and thumbnails
/js/ # Optional JavaScript files

## Features
- Responsive navigation bar on all pages
- Contact form implemented as a modal popup (no dedicated contact page)
- Highlighted projects with images and descriptions
- Clean typography and color palette
- Minimal tracking for privacy (no invasive analytics)

---

## Next Steps (Optional)
If you want to modernize your portfolio later:
- Consider moving to React or Next.js for easier page management and scalability
- Add CSS Modules or Styled Components for scoped styling
- Use Markdown or a CMS for easier content updates

---

If you want me to help build or update any part of your current site or start a React/Next.js version, just let me know!
