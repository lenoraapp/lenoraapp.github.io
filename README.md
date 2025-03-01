# Lenora AI Dating Coach - Website

This is a static website for the Lenora AI Dating Coach iOS app. The website showcases the app's features with a clean, modern design.

## Files

- `index.html` - The main HTML structure of the website
- `styles.css` - The CSS styling for the website
- `images/` - Directory for app screenshots and icon

## How to Use

1. Simply open the `index.html` file in a web browser to view the website locally.
2. To deploy the website, upload all files to your web hosting service.

## Customization

### Adding Your App Icon

The website includes placeholder sections for your app icon:

1. In the hero section at the top of the page
2. In the footer

Replace the placeholder divs with your actual app icon:

```html
<div class="app-icon">
    <img src="images/app-icon.png" alt="Lenora App Icon">
</div>
```

### Adding Screenshots

The website includes placeholder sections for app screenshots. To add your actual screenshots:

1. Add your screenshot images to the `images` folder
2. Replace the placeholder divs in the HTML with actual images:

```html
<div class="screenshot">
    <img src="images/your-screenshot.png" alt="Description of screenshot">
    <p>Description of what the screenshot shows</p>
</div>
```

### Updating Content

- Update the text content in the HTML file to match your app's specific features and descriptions
- Add links to your actual privacy policy and terms of service pages in the footer
- Update the copyright year in the footer

### Customizing Colors

The website uses your app's accent color (#20958D) as the primary color and iOS system purple (#af52de) as an accent. You can modify these colors in the `styles.css` file:

```css
:root {
    --primary-color: #20958D;
    --primary-dark: #1a7a73;
    --primary-light: #25b0a6;
    --accent-color: #af52de; /* iOS system purple */
    /* other color variables */
}
```

## App Store Link

Don't forget to update the App Store download link in the HTML file once your app is published:

```html
<a href="https://apps.apple.com/app/your-app-id" class="download-btn">Download on the App Store</a>
```

## Contact Information

Update the social media links in the footer section with your actual social media profiles. # lenoraapp.github.io
