# diStreaming

A modern landing page for a movie trailer streaming platform. Clean design, smooth animations, and fully responsive.

**Live Demo:** [distreaming.github.io](https://sayyeone.github.io/distreaming)

## What's This?

diStreaming is a landing page for a free movie trailer streaming service. It showcases the platform's key features like worldwide content access, thousands of titles, and device-friendly streaming. Perfect for presenting your streaming service idea or movie-related startup.

## Tech Stack

Just the basics:
- HTML5 & CSS3
- Custom CSS animations
- Responsive design
- Pure vanilla - no frameworks needed

No complicated setup. Just download and open the HTML file.

## Getting Started

**Option 1: Just open it**

Clone the repo and double-click `index.html`. Done.
```bash
git clone https://github.com/yourusername/distreaming.git
cd distreaming
# Double click index.html
```

**Option 2: Use Live Server (recommended)**

If you're using VS Code:
1. Install the Live Server extension
2. Right click `index.html` → Open with Live Server
3. Browser opens automatically at `localhost:5500`

**Option 3: Python server**
```bash
python -m http.server 8000
# Open http://localhost:8000 in your browser
```

## Deploying to GitHub Pages

Want to put this online? Super easy.

1. Push your code to GitHub:
```bash
git add .
git commit -m "initial commit"
git push origin main
```

2. Go to your repo → Settings → Pages

3. Under "Source", select `main` branch and `/ (root)` folder

4. Hit Save and wait a minute

Your site will be live at `https://yourusername.github.io/distreaming`

### Custom Domain

Got your own domain? Create a `CNAME` file with your domain:
```
yourdomain.com
```

Then configure DNS with your domain provider. Wait 24 hours for propagation.

## Customizing

Everything's straightforward to customize.

**Change colors:**
Edit the CSS variables in `style.css`:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
}
```

**Update images:**
Replace files in the `img/` folder with your own images. Keep the same filenames or update the HTML `src` attributes.

**Modify text:**
Edit directly in `index.html`. All content is clearly structured with semantic HTML.

**Add sections:**
Copy any existing section structure and modify the content to match your needs.

## Project Structure
```
distreaming/
├── index.html          # Main HTML file
├── style.css           # All styling
├── img/
│   ├── Image.png       # Hero background
│   └── group (1).png   # Content image
├── README.md          # You're reading it
└── screenshot.png     # Add your screenshot
```

Simple structure - easy to understand and modify.

## Features

- **Hero Section** - Eye-catching hero with overlay and CTA button
- **Features Grid** - Showcase 4 key features with icons
- **Content Preview** - New content section with image and CTA
- **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Clean Code** - Well-structured HTML and organized CSS
- **Fast Loading** - Optimized images and minimal code

## Browser Support

Works on all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Credits

- Design inspired by modern streaming platforms
- Icons: Emoji (built-in)
- Images: Add your own or use placeholder images

---

Made with ❤️ by [Sayyeone](https://github.com/sayyeone)

Questions? Open an issue or reach out!
