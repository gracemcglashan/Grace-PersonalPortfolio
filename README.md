# Grace-PersonalPortfolio

## About me
I'm a Psychology major at Tulane University with minors in SLAM and Design.

## About this site
A personal portfolio website built with plain HTML, CSS, and JavaScript (no
build step required). It includes:

- A hero section with intro and calls to action
- An About section
- A Skills section
- A Projects section with placeholder project cards
- A Contact section

## Running locally
Just open `index.html` in a browser, or serve the folder with any static
server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customizing
- Update your bio in the About section of `index.html`.
- Replace the placeholder project cards in the Projects section with your
  own work, links, and descriptions.
- Update the contact email and social links in the Contact section.
- Colors and fonts are defined as CSS variables at the top of
  `css/style.css`.

## Deploying
This site is static, so it can be deployed for free with GitHub Pages:

1. Push this repo to GitHub (already done if you're reading this on GitHub).
2. Go to **Settings > Pages**.
3. Under "Build and deployment", set the source to the `main` branch (root).
4. Your site will be published at `https://<username>.github.io/<repo-name>/`.
