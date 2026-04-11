# Task 8 - Laundry Services Hamburger Menu

## Project Description
This is a responsive landing page for a laundry service website that features a cool hamburger menu on mobile devices! The page has a navigation bar with links, a username badge, and a hero section with text and an image. What makes it special is the mobile menu that appears when you click the hamburger icon - and it works using only CSS, no JavaScript needed!

The page adapts to different screen sizes:
- On desktop: Regular navigation menu with all links visible
- On tablet: Slightly smaller text and spacing
- On mobile: Hamburger menu that slides in from the right side

## How to Run
1. Download or clone the `Nayan_Task8` folder
2. Make sure all files are in the same folder:
   - `index.html`
   - `style.css`
   - The `images` folder should be in the parent directory
3. Double-click `index.html` to open it in your web browser
4. To test the hamburger menu:
   - Resize your browser window to be narrow (less than 455px wide)
   - Or open Developer Tools (F12) and use responsive design mode
   - Click the hamburger icon (three lines) to see the menu slide in!

## Concepts Demonstrated

### HTML Concepts:
- Semantic HTML tags (`<header>`, `<nav>`, `<main>`)
- Using the `<span>` tag for styling specific text

### CSS Concepts:
- **CSS Variables** - Defined colors once and used them everywhere
- **Flexbox** - Used to layout navbar and hero section
- **Media Queries** - Different styles for tablet (992px) and mobile (455px)
- **Position Absolute** - Used to place the mobile menu panel
- **Pseudo-classes** - `:hover`, `:focus`, `:focus-within` for interactions
- **CSS-only Menu Toggle** - No JavaScript! Used `:focus-within` trick to show/hide menu
- **transform and transition** - Scalling and rotating with ease

### Responsive Design:
- Desktop view (992px and above)
- Tablet view (641px to 992px)
- Mobile view (455px and below)

