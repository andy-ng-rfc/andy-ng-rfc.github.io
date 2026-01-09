# Personal Portfolio Website

A modern, responsive personal portfolio website ready to deploy on GitHub Pages.

## 🚀 Deployment Instructions

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and log in to your **ngtridung** account
2. Click the "+" icon in the top right and select "New repository"
3. Repository name: **`ngtridung.github.io`** (exactly as shown)
4. Description: "My personal portfolio website"
5. Keep it **Public**
6. Do NOT initialize with README (we already have one)
7. Click "Create repository"

### Step 2: Customize Your Website

Before deploying, personalize the content in `index.html`:

- Replace `[Your Name]` with your actual name
- Update the hero subtitle/description
- Change social media links (GitHub, LinkedIn, Twitter, Email)
- Update the "About Me" section with your info
- Modify skills to match your actual skills
- Replace project examples with your real projects
- Update contact information (email, phone, location)

### Step 3: Deploy to GitHub

Open PowerShell in this directory and run these commands:

```powershell
# Initialize git repository
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit: Personal portfolio website"

# Rename branch to main
git branch -M main

# Add your GitHub repository as remote (replace ngtridung with your username if different)
git remote add origin https://github.com/ngtridung/ngtridung.github.io.git

# Push to GitHub
git push -u origin main
```

### Step 4: Enable GitHub Pages (if not automatic)

1. Go to your repository on GitHub: `https://github.com/ngtridung/ngtridung.github.io`
2. Click "Settings" tab
3. Scroll to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"

### Step 5: Access Your Website

Your website will be live at: **`https://ngtridung.github.io`**

It may take 1-5 minutes for the site to become available after your first push.

## 📁 Project Structure

```
Test_web/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive features and animations
└── README.md          # This file
```

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Scroll effects and hover animations
- **Navigation**: Fixed navbar with smooth scrolling
- **Sections**:
  - Hero with call-to-action buttons
  - About Me with statistics
  - Skills categorized by Frontend, Backend, and Tools
  - Projects showcase with overlay effects
  - Contact form
  - Social media links

## 🔧 Customization Tips

### Adding Your Photo
Replace the placeholder image URL in the About section:
```html
<img src="your-image-url-or-path" alt="Profile Picture">
```

### Changing Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;    /* Main theme color */
    --secondary-color: #8b5cf6;  /* Secondary accent */
}
```

### Adding More Projects
Copy a project card block in `index.html` and modify the content.

### Connecting Contact Form
The form currently shows an alert. To make it functional:
- Use [Formspree](https://formspree.io/)
- Use [EmailJS](https://www.emailjs.com/)
- Create your own backend API

## 🔄 Updating Your Website

After making changes:

```powershell
git add .
git commit -m "Description of your changes"
git push
```

Changes will appear on your live site within 1-2 minutes.

## 📱 Social Media Links to Update

In `index.html`, find and update:
- GitHub: `https://github.com/ngtridung`
- LinkedIn: `https://linkedin.com/in/yourprofile`
- Twitter: `https://twitter.com/yourprofile`
- Email: `your.email@example.com`

## 🎨 Optional Enhancements

- Add a blog section
- Integrate Google Analytics
- Add a dark mode toggle
- Include a resume download button
- Add more project details with modals
- Include testimonials section

## 📧 Need Help?

If you encounter issues:
1. Check GitHub repository settings
2. Ensure repository name is exactly `ngtridung.github.io`
3. Verify repository is public
4. Wait a few minutes after pushing

---

**Good luck with your portfolio! 🎉**
