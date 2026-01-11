# Computer Engineering Website

A comprehensive educational website about Computer Engineering, covering education requirements, career opportunities, job roles, and salary insights.

## 📋 Project Description

This website provides valuable information about the Computer Engineering field, including:

- **Education**: Requirements, certifications, and academic paths
- **Career Paths**: Various job roles and opportunities in Computer Engineering
- **Salary Insights**: Detailed salary information for different positions
- **Tasks & Responsibilities**: What Computer Engineers do on a daily basis
- **Computer Science Integration**: How CS principles apply to Computer Engineering

## 🚀 Features

- Clean, semantic HTML5 structure
- Responsive design for mobile, tablet, and desktop
- Accessibility-focused (skip-to-content links, ARIA labels, keyboard navigation)
- SEO optimized with meta tags, Open Graph, and Twitter cards
- WebP images with fallback for better performance
- Consolidated CSS stylesheet for maintainability
- Valid HTML (passes W3C validation)

## 🌐 GitHub Pages Deployment

### Deployment Instructions

This website is designed to be deployed on GitHub Pages. Follow these steps:

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to the "Pages" section
   - Under "Source", select the branch you want to deploy (e.g., `main`)
   - Click "Save"

2. **Access Your Website**:
   - Your site will be available at: `https://fadelessspyeeko.github.io/Computer-engineering-website/`
   - It may take a few minutes for the site to become available

3. **Custom Domain (Optional)**:
   - If you have a custom domain, you can configure it in the Pages settings
   - Add a `CNAME` file to the repository root with your domain name

### Local Development

To test the website locally:

```bash
# Clone the repository
git clone https://github.com/fadelessspyEeko/Computer-engineering-website.git
cd Computer-engineering-website

# Serve locally using Python
python -m http.server 8000

# Or use Python 2
python -m SimpleHTTPServer 8000

# Or use Node.js http-server
npx http-server

# Or use PHP
php -S localhost:8000
```

Then open your browser to `http://localhost:8000`

## 📁 Project Structure

```
Computer-engineering-website/
├── index.html              # Main entry page with navigation
├── Website.html            # Home page with header image
├── education.html          # Education requirements and information
├── jobs.html              # Job tasks and CS role information
├── salary.html            # Salary insights and job opportunities
├── assets/
│   ├── css/
│   │   └── style2.css     # Consolidated stylesheet
│   └── images/
│       ├── Csc.jpg        # Header image (JPG)
│       ├── Csc.webp       # Header image (WebP)
│       ├── c1.jpg         # Education image (JPG)
│       ├── c1.webp        # Education image (WebP)
│       ├── c2.jpg         # Jobs image (JPG)
│       ├── c2.webp        # Jobs image (WebP)
│       ├── Terh-logo.jpg  # Logo (JPG)
│       └── Terh-logo.webp # Logo (WebP)
├── robots.txt             # Search engine crawler instructions
├── sitemap.xml            # Site structure for SEO
├── .github/
│   └── workflows/
│       └── html-validation.yml  # CI workflow for HTML validation
└── README.md              # This file
```

## 🧪 Testing

### Manual Testing

1. **Serve Locally**: Use the local development instructions above
2. **Test Navigation**: Verify all links work correctly
3. **Test Accessibility**: 
   - Press `Tab` to navigate using keyboard
   - Use the "Skip to content" link (press `Tab` on page load, then `Enter`)
4. **Test Images**: 
   - Modern browsers should load WebP images
   - Older browsers should fall back to JPG
5. **Test Responsiveness**: Resize your browser window to test different screen sizes

### Automated Testing

The repository includes a GitHub Actions workflow that validates HTML on every push and pull request:

- Navigate to the "Actions" tab in your GitHub repository
- Check the status of the "HTML Validation" workflow
- Review any errors or warnings

## 🛠️ Technologies Used

- HTML5
- CSS3
- WebP image format with JPG fallback
- Semantic markup
- ARIA attributes for accessibility
- GitHub Actions for CI/CD

## 🎨 Styling

The website uses a professional color scheme:
- Primary color: `#003366` (dark blue)
- Text color: `#333` (dark gray)
- Background: White with subtle hover effects

## ♿ Accessibility Features

- Skip-to-content links for keyboard navigation
- Proper heading hierarchy (h1, h2)
- ARIA labels for navigation
- High contrast support
- Reduced motion support
- Keyboard-friendly focus indicators

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Tablet: 481px - 768px
- Mobile: ≤ 480px

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

Published by: Terh Billgate

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📞 Support

For support, please open an issue in the GitHub repository.
