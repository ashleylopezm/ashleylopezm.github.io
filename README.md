# Ashley Lopez — Personal Portfolio Website

A responsive, single-page personal portfolio and resume website for Ashley Lopez showcasing experience, technical projects, skills, education, and community involvement at the intersection of computer science, data engineering, machine learning, and criminal justice / public policy.

---

## Overview

- **Site Type:** Static Single-Page Webpage (Portfolio / Resume)
- **Tech Stack:**
  - **Languages:** HTML5, CSS3, Vanilla JavaScript
  - **Frameworks / Libraries:** None (Zero external JavaScript dependencies; uses standard web APIs and Google Fonts for typography)
  - **Package Manager:** None (Static assets served directly)
- **Key Features:**
  - Responsive layout (CSS Grid & Flexbox) with dark and light theme support (`prefers-color-scheme` and data-theme attributes)
  - Print-friendly stylesheets for resume generation
  - Performance-oriented scroll reveal animations using `IntersectionObserver`
  - Reading progress bar indicator
  - Accessible design respecting `prefers-reduced-motion` settings

---

## Requirements

- **Browser:** Any modern web browser supporting modern HTML5, CSS Grid, and the `IntersectionObserver` API (e.g., Chrome, Firefox, Safari, Edge).
- **Local Development (Optional):** Any standard local HTTP server (Python 3, Node.js / npx, PHP, etc.) for serving static files.

---

## Setup & Running Locally

Because this project consists of plain HTML, CSS, and JavaScript, no build step or package installation is required.

### 1. Direct Browser Preview
Open `index.html` directly in your default web browser:
- **macOS:**
  ```bash
  open index.html
  ```
- **Linux:**
  ```bash
  xdg-open index.html
  ```
- **Windows:**
  ```cmd
  start index.html
  ```

### 2. Local HTTP Server (Recommended)
You can serve the static files locally using any of the following tools:

- **Using Python 3:**
  ```bash
  python3 -m http.server 8000
  ```
  Then visit `http://localhost:8000` in your browser.

- **Using Node.js (`npx`):**
  ```bash
  npx serve .
  ```

- **Using PHP:**
  ```bash
  php -S localhost:8000
  ```

---

## Scripts

There are currently no build, bundling, or package management scripts configured for this repository.

- `<!-- Embedded JS in index.html -->`: Handles scroll reveal animations via `IntersectionObserver` and updates the top reading progress bar during scrolling.
- *(TODO: Add npm/Node or Makefile scripts if a bundler, CSS preprocessor, or linter is introduced).*

---

## Environment Variables

No environment variables are required to run this static website.

- *(TODO: Define environment variables if deploying via CI/CD pipelines or integrating dynamic backends/form endpoints).*

---

## Testing

There is currently no automated test suite configured.

- **Manual Testing Checklist:**
  - Validate responsive layout across mobile, tablet, and desktop viewports.
  - Verify light and dark mode styling.
  - Test print view formatting (`Cmd+P` / `Ctrl+P`).
  - Verify smooth animations and ensure `prefers-reduced-motion` disables animations as expected.
- *(TODO: Add automated HTML/CSS validation or visual regression testing tools like Playwright/Cypress/HTMLHint).*

---

## Project Structure

```
.
├── index.html    # Main entry point containing page structure, embedded CSS styles, and client-side JavaScript
└── README.md     # Project documentation and setup guide
```

---

## License

<!-- TODO: Specify project license (e.g. MIT, CC-BY-4.0, or All Rights Reserved) -->
TODO: No license file currently provided. Specify an appropriate open-source or proprietary license.
