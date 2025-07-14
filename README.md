# Yash Mathur - Portfolio Website

A modern, responsive portfolio website showcasing my skills, experience, and projects.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-friendly interface
- ⚡ Fast loading and smooth animations
- 📧 Contact form with spam protection
- 🎯 Interactive timeline for experience
- 🌟 Animated background with tech keywords

## Contact Form Setup

The contact form uses Formspree for spam protection and email delivery. The form ID is already configured in the HTML file.

### Current Setup

The form is configured to use Formspree form ID: `mldlrwqy`

### To Change the Form ID

If you want to use a different Formspree form:

1. Go to [Formspree.io](https://formspree.io/) and create a new form
2. Copy your form ID
3. Update the `action` attribute in the form tag in `index.html`:

```html
<form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_NEW_FORM_ID" method="POST">
```

### Test the Form

1. Start your local server: `python3 -m http.server 8000`
2. Open `http://localhost:8000`
3. Test the contact form - it should work immediately!

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── .gitignore          # Git ignore rules
├── README.md           # This file
└── profile-pic.jpeg    # Profile picture
```

## Security

- ✅ Formspree form IDs are safe to expose in public code
- ✅ Spam protection via Formspree
- ✅ Honeypot fields to catch bots
- ✅ Rate limiting and validation

## Deployment

You can deploy this portfolio to any static hosting service:

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Push to a GitHub repository
- **AWS S3**: Upload files to S3 bucket

## Customization

- Update personal information in `index.html`
- Modify colors and styles in `styles.css`
- Add new sections or features in `script.js`
- Replace `profile-pic.jpeg` with your own photo

## License

This project is open source and available under the [MIT License](LICENSE). 