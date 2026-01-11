# Computer Engineering Website

A comprehensive informational website about Computer Engineering, covering education requirements, career paths, job opportunities, and salary insights.

## 🌟 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Accessible**: WCAG 2.1 compliant with skip links and proper semantic HTML
- **SEO Optimized**: Includes meta tags, Open Graph tags, sitemap, and robots.txt
- **Image Optimization**: WebP images with JPG fallbacks for better performance
- **Clean Structure**: Consolidated CSS and proper HTML5 semantic elements

## 📄 Pages

1. **index.html** - Landing page with hero image
2. **Website.html** - Main homepage with site overview
3. **education.html** - Information about Computer Engineering education
4. **jobs.html** - Career opportunities and job roles
5. **salary.html** - Salary insights and compensation data

## 🚀 Deployment to GitHub Pages

### Prerequisites
- GitHub account
- Repository with GitHub Pages enabled

### Steps to Deploy

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Source", select the branch you want to deploy (usually `main`)
   - Select the root folder `/`
   - Click "Save"

2. **Verify Deployment**:
   - Wait a few minutes for the build to complete
   - Your site will be available at: `https://fadelessspyeeko.github.io/Computer-engineering-website/`

3. **Custom Domain (Optional)**:
   - Add a `CNAME` file with your custom domain
   - Configure DNS settings with your domain provider
   - Update the domain in repository settings

## 🛠️ Local Development

### Running Locally

You can test the website locally using any static file server:

**Option 1: Python HTTP Server**
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000 in your browser.

**Option 2: Node.js HTTP Server**
```bash
npx http-server -p 8000
```

**Option 3: VS Code Live Server**
- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

### Testing Navigation

1. Open `index.html` or `Website.html` in your browser
2. Test the skip-to-content link (press Tab on page load)
3. Navigate through all pages using the navigation menu
4. Verify images load correctly (WebP in modern browsers, JPG fallback in others)
5. Test responsive design by resizing the browser window

## 📁 Project Structure

```
Computer-engineering-website/
├── assets/
│   ├── css/
│   │   └── style2.css          # Consolidated stylesheet
│   ├── images/                 # Image assets
│   │   ├── Csc.jpg / Csc.webp
│   │   ├── c1.jpg / c1.webp
│   │   ├── c2.jpg / c2.webp
│   │   └── Terh-logo.jpg / Terh-logo.webp
│   └── favicon.ico             # Site favicon
├── .github/
│   └── workflows/
│       └── html-validation.yml # CI workflow for HTML validation
├── index.html                  # Landing page
├── Website.html                # Main homepage
├── education.html              # Education information
├── jobs.html                   # Job opportunities
├── salary.html                 # Salary insights
├── robots.txt                  # Search engine crawler instructions
├── sitemap.xml                 # Site structure for search engines
└── README.md                   # This file
```

## 🔄 Recent Changes

### Site Improvements (January 2026)

- ✅ **HTML Structure Normalized**: All pages now have proper DOCTYPE, html, head, and body tags
- ✅ **CSS Consolidated**: Moved all inline styles to `assets/css/style2.css`
- ✅ **Assets Reorganized**: Images moved to `assets/images/` directory
- ✅ **Image Optimization**: Added WebP versions of all images with fallbacks
- ✅ **Lazy Loading**: Images now use `loading="lazy"` attribute
- ✅ **Accessibility**: Added skip links, proper ARIA labels, and semantic HTML
- ✅ **SEO**: Added meta tags, Open Graph tags, sitemap.xml, and robots.txt
- ✅ **Responsive Design**: Mobile-friendly with responsive CSS rules
- ✅ **CI/CD**: Added GitHub Actions workflow for HTML validation

## 🧪 Testing & Validation

### HTML Validation
The repository includes a GitHub Actions workflow that automatically validates HTML on every push and pull request:
- Location: `.github/workflows/html-validation.yml`
- Runs HTMLHint validation on all HTML files
- Check the "Actions" tab in GitHub to see validation results

### Manual Testing Checklist
- [ ] All pages load without errors
- [ ] Navigation works across all pages
- [ ] Images display correctly (WebP or JPG)
- [ ] Skip-to-content link works (Tab key on page load)
- [ ] Responsive design works on mobile/tablet/desktop
- [ ] All links are functional
- [ ] Tables display properly
- [ ] Footer appears on all pages

## 🤝 Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly (run HTML validation)
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

Published by: Terh Billgate

## 🔗 Links

- **Live Site**: https://fadelessspyeeko.github.io/Computer-engineering-website/
- **Repository**: https://github.com/fadelessspyEeko/Computer-engineering-website

---

*Last updated: January 11, 2026*
