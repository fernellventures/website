# Fernell Ventures Ltd - Website

Official website for Fernell Ventures Ltd, showcasing our innovative web solutions for the education sector.

## About

Fernell Ventures Ltd is a web app development company focused on creating innovative solutions for simple problems in the education sector. We provide tools to support school teams at all levels—from entry-level staff to middle management and leadership.

## Products

### 1. Your School Hub
Transforms school risk assessments from paper chaos into streamlined digital workflows. Designed for headteachers, safeguarding leads, and MAT leadership teams with automated review tracking and compliance reporting.

### 2. Indie Schools
The UK's digital marketplace connecting families with independent schools. Parents discover and compare schools, while schools receive qualified enquiries and streamline their admissions pipeline.

### 3. Hunter
A Hide and Seek game supported by tech. An innovative approach to physical activity and outdoor learning combining traditional playground games with modern technology.

### 4. Learning Walk
A multiplatform web app allowing School Leaders and Middle Management to carry out and log Learning Walks in one place. Also works as a tool for site walks and report generation.

### 5. ECT Journey
Helps schools manage the two-year teacher induction process with ease. ECTs capture evidence on-the-go, mentors save hours on admin, and induction tutors get one-click Appropriate Body reporting.

## Website Structure

```
/
├── index.html       # Main HTML file
├── styles.css       # CSS styling
├── script.js        # JavaScript for interactions
└── README.md        # This file
```

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Product Showcase**: Detailed cards for each product
- **Contact Form**: Easy way for potential clients to get in touch
- **Smooth Navigation**: Fixed navbar with smooth scrolling
- **Accessibility**: Keyboard navigation and ARIA labels

## Technology Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## Local Development

To run this website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/fernellventures/website.git
   cd website
   ```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using Node.js (http-server)
     npx http-server
     ```

3. Visit `http://localhost:8000` in your browser

## Customization

### Updating Product Information

Edit the product cards in `index.html` within the `<section id="products">` section. Each product card has:
- Product icon (emoji or can be replaced with image)
- Product name
- Description
- Feature list
- Link to learn more

### Changing Colors

Update CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;   /* Secondary brand color */
    --accent-color: #3b82f6;      /* Accent color */
    /* ... other colors */
}
```

### Contact Form Integration

The contact form currently logs to console. To connect it to a backend:

1. Uncomment the fetch code in `script.js`
2. Update the API endpoint
3. Set up your backend to handle form submissions

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select branch (usually `main`) and root directory
4. Save and wait for deployment

### Netlify

1. Connect your GitHub repository to Netlify
2. Build settings: None needed (static site)
3. Deploy

### Vercel

1. Import project from GitHub
2. No build configuration needed
3. Deploy

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

This is a private company website. For internal updates:

1. Create a feature branch
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## License

Copyright © 2026 Fernell Ventures Ltd. All rights reserved.

## Contact

- **Email**: info@fernellventures.com
- **GitHub**: https://github.com/fernellventures

---

Built with ❤️ by Fernell Ventures Ltd
