# Task 7 - Laundry Services Page

## What This Is
Made a responsive landing page for a laundry service. It has a navbar at top with logo, menu links, and username button. Then there's the main section with a heading, some text, a button, and an image on the side.

The main thing I learned here was making it work on different screen sizes - desktop, tablet, and phone.

## How to Run
1. Just open `index.html` in a browser 
2. Make sure the images folder is in the parent directory or the image won't show
3. To check responsive: 
   - Resize browser window smaller and bigger
   - Or right-click > Inspect > toggle device toolbar
   - Check it at different widths

## What I Learned

**CSS Variables** - Put them in `:root` and then used `var(--blue)` everywhere. Naming them was confusing at first, I kept them simple like --blue, --dark, --gray.

**Flexbox** - Used this for navbar to put logo, menu, username in a row. Also used for hero section to put text and image side by side. The `flex: 1` thing took me a while to understand - it basically means take equal space.

**Media Queries** - This was the hardest part. I used 992px for tablet and 450px for mobile.
- Why 992px? Honestly just saw it in google and it seemed to work well for tablets
- Why 450px? Tested on Chrome Toggle device (which is around 390px wide) and 450px seemed like a good cutoff

**Confusing Parts:**
- `flex-direction: column` - didn't realize I needed this to stack things vertically on mobile. First time I forgot it and everything was still side by side which looked bad
- The min() function - still not 100% clear on this but I think it picks the smaller value? Used it for width stuff
- `justify-content: space-between` vs `justify-content: center` - had to google this.

**Things I'd Improve:**
- The menu disappears completely on mobile which isn't great, maybe should add a hamburger menu button
- Padding/spacing could probably be better, I just adjusted until it looked okay
- Not sure if my breakpoints are the correct ones

## Files
- index.html - the HTML structure
- style.css - all the CSS
