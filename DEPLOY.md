# 🚀 GitHub Pages Deployment Guide

Your presentation is ready to be published on GitHub Pages!

## 📦 Files Ready for Deployment

✅ `index.html` - Main presentation file  
✅ `rodrigo-pfp.jpg` - Rodrigo's profile photo  
✅ `alexandre-pfp.jpeg` - Alexandre's profile photo  
✅ `README.md` - Repository documentation  

## 🌐 Your Site URL

Once deployed, your presentation will be live at:
**https://brinvestapp.github.io/**

## 📤 Deployment Steps

### 1. Stage All Files
```bash
git add index.html rodrigo-pfp.jpg alexandre-pfp.jpeg README.md presentatio1.html
```

### 2. Commit Changes
```bash
git commit -m "Add brRWA investor presentation with team photos"
```

### 3. Push to GitHub
```bash
git push origin main
```

### 4. Enable GitHub Pages (if not already enabled)
1. Go to your repository on GitHub: https://github.com/brinvestapp/brinvestapp.github.io
2. Click on **Settings**
3. Scroll down to **Pages** section
4. Under **Source**, select **main** branch
5. Click **Save**

## ⏱️ Wait Time

After pushing, GitHub Pages typically takes 1-5 minutes to build and deploy your site.

## ✅ Verify Deployment

Visit https://brinvestapp.github.io/ to see your live presentation!

## 🎯 Quick Deploy Command

Run this single command to deploy everything:
```bash
git add . && git commit -m "Deploy brRWA presentation" && git push origin main
```

## 📝 Notes

- **index.html** is automatically served as the homepage
- All external resources (Tailwind CSS, fonts) are loaded from CDNs
- Images are loaded locally from the repository
- The presentation works offline once loaded

## 🔄 Future Updates

To update the presentation:
1. Make changes to `index.html`
2. Commit: `git commit -am "Update presentation"`
3. Push: `git push origin main`
4. Wait 1-5 minutes for GitHub Pages to rebuild

## 🎨 Customization

The presentation uses:
- **Tailwind CSS** - via CDN (no build required)
- **Animate.css** - for animations
- **Google Fonts** - Inter font family

All styling is inline, so no additional CSS files needed!

---

**Ready to deploy?** Run the commands above and your presentation will be live! 🚀

