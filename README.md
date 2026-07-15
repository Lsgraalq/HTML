# HTML — "AutoExpress" landing page

> **Created: January 2022** — learning project (responsive landing-page layout).

A single-page **car-dealership landing page** ("AutoExpress" — a mock service for importing cars from the USA to Ukraine), built as practice in cutting a real design into responsive HTML/CSS.

This was a step up from earlier static pages: a full multi-section layout using Bootstrap's grid, custom styling, hover states, and mobile breakpoints.

## What it includes

- **Header** — logo, phone, headline/subheadline, call-to-action button, social icons, and a hero car image over a background image.
- **Services** — an "our services" section with descriptive text and a numbered list of steps (purchase, sea delivery, customs, repair, certification, registration), with hover effects on each item.
- **"Why us"** — stats block (cars delivered, years on the market, client trust).
- **Slider section** — a Slick carousel placeholder for showcasing cars.

## Techniques practiced

- Bootstrap 5 grid and buttons (loaded from CDN)
- Custom CSS with pseudo-elements (`::before` / `::after`) for decorative lines and labels
- Responsive design with multiple `@media` breakpoints (down to ~575px)
- Google Fonts (Oswald) and Bootstrap Icons
- jQuery + [Slick](https://kenwheeler.github.io/slick/) carousel (`main.js`)

## Running

Open `index.html` (inside the project subfolder) in a browser.

## Stack

- HTML / CSS
- Bootstrap 5
- JavaScript, jQuery, Slick
