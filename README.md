# Personal Website for AI Researcher

A clean, minimalistic personal website designed for academic researchers and AI professionals.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Semantic HTML5**: Clean, well-structured code
- **Lightweight**: No heavy frameworks - just pure HTML and CSS
- **Professional Sections**:
  - About Me with photo placeholder
  - News & Updates
  - Work Experience
  - Publications
  - Blog/Writing
  - Contact Information

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize content**: Replace all placeholder text marked with `[brackets]`
3. **Add your photo**: Replace the photo placeholder with your actual photo
4. **Update links**: Add real links to your PDFs, arXiv papers, GitHub, social media, etc.

## Customizing Your Website

### Basic Information
- Update `[Your Name]` throughout the HTML
- Replace placeholder bio text with your actual information
- Update meta description in the `<head>` section

### Photo
Replace the photo placeholder div with an actual image:
```html
<div class="about-photo">
    <img src="path/to/your/photo.jpg" alt="Your Name" style="width: 100%; border-radius: 4px;">
</div>
```

### Publications
Add or remove publication entries in the Publications section. Each publication follows this format:
- Title
- Authors (bold your name)
- Venue and year
- Links (PDF, arXiv, Code, etc.)

### Colors and Styling
Edit `styles.css` to customize:
- Colors (currently minimalistic black on white)
- Fonts (currently using system fonts)
- Spacing and layout
- Link colors (currently blue: #007bff)

## File Structure

```
personal_website/
├── index.html       # Main HTML file
├── styles.css       # All styling
└── README.md        # This file
```

## Browser Compatibility

This website works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Mobile browsers

## Deployment

You can host this website on:
- **GitHub Pages**: Free and easy for academic sites
- **Netlify**: Simple drag-and-drop deployment
- **Your institution's server**: Check with your IT department
- **Custom domain**: Point any domain to your hosting service

## Tips for Academic Websites

1. **Keep it updated**: Regularly add new publications and news
2. **Professional email**: Use your institutional email
3. **Google Scholar**: Keep your profile linked and updated
4. **ArXiv links**: Always include preprint links when available
5. **Code availability**: Link to GitHub repos for reproducibility
6. **SEO**: Use descriptive titles and meta descriptions

## License

This template is free to use and modify for your personal academic website.
