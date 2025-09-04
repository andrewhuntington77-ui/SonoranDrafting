# Sonoran Drafting and Design LLC Website

A modern, responsive single-page website for Sonoran Drafting and Design LLC, featuring a clean desert-inspired design with warm earth tones and professional layout.

## Features

- 🎨 **Modern Desert Theme**: Beautiful color palette inspired by the Sonoran Desert
- 📱 **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- ⚡ **Fast Loading**: Lightweight and optimized for performance
- 🎯 **Single Page**: All content organized in a clean, scrollable layout
- 📧 **Contact Form**: Interactive contact form with validation
- 🎭 **Smooth Animations**: Subtle animations and transitions
- 🚀 **GitHub Pages Ready**: Automatic deployment with GitHub Actions

## Sections

- **Hero**: Eye-catching introduction with call-to-action
- **Services**: Showcase of drafting and design services
- **About**: Company information and statistics
- **Contact**: Contact information and inquiry form

## Color Palette

The website uses a carefully curated desert-inspired color palette:

- **Desert Sand**: `#E6D7C3` - Light, warm background tones
- **Warm Sand**: `#D4B896` - Secondary background color
- **Sage Green**: `#8B9A8B` - Accent color for text and elements
- **Dusty Rose**: `#C49B91` - Subtle accent color
- **Terracotta**: `#B8673A` - Primary brand color for buttons and highlights
- **Deep Canyon**: `#7A5A3F` - Dark color for headings and important text
- **Cactus Green**: `#4A5D4A` - Text color for secondary content

## Local Development

1. Clone this repository
2. Open `index.html` in your browser or serve with a local web server
3. For live reloading during development, you can use:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## GitHub Pages Deployment

This website is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup Instructions:

1. **Create a new repository** on GitHub for your website
2. **Push this code** to your repository
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "GitHub Actions"
4. **The workflow will automatically deploy** your site when you push to the main branch

### Custom Domain (Optional):

To use a custom domain:

1. Add a `CNAME` file to the root directory with your domain name
2. Configure your domain's DNS to point to GitHub Pages
3. Enable "Enforce HTTPS" in repository settings

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment workflow
└── README.md           # This file
```

## Customization

### Content Updates:
- Edit `index.html` to update text, contact information, and services
- Modify the contact details in the contact section
- Update company information in the about section

### Styling:
- Adjust colors by modifying CSS custom properties in `styles.css`
- Change fonts by updating the Google Fonts import and CSS variables
- Modify layout and spacing as needed

### Functionality:
- The contact form currently shows a success message (no backend integration)
- Add form backend integration by modifying the form submission in `script.js`
- Customize animations and interactions as desired

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+ (with reduced functionality)

## Performance

- Optimized images and assets
- Minimal external dependencies
- CSS and JavaScript are minification-ready
- Uses modern CSS features with fallbacks

## License

This project is created for Sonoran Drafting and Design LLC. All rights reserved.

---

For questions or support, please contact the development team.
