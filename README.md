# Spencer Steed - Professional Resume

A modern, responsive resume website built with HTML and CSS, designed to be deployed on GitHub Pages at `spencersteed.github.io/resume`.

## 🚀 Live Demo

Visit the live resume at: **https://spencersteed.github.io/resume/**

## ✨ Features

- 📱 **Fully Responsive** - Looks great on desktop, tablet, and mobile devices
- 🎨 **Modern Design** - Clean, professional design with gradient backgrounds and smooth animations
- 🖨️ **Print-Friendly** - Optimized for printing with a dedicated print button
- ⚡ **Fast Loading** - Lightweight with no external dependencies
- 🔧 **Easy to Customize** - Simple HTML structure for easy editing
- 🌟 **Interactive Elements** - Hover effects and smooth animations
- 📧 **Clickable Contact Info** - Direct links to email, phone, LinkedIn, and GitHub

## 🛠️ Quick Setup for GitHub Pages

### Step 1: Create Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it exactly: `resume` (this is important for the URL)
3. Make sure it's public (required for GitHub Pages)

### Step 2: Upload Files
1. Clone your repository locally:
   ```bash
   git clone https://github.com/spencersteed/resume.git
   cd resume
   ```

2. Copy the `index.html` file to your repository folder

3. Commit and push:
   ```bash
   git add .
   git commit -m "Add professional resume website"
   git push origin main
   ```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait 2-3 minutes for deployment

### Step 4: Access Your Resume
Your resume will be live at: **https://spencersteed.github.io/resume/**

## 🎨 Customization Guide

### Personal Information
Update the header section in `index.html`:

```html
<h1>Your Name</h1>
<div class="subtitle">Your Professional Title</div>
```

Update contact information:
```html
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+1234567890">(123) 456-7890</a>
<a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a>
<a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a>
```

### Work Experience
Replace the sample experience with your own:

```html
<div class="experience-item">
    <div class="job-title">Your Job Title</div>
    <div class="company">Company Name</div>
    <div class="duration">Start Date - End Date</div>
    <div class="description">
        <ul>
            <li>Your achievement or responsibility</li>
            <li>Another key accomplishment</li>
        </ul>
    </div>
</div>
```

### Skills Section
Modify the skills in the skills grid:

```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <ul class="skill-list">
        <li>Your skill 1</li>
        <li>Your skill 2</li>
    </ul>
</div>
```

### Education
Update the education section:

```html
<div class="education-item">
    <div class="job-title">Your Degree</div>
    <div class="company">University Name</div>
    <div class="duration">Start Year - End Year</div>
    <div class="description">Additional details or relevant coursework</div>
</div>
```

## 🎨 Design Customization

### Colors
The main color scheme uses a blue gradient. To change colors, update these CSS values:

```css
/* Header gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Section headers */
color: #667eea;
border-bottom: 3px solid #667eea;
```

### Fonts
The resume uses system fonts for fast loading. To use custom fonts:

1. Add a Google Fonts link in the `<head>` section:
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
   ```

2. Update the font-family in CSS:
   ```css
   body {
       font-family: 'Inter', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
   }
   ```

## 📱 Mobile Optimization

The resume is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly buttons and links
- Optimized typography for small screens
- Collapsible navigation elements

## 🖨️ Print Optimization

- Print button in the top-right corner
- Optimized styles for A4 paper
- Clean, professional print layout
- No background colors or shadows in print mode

## 🔧 Technical Details

- **No Dependencies**: Pure HTML and CSS
- **No Build Process**: Direct deployment to GitHub Pages
- **SEO Optimized**: Meta tags and Open Graph support
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Performance**: Optimized CSS and minimal JavaScript

## 📁 File Structure

```
resume/
├── index.html          # Main resume file
├── README.md           # This documentation
└── .gitignore          # Git ignore file (optional)
```

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you need help with deployment or customization, please open an issue in this repository.

---

**Need help?** Check the [GitHub Pages documentation](https://docs.github.com/en/pages) or open an issue in this repository.