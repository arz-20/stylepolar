# Style Polar - Flooring Website

A modern, responsive website for Style Polar flooring company specializing in carpet and vinyl installation services.

## Features

### 🎨 Design
- Modern, professional design with gradient accents
- Fully responsive layout for all devices
- Smooth animations and transitions
- Interactive gallery with lightbox functionality
- Mobile-first approach

### 🔧 Services Highlighted
- **Carpet Installation**: Residential & Commercial, all carpet types
- **Vinyl Installation**: Luxury vinyl plank, vinyl tile, sheet vinyl, waterproof options

### 📱 Functionality
- Responsive navigation with mobile hamburger menu
- Smooth scrolling navigation
- Contact form with validation
- Image gallery with lightbox viewer
- Animated counters and statistics
- Performance optimized with lazy loading

### 🛠️ Technical Stack
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript ES6+**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family
- **Unsplash Images**: High-quality stock photos

## File Structure

```
style-polar-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # Project documentation
```

## Sections

1. **Header/Navigation** - Fixed header with smooth navigation
2. **Hero Section** - Eye-catching introduction with call-to-action buttons
3. **Services** - Detailed information about carpet and vinyl installation
4. **Why Choose Us** - Key benefits and differentiators
5. **Gallery** - Showcase of completed projects
6. **About** - Company information and statistics
7. **Contact** - Contact form and business information
8. **Footer** - Additional links and social media

## Key Features

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 480px
- Flexible grid layouts
- Touch-friendly navigation

### Performance
- Optimized images from Unsplash CDN
- Lazy loading implementation ready
- Throttled scroll events
- Efficient CSS animations

### User Experience
- Smooth scrolling navigation
- Interactive hover effects
- Form validation and feedback
- Accessible design patterns
- Fast loading times

## Setup Instructions

1. **Download/Clone the files**
   ```bash
   # If using git
   git clone [repository-url]
   
   # Or download the files directly
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - No server setup required for basic functionality

3. **For development**
   - Use a local server for best experience
   - Python: `python -m http.server 8000`
   - Node.js: `npx http-server`
   - VS Code: Use Live Server extension

## Customization

### Colors
The website uses a consistent color scheme that can be easily customized by updating these CSS variables:

```css
/* Main brand colors */
--primary: #667eea;
--secondary: #764ba2;
--dark: #2c3e50;
--light: #f8f9fa;
```

### Content
- Update business information in the contact section
- Replace placeholder phone numbers and email addresses
- Modify service descriptions and features
- Add your own project images in the gallery

### Images
Current images are sourced from Unsplash. To use your own images:
1. Replace the Unsplash URLs with your image paths
2. Ensure images are optimized for web (WebP format recommended)
3. Update alt text for accessibility

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+ (limited support)

## Contact Form Integration

The contact form currently shows a success notification. To make it functional:

1. **Backend Integration Options:**
   - PHP mail function
   - Node.js with Express and Nodemailer
   - Third-party services (Netlify Forms, Formspree, etc.)
   - Email service APIs (SendGrid, Mailgun)

2. **Example PHP Integration:**
   ```php
   <?php
   if ($_POST['name']) {
       $to = "info@stylepolar.com";
       $subject = "Website Contact Form";
       $message = $_POST['message'];
       mail($to, $subject, $message);
   }
   ?>
   ```

## SEO Optimization

The website includes basic SEO elements:
- Semantic HTML structure
- Meta descriptions and titles
- Alt text for images
- Proper heading hierarchy
- Fast loading times

For enhanced SEO, consider adding:
- Schema markup for local business
- Open Graph meta tags
- Google Analytics
- Google Search Console integration

## Performance Tips

1. **Image Optimization**
   - Use WebP format when possible
   - Implement lazy loading for below-fold images
   - Optimize image sizes for different screen sizes

2. **Code Minification**
   - Minify CSS and JavaScript for production
   - Use CSS preprocessing for better organization
   - Consider bundling assets

3. **Caching**
   - Implement browser caching headers
   - Use CDN for static assets
   - Enable gzip compression

## License

This project is created for Style Polar flooring company. Feel free to modify and customize according to your needs.

## Support

For questions or customization requests, please contact the development team.

---

**Style Polar** - Premium Flooring Solutions
Transform your space with professional carpet and vinyl installation services.
