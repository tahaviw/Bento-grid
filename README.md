# Frontend Mentor - Bento Grid

Bento Grid is a fully responsive landing page challenge from Frontend Mentor built with semantic HTML5 and modern CSS techniques. The project showcases a visually structured "bento-style" layout optimized for both desktop and mobile devices using CSS Grid, Flexbox, responsive media queries, and reusable design systems.

This project focuses on responsive front-end architecture, layout composition, typography management, and adaptive UI behavior while maintaining clean and scalable code organization.

---

## Features

- Fully responsive Bento Grid layout
- Mobile-first responsive design approach
- Advanced CSS Grid implementation
- Dynamic layout restructuring between mobile and desktop views
- Reusable design tokens using CSS variables
- Responsive typography and spacing system
- Optimized asset management
- Semantic and accessible HTML structure
- Custom font integration
- Adaptive image scaling and overflow handling

---

## Built With

- HTML5
- CSS3
- CSS Grid
- Flexbox
- JavaScript ES6

---

## Project Structure

```bash
Frontend-Mentor-Bento-Grid/
│
├── index.html
├── style.css
├── README.md
├── preview.jpg
├── style-guide.md
│
├── assets/
│   ├── fonts/
│   └── images/
│
└── design/
    ├── desktop-design.jpg
    └── mobile-design.jpg
```

---

## Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/your-username/frontend-mentor-bento-grid.git
```

### Navigate to the Project Directory

```bash
cd frontend-mentor-bento-grid
```

### Launch the Project

Option 1 — Open the HTML file directly in your browser:

```bash
open index.html
```

Option 2 — Run using VS Code Live Server:

```bash
Right Click on index.html -> Open with Live Server
```

Option 3 — You can view the live demo of the project here:

```bash
https://tahaviw.github.io/Bento-grid/
```

---

## Usage

1. Open the application in your browser.
2. View the responsive Bento Grid layout.
3. Resize the browser window to observe adaptive desktop and mobile layouts.
4. Explore the content sections showcasing:
   - Social media analytics
   - AI-powered content creation
   - Audience growth metrics
   - Scheduling and platform management
5. Analyze the responsive grid behavior and layout transitions across breakpoints.

---

## Application Logic

### Responsive Grid Architecture

The application uses CSS Grid as the primary layout system for desktop displays:

```css
.container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(6, 1fr);
}
```

This enables precise positioning and scaling of Bento Grid sections.

---

### Mobile-First Layout Strategy

The project initially renders using a stacked flex-column mobile layout:

```css
.container {
    display: flex;
    flex-direction: column;
}
```

Desktop layouts are then progressively enhanced using media queries:

```css
@media screen and (min-width: 1024px)
```

This ensures optimal rendering across multiple screen sizes.

---

### Reusable Design System

CSS custom properties are used for centralized color management:

```css
:root {
    --clr-Yellow-DARK : hsl(39, 100%, 71%);
    --clr-Purple-DARK : hsl(256, 67%, 59%);
}
```

Benefits include:

- Easier theme management
- Consistent visual styling
- Improved scalability and maintainability

---

### Dynamic Content Positioning

Individual Bento cards are positioned using explicit grid placement:

```css
.div1 {
    grid-column: span 2 / span 2;
    grid-row: span 2 / span 2;
}
```

This approach allows precise control over:

- Card dimensions
- Grid spanning
- Responsive alignment
- Visual hierarchy

---

### Typography & Asset Management

The project integrates both:

- Google Fonts
- Local custom font files

```css
@font-face {
    font-family: DMSans-Regular;
}
```

Optimized image assets are used throughout the interface to improve responsiveness and visual clarity.

---

## Responsive Design

The interface is optimized for:

- Mobile devices
- Tablets
- Desktop displays
- Large screens

Responsive improvements include:

- Dynamic grid restructuring
- Adaptive typography scaling
- Overflow handling
- Responsive image resizing
- Layout repositioning based on viewport width

---

## Future Improvements

- Add dark mode support
- Improve accessibility with ARIA labels
- Add subtle UI animations and transitions
- Optimize asset loading performance
- Implement CSS container queries
- Add Lighthouse performance optimizations
- Convert layout into reusable React components

---

## Challenge Source

This project was built as part of the Frontend Mentor coding challenges platform:

- Responsive UI replication challenge
- CSS Grid and layout practice
- Real-world front-end design implementation

---

## Author

Taha Belghiti — Junior Front-End Developer  
Built with HTML, CSS· © 2026
