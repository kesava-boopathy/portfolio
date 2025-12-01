# Portfolio Website

A clean, simple, and modern portfolio website built with HTML, Tailwind CSS, and vanilla JavaScript.

## Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation** - Smooth scrolling between sections
- **Mobile Menu** - Hamburger menu for mobile devices
- **Modern Styling** - Built with Tailwind CSS for a professional look
- **No Dependencies** - Pure HTML, CSS, and JavaScript (Tailwind via CDN)

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Custom CSS styles
├── js/
│   └── script.js       # JavaScript functionality
├── assets/             # For future images, icons, etc.
└── README.md           # This file
```

## Sections Included

1. **Navigation Bar** - Fixed header with links to all sections
2. **Hero Section** - Eye-catching introduction with call-to-action buttons
3. **Projects Section** - Showcase of 4 project cards with descriptions and technologies
4. **Skills Section** - Organized list of frontend, backend, and tools/other skills
5. **Contact Section** - Quick links to email, LinkedIn, and GitHub

## How to Use

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Python 2
   python -m SimpleHTTPServer 8000

   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## Customization

### Update Your Information

- Replace "Your Name" with your actual name in `index.html`
- Update project titles, descriptions, and links in the Projects section
- Modify skills list based on your expertise
- Update contact links (email, LinkedIn, GitHub) in the Contact section

### Add Your Projects

Edit the project cards in the Projects section to reflect your actual work:
- Update project titles and descriptions
- Add relevant technology tags
- Link to GitHub repositories or project demos

### Change Colors

The portfolio uses Tailwind CSS with blue accents. To change the color scheme:
- Replace `blue-600` and `blue-700` with other Tailwind colors (e.g., `purple-600`, `green-600`)
- Modify the gradient in the hero section if desired

### Add Images

1. Save images to the `assets/` folder
2. Reference them in HTML:
   ```html
   <img src="assets/project-image.jpg" alt="Project description">
   ```

## Deployment

### GitHub Pages (Recommended)

1. Create a GitHub repository named `yourusername.github.io`
2. Push your portfolio files to the `main` branch
3. Your site will be live at `https://yourusername.github.io`

### Other Hosting Options

- **Netlify** - Connect your GitHub repo for automatic deployments
- **Vercel** - Zero-config deployment for static sites
- **Firebase Hosting** - Google's hosting solution
- **Traditional Web Hosting** - Any provider that serves static files

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## Performance

- Lightweight - Uses CDN for Tailwind CSS, no build tools needed
- Fast loading - No external dependencies to download
- SEO friendly - Semantic HTML structure

## License

Feel free to use this template for your own portfolio. No license restrictions.

## Need Help?

- Check Tailwind CSS documentation: https://tailwindcss.com
- JavaScript learning resources: https://developer.mozilla.org/en-US/docs/Web/JavaScript
- HTML guide: https://developer.mozilla.org/en-US/docs/Web/HTML

---

**Happy coding and best of luck with your portfolio!** 🚀
