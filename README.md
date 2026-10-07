# Anniejel D. Llaguno | Computer Engineering Portfolio

A responsive, static portfolio of a BS Computer Engineering student, prepared for an internship application to the DOST-ASTI Computer Software Division (NAIRA Project). Built with plain HTML, CSS, and JavaScript. No framework or build step.

## Overview

The portfolio supports my CV with a short profile, skills, two academic projects, certifications, and a project write-up.

**Projects featured**
- **DLSP Engineering Insights Repository**: a web development and database academic team project (May 2026)
- **OZkar OS: Turn Distraction Into Direction**: a UI/UX and operating systems academic concept, including the KarGo study-management application (June 2025)

## Features

- Responsive layouts for mobile, tablet, and desktop
- Accessible navigation: skip link, keyboard-friendly menu, `aria-current` on the active section
- Sections: Home, About, Education, Skills, Projects, Certifications, Documentation, Contact
- Light reveal animations that respect `prefers-reduced-motion`
- SEO and Open Graph metadata

## Technologies

HTML5, CSS3 (variables, Grid, Flexbox), and vanilla JavaScript. Fonts: Space Grotesk and DM Sans via Google Fonts.

## Project structure

```
Portfolio/
├── index.html
├── style.css
├── script.js
├── resume.pdf
└── README.md
```

## CV file

The "Download CV" buttons point to `Llaguno_Anniejel_CV.pdf` in the project root. To update my CV, replace that file and keep the same filename.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deployment

**Vercel**
1. Sign in at vercel.com with GitHub.
2. Choose **Add New → Project** and import this repository.
3. Keep the default settings (no build command or output directory) and click **Deploy**.

Every push to `main` redeploys the site automatically.

**GitHub Pages (alternative)**
1. Go to **Settings → Pages**.
2. Under "Build and deployment", choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

## Updating the site

After editing a file:

```
git add .
git commit -m "Describe the change"
git push
```

## Customization

- **Links:** GitHub and live-demo links for the projects are not shown yet. When they are available, add buttons inside the project cards in `index.html`, and a GitHub row in the Contact list.
- **Open Graph URL:** after deployment, add the live URL to an `og:url` meta tag in `index.html`.
- **Colors:** edit the CSS variables at the top of `style.css`.
- **Content:** only list skills, projects, and certifications that can be discussed in an interview.

## Contact

Anniejel D. Llaguno · anniejeldejesusllaguno@gmail.com · [LinkedIn](https://www.linkedin.com/in/anniejel-llaguno-654208299)
