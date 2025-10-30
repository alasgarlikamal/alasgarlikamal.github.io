# Kamal Alasgarli - Portfolio Website

A clean, minimalist portfolio website showcasing my experience, projects, and skills as a Software Engineer.

## Features

- **Minimalist Design**: Clean, content-focused layout inspired by modern blog designs
- **Dark/Light Mode**: Automatic theme detection with manual toggle
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Sticky header with smooth scrolling
- **Performance Optimized**: Fast loading with minimal dependencies
- **Accessible**: Semantic HTML and ARIA labels for better accessibility

## Technologies Used

- HTML5 (Semantic markup)
- CSS3 (CSS Variables, Grid, Flexbox)
- Vanilla JavaScript (No frameworks)
- Google Fonts (Inter)

## Design Philosophy

This portfolio follows a minimalist, blog-style design approach:
- Focus on content and readability
- Clean typography with Inter font
- Subtle colors and borders
- Dark/light mode support with system preference detection
- Mobile-first responsive design

## Deployment to GitHub Pages

### Step 1: Initialize Git Repository (if not already done)

```bash
git init
git add .
git commit -m "Initial commit: Minimalist portfolio website"
```

### Step 2: Create GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right and select "New repository"
3. Name it: `alasgarlikamal.github.io` (must match your GitHub username)
4. Do NOT initialize with README, .gitignore, or license
5. Click "Create repository"

### Step 3: Push to GitHub

```bash
git remote add origin https://github.com/alasgarlikamal/alasgarlikamal.github.io.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"

Your website will be live at: `https://alasgarlikamal.github.io`

Note: It may take a few minutes for the site to become available.

## File Structure

```
alasgarlikamal.github.io/
├── index.html              # Main HTML file
├── styles.css              # Styling with theme support
├── script.js               # JavaScript for theme toggle and navigation
├── profile.jpg             # Profile photo
├── Kamal_Alasgarli_CV_Updated.pdf  # Downloadable resume
├── .gitignore              # Git ignore file
└── README.md               # This file
```

## Customization

### Update Theme Colors

Edit the CSS variables in `styles.css`:

```css
:root[data-theme="light"] {
    --bg-primary: #ffffff;
    --bg-secondary: #f9fafb;
    --text-primary: #111827;
    --text-secondary: #6b7280;
    --border-color: #e5e7eb;
    --accent: #2563eb;
    --accent-hover: #1d4ed8;
}

:root[data-theme="dark"] {
    --bg-primary: #0f172a;
    --bg-secondary: #1e293b;
    --text-primary: #f1f5f9;
    --text-secondary: #94a3b8;
    --border-color: #334155;
    --accent: #60a5fa;
    --accent-hover: #93c5fd;
}
```

### Update Content

- Edit `index.html` to update personal information, projects, and experience
- Replace `profile.jpg` with your own photo
- Update `Kamal_Alasgarli_CV_Updated.pdf` with your resume

### Add New Sections

Follow the existing structure in `index.html`:

```html
<section class="section" id="section-id">
    <h2 class="section-title">Section Title</h2>
    <!-- Your content here -->
</section>
```

## Features Explained

### Theme Toggle
- Automatically detects system preference (dark/light mode)
- Manual toggle button in navigation
- Saves user preference in localStorage
- Smooth transitions between themes

### Mobile Menu
- Hamburger menu for mobile devices
- Smooth slide-in animation
- Auto-closes when clicking outside or on a link

### Smooth Scrolling
- Smooth scroll to sections when clicking navigation links
- Accounts for fixed header height

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Minimal JavaScript (< 2KB)
- No external dependencies (except Google Fonts)
- Optimized images
- Fast loading times

## License

This project is open source and available for personal use.

## Contact

- **Email**: ka3088@columbia.edu
- **LinkedIn**: [linkedin.com/in/alasgarlikamal](https://linkedin.com/in/alasgarlikamal)
- **GitHub**: [github.com/alasgarlikamal](https://github.com/alasgarlikamal)
- **Phone**: +1 (212) 256-1461
