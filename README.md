# Rahiem Jerome Brooks - PANDA Portfolio

A professional portfolio website showcasing the PANDA Intervention research project and academic credentials.

## Overview

This portfolio website highlights:
- **PANDA Intervention** - A neuroscience-based early learning program for underserved children ages 3-5
- Research experience and academic achievements
- Conference presentations and awards
- Skills and technical capabilities

## Project Structure

```
Rahiem-CV/
├── index.html              # Main portfolio page
├── css/
│   └── style.css           # All styles
├── js/
│   └── main.js             # Interactive functionality
├── assets/
│   └── images/
│       ├── headshot.jpg    # Professional photo
│       ├── panda-logo.png  # PANDA Study logo
│       ├── research-poster.jpg  # Conference poster
│       └── app-preview.png # App screenshot
└── README.md
```

## Setup Instructions

### 1. Replace Placeholder Images

Replace the placeholder files in `assets/images/` with actual images:

| File | Description | Recommended Size |
|------|-------------|------------------|
| `headshot.jpg` | Professional headshot photo | 400x400px or larger |
| `panda-logo.png` | The PANDA Study logo | 200x200px |
| `research-poster.jpg` | Research poster image | 1200x900px or larger |
| `app-preview.png` | App/website screenshot | 280x560px (phone ratio) |

### 2. Add CV PDF

Place your CV PDF file at:
```
assets/Rahiem_Brooks_CV.pdf
```

### 3. Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve
```

### 4. Deployment

This site can be deployed to any static hosting service:

- **GitHub Pages**: Push to a `gh-pages` branch or enable Pages in repo settings
- **Netlify**: Connect your repository for automatic deployments
- **Vercel**: Import your repository for instant deployment

## Features

- Responsive design (mobile-friendly)
- Smooth scroll navigation
- Interactive lightbox for poster viewing
- Scroll-triggered animations
- Accessible and SEO-optimized

## Customization

### Colors

Edit CSS variables in `css/style.css`:

```css
:root {
    --primary: #2563eb;        /* Main brand color */
    --primary-dark: #1a365d;   /* Darker variant */
    --accent: #0d9488;         /* Secondary accent */
}
```

### Content

All content is in `index.html`. Update sections as needed:
- Hero section: Name, tagline, intro text
- About: Bio paragraphs, education details
- PANDA Project: Research description
- Impact: Conference presentations, awards
- Skills: Technical capabilities
- Contact: Email, phone, LinkedIn

## Links

- **PANDA Study Website**: [thepandastudy.com](https://www.thepandastudy.com/)
- **LinkedIn**: [linkedin.com/in/rahiembrooks](https://linkedin.com/in/rahiembrooks/)
- **Email**: rahiem@unc.edu

## License

This portfolio is for personal use by Rahiem Jerome Brooks.

---

Built with care for showcasing developmental neuroscience research.
