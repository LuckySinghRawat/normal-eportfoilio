# Professional Cybersecurity Portfolio

A modern, recruiter-friendly portfolio website showcasing expertise in compiler design, system hardening, secure architecture, and cybersecurity innovation.

## 🎯 Features

### Professional Design
- **Clean, Modern Layout**: Minimalist design with cybersecurity-themed aesthetics
- **Responsive**: Fully responsive on desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle scroll animations and transitions for engaging experience
- **Dark-Accent Color Scheme**: Cyan/blue accents for cybersecurity feel

### Content Sections
- **Hero Section**: Compelling introduction with code block visual
- **About**: Professional background with key statistics
- **Technical Expertise**: Organized skills across 6 categories
  - Programming Languages (Python, C++, Java, C)
  - Compiler & Systems (Lex/Flex, LLVM, MinGW)
  - Security Frameworks (JWT, OTP, RBAC)
  - System Hardening
  - Architecture & Design
  - Tools & Platforms

- **Featured Projects**: 3 detailed case studies with impact metrics
  - Secure Compiler Framework
  - System Hardening Toolkit
  - Privacy-Conscious AI Education Platform

- **Achievements**: Hackathons, educational leadership, and technical contributions
- **Why Work With Me**: 4 key value propositions
- **Contact**: Email form and social links

### Interactive Features
- Smooth scrolling navigation
- Mobile hamburger menu
- Form validation and submission
- Scroll animations
- Keyboard accessibility
- External link handling

## 📋 File Structure

```
portfolio/
├── index.html          # Main HTML structure
├── style.css          # All styling and layouts
├── script.js          # JavaScript for interactivity
├── README.md          # This file
└── assets/            # (Optional) Images, icons, etc.
```

## 🚀 Quick Start

### Option 1: Open Locally
1. Clone or download this portfolio
2. Open `index.html` in your web browser
3. No server required!

### Option 2: Deploy to GitHub Pages
1. Push files to a GitHub repository
2. Go to **Settings** → **Pages**
3. Select source branch (main)
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 3: Deploy to Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty if static)
3. Set publish directory: (leave as root)
4. Deploy!

### Option 4: Deploy to Vercel
1. Connect your GitHub repository
2. Vercel will automatically detect and deploy
3. Get a live URL instantly

## ✏️ Customization Guide

### Update Personal Information

**In `index.html`:**

```html
<!-- Update email -->
<a href="mailto:your.email@example.com">your.email@example.com</a>

<!-- Update social links -->
<a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a>
<a href="https://github.com/yourprofile" target="_blank">github.com/yourprofile</a>
```

### Customize Hero Section
```html
<h1 class="hero-title">
    Your Title <span class="highlight">Here</span>
</h1>
<p class="hero-subtitle">
    Your compelling subtitle about your expertise
</p>
```

### Update Project Cards
Find the `<!-- Project 1: Secure Compiler Framework -->` section and modify:
- Project title and description
- Key achievements
- Technologies used
- Impact statement

### Modify Color Scheme
Edit CSS variables in `style.css`:

```css
:root {
    --primary-color: #0F172A;      /* Dark navy */
    --accent-color: #06B6D4;       /* Cyan */
    --accent-light: #22D3EE;       /* Light cyan */
    /* ... more colors ... */
}
```

### Add Your Own Skills
In the expertise section, update skill categories:

```html
<div class="skill-category">
    <h3><i class="fas fa-code"></i> Your Skill Category</h3>
    <div class="skill-tags">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
    </div>
</div>
```

### Update Statistics
Modify the about section stats:

```html
<div class="about-stats">
    <div class="stat">
        <div class="stat-number">YOUR_NUMBER</div>
        <div class="stat-label">Your Label</div>
    </div>
</div>
```

## 🎨 Design Elements

### Color Palette
- **Primary**: #0F172A (Dark Navy)
- **Secondary**: #1E293B (Slate Blue)
- **Accent**: #06B6D4 (Cyan)
- **Accent Light**: #22D3EE (Light Cyan)
- **Text Primary**: #0F172A
- **Text Secondary**: #64748B (Slate)

### Typography
- **Font Family**: Segoe UI, Tahoma, Geneva, Verdana (System fonts - no external dependencies)
- **Headings**: Bold, -0.5px letter spacing
- **Body**: Regular weight, 1.6 line height

### Icons
Using Font Awesome 6.4.0 via CDN. Available icons include:
- `fas fa-shield-alt` - Security/Shield
- `fas fa-code` - Code
- `fas fa-lock` - Lock/Security
- `fas fa-microchip` - Compiler/System
- `fas fa-brain` - AI/Intelligence
- `fas fa-trophy` - Achievement
- `fas fa-graduation-cap` - Education
- `fas fa-chart-line` - Metrics

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (Full layout)
- **Tablet**: 769px - 1199px (Adjusted grid)
- **Mobile**: Below 768px (Single column, stacked layout)
- **Small Mobile**: Below 480px (Optimized font sizes, padding)

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA labels for interactive elements
- Keyboard navigation support (Tab, Enter, Escape)
- Focus states for keyboard users
- Color contrast meeting WCAG standards
- Form field validation

## 🔍 SEO Optimization

### Recommendations:
1. Update the `<title>` and `<meta>` tags in `index.html`
2. Add meaningful alt text to any images
3. Use semantic HTML tags (already implemented)
4. Structure content with proper heading hierarchy
5. Add JSON-LD schema for rich snippets

```html
<!-- Add to <head> -->
<meta name="description" content="Professional cybersecurity portfolio...">
<meta name="keywords" content="cybersecurity, compiler design, system hardening...">
<meta property="og:title" content="Your Name - Cybersecurity Expert">
```

## 🐛 Troubleshooting

### Icons not showing?
- Ensure Font Awesome CDN link in `index.html` is correct
- Check browser console for CORS errors
- May need to use alternative icon set if CDN is blocked

### Form not submitting?
- Check browser console for JavaScript errors
- Verify all form fields are filled
- Email validation regex in `script.js` may need adjustment

### Layout issues on mobile?
- Clear browser cache (Ctrl+Shift+Delete)
- Check that viewport meta tag is present
- Test with browser DevTools mobile view

## 🚀 Performance Tips

1. **Optimize Images**: If adding images, compress them
2. **Minimize CSS/JS**: Consider minifying for production
3. **Lazy Loading**: Add `loading="lazy"` to images
4. **Remove Unused CSS**: Clean up unused styles
5. **Enable Gzip**: On your hosting provider

## 📄 License

Free to use and modify for personal and professional purposes.

## 🤝 Contributing

Feel free to improve and customize this portfolio!

## 📞 Support

For questions about customization:
1. Check the inline HTML comments
2. Review CSS variable definitions
3. Test changes in browser DevTools
4. Use browser console for debugging

---

**Happy customizing! Good luck with your cybersecurity career! 🛡️**
