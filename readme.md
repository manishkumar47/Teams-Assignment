# Design Decisions

## `calc()`
The `calc()` function was used to dynamically calculate the available height for the main content area after allocating space for the header. This ensures that the content always fits within the viewport.

**Example:**
- Header height: `100px`
- Main content height: `calc(100vh - 100px)`

---

## Flexbox
Flexbox was used to align the header elements (logo and title) horizontally. It provides a simple and efficient way to center and space items while maintaining responsiveness.

---

## CSS Grid
CSS Grid was used to arrange the team member cards because it is well-suited for two-dimensional layouts. It allows the cards to be displayed in multiple rows and columns while maintaining consistent spacing.

---

## Media Queries
Media queries were implemented to make the webpage responsive across different screen sizes. The layout automatically adjusts for:
- Desktop
- Tablet
- Mobile devices

---

## Accessibility
`aria-label` attributes were added to interactive elements to improve accessibility. These labels help screen readers provide meaningful descriptions, making the webpage easier to navigate for users who rely on assistive technologies.

---

## Performance Optimization
The `loading="lazy"` attribute was applied to team member images so they are loaded only when they are about to enter the viewport. This improves the initial page load time and overall performance.

---

## Responsive Images
The `object-fit: cover` property was used for profile images to ensure they maintain their aspect ratio while filling the circular image container without distortion.

---

## Smooth User Experience
CSS transitions and hover effects were added to team cards and social media icons to provide subtle visual feedback, resulting in a more interactive and modern user experience.