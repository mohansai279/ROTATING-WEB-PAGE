# Toggle Layout Header

## Overview
This HTML document creates a webpage with a fixed header, a main content area, and a slide-in menu. The menu can be toggled by clicking a button in the header, causing the main content to rotate and shift to reveal the menu. This layout is useful for creating an interactive and visually appealing user interface.

## Features
- **Fixed Header**: A header that remains fixed at the top of the page.
- **Slide-In Menu**: A hidden menu that slides in from the left when the toggle button is clicked.
- **Rotating Content**: The main content rotates and shifts to make room for the menu.
- **Responsive Design**: The layout adjusts to different screen sizes.

## HTML Structure
- The HTML document uses HTML5 and includes meta tags for character set and viewport settings.
- The title of the page is set to "Toggle Layout Header".

## CSS Styling
- **Global Styles**:
  - The `html` and `body` elements have no margin or padding, and use a flex layout to fill the height of the viewport.
  - The body has a background color of `antiquewhite`.
  
- **Header Styles**:
  - The header is styled with a dark orange background and contains a button for toggling the menu.
  - The header is fixed at the top of the page and stretches across the full width.

- **Main Content Styles**:
  - The main content area has a white background, shadow effect, and padding.
  - It is positioned relative to the container and has a transition effect for smooth rotation and translation.

- **Menu Styles**:
  - The menu is initially hidden off-screen to the left and slides in when activated.
  - It has a white background, shadow effect, and rounded corners.
  - Menu links are styled to scale up and change color when hovered.

## JavaScript Functionality
- **Toggle Menu**: The JavaScript code listens for clicks on the toggle button. When clicked, it toggles the menu's visibility and applies a rotation and translation to the main content.
  - If the menu is active, it slides in from the left, and the main content tilts and shifts to the right.
  - If the menu is inactive, it slides back out, and the main content returns to its normal position.

## Sample Content
- The main content includes a section about Bhagat Singh, with headings, paragraphs, and images.
- The menu contains links for "Home", "About Us", "Contact Us", and "Website".

## Usage
To view the toggle layout in action, open the `highlight.html` file in a web browser. Click the menu icon in the header to toggle the visibility of the side menu and see the main content rotate and shift accordingly.
