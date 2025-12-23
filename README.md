# Developer Josh – Portfolio

A clean, single-page portfolio site. Pure HTML/CSS/JS.

## Live Demo

- Website: https://developer-josh.de/

## Preview

[![Developer Josh – Portfolio preview](assets/portfolio-preview.png)](https://developer-josh.de/)

## Features

- Hero section with avatar, role, and smooth-scroll CTA
- Sidebar navigation with custom smooth scrolling and section mini-map
- Skills, tech stack, projects, experience timeline, and contact sections
- Animated particle background and subtle parallax hero accent
- Responsive layout using modern CSS (flexbox, grid, clamp, gradients)
- Dynamic age and footer year range calculated in JavaScript
- Custom scroll progress indicator and reveal-on-scroll animations
- Error pages for common HTTP error states (404, 500)

## Tech Stack

- **HTML5** – single-page layout
- **CSS3** – custom styling, animations, responsive layout
- **JavaScript (vanilla)** – interactions, animations, dynamic content
- **Devicon** – icon font for tech stack logos (served via CDN)

## Project Structure

- `index.html` – main portfolio page
- `assets/` – favicon, avatar and other static assets
- `errorpages/404.html` – custom 404 error page
- `errorpages/500.html` – custom 500 error page
- `robots.txt` – crawler directives
- `sitemap.xml` – sitemap for search engines
- `LICENSE` – MIT license

## Getting Started

You can run this portfolio locally with any static file server or simply open the HTML file in a browser.

### Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/portfolio.git
   cd portfolio
   ```
2. Open `index.html` in your browser, **or** serve the folder with a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   # then visit http://localhost:8000
   ```

### Deploying

This project is a static site and can be deployed on almost any platform, for example:

- GitHub Pages
- Netlify
- Vercel
- Any static web server (Nginx, Apache, etc.)

For GitHub Pages, push the repository and enable Pages for the `main` branch (or a `docs`/`gh-pages` branch) with the project root as the site source.

## Attribution & License

The source code in this repository is licensed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

Additionally, the HTML/CSS/JS for the main page may be reused or adapted for your own personal or commercial projects **as long as you keep an attribution link back to https://developer-josh.de/ and credit me as the original author**, as noted in the header comment of `index.html`.

