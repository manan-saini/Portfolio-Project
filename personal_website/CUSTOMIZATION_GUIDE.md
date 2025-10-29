# Quick Customization Guide

## Step-by-Step: Making This Website Yours

### 1. 🖼️ Add Your Photo (MOST IMPORTANT!)

**In `index.html`, line 33:**

Replace:
```html
<img src="https://via.placeholder.com/300x300/1d1d1f/ffffff?text=Your+Photo" alt="Manan Saini" class="hero-image">
```

With:
```html
<img src="your-photo.jpg" alt="Your Name" class="hero-image">
```

**Photo Tips:**
- Size: 300x300px or larger (will be displayed at 200x200px)
- Format: JPG or PNG
- Quality: High resolution, professional photo
- Put the image file in the same folder as index.html

---

### 2. ✏️ Update Hero Section

**In `index.html`, lines 34-41:**

```html
<h1 class="hero-title fade-in-up">Your Name</h1>
<p class="hero-subtitle fade-in-up delay-1">Your Title/Role</p>
<p class="hero-description fade-in-up delay-2">
    Your tagline or mission statement
</p>
```

**Example:**
```html
<h1 class="hero-title fade-in-up">Jane Doe</h1>
<p class="hero-subtitle fade-in-up delay-1">Product Designer & Developer</p>
<p class="hero-description fade-in-up delay-2">
    Creating beautiful digital experiences that users love
</p>
```

---

### 3. 📝 Update About Section

**In `index.html`, lines 56-71:**

Write 2-3 paragraphs about yourself:
- Your background and passion
- Your approach to work
- What makes you unique

**Update Statistics:**
```html
<div class="stat-number">5+</div>
<div class="stat-label">Years Experience</div>
```

Change the numbers to reflect your actual experience!

---

### 4. 💼 Add Your Skills

**In `index.html`, lines 85-132:**

Each skill card follows this format:
```html
<div class="skill-card reveal">
    <div class="skill-icon">💻</div>
    <h3>Your Skill Category</h3>
    <p>Technologies, Tools, Languages</p>
</div>
```

**Emoji Ideas:**
- 💻 Frontend/Development
- ⚙️ Backend/Systems
- 📱 Mobile
- 🎨 Design
- ☁️ Cloud/DevOps
- 🗄️ Database
- 🤖 AI/ML
- 📊 Data Science

---

### 5. 📅 Update Experience Timeline

**In `index.html`, lines 140-184:**

For each job, update:
```html
<div class="timeline-date">2022 - Present</div>
<h3>Your Job Title</h3>
<h4>Company Name</h4>
<p>What you did and achieved in this role.</p>
```

**Tips:**
- List most recent first
- Use action words (Led, Developed, Implemented)
- Focus on achievements and impact
- Keep descriptions to 2-3 lines

---

### 6. 🎨 Add Your Projects

**In `index.html`, lines 192-270:**

For each project:
1. Replace the placeholder image URL
2. Update the project title
3. Write a brief description
4. Update the technology tags

```html
<div class="project-card reveal">
    <div class="project-image">
        <img src="project1.jpg" alt="Project Name">
        <div class="project-overlay">
            <a href="https://your-project-link.com" class="project-link">View Project →</a>
        </div>
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Brief description of what the project does.</p>
        <div class="project-tags">
            <span class="tag">Tech 1</span>
            <span class="tag">Tech 2</span>
            <span class="tag">Tech 3</span>
        </div>
    </div>
</div>
```

**Project Image Tips:**
- Size: 600x400px
- Format: JPG or PNG
- Show: Screenshots, mockups, or project visuals
- Optimize: Compress images before uploading

---

### 7. 📧 Update Contact Information

**In `index.html`, lines 283-302:**

Update your contact details:
```html
<a href="mailto:your-email@example.com">your-email@example.com</a>
```

```html
<a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a>
```

```html
<a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a>
```

**Contact Form Setup:**

The form currently shows a success message but doesn't send emails. To actually send emails:

