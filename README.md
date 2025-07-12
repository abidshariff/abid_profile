# Abid Shaik - Professional Resume Website

This is a professional resume website for Abid Shaik, Senior Data Engineer.

## Features

- Responsive design that works on mobile, tablet, and desktop devices
- Modern, clean layout with professional styling
- Interactive navigation menu
- Animated section transitions
- Comprehensive display of professional experience, skills, education, and certifications

## How to Use

1. Simply open the `index.html` file in any modern web browser to view the website.
2. To make changes to your information:
   - Edit the `index.html` file to update content
   - Modify the `styles.css` file to change the appearance
   - Adjust the `script.js` file to alter the interactive behavior

## Customization Options

### Adding a Profile Picture

To replace the profile icon with an actual photo:

1. Add your profile image to the website folder
2. In `index.html`, replace the placeholder div with an image tag:

```html
<div class="profile-image">
    <img src="your-photo.jpg" alt="Abid Shaik">
</div>
```

3. In `styles.css`, add styling for the image:

```css
.profile-image img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
}
```

### Changing Colors

The website uses CSS variables for colors. To change the color scheme, edit the following variables in `styles.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --text-color: #333;
    --light-bg: #f9f9f9;
    --dark-bg: #2c3e50;
}
```

### Adding More Sections

To add a new section:

1. Add the HTML for the new section in `index.html`
2. Add a link to the navigation menu
3. Style the new section in `styles.css`

## Deployment

To deploy this website online:

1. Upload all files to a web hosting service
2. Ensure the file structure remains intact
3. The website should work immediately without any additional configuration

## Browser Compatibility

This website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge
