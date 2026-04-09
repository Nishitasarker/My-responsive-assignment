# 🌍 TechWave: Responsive Content & Podcast Platform

**TechWave** is a high-performance, mobile-first web interface designed for tech-centric content delivery. This project serves as a showcase of modern CSS architecture, focusing on flexible layouts, semantic HTML, and cross-browser accessibility.

---

## 🚀 Deployment & Links
- **Live Production URL:** [https://nishitasarker.github.io/My-responsive-assignment/](https://nishitasarker.github.io/My-responsive-assignment/)
- **GitHub Repository:** [https://github.com/nishitasarker/My-responsive-assignment](https://github.com/nishitasarker/My-responsive-assignment)

## 📋 Table of Contents
1. [Core Functionalities](#-core-functionalities)
2. [Technical Stack](#-technical-stack)
3. [Architecture & Design Decisions](#-architecture--design-decisions)
4. [Developer Onboarding](#-developer-onboarding)
5. [Roadmap](#-roadmap)
6. [Author](#-author)

---

## ⚙️ Core Functionalities
The platform is engineered to handle various content types with a focus on user engagement:
* **Dynamic Navigation:** A responsive header that adapts from a full-link desktop view to a condensed mobile-friendly layout.
* **Hero Section:** High-impact visual area designed for primary Call-to-Action (CTA) and brand messaging.
* **Content Grid:** A multi-column layout for tech articles and podcasts that utilizes fluid sizing to prevent overflow.
* **Interactive Components:** Optimized buttons and cards with CSS hover states and transitions for better tactile feedback.
* **Footer Architecture:** A comprehensive footer for secondary navigation and social proof.

## 🛠️ Technical Stack
* **HTML5:** Semantic markup (e.g., `<header>`, `<main>`, `<section>`, `<footer>`) to ensure SEO optimization and screen-reader accessibility.
* **CSS3:** Custom properties (variables) for consistent theming and advanced layout modules (Flexbox/Grid).
* **Git:** Version control managed through a clean branching strategy.

## 🏗️ Architecture & Design Decisions
To maintain a professional codebase, the following principles were applied:
1.  **Mobile-First Workflow:** Styles were written for small screens first, using `min-width` media queries to scale up. This reduces the amount of CSS needed for mobile devices.
2.  **Fluid Typography:** Font sizes are calculated to ensure readability across all DPI settings.
3.  **Performance Optimization:** Minimal use of external libraries to ensure fast First Contentful Paint (FCP) and low Cumulative Layout Shift (CLS).

## 📸 Screenshot
![WhatsApp Image 2026-04-09 at 17 04 17](https://github.com/user-attachments/assets/9af2ac0b-9e31-4cf8-9f2e-7fed6b72d680)
Responsive
![WhatsApp Image 2026-04-09 at 17 46 24](https://github.com/user-attachments/assets/bd7c7bd4-287a-4a8c-9824-600384d52a08)


## 💻 Developer Onboarding
For developers looking to extend this project, follow these steps:

### Setup
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/nishitasarker/My-responsive-assignment.git](https://github.com/nishitasarker/My-responsive-assignment.git)
Open the environment:
We recommend using VS Code with the Live Server extension.

Configuration:
Global styles (colors, spacing) can be modified in the root of the CSS file via variables:

CSS
:root {
  --primary-color: #your-color;
  --transition-speed: 0.3s;
}

Contribution Workflow
 1.Branching: Always create a feature branch (git checkout -b feat/your-feature).

 2.Naming Convention: Use kebab-case for CSS classes (e.g., .nav-container).

 3.Testing: Ensure the layout is checked on at least 3 breakpoints (320px, 768px, 1200px).


👤 Author
Nishita Sarker

Portfolio: GitHub Profile

Professional Networking: LinkedIn

© 2026 Nishita Sarker. This project is open-source and available under the MIT License.
