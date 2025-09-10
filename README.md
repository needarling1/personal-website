# Personal Website Template

A modern, responsive personal website template designed for computer science students and professionals. Perfect for showcasing internships, projects, education, and skills to potential employers.

## Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling, hover effects, and dynamic animations
- **Sections Included**:
  - Hero section with introduction
  - About section with personal stats
  - Experience timeline (perfect for internships)
  - Featured projects showcase
  - Education details
  - Skills grid with icons
  - Contact form and social links

## Quick Start

1. **Clone or download** this repository
2. **Customize** the content in `index.html`:
   - Replace "Your Name" with your actual name
   - Update contact information
   - Add your actual internships and projects
   - Modify education details
   - Update skills and technologies
3. **Add your profile photo** by replacing the placeholder icon in the hero section
4. **Deploy** to GitHub Pages, Netlify, or any web hosting service

## Customization Guide

### Personal Information
- **Name**: Replace "Your Name" throughout the HTML
- **Email**: Update the email in the contact section
- **Phone**: Update phone number in contact section
- **Location**: Update city/state in contact section
- **Social Links**: Update LinkedIn, GitHub, Twitter, and resume links

### Experience Section
Add your internships and work experience by duplicating the timeline items:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <span class="timeline-date">Date Range</span>
        <p>Brief description of your role and responsibilities.</p>
        <ul>
            <li>Key achievement or responsibility</li>
            <li>Another key achievement</li>
            <li>Third key achievement</li>
        </ul>
    </div>
</div>
```

### Projects Section
Add your projects by duplicating project cards:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i> <!-- Change icon as needed -->
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description and what it does.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
            <span class="tech-tag">Technology 3</span>
        </div>
        <div class="project-links">
            <a href="github-link" class="project-link"><i class="fab fa-github"></i> GitHub</a>
            <a href="live-demo-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
        </div>
    </div>
</div>
```

### Skills Section
Update the skills by modifying the skill items:

```html
<div class="skill-item">
    <i class="fab fa-python"></i> <!-- FontAwesome icon -->
    <span>Python</span>
</div>
```

### Education Section
Update your education details:

```html
<h3>Your Degree</h3>
<span class="education-date">Start Year - End Year</span>
<h4>University Name</h4>
<p>Description of your program and focus areas.</p>
<div class="education-details">
    <div class="gpa">
        <strong>GPA:</strong> Your GPA
    </div>
    <div class="relevant-courses">
        <strong>Relevant Coursework:</strong>
        <ul>
            <li>Course 1</li>
            <li>Course 2</li>
            <li>Course 3</li>
        </ul>
    </div>
</div>
```

## Deployment Options

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be deployed instantly with a random URL
4. You can customize the domain name in site settings

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with default settings
4. Your site will be live with a custom URL

## File Structure

```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons for skills and projects
- **Google Fonts**: Inter font family for modern typography

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Tips for Success

1. **Keep it updated**: Regularly update your projects and experience
2. **Use real data**: Replace all placeholder content with your actual information
3. **Add a profile photo**: Replace the placeholder icon with your actual photo
4. **Test responsiveness**: Check how your site looks on different devices
5. **Optimize images**: Compress images for faster loading
6. **Add analytics**: Consider adding Google Analytics to track visitors

## Customization Ideas

- **Color scheme**: Modify the CSS variables to match your personal brand
- **Additional sections**: Add sections for certifications, publications, or awards
- **Dark mode**: Implement a dark/light theme toggle
- **Blog section**: Add a blog to showcase your writing
- **Portfolio gallery**: Create a visual portfolio of your work

## Support

If you need help customizing this template or have questions about deployment, feel free to:
- Open an issue on GitHub
- Check the documentation of your chosen hosting platform
- Refer to HTML/CSS/JavaScript tutorials for advanced customization

## License

This template is free to use for personal and commercial projects. Feel free to modify and distribute as needed.

---

**Happy coding!** 🚀
