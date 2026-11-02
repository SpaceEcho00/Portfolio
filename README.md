# Professional Portfolio Website

A modern, responsive, and professional portfolio website built with HTML5, CSS3, and JavaScript.

## Features

- **Responsive Design** - Works on all devices (mobile, tablet, desktop)
- **Smooth Scrolling** - Seamless navigation between sections
- **Mobile Menu** - Hamburger menu for mobile devices
- **Interactive Projects** - Hover effects on project cards
- **Contact Form** - Functional contact form with submission feedback
- **Scroll Animations** - Elements animate into view as you scroll
- **Active Navigation** - Highlights current section in the nav
- **Modern Design** - Clean, professional aesthetic with CSS variables

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── script.js       # JavaScript interactivity
└── README.md       # This file
```

## Getting Started

### Option 1: Open Directly
Simply open `index.html` in any web browser to view your portfolio.

### Option 2: Use a Local Server (Recommended)
For the best experience, use a local server:

**Using Python:**
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`

**Using Node.js (http-server):**
```bash
npx http-server
```

**Using VS Code Live Server:**
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Customization Guide

### 1. Update Personal Information
Edit `index.html` and replace the following:
- **Name**: Search for "Your Name" and replace with your name
- **Email**: Replace `your.email@example.com` with your email
- **Location**: Replace "Your City, Country" with your location
- **Phone**: Replace `+1 (555) 123-4567` with your phone number
- **Website**: Replace `www.yourportfolio.com` with your website

### 2. Add Your Profile Photo
Replace the `src` attribute in the hero section:
```html
<img src="images/your-photo.jpg" alt="Profile" class="profile-img">
```
Place your photo in an `images/` folder and update the path.

### 3. Update Projects
Edit the project cards in `index.html`:
- Replace placeholder images with your actual project screenshots
- Update project titles, descriptions, and technologies
- Add your GitHub and live demo links

### 4. Update Skills
Modify the skill lists in the Skills section to match your expertise.

### 5. Customize Colors
Edit CSS variables in `style.css`:
- Primary color: `#111827` (dark gray/black)
- Accent color: `#2563eb` (blue)
- Background: `#f9fafb` (light gray)

### 6. Social Media Links
Replace the `#` href values in social links with your actual profile URLs:
- GitHub
- LinkedIn
- Twitter
- Instagram

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

You can deploy this static website for free on:
- **GitHub Pages**
- **Netlify** (drag and drop)
- **Vercel**
- **Firebase Hosting**

## License

MIT License - feel free to use this for your own portfolio!

## Contact

Have questions? Feel free to reach out via the contact form on the website or email me directly.