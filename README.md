# SkyView Drone Services Website

A modern, responsive website for a drone services business specializing in aerial photography, videography, mapping, and inspections.

## Features

- Modern, responsive design optimized for all device sizes
- Fully accessible with ARIA attributes and semantic HTML
- GDPR-compliant with cookie consent banner and privacy policy
- SEO-optimized with appropriate meta tags, sitemap, and robots.txt
- High-performance with minimal dependencies
- Clean, well-structured code following best practices

## File Structure

```
├── index.html                # Homepage
├── services.html             # Services page (placeholder)
├── portfolio.html            # Portfolio page (placeholder)
├── about.html                # About page (placeholder)
├── contact.html              # Contact page with form
├── privacy.html              # Privacy policy
├── terms.html                # Terms of service (placeholder)
├── robots.txt                # Instructions for search engine crawlers
├── sitemap.xml               # Site structure for search engines
├── css/
│   ├── normalize.css         # CSS reset/normalize
│   ├── styles.css            # Main stylesheet
│   └── contact.css           # Contact page specific styles
├── js/
│   └── main.js               # Main JavaScript file
└── images/                   # Image directory (placeholder)
    └── Various images
```

## Technology Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox for layouts)
- JavaScript (vanilla, no frameworks)
- Font Awesome for icons
- Google Fonts for typography

## SEO Features

- Semantic HTML structure
- Meta tags for better indexing
- Open Graph meta tags for social sharing
- Structured data for search engines
- XML sitemap and robots.txt
- Optimized image alt texts
- Mobile-friendly design (Google ranking factor)

## Accessibility Features

- ARIA attributes where appropriate
- Semantic HTML5 elements
- Keyboard navigation support
- Color contrast compliance
- Alt text for all images
- Focus states for interactive elements
- Screen reader compatibility

## GDPR Compliance

- Cookie consent banner
- Privacy policy
- Data collection transparency
- Form consent checkbox
- Option to decline non-essential cookies
- Documentation of data processing activities

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11 (basic support)

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser to view the site locally
3. Edit content as needed (placeholder text and images should be replaced)
4. Upload to your web hosting provider

## Customization

### Changing Colors

The color scheme can be easily modified by changing the CSS variables in the `:root` selector in `css/styles.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --light-color: #ecf0f1;
    --dark-color: #2c3e50;
    /* ...other variables... */
}
```

### Adding New Pages

1. Copy the structure of an existing page (like `about.html`)
2. Update the meta tags, title, and content
3. Add the page to the navigation menu in all HTML files
4. Add the page to `sitemap.xml`

## License

This project is available for personal and commercial use.

## Credits

- Google Fonts for typography
- Font Awesome for icons
- Normalize.css

## Contact

For any questions or support, please contact:
info@skyviewdrones.com 