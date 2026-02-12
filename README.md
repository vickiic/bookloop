# BookLoop - Small Business Finance App

A modern, AI-powered finance management tool designed for small business owners.

## 🚀 Features

- **AI Co-Pilot**: Ask questions in plain English about your finances
- **Owner-First Dashboard**: Answers critical questions like "Can I afford to hire?"
- **Smart Insights**: Actionable recommendations, not just data
- **Cash Runway Tracking**: See how many days of cash you have left
- **Invoice Management**: Create and send professional invoices
- **Bank Reconciliation**: Easy monthly reconciliation
- **Inventory Tracking**: Monitor stock levels and value
- **Plain Language**: Zero accounting jargon

## 📁 Files

- `index.html` - Main application file (open this in a browser)
- `README.md` - This file

## 🌐 Deploy to GitHub Pages

### Method 1: GitHub Web Interface (Easiest)

1. **Create a new repository on GitHub:**
   - Go to https://github.com/new
   - Name it `bookloop` (or any name you want)
   - Make it Public
   - Click "Create repository"

2. **Upload the file:**
   - Click "uploading an existing file"
   - Drag `index.html` into the upload area
   - Click "Commit changes"

3. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at: `https://yourusername.github.io/bookloop`

### Method 2: Using Git Command Line

```bash
# Navigate to your project folder
cd /path/to/bookloop

# Initialize git repository
git init

# Add the file
git add index.html README.md

# Commit
git commit -m "Initial commit: BookLoop finance app"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/bookloop.git

# Push to GitHub
git push -u origin main

# Enable GitHub Pages in repository Settings → Pages
```

## 🎨 Customization

The app uses CSS variables for easy theming. Colors are defined at the top of `index.html`:

```css
--primary: #5B7C99;        /* Main brand color */
--primary-light: #7D9CB8;  /* Light variant */
--primary-dark: #3D5A73;   /* Dark variant */
--accent: #E89B6C;         /* Accent color */
```

## 📱 Local Development

Simply open `index.html` in any modern web browser:

- Chrome
- Firefox  
- Safari
- Edge

No build process or dependencies required!

## 🔧 Technology

- Pure HTML, CSS, and JavaScript
- No frameworks or dependencies
- Works offline once loaded
- Mobile responsive

## 📄 License

Free to use and modify for personal or commercial projects.

## 🤝 Contributing

This is a prototype/demo application. Feel free to fork and customize for your needs!

---

**Live Demo:** [Add your GitHub Pages URL here after deployment]

**Questions?** Open an issue on GitHub or contact the team.
