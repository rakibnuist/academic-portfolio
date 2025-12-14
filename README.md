# Abdullah Al Rakib - Academic Portfolio

Professional academic portfolio website showcasing research, publications, and experience.

## 🌐 Live Website

[View Portfolio](#) *(Update with your GitHub Pages URL after deployment)*

## 📄 About

This portfolio website is designed for PhD program and scholarship applications, featuring:
- Research interests and experience
- 8 Publications with Google Scholar links
- Education timeline with thesis downloads
- Technical skills and leadership experience
- Awards and honors
- Professional contact information

## 🚀 Deployment Instructions

### Step 1: Initialize Git Repository

```bash
cd /Users/a1/.gemini/antigravity/playground/orbital-oort/portfolio
git init
git add .
git commit -m "Initial commit: Academic portfolio website"
```

### Step 2: Create GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **+** icon (top right) → **New repository**
3. Repository name: `academic-portfolio` (or your preferred name)
4. Description: "Academic portfolio for PhD applications"
5. Choose **Public**
6. **Do NOT** initialize with README, .gitignore, or license
7. Click **Create repository**

### Step 3: Add Thesis PDFs

1. Create the documents folder if it doesn't exist:
   ```bash
   mkdir -p assets/documents
   ```

2. Copy your thesis PDF files to `assets/documents/`:
   - `assets/documents/masters-thesis.pdf` - Your Master's thesis
   - `assets/documents/bachelor-thesis.pdf` - Your Bachelor's thesis

### Step 4: Push to GitHub

Replace `YOUR_USERNAME` with your GitHub username:

```bash
git remote add origin https://github.com/YOUR_USERNAME/academic-portfolio.git
git branch -M main
git push -u origin main
```

### Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes, then visit: `https://YOUR_USERNAME.github.io/academic-portfolio/`

## 📁 Project Structure

```
portfolio/
├── index.html           # Main HTML file
├── css/
│   └── style.css       # Styles
├── js/
│   └── main.js         # JavaScript interactions
├── assets/
│   ├── images/         # Images (if needed)
│   └── documents/      # Thesis PDFs
│       ├── masters-thesis.pdf
│       └── bachelor-thesis.pdf
└── README.md           # This file
```

## 🎨 Features

- **Responsive Design** - Works on mobile, tablet, and desktop
- **Smooth Animations** - Scroll-triggered fade-in effects
- **Google Scholar Integration** - Direct links to publications
- **Thesis Downloads** - PDF download buttons for both degrees
- **SEO Optimized** - Meta tags for search engines
- **Fast Loading** - Minimal dependencies

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Google Fonts (Inter, Playfair Display)
- Font Awesome Icons

## 📝 Customization

### Update Personal Links

Edit `index.html` and replace placeholder links:

```html
<!-- Line 82 - Google Scholar link is already set -->
<a href="https://scholar.google.com/citations?user=4GZWQ3YAAAAJ" ...>

<!-- Line 85-90 - Add your LinkedIn and GitHub -->
<a href="YOUR_LINKEDIN_URL" ...>
<a href="YOUR_GITHUB_URL" ...>
```

### Update Colors

Edit `css/style.css` - lines 12-24 (CSS variables):

```css
:root {
    --primary-color: #1a2332;   /* Change main color */
    --accent-color: #d4af37;    /* Change accent color */
}
```

## 📧 Contact

- **Email**: rakibabdullah011@gmail.com
- **Phone**: +880 1816585926
- **Location**: Dhaka, Bangladesh / Nanjing, China

## 📄 License

This portfolio website is for personal use. Feel free to use as inspiration for your own portfolio.

---

**Built with ❤️ for academic excellence**
