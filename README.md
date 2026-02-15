# Arinze Johnpaul - Data Analyst Portfolio

A modern, professional portfolio website showcasing data analytics projects and experience with a dark blue and black theme.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern Aesthetics**: Dark blue and black theme with smooth animations
- **Interactive Navigation**: Smooth scrolling and active section highlighting
- **Project Showcase**: Detailed presentation of major data analytics projects
- **Professional Timeline**: Visual representation of career experience
- **Contact Form**: Easy-to-use contact form with email integration
- **Performance Optimized**: Fast loading with optimized animations

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Outfit & JetBrains Mono)

## File Structure

```
portfolio-site/
│
├── index.html          # Main HTML file with all content
├── styles.css          # Complete styling with dark blue/black theme
├── script.js           # Interactive features and animations
└── README.md           # This file
```

## Setup Instructions

1. **Download the Files**
   - Download all files in the portfolio-site folder
   - Keep all files in the same directory

2. **Open in Browser**
   - Simply double-click `index.html` to open in your default browser
   - Or right-click and select "Open with" to choose a specific browser

3. **Customize Content** (Optional)
   - Edit `index.html` to update personal information
   - Modify colors in `styles.css` by changing CSS variables in the `:root` section
   - Add or remove projects as needed

## Color Scheme

The portfolio uses a sophisticated dark blue and black color palette:

- **Primary Blue**: #0A4D8C
- **Accent Cyan**: #00D9FF
- **Background Black**: #000000
- **Secondary Background**: #0A0F1C

You can easily customize these colors by editing the CSS variables in `styles.css`.

## Sections

1. **Hero Section**: Eye-catching introduction with animated text and statistics
2. **About**: Comprehensive overview of skills and expertise
3. **Experience**: Timeline of professional experience
4. **Projects**: Detailed showcase of major data analytics projects:
   - Workers Aggregated Credit Scheme (WACS)
   - Import Duty Exemption Certificate (IDEC)
   - Police Specialized Service Automation Platform (POSSAP)
   - National Social Investment Management System (NASIMS)
5. **Contact**: Contact information and form

## Key Features

### Navigation
- Fixed navbar with smooth scrolling
- Active section highlighting
- Mobile-responsive hamburger menu

### Hero Section
- Large circular portrait on the left side
- Animated typing effect for job titles
- Glowing border effects
- Statistics counters

### Project Showcase
- **Circular project icons** - Each project has a customizable 80px circular image
- Hover effects with scaling animations
- Detailed project information cards

### Animations
- Fade-in effects on scroll
- Typing animation for hero title
- Hover effects on cards and buttons
- Smooth transitions throughout

### Interactivity
- Animated statistics counters
- Project card hover effects
- Contact form with email integration
- Parallax background effects

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Customization Tips

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --color-primary: #0A4D8C;
    --color-accent: #00D9FF;
    /* Add your colors here */
}
```

### Add Projects
Add a new project card in `index.html` within the `.projects-grid` div:
```html
<div class="project-card">
    <!-- Your project content -->
</div>
```

### Modify Typing Animation
Edit the words array in `script.js`:
```javascript
const words = ['Data Analyst', 'Your Title', 'Another Title'];
```

## Performance Tips

- All assets load from CDN (Google Fonts)
- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- No external dependencies beyond fonts

## Contact Form

The contact form opens the user's default email client with pre-filled information. To use a different email service:

1. Modify the form handler in `script.js`
2. Integrate with a backend service (e.g., Formspree, EmailJS)
3. Or connect to your own server-side handler

## Future Enhancements

Potential additions you might consider:

- Blog section for data analytics insights
- Downloadable resume/CV
- Dark/light mode toggle
- Additional project case studies
- Testimonials section
- Skills proficiency charts

## Support

For any questions or issues, please contact:
- Email: arinzedata101@gmail.com
- Phone: +234 814 348 5343

## License

This portfolio template is created for Odoh Arinze Johnpaul. Feel free to use as a reference for your own portfolio.

---

**Designed and Developed**: February 2026
**Version**: 1.0.0
