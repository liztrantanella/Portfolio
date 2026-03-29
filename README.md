# Portfolio Website

A modern, beautiful portfolio website built with vanilla HTML, CSS, and JavaScript. Features a custom color palette and fully responsive design.

## Features

✨ **Modern Design** - Clean, professional interface inspired by contemporary portfolios  
📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices  
🎨 **Custom Color Palette** - Beautiful, cohesive color scheme included  
⚡ **No Dependencies** - Pure HTML, CSS, and JavaScript (no build tools needed)  
♿ **Accessible** - Semantic HTML and WCAG-compliant interactive elements  
🌙 **Dark Mode Support** - Automatically adapts to system preferences  
🎯 **Smooth Interactions** - Scroll animations and interactive elements  

## Color Palette

- **Evergreen** (#16302b) - Primary dark color
- **Lime Cream** (#d6f599) - Bright accent color
- **Slate Grey** (#788aa3) - Secondary color
- **Lavender Blush** (#f5e6e8) - Light background
- **Dark Walnut** (#4c230a) - Dark accent

## Getting Started

1. **Open in VS Code** - The Portfolio folder is already open
2. **Live Server** - Right-click on `index.html` and select "Open with Live Server"
   - OR Use any local server: `python3 -m http.server 8000`
3. **View in Browser** - Navigate to `http://localhost:8000` or `http://localhost:5500`

## Customization Guide

### Update Your Information

Edit `index.html` to add your own content:

- **Hero Section** - Change the title and subtitle
- **Projects** - Update the featured projects with your own work
- **About Section** - Add your bio and skills
- **Articles** - Update with your blog posts or writing
- **Contact** - Update email and links

### Modify Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --evergreen: #16302b;
    --lime-cream: #d6f599;
    --slate-grey: #788aa3;
    --lavender-blush: #f5e6e8;
    --dark-walnut: #4c230a;
}
```

### Add Images

1. Create an `images` folder in the portfolio directory
2. Add your project images and update the `project-image` divs:

```html
<div class="project-image">
    <img src="images/project-1.jpg" alt="Project Description">
</div>
```

Update the CSS to handle images:

```css
.project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

### Change Fonts

Update the `body` font-family in `styles.css`:

```css
body {
    font-family: 'Your Font Here', sans-serif;
}
```

## File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and layout
├── script.js           # Interactive features
├── README.md           # This file
└── images/             # Add your project images here
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

Deploy to any static hosting service:

- **GitHub Pages** - Push to a GitHub repository
- **Netlify** - Drag and drop the Portfolio folder
- **Vercel** - Connect your Git repository
- **Surge.sh** - Quick CLI deployment
- **Any Web Server** - FTP or file upload

## Tips for Success

1. **High-Quality Images** - Use 1200x800px images for projects
2. **Compelling Copy** - Write clear, concise project descriptions
3. **External Links** - Update all href="#" with real links to your projects
4. **SEO** - Update the `<title>` and add meta descriptions
5. **Performance** - Optimize images before adding to the portfolio

## Customizing Further

### Add a Contact Form

Replace the contact section with a form service like Formspree or Netlify Forms:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="email" name="email" required>
    <textarea name="message" required></textarea>
    <button type="submit">Send</button>
</form>
```

### Add a Blog

Create a `blog/` folder with separate HTML files for each post, or link to an external blog platform.

### Add Analytics

Add Google Analytics or similar by including a tracking script in the `<head>`:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
```

## Support

Need help? Check:
- Your browser's Developer Tools (F12)
- The CSS and JS comments in the files
- Common customization examples in this README

Enjoy building your portfolio! 
