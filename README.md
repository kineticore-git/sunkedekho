# StreetTest Landing Page

A modern, responsive landing page for StreetTest - a service that helps businesses test their ideas on the streets to get real feedback.

## Features

- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scrolling, hover effects, and animated statistics
- **QR Code Integration**: WhatsApp QR code for easy contact
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Accessibility**: Keyboard navigation and focus management

## Files Structure

- `index.html` - Main HTML structure
- `styles.css` - CSS styling and responsive design
- `script.js` - JavaScript for interactivity and QR code generation
- `README.md` - This documentation file

## Customization

### 1. Update WhatsApp Number
In `script.js`, find the `generateQRCode()` function and replace:
```javascript
const whatsappNumber = '1234567890'; // Replace with your actual WhatsApp number
```

### 2. Update Contact Information
In `index.html`, update the contact section:
- Email address in the contact methods
- Any other contact details

### 3. Customize Colors
In `styles.css`, you can change the color scheme by updating:
- Primary color: `#6366f1` (used for buttons, links, etc.)
- Gradient colors in hero section
- Background colors for different sections

### 4. Update Content
- Hero title and subtitle in `index.html`
- About section text
- Feature descriptions
- Footer information

### 5. Add Your Logo
Replace the text logo "StreetTest" in the navigation with your actual logo image.

## How to Use

1. Open `index.html` in a web browser
2. The QR code will automatically generate when the page loads
3. Test the responsive design by resizing your browser window
4. All navigation links work with smooth scrolling

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Dependencies

- Font Awesome (for icons)
- Google Fonts (Inter font family)
- QRCode.js (for QR code generation)

All dependencies are loaded from CDNs, so an internet connection is required.

## Notes

- The QR code generates a WhatsApp link with a pre-filled message
- All animations are CSS-based for better performance
- The design follows modern web standards and best practices
- Mobile-first responsive design approach
