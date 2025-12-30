# Om Shekokar - Portfolio Website

A professional portfolio website showcasing data science expertise, full-stack development skills, and healthcare-focused projects.

## 🚀 Features

- **Modern & Responsive Design**: Beautiful UI that works seamlessly on all devices
- **Smooth Animations**: Interactive elements with scroll-triggered animations
- **Resume Download**: Download resume button in hero and contact sections
- **Professional Sections**:
  - Hero section with engaging introduction
  - About section with timeline of experience
  - Featured projects with descriptions and links
  - Technical skills organized by category
  - Contact form for inquiries

## 📋 Sections

1. **Home/Hero**: Introduction with call-to-action buttons
2. **About**: Educational background, internships, and certifications
3. **Projects**: Three featured healthcare and data science projects
4. **Skills**: Organized technical skills with visual representations
5. **Contact**: Contact information and inquiry form

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom properties, Flexbox, Grid)
- JavaScript (Vanilla ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## 📦 Installation & Setup

1. **Clone or download** this repository

2. **Open the project** in your code editor

3. **No build process required** - This is a pure HTML/CSS/JavaScript website

4. **Add your resume**: Place your resume PDF file in the root directory and name it `resume.pdf`
   - The resume download buttons are already linked to `resume.pdf`
   - If you name it differently, update the links in `index.html`

5. **Open `index.html`** in your web browser to view the website

## 🌐 Deployment

### Option 1: Netlify (Recommended)

1. Create a free account at [Netlify](https://www.netlify.com)
2. Drag and drop your project folder to Netlify
3. Your site will be live instantly with a free URL

### Option 2: Vercel

1. Create a free account at [Vercel](https://vercel.com)
2. Install Vercel CLI: `npm i -g vercel`
3. Run `vercel` in your project directory
4. Follow the prompts to deploy

### Option 3: GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to Settings > Pages
4. Select the main branch as source
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 4: Any Static Hosting

You can host this website on any static hosting service:
- AWS S3 + CloudFront
- Firebase Hosting
- Surge.sh
- Any web server

## 🎨 Customization

### Update Personal Information

1. **Resume**: Add your resume PDF file to the root directory as `resume.pdf`
   - The download buttons are already configured to link to this file
   - Alternatively, upload to a cloud service and update the links

2. **Contact Information**: Edit the email and LinkedIn links in `index.html`
   - Search for `om.shekokar@example.com` and replace with your email
   - Update LinkedIn and GitHub URLs

3. **Social Links**: Update social media links in the hero section

4. **Project Links**: Add your actual GitHub and blog post URLs to the project cards

### Color Scheme

The color scheme can be customized in `styles.css` by modifying the CSS variables in the `:root` selector:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #10b981;
    --accent-color: #8b5cf6;
    /* ... */
}
```

### Add More Projects

To add more projects, duplicate a `.project-card` div in the projects section and update:
- Project title
- Project description
- Project tags
- Project links (GitHub and blog)

### Modify Skills

Update skills in the skills section of `index.html`. You can:
- Adjust skill bar percentages
- Add or remove skill tags
- Add new skill categories

## 📝 Contact Form Setup

The contact form currently shows an alert on submission. To make it functional, you can integrate with:

1. **EmailJS** (Free tier available):
   - Sign up at [EmailJS](https://www.emailjs.com)
   - Add your service and template IDs to `script.js`
   - Uncomment the EmailJS code in the form handler

2. **Formspree** (Free tier available):
   - Sign up at [Formspree](https://formspree.io)
   - Add `action="https://formspree.io/f/YOUR_FORM_ID"` to the form tag
   - Add `method="POST"` attribute

3. **Backend Integration**:
   - Create your own API endpoint
   - Update the form submission handler in `script.js`

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available for personal use.

## 🙏 Credits

- Font Awesome for icons
- Google Fonts for typography
- Design inspired by modern portfolio best practices

## 📞 Support

For questions or issues, please contact through the portfolio's contact form or via LinkedIn.

---

**Built with ❤️ for showcasing data science and full-stack development expertise**

