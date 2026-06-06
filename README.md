# Advanced CSS3 & Responsive Portfolio Website

A modern, visually appealing, and fully responsive multi-page portfolio website built using semantic HTML5 and advanced CSS3 technologies.

## Project Overview

This project transforms a semantic portfolio website into a highly responsive and visually stunning web application using modern CSS3 layout architectures including CSS Grid, Flexbox, responsive media queries, and CSS custom properties.

The website is designed to provide a seamless user experience across all device sizes including mobile phones, tablets, laptops, and desktop screens.

## Features

* Semantic HTML5 structure
* Advanced CSS3 styling
* CSS Grid layouts
* Flexbox alignment
* Mobile-first responsive design
* Dynamic light/dark theme
* CSS custom variables
* Accessible navigation
* Responsive contact form
* SEO-friendly structure
* WCAG accessibility support

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* Media Queries
* CSS Variables
* GitHub Pages

## CSS Grid Implementation

CSS Grid is used for complex two-dimensional layouts including:

* Responsive project sections
* Multi-column layouts
* Adaptive content arrangement
* Dynamic responsive structures

Example:

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}
```

## Flexbox Usage

Flexbox is used for localized component alignment such as:

* Navigation bars
* Buttons
* Form alignment
* Responsive positioning
* Content organization

Example:

```css
nav ul {
  display: flex;
  gap: 1rem;
}
```

## Responsive Design

The website follows a mobile-first responsive design approach using CSS media queries.

Responsive support includes:

* Mobile devices
* Tablets
* Laptops
* Desktop screens

Example:

```css
@media (min-width: 768px) {
  .grid-container {
    grid-template-columns: repeat(2, 1fr);
  }
}
```

## Light/Dark Mode Theme

The website includes a dynamic theming system using CSS variables.

Example:

```css
:root {
  --background-color: #ffffff;
  --text-color: #111111;
}

[data-theme="dark"] {
  --background-color: #111111;
  --text-color: #ffffff;
}
```

## Accessibility Features

This project follows WCAG accessibility standards:

* Semantic HTML5 tags
* Keyboard navigation support
* Focus outlines
* ARIA labels
* Screen reader friendly structure
* Accessible forms
* Proper heading hierarchy

## SEO Optimization

SEO-friendly features include:

* Meta descriptions
* Viewport optimization
* Semantic structure
* Optimized heading hierarchy

## Project Structure

```text
portfolio-website/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
├── style.css
└── README.md
```

## Lighthouse Goals

This project is designed to achieve high Lighthouse scores:

* Accessibility: 100
* SEO: 100
* Best Practices: 100

## Expected Outcome

A pixel-perfect, highly responsive portfolio website that adapts seamlessly across:

* Mobile Phones
* Tablets
* Laptops
* Desktop Screens

The website maintains accessibility, responsiveness, and visual consistency on all screen sizes.
