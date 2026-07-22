# Okuhle Madikwa — Portfolio / Virtual CV

Live site: https://o-madikwa.github.io/portfolio/

A single-page portfolio site built as a "Virtual CV" for Graduate Programme applications in **Quality Assurance**,
**Systems/Business Analysis**, and **Data Analysis**.

## About

This site presents my academic background, project experience, and skills in a format designed to complement my
traditional CV and LinkedIn profile. It's built from scratch with no frameworks or page builders.

## Features

- Single-page layout with smooth-scroll navigation and a responsive mobile menu
- Terminal-style animated role indicator in the hero section
- Scroll-triggered reveal animations (progressively enhanced — content stays visible if JavaScript fails to load)
- Fully responsive: tested from mobile (390px) up to desktop widths
- Respects `prefers-reduced-motion` for accessibility
- Visible keyboard focus states throughout

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties (design tokens), CSS Grid & Flexbox, media queries, no framework
- **Vanilla JavaScript** — no dependencies (mobile nav toggle, typing/role-cycling effect, IntersectionObserver-based
  scroll reveal)
- **Google Fonts** — Space Grotesk, Inter, IBM Plex Mono
- **Hosting** — GitHub Pages

## Project Structure

```
portfolio/
├── index.html          # Page structure & content
├── style.css           # All styling (design tokens at the top)
├── script.js           # Interactivity
├── assets/
│   └── Okuhle_Madikwa_CV.pdf   # Downloadable CV
└── README.md
```

## Running Locally

No build step required. Clone the repo and open `index.html` in a browser, or serve it locally:

```bash
git clone https://github.com/O-Madikwa/portfolio.git
cd portfolio
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deployment

Hosted via **GitHub Pages** from the `main` branch. See repo Settings → Pages.

## Contact

- Email: kuhleokuhle930@gmail.com
- LinkedIn: [okuhle-madikwa](https://www.linkedin.com/in/okuhle-madikwa-498476389)
- GitHub: [@O-Madikwa](https://github.com/O-Madikwa)
