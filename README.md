# Web Technologies Laboratory - Assignment 2

**Student Name:** Tunahan Mutlu  
**Student ID:** 230408002

## 1. File Organization

The project consists of a single HTML file styled by two separate CSS files to create completely distinct visual layouts without changing the markup structure:

- `index.html`: The base HTML structure containing the six box elements (`A` through `F`).
- `styleA.css`: Version A stylesheet utilizing CSS Flexbox to vertically align, space, and center all six box elements.
- `styleB.css`: Version B stylesheet implementing horizontal alignment with non-wrapping boxes and a fixed bottom-right element.
- `README.md`: Documentation explaining the file structure and implementation challenges.

## 2. Challenges Faced & Solutions

- **Flexbox Spacing in Style A:** Ensuring boxes were equally spaced vertically across the full browser height without resizing required using `display: flex`, `flex-direction: column`, `justify-content: space-evenly`, and setting `flex-shrink: 0` on the child elements.
- **Preventing Text/Box Wrapping in Style B:** To prevent boxes A through E from wrapping when the window is resized, `white-space: nowrap` was applied to the parent container alongside `display: inline-block` for individual boxes.
- **Fixed Positioning of Box F in Style B:** Positioning Box F in the bottom-right corner while keeping it independent of the top layout was solved using `position: fixed; bottom: 10px; right: 10px;`.
