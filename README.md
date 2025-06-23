# Paul Zadra - Portfolio Website

A modern, responsive, bilingual (English/French) portfolio website built with HTML5, CSS3, and vanilla JavaScript.

## Features

- 🌐 Bilingual support (English/French)
- 📱 Responsive design (mobile-first approach)
- ✨ Modern UI with smooth animations
- 🎯 Dynamic content loading
- 🔄 Language switching with content persistence
- 📊 Interactive timeline for experience
- 🎨 Beautiful project cards with hover effects
- 💼 Skills showcase with categorized display
- 🔍 SEO optimized

## Technical Stack

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Font Awesome 6.0.0
- Google Fonts (Poppins)

## Project Structure

```
portfolio/
├── index.html
├── css/
│   └── styles.css
├── js/
│   ├── main.js
│   └── translations.js
└── README.md
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Open the project in your preferred code editor.

3. Serve the files using a local development server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Features Implementation

### Language System
- Uses data attributes for translations
- Smooth transition between languages
- Local storage for language preference
- Browser language detection

### Animations
- Fade-up animations for sections
- Typing animation in hero section
- Hover effects on cards and buttons
- Floating technology icons
- Smooth scroll behavior

### Responsive Design
- Mobile-first approach
- Breakpoints:
  - Desktop: > 768px
  - Tablet: 768px
  - Mobile: 480px

### SEO Optimization
- Semantic HTML structure
- Meta tags
- Proper heading hierarchy
- Alt text for images
- Responsive images

## Development

### CSS Variables
The project uses CSS variables for consistent theming:
```css
--primary-color: #2563eb
--secondary-color: #1e40af
--text-color: #1f2937
--light-text: #6b7280
--background: #ffffff
--section-bg: #f3f4f6
```

### Adding New Content
1. Update the translations in `js/translations.js`
2. Content will be automatically populated through the data attributes system

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Paul Zadra
- Email: paul.zadra2004@gmail.com
- LinkedIn: [Paul Zadra](https://www.linkedin.com/in/paul-zadra-976269289/) 
