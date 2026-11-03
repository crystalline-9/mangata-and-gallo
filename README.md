# Mangata & Gallo — Homepage

A responsive homepage concept for Mangata & Gallo, a fictional fine-jewelry business based in Austin, Texas.

This project was developed as part of Course 4: HTML and CSS in Depth, within the Meta Full Stack Developer Specialization on Coursera.

The specialization consists of ten courses covering front-end and back-end development. This project focuses on semantic HTML, CSS layout techniques, visual styling, interactive states, and responsive design.

## Project Overview

Mangata & Gallo specializes in fine jewelry for engagements, weddings, anniversaries, and other meaningful occasions.

The homepage was designed to communicate the brand's emphasis on timeless design, quality craftsmanship, and thoughtfully created jewelry.

The design uses an editorial-inspired aesthetic, with coordinated photography, refined typography, and a restrained colour palette.

## Features

- Semantic HTML5 page structure.
- Branded header with navigation and logo.
- Promotional hero banner with a call-to-action.
- Three featured content sections:
  - Engagement
  - Our Collections
  - Craftsmanship
- Two-column footer with brand wordmark and copyright information.
- Responsive layouts for desktop, tablet, and mobile screens.
- Interactive hover states for navigation, buttons, and feature cards.
- Keyboard-visible focus indicators.
- Reduced-motion accessibility consideration.
- Descriptive alternative text for images.

## Technologies

- HTML5
- CSS3
- Flexbox
- CSS media queries
- Google Fonts:
  - Cormorant Garamond
  - Lato
- Git and GitHub for version control.

No JavaScript or external frameworks are required.

## Design Direction

The visual identity uses a warm, understated palette:

| Colour    | Hex       | Purpose                         |
| --------- | --------- | ------------------------------- |
| Ivory     | `#F5F2E9` | Primary background              |
| Charcoal  | `#30312F` | Text and contrast               |
| Champagne | `#D6C29A` | Accent and interactive elements |
| White     | `#FFFFFF` | Feature card backgrounds        |

Cormorant Garamond provides an editorial serif style for headings, while Lato maintains readability across navigation and body text.

The photography and generous spacing reinforce the brand's focus on craftsmanship and meaningful occasions.

## Design Rationale

Mangata & Gallo is a fictional fine-jewelry business based in Austin, Texas, specializing in meaningful pieces for engagements, weddings, anniversaries, and other special occasions. Its intended audience includes people seeking thoughtfully designed, high-quality jewelry that combines craftsmanship with timeless style.

Flexbox was selected to organize the three content sections and footer. It provides a straightforward way to create evenly distributed columns, maintain consistent spacing, and adapt the layout for smaller screens.

The visual style uses a warm palette of ivory, charcoal, and champagne gold to communicate elegance, quality, and warmth without making the page feel overly decorative or crowded. Cormorant Garamond provides an editorial feel for headings, while Lato keeps navigation and body text clean and readable.

Interactive states include hover effects on navigation links, buttons, and content cards. Subtle colour transitions, shadows, and movement provide visual feedback without distracting from the content.

Accessibility and usability were also considered. Images include descriptive alternative text, links have visible keyboard-focus indicators, and responsive CSS allows the layout to adapt to different screen sizes. A reduced-motion preference is also respected.

## Project Structure

```text
mangata-and-gallo/
├── index.html
├── README.md
├── css/
│   └── styles.css
└── images/
    ├── collections/
    │   ├── collections.jpg
    │   ├── craftsmanship.jpg
    │   └── engagement-ring.jpg
    ├── hero/
    │   └── hero-editorial.jpg
    └── logo/
        ├── monogram-black.png
        ├── monogram-white.png
        ├── wordmark-black.png
        └── wordmark-white.png
```

## Running Locally

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.

Google Fonts are loaded externally, so an internet connection is needed for the selected fonts. System fallback fonts are provided.

## Project Status

**Completed — Course Capstone Project**

This project represents a completed homepage design exercise focused on semantic HTML, CSS layout, visual design, and responsive implementation.

## Repository

[GitHub — crystalline-9/mangata-and-gallo](https://github.com/crystalline-9/mangata-and-gallo)
