# Caue Casonato - Portfolio Website

A modern, responsive personal portfolio website for Caue Casonato, featuring a clean design with dark/light mode functionality.

## Features

- **Responsive Design**: Mobile-friendly layout using Flexbox/Grid
- **Theme Switching**: Toggle between light and dark mode with preferences saved in localStorage
- **Smooth Transitions**: Animated theme changes and section scrolling
- **Semantic HTML**: Optimized for SEO with appropriate meta tags

## Sections

1. **Home**: Hero section with name, tagline, and profile picture
2. **About**: Bio, certifications, and experience timeline
3. **Contact**: Email form and social links

## Customization

### Profile Image

Replace the placeholder image by adding your own image file at `images/profile.jpg`. The current implementation includes a fallback SVG if the image is not found.

### Colors

The color scheme can be customized by modifying the CSS variables in the `css/styles.css` file:

```css
:root {
    /* Light Mode Colors */
    --bg-color: #ffffff;
    --text-color: #333333;
    --primary-color: #1A365D;
    /* ... other variables ... */
}

.dark-mode {
    /* Dark Mode Colors */
    --bg-color: #1A202C;
    --text-color: #F7FAFC;
    --primary-color: #87CEEB;
    /* ... other variables ... */
}
```

### Content

Update the personal information, experience, and certifications by editing the corresponding sections in the `index.html` file.

## Usage

Simply open the `index.html` file in a web browser to view the portfolio website. No server or build process is required as this is a static website.

## Technologies Used

- HTML5
- CSS3 (with variables and Flexbox/Grid)
- JavaScript (ES6+)
- Font Awesome for icons
- Google Fonts (Inter)

## Browser Support

This website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your own portfolio website.