# Grace-PersonalPortfolio

_Last updated: 2026-09-22_

## About me
I'm a Tulane University student with a background in marketing, public
relations, interior design, and media production.

## About this site
A personal portfolio website built with plain HTML, CSS, and JavaScript (no
build step required), populated from my resume. It includes:

- A hero section with intro and calls to action
- An About section with education and study abroad details
- An Experience timeline of internships and roles
- A Skills section
- A Projects & Community Involvement section
- A Contact section with a downloadable resume (`assets/Grace_McGlashan_Resume.pdf`)

## Running locally
Just open `index.html` in a browser, or serve the folder with any static
server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customizing
- Update your bio in the About section of `index.html`.
- Keep the Experience and Projects sections in sync with your resume as it
  changes, and swap `assets/Grace_McGlashan_Resume.pdf` for an updated file
  when needed (keep the same filename, or update the links in `index.html`).
- Update the contact email and social links in the Contact section.
- Colors and fonts are defined as CSS variables at the top of
  `css/style.css`.

## Deploying
This site is static, so it can be deployed for free with GitHub Pages:

1. Push this repo to GitHub (already done if you're reading this on GitHub).
2. Go to **Settings > Pages**.
3. Under "Build and deployment", set the source to the `main` branch (root).
4. Your site will be published at `https://<username>.github.io/<repo-name>/`.

## Changelog
- **2026-09-22** &mdash; Populated the site with real content from Grace's
  resume: About, Experience timeline, Skills, Projects & Community
  Involvement, and a downloadable resume in the Contact section.
- **2026-09-17** &mdash; First version of the portfolio site: hero, About,
  Skills, Projects, and Contact sections with placeholder content.
