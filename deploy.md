# Quick Deployment Guide

## 🚀 Deploy to GitHub Pages in 3 Steps

### 1. Create Repository
- Go to [GitHub](https://github.com/new)
- Repository name: `resume` (exactly this name)
- Make it **Public**
- Don't initialize with README (we already have files)

### 2. Upload Files
```bash
# Clone the repository
git clone https://github.com/spencersteed/resume.git
cd resume

# Copy your files here (index.html, README.md)
# Then commit and push
git add .
git commit -m "Add professional resume website"
git push origin main
```

### 3. Enable GitHub Pages
- Go to repository **Settings**
- Scroll to **Pages** section
- Source: **Deploy from a branch**
- Branch: **main** / **/ (root)**
- Click **Save**

### 4. Access Your Resume
**https://spencersteed.github.io/resume/**

---

## ✅ That's it! Your resume is now live.

The URL will be: **https://spencersteed.github.io/resume/**

Remember to customize the content in `index.html` with your actual information before deploying.
