# Portfolio Website 🎨

A modern, responsive portfolio website built with **HTML**, **CSS**, and **JavaScript**.

## Features ✨

- **Responsive Design** - Works perfectly on all devices (mobile, tablet, desktop)
- **Modern UI** - Beautiful gradient colors and smooth animations
- **Navigation** - Sticky navigation bar with smooth scrolling
- **Hero Section** - Eye-catching introduction with animated profile image
- **About Section** - Personal information with statistics
- **Skills Section** - Showcase of technical skills in organized cards
- **Projects Section** - Featured projects with descriptions and tags
- **Contact Section** - Contact form and social media links
- **Mobile Menu** - Hamburger menu for mobile devices
- **Animations** - Smooth scroll animations and hover effects
- **SEO Friendly** - Semantic HTML structure

## Sections Included 📑

1. **Navigation Bar** - Sticky header with smooth navigation
2. **Hero Section** - Eye-catching introduction
3. **About** - Your story and achievements
4. **Skills** - Technical skills display
5. **Projects** - Featured work samples
6. **Contact** - Get in touch section with form
7. **Footer** - Copyright and credits

## Technologies Used 🛠️

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript (Vanilla)** - Interactivity and smooth scrolling
- **Font Awesome** - Icon library
- **Responsive Design** - Mobile-first approach

## Getting Started 🚀

### 1. Clone or Download
```bash
git clone https://github.com/Maruthi927/Portfolio-website.git
cd Portfolio-website
```

### 2. Open in Browser
Simply open `index.html` in your web browser, or use a live server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using VS Code Live Server Extension
# Right-click on index.html and select "Open with Live Server"
```

### 3. Customize
Edit the following sections to personalize:
- Update your name and title in the hero section
- Replace placeholder text with your information
- Update project details and descriptions
- Add your actual contact information
- Replace social media links
- Customize colors in `styles.css` (CSS variables)

## Customization Guide 🎨

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;      /* Main color */
    --secondary-color: #764ba2;    /* Accent color */
    --text-dark: #2d3436;          /* Dark text */
    --text-light: #636e72;         /* Light text */
    --bg-light: #f5f6fa;           /* Light background */
}
```

### Add Your Projects
Edit the projects section in `index.html`:
```html
<div class="project-card">
    <div class="project-image">
        <div class="project-img-placeholder"></div>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description here</p>
        <div class="project-tags">
            <span class="tag">Technology1</span>
            <span class="tag">Technology2</span>
        </div>
        <a href="your-link" class="btn btn-secondary">View Project</a>
    </div>
</div>
```

### Update Contact Information
Replace the placeholder email, phone, and location:
```html
<p>your-email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your City, Country</p>
```

### Add Social Links
Update social media links:
```html
<a href="https://github.com/yourprofile" class="social-link"><i class="fab fa-github"></i></a>
<a href="https://linkedin.com/in/yourprofile" class="social-link"><i class="fab fa-linkedin"></i></a>
```

## File Structure 📁

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Features Explained 📚

### Mobile Menu
The hamburger menu automatically appears on mobile devices for easy navigation.

### Smooth Scrolling
Click on any navigation link and the page smoothly scrolls to the corresponding section.

### Contact Form
The contact form includes validation and shows a success message when submitted. For actual email functionality, you'd need to connect it to a backend service.

### Animations
- Floating hero image
- Card hover effects
- Scroll-based animations
- Counter animations on the about section

## Browser Support 🌐

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Tips for Better Results 💡

1. **Add Real Images** - Replace placeholder divs with actual images
2. **Update Content** - Personalize all text with your information
3. **Add Project Links** - Link to your actual projects or GitHub repositories
4. **Setup Email** - Use a service like Formspree or EmailJS for actual email functionality
5. **Deploy** - Host on GitHub Pages, Netlify, or Vercel for free

## Deployment Options 🌍

### GitHub Pages (Free)
1. Push this code to GitHub
2. Go to Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/portfolio-website`

### Netlify (Free)
1. Connect your GitHub repository
2. Auto-deploys on every push
3. Custom domain support

### Vercel (Free)
1. Similar to Netlify
2. Excellent performance
3. Easy integration with GitHub

## JavaScript Features 📝

- **Mobile Menu Toggle** - Opens/closes menu on mobile
- **Smooth Navigation** - Smooth scroll to sections
- **Form Validation** - Validates contact form
- **Scroll Animations** - Animates cards on scroll
- **Active Link Highlighting** - Shows current section in nav
- **Counter Animation** - Animates statistics

## License 📄

This project is open source and available under the MIT License.

## Support 💬

If you have any questions or need help customizing, feel free to:
- Open an issue on GitHub
- Contact through the portfolio contact form
- Check the code comments for help

## Future Enhancements 🔮

- Dark mode toggle
- Blog section
- Testimonials section
- Skill progress bars
- Download resume button
- Email integration
- Blog functionality
- Search functionality

---

**Happy coding! 🎉 Build your amazing portfolio and showcase your work to the world!**

Made with ❤️ using HTML, CSS & JavaScript