**Option 1: Formspree (Easiest)**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
    <input type="text" name="name" class="form-input" placeholder="Your Name" required>
    <input type="email" name="email" class="form-input" placeholder="Your Email" required>
    <textarea name="message" class="form-input" rows="5" placeholder="Your Message" required></textarea>
    <button type="submit" class="btn-primary">Send Message</button>
</form>
```

1. Go to https://formspree.io
2. Sign up for free
3. Create a new form
4. Copy your form ID
5. Replace YOUR_FORM_ID in the code above

**Option 2: EmailJS**
- Go to https://emailjs.com
- Follow their integration guide

**Option 3: Web3Forms**
- Go to https://web3forms.com
- Get your access key

---

### 8. 🎨 Customize Colors (Optional)

**In `styles.css`, lines 1-12:**

Change the accent color to your brand color:
```css
--color-accent: #0071e3;        /* Change this! */
--color-accent-hover: #0077ed;  /* Slightly brighter version */
```

**Popular Color Choices:**
- Apple Blue: `#0071e3`
- Purple: `#6366f1`
- Green: `#10b981`
- Orange: `#f97316`
- Pink: `#ec4899`
- Red: `#ef4444`

**Pro Tip:** Use https://coolors.co to create a color palette!

---

### 9. 🔍 SEO & Meta Tags (Important!)

**In `index.html`, add these in the `<head>` section:**

```html
<meta name="description" content="Your name - Your title. Brief description of what you do.">
<meta name="keywords" content="your name, web developer, portfolio, your skills">
<meta name="author" content="Your Name">

<!-- Open Graph / Social Media -->
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Your professional tagline">
<meta property="og:image" content="https://yourwebsite.com/preview-image.jpg">
<meta property="og:url" content="https://yourwebsite.com">

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Your Name - Portfolio">
<meta name="twitter:description" content="Your professional tagline">
<meta name="twitter:image" content="https://yourwebsite.com/preview-image.jpg">
```

---

### 10. 🚀 Add a Favicon

Create a favicon (website icon that appears in browser tabs):

1. Create a 512x512px image with your logo or initials
2. Use https://favicon.io to convert it
3. Download the files
4. Add to your `<head>`:

```html
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
```

---

## 🎯 Quick Checklist

Before launching your website:

- [ ] Replaced placeholder photo with your actual photo
- [ ] Updated name and title in hero section
- [ ] Written custom About section
- [ ] Added your actual skills
- [ ] Listed your work experience
- [ ] Added 4-6 of your best projects with real images
- [ ] Updated all contact information
- [ ] Set up contact form (Formspree/EmailJS)
- [ ] Changed accent color to your brand color
- [ ] Added meta tags for SEO
- [ ] Created and added favicon
- [ ] Tested on mobile and desktop
- [ ] Checked all links work
- [ ] Optimized all images
- [ ] Spell-checked all content

---

## 🌐 How to Open Your Website

### On Your Computer:
1. Double-click `index.html`
2. It will open in your default browser

### For Testing:
- Use a local server for best results:
  - Python: `python -m http.server 8000`
  - Node.js: `npx serve`
  - VS Code: Install "Live Server" extension

### To Share:
- Deploy to Vercel, Netlify, or GitHub Pages
- See README.md for deployment instructions

---

## 💡 Pro Tips

1. **Keep it Simple**: Less is more (Apple philosophy)
2. **Quality over Quantity**: 4 great projects > 10 mediocre ones
3. **Mobile First**: Test on your phone!
4. **Fast Loading**: Optimize images (use TinyPNG.com)
5. **Professional Photo**: Invest in a good headshot
6. **Proofread**: Check for typos and grammar
7. **Get Feedback**: Ask friends to review before launching

---

## 🆘 Common Issues

**Problem**: Images not showing
- **Solution**: Make sure image files are in the same folder as index.html, or use the correct path

**Problem**: Animations not working
- **Solution**: Make sure script.js is in the same folder and linked correctly

**Problem**: Mobile menu not working
- **Solution**: Check that JavaScript is enabled in your browser

**Problem**: Contact form not sending emails
- **Solution**: Integrate with Formspree or EmailJS (see step 7)

---

**Remember**: This is YOUR website. Make it reflect your personality and professional brand! 🎨✨

