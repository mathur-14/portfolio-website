# Yash Mathur - Personal Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases professional experience, projects, skills, and provides a contact form for potential opportunities.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Mobile-friendly navigation menu
  - Smooth scrolling between sections
  - Contact form with validation
  - Animated elements on scroll
  - Typing effect on hero section
- **Sections Included**:
  - Hero section with introduction
  - About section with personal information
  - Experience timeline
  - Featured projects showcase
  - Skills and technologies
  - Contact form and information

## Files Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── Yash-Mathur-resume.pdf  # Your resume (for reference)
```

## How to Run

### Method 1: Direct Browser Opening (Simplest)
1. Navigate to the portfolio folder in your file explorer
2. Double-click on `index.html` to open it in your default web browser
3. The portfolio will load and be fully functional

### Method 2: Using a Local Server (Recommended)
For the best experience, especially if you plan to add more features:

#### Using Python (if you have Python installed):
```bash
# Navigate to the portfolio directory
cd /path/to/your/portfolio

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then open your browser and go to: `http://localhost:8000`

#### Using Node.js (if you have Node.js installed):
```bash
# Install a simple HTTP server globally
npm install -g http-server

# Navigate to the portfolio directory
cd /path/to/your/portfolio

# Start the server
http-server
```
Then open your browser and go to: `http://localhost:8080`

#### Using Live Server (VS Code Extension):
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. The portfolio will open in your default browser

## Customization Guide

### Personal Information
Edit the following sections in `index.html`:

1. **Hero Section** (lines 47-65):
   - Update your name, title, and description
   - Modify social media links

2. **About Section** (lines 75-105):
   - Update personal description
   - Modify statistics (years of experience, projects, etc.)

3. **Experience Section** (lines 115-145):
   - Replace with your actual work experience
   - Update company names, dates, and responsibilities

4. **Projects Section** (lines 155-215):
   - Add your actual projects
   - Update project descriptions, technologies used
   - Add real links to GitHub repositories and live demos

5. **Skills Section** (lines 225-285):
   - Update skills based on your expertise
   - Add or remove skill categories as needed

6. **Contact Section** (lines 295-325):
   - Update contact information
   - Modify email address and social links

### Styling Customization
Edit `styles.css` to customize:

- **Colors**: Update the color scheme by changing CSS variables
- **Fonts**: Modify font families and sizes
- **Layout**: Adjust spacing, padding, and margins
- **Animations**: Customize transition effects and timing

### Functionality Customization
Edit `script.js` to modify:

- **Contact Form**: Add backend integration for form submission
- **Animations**: Customize scroll animations and effects
- **Navigation**: Modify mobile menu behavior
- **Validation**: Update form validation rules

## Browser Compatibility

This portfolio is compatible with:
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Responsive images and icons
- Smooth animations with hardware acceleration
- Mobile-first responsive design

## Deployment Options

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your portfolio will be available at `https://yourusername.github.io/repositoryname`

### Netlify (Free)
1. Sign up for Netlify
2. Drag and drop your portfolio folder
3. Get a custom URL instantly
4. Option to add custom domain

### Vercel (Free)
1. Sign up for Vercel
2. Connect your GitHub repository
3. Deploy automatically on every push
4. Get custom domain and SSL

## Contact Form Setup

The current contact form shows a success message but doesn't actually send emails. To make it functional, you can:

1. **Use a form service** like Formspree, Netlify Forms, or Getform
2. **Add backend integration** with Node.js, Python, or PHP
3. **Use email services** like SendGrid or AWS SES

Example with Formspree:
```html
<form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
```

## SEO Optimization

To improve search engine visibility:

1. Add meta tags in the `<head>` section
2. Include Open Graph tags for social media sharing
3. Add structured data markup
4. Optimize image alt texts
5. Create a sitemap.xml

## Analytics

Consider adding Google Analytics or other tracking tools:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## Support

If you encounter any issues or need help customizing the portfolio:

1. Check browser console for JavaScript errors
2. Ensure all files are in the same directory
3. Verify file paths in HTML are correct
4. Test on different browsers and devices

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Happy coding! 🚀** 