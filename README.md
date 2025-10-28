# Personal Portfolio Website

A responsive, modern personal portfolio website built with HTML, CSS, and JavaScript (no frameworks).

## Features

- ✅ Fully responsive design (desktop, tablet, mobile)
- ✅ Modern, clean design with smooth animations
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly hamburger menu
- ✅ Contact form with JavaScript validation
- ✅ Interactive skill cards and project showcases
- ✅ Accessibility features
- ✅ SEO-friendly structure
- ✅ Fast loading and optimized

## Sections Included

1. **Header/Navigation** - Logo and navigation menu
2. **Hero Section** - Name, tagline, and download resume button
3. **About Me** - Profile picture, bio, education, and experience
4. **Skills** - Categorized skills with icons
5. **Projects** - Project showcase with demo and GitHub links
6. **Resume** - Download resume section
7. **Contact** - Contact form and social links
8. **Footer** - Copyright and social icons

## Customization Guide

### 1. Replace Placeholder Values

Find and replace all `{{PLACEHOLDER}}` values in `index.html`:

```html
<!-- Replace these placeholders -->
{{NAME}} - Your full name
{{TAGLINE}} - Your professional tagline
{{SHORT_BIO}} - Brief description about yourself
{{EDUCATION_DETAILS}} - Your education information
{{EXPERIENCE_DETAILS}} - Your work experience
{{EMAIL}} - Your email address
{{YEAR}} - Current year
{{RESUME_FILE}} - Your resume filename (e.g., "resume.pdf")

<!-- Project placeholders -->
{{PROJECT_1_TITLE}} - First project title
{{PROJECT_1_DESCRIPTION}} - First project description
{{PROJECT_1_DEMO}} - First project demo URL
{{PROJECT_1_GITHUB}} - First project GitHub URL

{{PROJECT_2_TITLE}} - Second project title
{{PROJECT_2_DESCRIPTION}} - Second project description
{{PROJECT_2_DEMO}} - Second project demo URL
{{PROJECT_2_GITHUB}} - Second project GitHub URL

{{PROJECT_3_TITLE}} - Third project title
{{PROJECT_3_DESCRIPTION}} - Third project description
{{PROJECT_3_DEMO}} - Third project demo URL
{{PROJECT_3_GITHUB}} - Third project GitHub URL

<!-- Social media URLs -->
{{LINKEDIN_URL}} - Your LinkedIn profile URL
{{GITHUB_URL}} - Your GitHub profile URL
```

### 2. Add Your Assets

Place the following files in the `assets/` folder:

- `profile.jpg` - Your profile picture (recommended: 400x400px)
- `resume.pdf` - Your resume file
- `project1.jpg` - First project screenshot (recommended: 600x400px)
- `project2.jpg` - Second project screenshot (recommended: 600x400px)
- `project3.jpg` - Third project screenshot (recommended: 600x400px)

### 3. Customize Skills

In the Skills section, you can:
- Add or remove skill categories
- Change skill icons (using Font Awesome classes)
- Modify skill names
- Reorder skills as needed

### 4. Customize Colors and Styling

In `style.css`, you can modify:
- Color scheme (search for color values like `#667eea`, `#2c3e50`)
- Font sizes and typography
- Spacing and layout
- Animation effects

### 5. Add More Projects

To add more projects:
1. Copy the project card HTML structure
2. Add a new project image to the assets folder
3. Update the projects grid CSS if needed

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/             # Assets folder
    ├── profile.jpg     # Your profile picture
    ├── resume.pdf      # Your resume
    ├── project1.jpg    # Project 1 screenshot
    ├── project2.jpg    # Project 2 screenshot
    └── project3.jpg    # Project 3 screenshot
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized images
- Minimal JavaScript
- CSS animations with hardware acceleration
- Responsive images
- Fast loading times

## Accessibility Features

- Semantic HTML structure
- Keyboard navigation support
- Focus management
- ARIA labels
- High contrast colors
- Screen reader friendly

## Getting Started

1. Download or clone this repository
2. Replace all placeholder values in `index.html`
3. Add your assets to the `assets/` folder
4. Customize colors and styling in `style.css` if desired
5. Open `index.html` in your browser to preview
6. Deploy to your preferred hosting service

## Deployment

You can deploy this portfolio to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

## Support

If you need help customizing this portfolio, check the comments in the code files for guidance on specific sections.

## License

This project is open source and available under the MIT License.
