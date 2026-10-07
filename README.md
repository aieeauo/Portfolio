# Anniejel D. Llaguno | Computer Engineering Portfolio

A responsive, static portfolio for my application to the DOST-ASTI Computer Software Division (NAIRA Project) internship. Built with plain HTML, CSS, and JavaScript. No framework or build step.

## Features
- Responsive layouts for mobile, tablet, and desktop
- Accessible navigation: skip link, keyboard-friendly menu, `aria-current` on the active section
- Sections: Hero, About, Education, Skills, Projects (two), Certifications, Documentation, Contact
- Light reveal animations that respect `prefers-reduced-motion`
- SEO and Open Graph metadata

## Technologies
HTML5, CSS3 (variables, Grid, Flexbox), vanilla JavaScript. Fonts: Space Grotesk and DM Sans via Google Fonts.

## Project structure
```
portfolio/
├── index.html
├── style.css
├── script.js
├── resume.pdf     <- you add this
└── README.md
```

## CV file
<!-- IMPORTANT: place your actual CV PDF in the project root and name it exactly: resume.pdf -->
Place your actual CV in the project root and name it `resume.pdf`. The "Download CV" buttons point to this file. No CV is included in this repository.

## Run locally
Open `index.html` in a browser, or serve the folder:
```
python -m http.server 8000
```
Then visit http://localhost:8000.

## Deploy to GitHub Pages
1. Create a GitHub repository (for example `portfolio`).
2. Upload `index.html`, `style.css`, `script.js`, `resume.pdf`, and `README.md` to the repository root.
3. Go to Settings → Pages.
4. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, then Save.
5. After a minute or two, your site is live at the URL shown on that page.
6. Add the URL to your CV, and to the `og:url` meta tag in `index.html`.

## Customization
- **Links:** GitHub and live-demo links are not shown yet. When ready, add buttons inside the project cards in `index.html`, and a GitHub row in the Contact list.
- **Colors:** edit the CSS variables at the top of `style.css`.
- **Content:** only list skills, projects, and certifications you can discuss in an interview.
