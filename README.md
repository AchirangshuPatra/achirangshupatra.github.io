# Achirangshu Patra - CV Website

A modern, responsive CV website built with HTML, CSS, and JavaScript. This website showcases professional experience, skills, projects, and contact information in an elegant and interactive design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Mobile-friendly hamburger menu
  - Animated skill bars
  - Contact form with validation
  - Scroll-triggered animations
- **Professional Sections**:
  - Hero section with call-to-action buttons
  - About section with statistics
  - Experience timeline
  - Skills with progress bars
  - Featured projects
  - Contact information and form

## File Structure

```
achirangshupatra.github.io/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── achi_parta.pdf      # Original CV (for reference)
```

## Customization Guide

### 1. Personal Information

Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Your Name</h1>
<p class="hero-subtitle">Your Title</p>
<p class="hero-description">Your brief description</p>
```

#### About Section
```html
<div class="about-text">
    <p>Your personal description paragraph 1</p>
    <p>Your personal description paragraph 2</p>
</div>
```

#### Statistics
```html
<div class="stat-item">
    <h3>3+</h3>
    <p>Years Experience</p>
</div>
```

### 2. Experience

Update the timeline items in the Experience section:

```html
<div class="timeline-content">
    <h3>Your Job Title</h3>
    <h4>Company Name</h4>
    <p class="timeline-date">Duration</p>
    <ul>
        <li>Key responsibility 1</li>
        <li>Key responsibility 2</li>
        <li>Key responsibility 3</li>
    </ul>
</div>
```

### 3. Skills

Modify the skills section by updating skill names and percentages:

```html
<div class="skill-item">
    <span class="skill-name">Skill Name</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### 4. Projects

Update the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="live-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### 5. Contact Information

Update contact details in the Contact section:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

Also update the social media links:

```html
<div class="social-links">
    <a href="linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="github-url" class="social-link"><i class="fab fa-github"></i></a>
    <a href="twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
</div>
```

### 6. Colors and Styling

The website uses a blue color scheme. To change colors, update the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #3b82f6;
--secondary-color: #8b5cf6;
--accent-color: #667eea;
```

## How to Use

1. **Local Development**: Simply open `index.html` in your web browser
2. **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages
3. **Custom Domain**: Point your domain to the website files

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for better performance
- Responsive images and icons
- Smooth animations with hardware acceleration

## SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for social sharing
- Proper heading hierarchy
- Alt text for images
- Fast loading times

## Contact Form

The contact form includes:
- Client-side validation
- Success/error notifications
- Email format validation
- Form reset after submission

Note: The form currently shows a success message but doesn't actually send emails. To enable email functionality, you'll need to integrate with a backend service or email service provider.

## Customization Tips

1. **Add Your Photo**: Replace the icon in the profile card with your actual photo
2. **Update Links**: Make sure all project and social media links point to your actual profiles
3. **Add More Sections**: You can easily add new sections like Education, Certifications, etc.
4. **Change Fonts**: Update the Google Fonts import in the HTML head
5. **Add Analytics**: Include Google Analytics or other tracking codes

## License

This project is open source and available under the MIT License.

## Support

If you need help customizing the website or have questions, feel free to reach out!

---

**Note**: This is a template website. Please replace all placeholder content with your actual information before publishing. 