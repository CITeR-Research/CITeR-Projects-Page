# CITeR-Projects-Page

A static website showcasing research projects from the Center for Identification Technology Research (CITeR).

## 🌟 Features

- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI**: Clean and professional interface
- **Documentation**: Comprehensive docs folder with deployment guides
- **Static & Fast**: No build process required - just HTML, CSS, and JavaScript
- **Easy Deployment**: Ready to deploy to GitHub Pages, Netlify, or Vercel

## 📁 Project Structure

```
CITeR-Projects-Page/
├── index.html          # Main homepage
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── docs/               # Documentation folder
│   ├── index.html      # Documentation homepage
│   └── docs-style.css  # Documentation-specific styles
└── README.md           # This file
```

## 🚀 Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/CITeR-Research/CITeR-Projects-Page.git
   cd CITeR-Projects-Page
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

### Viewing the Site

Simply open `index.html` in any modern web browser to view the homepage. The documentation is available at `docs/index.html`.

## 📦 Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the sidebar
3. Select the branch you want to deploy (e.g., `main`)
4. Choose the root folder `/` as the source
5. Click "Save"
6. Your site will be available at `https://[username].github.io/CITeR-Projects-Page/`

### Netlify

1. Sign up at [Netlify](https://netlify.com)
2. Click "New site from Git"
3. Connect your GitHub repository
4. Leave build settings empty (no build required)
5. Set publish directory to `/` (root)
6. Click "Deploy site"

### Vercel

1. Sign up at [Vercel](https://vercel.com)
2. Click "Import Project"
3. Import your GitHub repository
4. No build configuration needed
5. Click "Deploy"

## 🎨 Customization

### Adding Projects

Edit `index.html` and add new project cards in the `<section id="projects">` section:

```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Your project description goes here.</p>
    <a href="#" class="btn">Learn More</a>
</div>
```

### Styling

Modify `styles.css` to customize colors, fonts, and layout. Key variables to change:
- Primary color: `#667eea`
- Secondary color: `#764ba2`
- Dark color: `#2c3e50`

### Adding Documentation Pages

Create new HTML files in the `docs/` folder and link them from `docs/index.html`.

## 📚 Documentation

Full documentation is available in the `docs/` folder. Open `docs/index.html` for:
- Getting Started guide
- Project structure overview
- Deployment instructions
- API reference
- Contributing guidelines

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test your changes locally
5. Commit your changes (`git commit -m 'Add some amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 📧 Contact

For questions or support, please contact the CITeR Research team.

---

**Built with ❤️ by CITeR Research**