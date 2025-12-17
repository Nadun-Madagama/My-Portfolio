# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean, minimalist design with dark mode support and smooth animations.

## Features

- ✨ Modern, minimalist UI design
- 🌙 Dark mode toggle with persistent theme preference
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth scroll animations
- 🎯 Interactive project cards with hover effects
- 📧 Contact form with validation
- 🚀 Smooth scrolling navigation
- 💼 Professional sections: Hero, About, Skills, Projects, Contact

## File Structure

```
Project 08/
├── index.html          # Main HTML file
├── style.css           # All styles and responsive design
├── script.js           # JavaScript functionality
├── assets/             # Images and icons folder
└── README.md           # This file
```

## How to Run Locally

### Method 1: Direct Browser Opening (Simplest)

1. **Navigate to the project folder** in your file explorer
2. **Double-click** on `index.html` to open it in your default browser
3. The website will load and you can interact with it immediately

### Method 2: Using a Local Server (Recommended)

For the best experience, especially when testing features like form submissions or API calls, use a local server:

#### Using Python (if installed):

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open your browser and navigate to: `http://localhost:8000`

#### Using Node.js (if installed):

```bash
# Install http-server globally (one-time setup)
npm install -g http-server

# Run the server
http-server -p 8000
```

Then open your browser and navigate to: `http://localhost:8000`

#### Using VS Code Live Server Extension:

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. The website will automatically open in your browser

## Customization Guide

### Personal Information

1. **Name and Title**: Edit the hero section in `index.html` (lines ~40-45)
2. **About Me**: Update the bio text in the About section (lines ~70-85)
3. **Skills**: Modify skill items in the Skills section (lines ~95-140)
4. **Projects**: Add/edit project cards in the Projects section (lines ~145-220)
5. **Contact Info**: Update email, phone, and location in Contact section (lines ~225-240)

### Colors

The color scheme is managed through CSS variables in `style.css`. To change colors:

1. Open `style.css`
2. Find the `:root` section (around line 5)
3. Modify the color values:
   - `--primary-color`: Main brand color (default: blue)
   - `--text-primary`: Main text color
   - `--background-color`: Page background
   - And other variables as needed

### Images

1. Add your profile photo to the `assets/` folder
2. Update the image placeholder in `index.html` (About section) with:
   ```html
   <img src="assets/your-photo.jpg" alt="Your Name">
   ```
3. Add project images to `assets/` and update project card images similarly

### Social Media Links

Update the social media links in:
- Hero section (line ~50)
- Footer section (line ~250)

Replace the placeholder URLs with your actual profiles.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Google Fonts**: Poppins font family

## Notes

- The contact form currently shows an alert on submission. To make it functional, you'll need to integrate it with a backend service or email service like Formspree, EmailJS, or your own API.
- All images use placeholder divs. Replace them with actual images for production use.
- The dark mode preference is saved in localStorage and persists across sessions.

## License

This project is open source and available for personal and commercial use.

---

**Enjoy building your portfolio! 🚀**

