<h1 align="center">📈 Horiseon Marketing: Code Refactor</h1>

<p align="center">An accessibility and SEO refactor of the landing page for Horiseon, a fictional digital-marketing agency.</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&amp;logo=css&amp;logoColor=white" alt="CSS3">
</p>

<p align="center">
  <img src="docs/screenshot.jpg" alt="Full Horiseon landing page on desktop with hero image, three service sections and a benefits sidebar" width="560" align="top">
  <img src="docs/screenshot-mobile.jpg" alt="Horiseon landing page on a phone" width="190" align="top">
</p>

## What Was Refactored

The goal was to make the existing site more accessible, better for search engines and easier to maintain, without changing how it looks on desktop.

**Accessibility and SEO**
- Replaced generic `<div>`s with semantic elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>` and `<footer>`
- Headings follow a logical order
- Descriptive `alt` text on content images. Decorative icons use empty `alt` so screen readers skip them.
- Added a descriptive `<title>`, a meta description and a viewport tag

**Maintainability**
- Consolidated three duplicated service blocks into one `.service` class, and three benefit blocks into one `.benefit` class
- Replaced float-based page layout with Flexbox
- Organized the CSS to follow the order of the HTML, with comments

**Responsive design**
- Added breakpoints for tablets (980px) and phones (640px)

## Page Sections

- Navigation linking to each service section
- Services:
  - Search Engine Optimization
  - Online Reputation Management
  - Social Media Marketing
- Benefits sidebar:
  - Lead Generation
  - Brand Awareness
  - Cost Management

## Built With

- HTML5
- CSS3 (Flexbox and Grid)

## Running Locally

No build step is needed.

1. Clone the repo:
   ```bash
   git clone https://github.com/ChristianKrantz11/horiseon-challenge.git
   ```
2. Open `index.html` in your browser.

## Author

[ChristianKrantz11](https://github.com/ChristianKrantz11)
