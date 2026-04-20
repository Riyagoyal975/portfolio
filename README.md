# Riya Goyal - Portfolio Website

A modern, clean, and fully responsive personal portfolio website for Riya Goyal, a first-year B.Tech CSE (AI & ML) student at Manav Rachna University.

## Features

- ✨ Modern and clean UI/UX design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Light theme with soft blue/gradient accents
- 🚀 Smooth scrolling navigation
- ✨ Subtle hover animations
- ⚡ Fast and optimized performance
- 📄 Working resume download functionality

## Sections

1. **Hero Section** - Introduction with name, title, and call-to-action buttons
2. **About Me** - Brief introduction and background
3. **Skills** - Technical skills showcase
4. **Projects** - Portfolio of completed and ongoing projects
5. **Certificates** - Completed and in-progress certifications
6. **Education** - Academic background
7. **Contact** - Contact information and social links

## Setup Instructions

### 1. Add Your Resume

Place your resume PDF file in the `assets` folder with the name:
```
assets/Riya_Goyal_Resume.pdf
```

**Important:** Make sure the resume file is named exactly as shown above for the download buttons to work properly.

### 2. Local Development

Simply open `index.html` in your web browser to view the portfolio locally.

### 3. Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push all files to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Under "Source", select "main" branch
5. Click Save
6. Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### 4. Customize Content

Update the following in `index.html`:
- Email address (currently: riya@example.com)
- LinkedIn URL (currently: placeholder)
- GitHub URL (currently: placeholder)
- Add more projects, certificates, or achievements as needed

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/
    └── Riya_Goyal_Resume.pdf  # Your resume (add this file)
```

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Resume Download Feature

The portfolio includes two "Download Resume" buttons:
1. In the Hero section
2. In the Contact section

Both buttons will download the PDF file from `assets/Riya_Goyal_Resume.pdf` when clicked.

**For GitHub Pages:** Make sure to commit and push the resume PDF file to your repository for the download to work on the live site.

## Customization Tips

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4A90E2;
    --secondary-color: #5BA3F5;
    --accent-color: #7B68EE;
    /* ... */
}
```

### Add More Sections
Follow the existing section structure in `index.html` and add corresponding styles in `styles.css`.

### Update Content
All content is in `index.html` - simply edit the text within the HTML tags.

## Performance

- Minimal external dependencies
- Optimized CSS with efficient selectors
- Lightweight JavaScript
- Fast loading times

## License

This portfolio template is free to use and modify for personal purposes.

## Contact

For any questions or suggestions, reach out to:
- Email: riya@example.com
- LinkedIn: [Update with your profile]
- GitHub: [Update with your profile]

---

Built with ❤️ by Riya Goyal
