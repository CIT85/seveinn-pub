# header (flexbox)
The header uses flexbox to organize the logo, main title, and navigation links. The layout adjusts based on screen size to keep the header readable and clean.

- logo
- h1 title
- nav
  - h2 title
    - home
    - intro
    - what is chess
    - studies
    - rankings

## mobile < 481px
- header stacks vertically: title → nav → quick links
- nav list becomes a single column for easier tapping
- quick links heading spans the full width
- spacing is tighter to fit small screens

## tablets 481–768px
- header stays stacked, but spacing improves
- nav items begin to wrap when needed
- quick links remain centered under the nav

## small screens laptops 769–1024px
- header switches to a horizontal row layout
- title moves to the left, navigation to the right
- quick links move below the header and expand to full width

## desktops 1025–1200px
- header becomes a wide horizontal layout
- navigation fully horizontal with even spacing
- quick links still full-width but more balanced visually

## extra large 1201px+
- same overall structure as desktop
- larger spacing, more padding, and more comfortable whitespace


# quick links
This section provides fast navigation to important study topics.

- h3
  - openings
  - tactics
  - endgame
  - elo
  - study
  - puzzles

## responsive behavior
- stays full width on all devices
- displays in one horizontal row on desktops
- stacks vertically on mobile for accessibility
- font and icon sizing slightly reduce on mobile screens


# main content grid
These are the primary sections of the homepage and each leads to a page or topic.

- why i created this website
- what is chess
- chess level table

## responsive behavior
- forms a multi-column grid on desktops
- becomes two columns on tablet screens
- stacks into one column for mobile
- maintains consistent even spacing and padding


# random puzzles to solve grid
This layout shows two images (start and end position) with explanations to the side.

- image 1
- text describing the position
- image 2
- text describing the notation

## responsive behavior
- images stack vertically for clarity
- text stays aligned right of the images on large screens
- on mobile, text moves below each image
- images shrink proportionally to remain inside the layout


# footer flexbox
- name
- links (back to top, site links)
- ai image link

## responsive behavior
- aligns horizontally on larger screens
- stacks and centers elements on mobile
- spacing stays consistent across all breakpoints


# accessibility
- semantic heading hierarchy: h1 → h2 → h3 → h4
- aria-label on navigation for screen readers (aria-label="menu navigation")
- alt text for every image, including puzzles and study images
- high contrast color palette for readability
- keyboard-friendly navigation using simple anchor links
- descriptive link text instead of vague “click here” phrasing


# standard i will follow
- mobile < 481px
- tablets 481px – 768px
- small screens / laptops 769px – 1024px
- desktops 1025px – 1200px
- extra large screens 1201px+
