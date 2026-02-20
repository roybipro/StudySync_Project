# StudySync Project

A responsive education-themed landing page built with **HTML5** and **CSS3**.

This project is a static frontend implementation of a product-style website for StudySync, including hero content, feature cards, testimonials, newsletter signup UI, and a multi-column footer.

## Preview

Open `index.html` in your browser to view the project locally.

## Tech Stack

- HTML5
- CSS3
- Google Fonts (`Inter`)

## Project Structure

```text
StudySync_Project/
├── index.html
├── style.css
├── README.md
└── images/
```

## Implemented Sections

- Header with logo, navigation links, contact button, and mobile menu button
- Hero section with headline, description, CTA buttons, and hero image
- Trusted companies section with brand logos
- Feature grid (6 cards)
- Testimonials section (3 cards)
- Newsletter signup section
- Footer with social links and 4 link columns

## Responsive Behavior

The layout is responsive using CSS media queries:

- Navigation switches between desktop links and mobile menu button
- Hero section changes from column to row on larger screens
- Feature grid collapses from 2 columns to 1 on smaller devices
- Footer layout adapts from multi-column desktop to stacked layout on smaller screens

## How to Run Locally

### Option 1: Open directly

1. Clone or download this repository.
2. Open `index.html` in any modern browser.

### Option 2: Use VS Code Live Server (recommended)

1. Open the project folder in VS Code.
2. Install the **Live Server** extension (if not installed).
3. Right-click `index.html` and select **Open with Live Server**.

## Customization Guide

### Update branding and content

- Edit text/content in `index.html`
- Replace images in `images/`

### Update colors and theme

Theme variables are defined in `style.css` under `:root`:

- `--primary-color`
- `--accent-color`
- `--text-color`
- `--background-color`
- `--light-gray`
- `--gray`
- `--dark-gray`

### Update typography

- Font import is at the top of `style.css`
- Global font family is set in the `*` selector

## Deployment

Because this is a static project, it can be deployed easily to:

- GitHub Pages
- Netlify
- Vercel (static)
- Any static hosting provider

## Notes

- This project currently focuses on frontend layout and styling.
- Buttons, nav links, and form submission are currently UI-only and can be wired to real functionality later.

## License

This project is currently unlicensed. Add a `LICENSE` file if you plan to distribute it.

