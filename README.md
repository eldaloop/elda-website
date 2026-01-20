# Elda Loop Website

Official website for Elda Loop — the app that helps you stop scrolling and start doing.

## Pages

- `/` — Home page
- `/articles` — Articles hub (hobbies, tips, guides)
- `/privacy` — Privacy Policy
- `/terms` — Terms of Service

## Tech Stack

- Pure HTML/CSS/JS (no build step required)
- Hosted on Vercel
- Clean URLs via vercel.json

## Deployment

Push to `main` branch for automatic deployment.

```bash
# Local development
npx serve

# Or just open index.html in browser
```

## Adding Screenshots

Replace phone placeholders with actual screenshots:

```html
<!-- In phone-content div, replace with: -->
<img src="/screenshots/home.png" alt="Elda Loop">
```

Create a `/screenshots` folder for images.

## Adding Articles

Articles are static HTML for now. Add new articles to the articles page grid.

Future: Articles can be fetched from a CMS or Supabase for use in the app.

## Structure

```
elda-website/
├── index.html       # Landing page
├── articles.html    # Articles hub
├── privacy.html     # Privacy Policy
├── terms.html       # Terms of Service  
├── favicon.svg      # Site icon
├── vercel.json      # Vercel config
└── README.md
```

## Brand Colors

- Purple: #8B5CF6
- Purple Light: #A78BFA
- Teal: #3DBDA8
- Teal Light: #5EEAD4
- Dark: #0D0A14

## Contact

- Website: [eldaloop.com](https://eldaloop.com)
- Email: hello@eldaloop.com
- Instagram: [@eldaloop](https://instagram.com/eldaloop)
- TikTok: [@eldaloop](https://tiktok.com/@eldaloop)
- X: [@eldaloop](https://twitter.com/eldaloop)

---

© 2026 Elda Loop LLC
