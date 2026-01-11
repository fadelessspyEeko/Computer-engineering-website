# Computer Engineering Website

A comprehensive educational website about the Computer Engineering field, covering education requirements, career opportunities, and salary insights.

## 📘 About This Project

This website provides detailed information about:
- Computer Engineering field overview
- Education requirements and pathways
- Career opportunities and job roles
- Salary insights and compensation data

## 🚀 Features

- **Responsive Design**: Optimized for all device sizes (mobile, tablet, desktop)
- **Accessibility**: Includes skip-to-content links and proper ARIA labels
- **SEO Optimized**: Meta tags, Open Graph, and Twitter Card support
- **Modern Web Standards**: Valid HTML5, consolidated CSS, WebP image support
- **Performance**: Optimized images with WebP format and fallbacks

## 📁 Project Structure

```
.
├── index.html              # Home/landing page
├── Website.html            # Main overview page
├── education.html          # Education requirements page
├── jobs.html              # Jobs and career page
├── salary.html            # Salary insights page
├── assets/
│   ├── css/
│   │   └── style2.css     # Consolidated stylesheet
│   ├── images/            # Image assets (JPG and WebP)
│   │   ├── Csc.jpg / Csc.webp
│   │   ├── c1.jpg / c1.webp
│   │   ├── c2.jpg / c2.webp
│   │   └── Terh-logo.jpg / Terh-logo.webp
│   └── favicon.ico        # Site favicon
├── robots.txt             # Search engine crawler instructions
├── sitemap.xml            # Site structure for search engines
└── README.md              # This file
```

## 🌐 GitHub Pages Deployment

This site is deployed using GitHub Pages. To deploy or update:

### Automatic Deployment

The site is automatically deployed from the `main` branch when changes are pushed.

1. Make your changes locally
2. Commit and push to the `main` branch:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```
3. GitHub Pages will automatically rebuild and deploy your site
4. Visit your site at: `https://fadelessspyeeko.github.io/Computer-engineering-website/`

### Manual GitHub Pages Setup

If GitHub Pages is not yet configured:

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select the `main` branch
4. Click **Save**
5. Your site will be published at `https://fadelessspyeeko.github.io/Computer-engineering-website/`

## 💻 Local Development

To run the site locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/fadelessspyEeko/Computer-engineering-website.git
   cd Computer-engineering-website
   ```

2. Start a local web server:
   ```bash
   python -m http.server 8000
   ```
   Or use any other local server (Node.js `http-server`, PHP built-in server, etc.)

3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## ✅ Testing

### Manual Testing

1. **Navigation**: Test all navigation links work correctly
2. **Accessibility**: 
   - Press Tab to test skip-to-content link
   - Test keyboard navigation throughout the site
   - Use a screen reader to verify content is accessible
3. **Images**: Verify all images load correctly with WebP/JPG fallback
4. **Responsive Design**: Test on different screen sizes

### HTML Validation

The project includes automated HTML validation via GitHub Actions:
- Runs on every push and pull request to `main`
- Uses [HTMLHint](https://htmlhint.com/) for validation
- Check the Actions tab for validation results

To run HTMLHint locally:
```bash
npm install -g htmlhint
htmlhint *.html
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and responsive design
- **WebP**: Modern image format for better performance
- **GitHub Pages**: Free static site hosting
- **GitHub Actions**: Automated HTML validation

## 📝 TODO

- [ ] Convert placeholder WebP files to actual WebP images (requires `cwebp` tool)
- [ ] Add actual favicon.ico (currently placeholder)
- [ ] Consider adding JavaScript for enhanced interactivity
- [ ] Add more content pages as needed

## 👤 Author

Published by: Terh Billgate

## 📄 License

This project is available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

*Last updated: 2026*
