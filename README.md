# Professional Litterati Website

A modern, responsive professional litterati website showcasing intellectual journey, study areas, and research interests in a chosen field.

## 🎯 Overview

This website serves as a reflective learning portfolio, featuring a clean and sophisticated design optimized for writers, researchers, think tankers and academics. Built with modern web technologies and designed with classic aesthetics in mind, it emphasises motivations and experiences, over factual listing of personal details.

## ✨ Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile viewing
- **Modern Aesthetics**: Professional black and gray color scheme with subtle animations
- **Reflective Focus**: Sections emphasizing intellectual journey and research philosophy
- **Social Integration**: Direct links to professional social media profiles across 6 platforms
- **Performance Optimized**: Fast loading with smooth scrolling and hover effects
- **Professional Typography**: Clean, readable fonts suitable for academic content

## 🏗️ Structure

```
├── index.html          # Main website file
├── profile.jpg         # Profile picture (add your own)
└── README.md           # This file
```

## 📱 Sections

### Header
- Professional profile picture with circular frame
- Name and title
- Clean, minimalist black gradient design

### Navigation
- Smooth scrolling to sections
- Sticky navigation bar
- Responsive mobile menu
- Three main sections: Intellectual Journey, Study Areas, Research Interests

### Intellectual Journey
- Interdisciplinary/ Multidisciplianary approach 
- Formation and/or application of knowledge
- Domains of expertise

### Study Areas
- Comprehensive overview of research fields
- Subject of philosophical grounding 
- Emphasis on ethical standards

### Research Interests
- Continuous exploration approach to scholarship
- Focus on relevance, credibility and discoverability
- Research as static/dynamic 

### Connect (Footer)
- Social media links across 6 platforms:
  - LinkedIn (Professional networking)
  - GitHub (Code repositories and projects)
  - X (Academic discourse)
  - Facebook (Personal presence)
  - Instagram (Visual content)
  - Blog (Academic writing)
- Copyright notice

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Customize Content
Edit the following in `index.html`:

- Replace `[Your Name]` with your actual name
- Update all social media URLs in the footer
- Add your profile picture and update the image source
- Modify the three main content sections with your own text
- Update any icons if desired

### 3. Add Profile Picture
- Add your profile picture to the repository (recommended: `profile.jpg`)
- Update the image source in the HTML:
```html
<img src="profile.jpg" alt="Your Name" class="profile-image">
```
- Or use GitHub raw URL:
```html
<img src="https://raw.githubusercontent.com/username/repo/main/profile.jpg" alt="Your Name" class="profile-image">
```

### 4. Deploy
You can deploy this website using:
- **GitHub Pages**: Enable in repository settings → Pages → Source: main branch
- **Netlify**: Connect your GitHub repository for automatic deployments
- **Vercel**: Deploy directly from GitHub with continuous integration
- **Any web hosting service**: Upload the HTML file to your hosting provider

## 🎨 Customization

### Color Scheme
The website uses a professional black and gray monochromatic palette defined in CSS custom properties:
```css
:root {
    --primary-color: #1a1a1a;      /* Deep black */
    --secondary-color: #2d2d2d;    /* Dark gray */
    --accent-color: #4a4a4a;       /* Medium gray */
    --text-primary: #1a1a1a;       /* Text color */
    --text-secondary: #4a4a4a;     /* Secondary text */
    --bg-light: #f5f5f5;           /* Light background */
    --bg-white: #ffffff;           /* White background */
    --border-light: #e5e5e5;       /* Border color */
}
```

You can easily change these values to customize the color scheme while maintaining consistency throughout the site.

### Typography
- **Primary font**: Georgia serif for academic readability and professional appearance
- **Font size**: 1.15rem for body text with 1.8 line height for comfortable reading
- **Text alignment**: Justified for formal academic presentation

### Layout
- Flexbox-based responsive layout
- Card-based content sections with hover effects
- Smooth animations and transitions
- Maximum content width: 1000px for optimal readability

### Icons
Font Awesome icons are used throughout:
- **Intellectual Journey**: Route icon (`fa-route`)
- **Study Areas**: Book-open icon (`fa-book-open`)
- **Research Interests**: Lightbulb icon (`fa-lightbulb`)
- **Social media**: Platform-specific icons

You can change icons by replacing the Font Awesome class names in the HTML.

## 📝 Content Guidelines

### Writing Style
This website emphasizes a **reflective and philosophical tone** rather than a traditional factual format:
- Focus on intellectual journey and scholarly approach
- Emphasize values, philosophy, and methodology
- Use thoughtful, contemplative language
- Avoid bullet points in favor of prose paragraphs

### Profile Picture
- **Recommended size**: 400x400px minimum (displays at 180x180px)
- **Format**: JPG, PNG, or WebP
- **Style**: Professional headshot with neutral background
- **File size**: Keep under 500KB for optimal loading
- **Aspect ratio**: Square (1:1) for best results

### Social Media Links
Update the footer links with your actual profiles:

**Professional Platforms:**
- **LinkedIn**: `https://linkedin.com/in/yourprofile` - Academic and professional networking
- **GitHub**: `https://github.com/yourusername` - Code repositories, data science projects

**Academic & Social:**
- **X**: `https://x.com/yourhandle` - Thought leadership and academic discourse
- **Blog**: `https://yourblog.blogspot.com` or your custom domain - Long-form academic writing

**Personal:**
- **Facebook**: `https://facebook.com/yourprofile` - Professional and personal presence
- **Instagram**: `https://instagram.com/yourhandle` - Visual content and insights

## 🌐 Browser Support

Tested and optimized for:
- Chrome/Chromium (recommended)
- Firefox
- Safari (desktop and mobile)
- Microsoft Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

### Dependencies
- **Font Awesome 6.0.0**: For icons throughout the site
- **No JavaScript frameworks**: Pure vanilla JavaScript for interactions
- **No build process**: Single HTML file, ready to deploy

### Performance
- Minimal external dependencies
- Optimized animations using CSS transforms
- Smooth scrolling with `scroll-behavior: smooth`
- Intersection Observer for scroll-triggered animations

## 📄 License

This project is open source and available for personal and professional use. Feel free to fork, modify, and adapt for your own website.

## 🤝 Contributing

If you find bugs or have suggestions for improvements:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Submit a pull request

## 💡 Customization Ideas

Consider adding these sections if relevant to your work:
- **Publications**: List of published papers and articles
- **Teaching**: Courses taught and educational philosophy
- **CV/Resume**: Downloadable PDF of your curriculum vitae
- **Projects**: Specific research or data science projects
- **Blog Integration**: Embed recent blog posts
- **Contact Form**: Allow visitors to reach out directly

## 📞 Support

For questions or issues with this template:
- Open an issue in the GitHub repository
- Check existing issues for solutions
- Review the code comments for implementation details

## 🔗 Live Demo

[View Live Website](https://yourusername.github.io/your-repo-name)

*Replace with your actual GitHub Pages URL once deployed*

---

**Note**: Remember to update all placeholder content (`[Your Name]`, social media URLs, profile picture) with your actual information before publishing your website.

## 📚 Resources

- [Font Awesome Icons](https://fontawesome.com/icons)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
- [Web Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

---

*Built with ❤️ for the lettered community*
