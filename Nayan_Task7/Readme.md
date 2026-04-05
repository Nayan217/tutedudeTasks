# Task 7 - Laundry Services Responsive

## Project Description
This is a responsive landing page for a laundry service company. The website has a navigation bar with links and a user button, and a hero section showing the main heading, description text, a call-to-action button, and an image. The page looks good on desktop computers, tablets, and mobile phones.

I made this page work on different screen sizes using media queries. On tablets, everything gets smaller. On phones, the navigation links hide and the content stacks vertically instead of side-by-side.

## Files
- `index.html` - The main HTML structure
- `style.css` - All the styling and responsive design code
- `Readme.md` - This file

## How to Run
1. Make sure the `images` folder is in the parent directory (one level up)
2. Open the `index.html` file in any web browser (Chrome, Firefox, Edge, etc.)
3. To test responsiveness:
   - Resize your browser window to see how it adapts
   - Or press F12 and click the device toolbar icon to simulate different devices
   - Try desktop (1200px+), tablet (640px-992px), and mobile (below 640px) views

## Concepts Demonstrated

### HTML Concepts:
- Semantic HTML tags (`<header>`, `<nav>`, `<main>`)
- Image with alt text for accessibility

### CSS Concepts:
- **CSS Variables** - Used `:root` to store colors and reuse them
- **Flexbox** - Used for navbar and hero section layouts
- **Media Queries** - `@media (max-width: ...)` for responsive design
- **Pseudo-classes** - `:hover` for interactive effects
- **Box Model** - Padding, margin, and box-sizing
- **Min/Max functions** - `min()` function to control widths
- **CSS Reset** - Universal selector `*` to reset default styles
- **Transitions** - Smooth color changes on hover

### Responsive Design:
- Desktop: Full 3-column navbar, large text and image
- Tablet (max-width: 992px): Smaller fonts, reduced spacing
- Mobile (max-width: 640px): Hidden nav links, vertical stacking with `flex-direction: column`

## What I Learned
- How to make websites work on phones and tablets
- Using flexbox to arrange items in rows and columns
- Media queries help change styles for different screen sizes
- CSS variables make it easy to change colors throughout the site
