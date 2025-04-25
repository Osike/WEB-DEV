# Web Dev Assignment Portfolio Website

A modern, responsive portfolio website showcasing professional services, skills, and achievements with interactive elements.

## Features

- Responsive navigation with dropdown menu
- Dynamic statistics counter on scroll
- Services section with professional layout
- Interactive portfolio gallery
- Contact form
- Social media integration

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Font Awesome Icons
- Intersection Observer API

## Key Components

### Dynamic Counter Implementation
The statistics section uses Intersection Observer to trigger counting animations when the user scrolls to that section. This creates an engaging user experience without impacting performance.

```javascript
// Example of counter implementation
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            startCounting();
        }
    });
});
```

### Responsive Design
The website is built with a mobile-first approach, ensuring optimal display across all device sizes using CSS Flexbox and Grid layouts.

## Setup

1. Clone the repository
2. Open `index.html` in your browser
3. For development, use a live server extension in VS Code

## Project Structure

```
portfolio-website/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Contributors
1. Naomi	Chepkorir
2. Shadrack Osike 
3. Wayne Chibeu

