# Apple-Inspired Portfolio Website

A modern, clean portfolio website inspired by Apple's design principles featuring smooth animations, minimalist aesthetics, and responsive design.

## 🎨 Features

- **Apple-like Design**: Clean, minimalist interface with subtle gradients and premium feel
- **Smooth Animations**: Fade-in effects, parallax scrolling, hover interactions, and reveal animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Modern Tech Stack**: Pure HTML5, CSS3, and Vanilla JavaScript (no dependencies)
- **Performance Optimized**: Fast loading with debounced scroll events and optimized animations
- **Interactive Elements**: 
  - Custom cursor effect (desktop)
  - Typing animation for hero subtitle
  - 3D tilt effect on project cards
  - Smooth scroll behavior
  - Mobile-friendly hamburger menu

## 📋 Sections

1. **Hero Section** - Profile photo with gradient glow effect and call-to-action buttons
2. **About** - Personal introduction with statistics
3. **Skills** - Technology expertise displayed in cards
4. **Experience** - Timeline view of work history
5. **Projects** - Portfolio of work with hover effects
6. **Contact** - Contact form and social links

## 🚀 Getting Started

1. **Replace Your Photo**: 
   - Replace the placeholder image URL in `index.html` (line 33)
   - Use your actual photo: `<img src="path/to/your-photo.jpg" alt="Manan Saini" class="hero-image">`

2. **Update Content**:
   - Edit all text content in `index.html` to match your information
   - Update statistics in the About section
   - Add your actual projects with images and links
   - Update skills to match your expertise
   - Modify experience timeline with your work history

3. **Customize Contact Info**:
   - Update email, LinkedIn, and GitHub links (search for `href=` in the contact section)
   - Connect the contact form to your backend or service (e.g., Formspree, EmailJS)

4. **Personalize Colors** (Optional):
   - Edit CSS variables in `styles.css` (lines 1-12)
   - Change `--color-accent` to your preferred brand color
   - Adjust gradients to match your style

## 🎨 Customization Guide

### Colors
Edit these CSS variables in `styles.css`:
```css
--color-accent: #0071e3;  /* Your brand color */
--color-bg: #ffffff;       /* Background color */
```

### Typography
The website uses Inter font (similar to Apple's San Francisco). To change:
```css
--font-primary: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
```

### Images
- Hero photo: 200x200px (circular display)
- Project images: 600x400px recommended
- Use high-quality, optimized images

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

### Animations
- Intersection Observer API for scroll reveal animations
- CSS keyframe animations for smooth transitions
- Parallax effect on hero section
- 3D transforms on project cards

### Performance
- Debounced scroll events
- Optimized animations with CSS transforms
- Lazy loading considerations
- Minimal JavaScript dependencies

## 📝 To-Do: Customize Your Website

- [ ] Replace placeholder photo with your actual photo
- [ ] Update hero section with your name and title
- [ ] Write your About section content
- [ ] Add your skills and technologies
- [ ] Fill in your work experience
- [ ] Add your actual projects with images and links
- [ ] Update contact information and social links
- [ ] Test contact form functionality
- [ ] Add your favicon
- [ ] Deploy to hosting (Vercel, Netlify, GitHub Pages, etc.)

## 🌐 Deployment

### Quick Deploy Options:

**Vercel/Netlify**: 
- Drag and drop the folder
- Automatically deployed

**GitHub Pages**:
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in repository settings

**Custom Hosting**:
- Upload all files to your web server
- Ensure `index.html` is in the root directory

## 📄 File Structure

```
personal_website/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 💡 Tips

1. **Images**: Optimize your images before uploading (use tools like TinyPNG)
2. **Content**: Keep text concise and impactful (Apple style)
3. **Projects**: Showcase your best 4-6 projects
4. **Contact Form**: Integrate with a backend service for email functionality
5. **SEO**: Add meta tags, OpenGraph tags for social sharing

## 🎯 Next Steps

1. Replace all placeholder content with your actual information
2. Add your real project images and descriptions
3. Set up a contact form backend (FormSpree, EmailJS, or custom)
4. Test on multiple devices and browsers
5. Deploy to your domain

## 📞 Need Help?

- Contact form requires backend integration
- Recommended services: Formspree, EmailJS, Web3Forms
- For custom features, consider adding a backend (Node.js, Python)

---

**Built with ❤️ inspired by Apple's timeless design**

