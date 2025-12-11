# Chess
- I chose this topic because I wanted to choose what I love but also trying a subject I haven't already worked on. For my web development class I did a sports page, over the summer when I practiced some more I had did a music page. I want to try and expand my knowledge while also challenging myself to do something new. I also want to try and make a website for chess to keep a record of my own personal favorite tactics, checkmates, and moments to help prepare for my upcoming tournament. 

## AI Prompts
- can you create an image of a chess game being played by two guys inside a room with a crowd watching

# Main menu
- What is Chess?
    - Rules
    - History
    - Benefits of chess
- Openings
    - My favorite Openings
    - Recommended
    - Beginner Tactics
- MiddleGame
    - Positional play
    - tactics
- Endgame
    - Checkmates
    - Puzzles
    - Winning or Losing?
- Personal games
* Just Ideas For Now

## Decorative or Positional Enhancement
**Fixed Back-to-Top Button**  
   - Implemented using `position: fixed; bottom: 2rem; right: 2rem;`  
   - Remains visible at all times in the viewport, allowing users to quickly scroll back to the top.  
   - Styled as a circular button with background color, border, and padding to make it prominent and clickable.

**Absolute Positioned Quote Block**  
   - Implemented using `position: absolute; top: 50%; left: 10%;`  
   - Placed over part of the page content for visual interest and emphasis.  
   - Styled with background color, border, padding, rounded corners, and italic font to differentiate it from other content.

## Phase 3 Overview
In this phase, I used **CSS Flexbox** and **CSS Grid** to improve the layout of my website. Flexbox is used in the navigation bar and foooter to align items evenly and help make it easier for future changes. CSS Grid is used for the clickable image sections to create organized rows and columns, making the layout more structured and responsive.

## New Subpage
I created a **Puzzles subpage** that focuses on chess learning from puzzles. This page displays chess puzzle images and challenges that encourage users to think strategically and practice their problem-solving skills. The purpose of this page is to give users a fun and engaging way to improve their chess knowledge through visual examples and practice scenarios. Puzzles are a great way to memorize known concepts, for critical thinking, and for learning new moves.

## Image Optimization
I optimized images by resizing them for web use, adding `alt` text for accessibility, and using the `loading="eager"` attribute on the images in the nav menu. I also used consistent image dimensions and compression to improve performance and reduce page load times. Although most images were already formatted as such.

## To Do List
- finish footer
- new images for puzzles and style
- fixing spacing between some of the sections
- change the image figcaptions
- update sites page

## Accessibility
- semantic heading hierarchy (h1 → h2 → h3 → h4) so screen readers understand structure
- ARIA label on navigation: aria-label="Menu Navigation"
- alt text for every image (especially puzzle images and study images)
- high-contrast color palette
- keyboard-friendly navigation using standard <a> elements
- descriptive link text (no “click here”)
