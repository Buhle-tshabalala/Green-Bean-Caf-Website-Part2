# Green Bean Café Website

A responsive café website for Green Bean Café, built using semantic HTML5 and a custom external stylesheet.

## Marker summary: what changed

This README clearly records the main changes made after the initial submission and explains how the website improved from Part 1 to Part 2. It is organised so a marker can quickly see:

- what was fixed in Part 1,
- what was improved for accessibility and structure,
- how the site was developed further in Part 2.

## Part 1: improvements made to fix the original issues

The first stage focused on correcting the structural and semantic problems raised in the marking feedback.

- Added proper HTML5 structure with `header`, `nav`, `main`, `section`, `article`, and `footer` across the site.
- Standardised navigation across all pages so each page uses the same top-level navigation layout.
- Added `meta charset="UTF-8"` and `meta name="viewport"` to all pages.
- Kept all pages linked to one shared stylesheet: `Style.css`.
- Corrected image paths and improved alt text for meaningful images.
- Improved heading hierarchy so each page has one clear `h1` and logical subheadings.
- Updated forms to use proper `label` elements with matching `for` and `id` attributes and clear `name` values.
- Removed unnecessary inline styling and moved the design into the external CSS file.
- Fixed the event call-to-action structure so links and buttons follow valid HTML nesting.
- Organised menu content into logical sections and article blocks for better structure and layout support.
- Improved indentation and readability to make the code easier to maintain.
- Reduced unnecessary comments and kept code clean and professional.

## Part 2: how the website was developed further

Part 2 focused on improving the design, usability, responsiveness, and overall presentation of the site.

### 1. Design and branding
- Created a consistent café style using warm browns, sage green, cream, and charcoal tones.
- Added shared colour, spacing, and shadow variables for a more polished visual system.
- Improved typography settings and spacing for a more professional, welcoming café brand.

### 2. Layout and navigation updates
- Applied consistent page shells and content containers across all pages.
- Improved the overall layout with hero sections, cards, and structured content blocks.
- Refined page navigation so the site feels more coherent and easier to move through.

### 3. Content and form improvements
- Improved the home page hero, feature sections, and promotional content.
- Refactored booking and contact form layouts for better readability and usability.
- Added consistent button and link styling with smoother hover and focus states.
- Kept content organised and easier to scan on each page.

### 4. Responsive design
- Added responsive layouts for desktop, tablet, and mobile devices.
- Improved spacing, stacking, and page flow at smaller screen sizes.
- Ensured menu content and form elements remain readable and usable on mobile screens.

### 5. Accessibility and final polish
- Added clear focus styles for links and buttons.
- Improved semantic landmark usage and accessibility consistency.
- Refined visual spacing and section separation across the site.
- Ensured the pages feel cleaner, more consistent, and more presentation-ready.

## Git status note

This workspace does not currently have Git installed in the execution environment, so local Git commit and push steps could not be completed here.

If Git is available on the developer machine, the recommended workflow is:

1. git init
2. git add .
3. git commit -m "Initial semantic HTML cleanup"
4. git commit -m "Improve café layout and responsive styling"
5. git commit -m "Finalise accessibility and content structure"
6. git remote add origin <repository-url>
7. git push -u origin main

## Website testing notes

The website was reviewed for semantic consistency, layout structure, and responsive design.

Recommended browser checks:

- Desktop width
- Tablet width
- Mobile width

Check that:

- navigation remains usable on every page,
- forms remain readable and properly spaced,
- images scale correctly without breaking the layout,
- headings and sections remain logical and clean,
- buttons and links maintain accessible hover and focus states.
