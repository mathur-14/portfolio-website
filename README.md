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

The contact form uses Formspree for spam protection and email delivery. Follow these steps to set it up:

### 1. Get Your Formspree Form ID

1. Go to [Formspree.io](https://formspree.io/) and sign up
2. Create a new form
3. Copy your form ID (looks like `xrgjqjqj`)

### 2. Configure the Form

1. Copy `config.template.js` to `config.js`
2. Replace `your_actual_form_id_here` with your actual Formspree form ID
3. The `config.js` file is already in `.gitignore` to keep your form ID private

```javascript
// config.js
const config = {
    formspreeFormId: 'your_actual_form_id_here' // Replace with your real form ID
};
```

### 3. Test the Form

1. Start your local server: `python3 -m http.server 8000`
2. Open `http://localhost:8000`
3. Test the contact form - it should work immediately!

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── config.js           # Configuration (private - not in git)
├── config.template.js  # Template for configuration
├── .gitignore          # Git ignore rules
├── README.md           # This file
└── profile-pic.jpeg    # Profile picture
```

## Security

- ✅ Form ID is kept private and not committed to git
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