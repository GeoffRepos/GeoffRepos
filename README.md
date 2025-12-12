# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Multiple Sections**:
  - Hero section with social links
  - About Me with downloadable resume
  - Featured Projects showcase
  - Skills & Technologies
  - Contact form
- **Interactive Navigation**: Smooth scrolling with active link highlighting
- **Optimized Performance**: Fast loading with efficient code
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🚀 Live Demo

Once deployed, your portfolio will be live at: `https://yourusername.github.io/Portfolio`

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── assets/             # Images and resources
│   ├── profile.jpg     # Your profile photo
│   ├── project1.jpg    # Project screenshot 1
│   ├── project2.jpg    # Project screenshot 2
│   ├── project3.jpg    # Project screenshot 3
│   ├── project4.jpg    # Project screenshot 4
│   └── resume.pdf      # Your resume
└── README.md           # This file
```

## 🛠️ Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace "Your Name" throughout the file
- **Title/Role**: Update the hero subtitle and roles
- **Location**: Update location information in About and Contact sections
- **Email**: Replace `your.email@example.com` with your actual email
- **Phone**: Update phone number in the contact section
- **Social Links**: Update URLs for GitHub, LinkedIn, Twitter, etc.

### 2. About Section

Update the about text in the About section to reflect your background, experience, and interests.

### 3. Projects

For each project in the Projects section, update:
- Project name and description
- Technologies used (tags)
- GitHub repository link
- Live demo link
- Project image (add screenshot to `assets/` folder)

### 4. Skills

Modify the skills in the Skills section to match your expertise. Add or remove skill categories and items as needed.

### 5. Images

Replace placeholder images in the `assets/` folder:
- `profile.jpg`: Your professional photo (400x400px recommended)
- `project1-4.jpg`: Project screenshots (800x600px or 16:9 ratio)
- `resume.pdf`: Your latest resume

### 6. Color Scheme

To change colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Secondary color */
    --accent-color: #3b82f6;     /* Accent highlights */
    /* ... other colors */
}
```

## 📤 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right, then "New repository"
3. Name your repository: `Portfolio` or `yourusername.github.io`
4. Make it public
5. Don't initialize with README (we already have one)
6. Click "Create repository"

### Step 2: Push Your Code

Open PowerShell in your portfolio folder and run:

```powershell
# Initialize Git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial portfolio commit"

# Add your GitHub repository as remote (replace with your URL)
git remote add origin https://github.com/yourusername/Portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select branch: `main`
5. Select folder: `/ (root)`
6. Click "Save"

Your site will be live at `https://yourusername.github.io/Portfolio` in a few minutes!

## 🔧 Local Development

To view your portfolio locally:

1. Simply open `index.html` in your web browser
2. Or use a local server for better development experience:

```powershell
# Using Python
python -m http.server 8000

# Using Node.js (if you have npx)
npx serve

# Using VS Code Live Server extension
# Right-click index.html and select "Open with Live Server"
```

Then open `http://localhost:8000` in your browser.

## 📝 Contact Form Integration

The contact form currently shows a success message but doesn't send emails. To make it functional:

### Option 1: FormSpree (Recommended - Free)
1. Go to [FormSpree](https://formspree.io/)
2. Create an account and get your form endpoint
3. Update the form in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: EmailJS
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Follow their integration guide
3. Update `script.js` with EmailJS code

### Option 3: Backend Service
Create your own backend API to handle form submissions.

## 🎨 Optional Enhancements

Uncomment these features in `script.js`:

- **Typing Effect**: Animated text rotation in hero section
- **Scroll to Top Button**: Quick navigation to top of page

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Contributing

This is a personal portfolio template. Feel free to fork and customize for your own use!

## 📄 License

Free to use for personal projects. Attribution appreciated but not required.

## 💡 Tips

1. **Keep it updated**: Regularly add new projects and update skills
2. **Optimize images**: Compress images before uploading for faster loading
3. **Test responsiveness**: Check on different devices and screen sizes
4. **SEO**: Update meta descriptions and add keywords
5. **Analytics**: Consider adding Google Analytics to track visitors
6. **Custom Domain**: You can use a custom domain with GitHub Pages

## 🐛 Troubleshooting

### Images not showing
- Check file paths are correct (case-sensitive)
- Ensure images are in the `assets/` folder
- Clear browser cache

### GitHub Pages not updating
- Wait a few minutes after pushing changes
- Check GitHub Actions tab for build status
- Ensure repository is public

### Responsive issues
- Test on actual devices, not just browser dev tools
- Check CSS media queries
- Validate HTML/CSS syntax

## 📞 Support

If you have questions or need help:
- Check GitHub Issues in the repository
- Review GitHub Pages documentation
- Search Stack Overflow for common issues

## 🎓 Learning Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [CSS Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)

---

**Good luck with your portfolio! 🚀**

Remember to personalize everything and showcase your unique skills and projects!
