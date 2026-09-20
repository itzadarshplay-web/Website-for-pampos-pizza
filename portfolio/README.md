# Adarsh's Portfolio Website

A modern, premium, responsive personal portfolio website for Adarsh - a Class 10 student, aspiring web developer, AI enthusiast, video editor, and graphic/thumbnail designer from Uttar Pradesh, India.

## 🌟 Features

- **Modern Design**: Clean, professional aesthetic with glassmorphism elements and subtle gradients
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Smooth Animations**: Fade-in effects, hover animations, and smooth scrolling
- **Interactive Gallery**: Masonry grid layout with lightbox functionality
- **Contact Form**: Functional contact form with validation
- **Dark Theme**: Premium tech-inspired dark color scheme

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css   # All styles and animations
│   ├── js/
│   │   └── main.js     # JavaScript functionality
│   └── images/
│       └── profile.jpg # Your profile photo (add your own)
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Local Development

1. Clone or download this repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   cd portfolio
   python3 -m http.server 8080
   # Visit http://localhost:8080
   ```

### Option 2: Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push all files to the repository
3. Go to Settings > Pages
4. Select the main branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 3: Deploy to Netlify/Vercel

1. Drag and drop the folder to Netlify Drop, or
2. Connect your GitHub repository to Vercel

## 🎨 Customization Guide

### Adding Your Profile Photo

1. Add your photo as `profile.jpg` in the `assets/images/` folder
2. Recommended size: 400x450 pixels (or similar aspect ratio)
3. The photo will automatically be used; if not found, a placeholder is shown

### Updating Social Links

Edit these links in `index.html`:
- LinkedIn: Search for `linkedin.com/in/yourprofile`
- GitHub: Search for `github.com/yourprofile`
- Email: Search for `adarsh@example.com`

### Adding Projects

Find the Projects section in `index.html` and duplicate a project card:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-image.jpg" alt="Project Name">
        <div class="project-overlay">
            <a href="#" class="project-btn">View Project</a>
        </div>
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Description here...</p>
        <div class="project-tech">
            <span>Tech 1</span>
            <span>Tech 2</span>
        </div>
    </div>
</div>
```

### Adding Gallery Images

Find the Gallery section and add more items:

```html
<div class="gallery-item" data-category="design">
    <img src="your-image.jpg" alt="Description">
    <div class="gallery-overlay">
        <span class="gallery-caption">Caption</span>
        <i class="fas fa-search-plus"></i>
    </div>
</div>
```

Categories: `design`, `thumbnail`, `video`, `web`

### Changing Colors

Edit the CSS variables in `assets/css/style.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main accent color */
    --secondary-color: #0ea5e9;    /* Secondary accent */
    --bg-primary: #0f0f23;         /* Main background */
    /* ... more variables */
}
```

## 📱 Sections Included

1. **Navigation**: Sticky navbar with mobile hamburger menu
2. **Hero**: Introduction with profile photo and CTA buttons
3. **About Me**: Personal introduction and interests
4. **Skills**: Skill cards with icons
5. **Projects**: Project showcase with hover effects
6. **Gallery**: Image gallery with lightbox
7. **Education**: Educational background
8. **Contact**: Contact form and social links
9. **Footer**: Minimal footer with social icons

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter, Poppins)

## ✨ Key Features Explained

### Glassmorphism Effect
The design uses backdrop-filter blur and semi-transparent backgrounds for a modern glass effect.

### Smooth Scrolling
All anchor links scroll smoothly to their sections with offset for the fixed navbar.

### Scroll Animations
Sections fade in as you scroll using Intersection Observer API.

### Lightbox Gallery
Click any gallery image to view it in full size with a caption.

### Form Validation
The contact form validates email format and required fields before submission.

### Mobile Responsive
The navigation converts to a hamburger menu on mobile devices.

## 📝 To-Do (Optional Enhancements)

- [ ] Add backend integration for contact form (Formspree, EmailJS, etc.)
- [ ] Add more projects
- [ ] Include actual work samples in the gallery
- [ ] Add blog section
- [ ] Integrate analytics
- [ ] Add theme switcher (light/dark mode)

## 📄 License

This portfolio is created for Adarsh's personal use. Feel free to use it as inspiration for your own portfolio.

## 👤 Contact

For questions or collaborations, reach out through:
- LinkedIn: [Your LinkedIn Profile]
- GitHub: [Your GitHub Profile]
- Email: [Your Email]

---

**Built with ❤️ by Adarsh**
