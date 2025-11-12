# Hercule - Fitness App Promotional Website

A modern, responsive promotional website for the Hercule fitness tracking app.

## Features

- 🎨 Beautiful dark theme with orange accents matching the app design
- 📱 Fully responsive design for all devices
- ⚡ Fast and lightweight (pure HTML & CSS)
- 🖼️ Image gallery showcasing app features
- 🎯 Clear call-to-action sections
- 💫 Smooth animations and transitions

## Setup Instructions

### 1. Add Screenshots

Place your app screenshots in the `/images` folder with the following names:

- `calendar-screen.png` - Main calendar view
- `settings-screen.png` - Settings/labels page
- `log-exercise-screen.png` - Exercise logging screen
- `today-log-screen.png` - Today's workout log
- `label-selection-screen.png` - Label selection modal
- `workout-detail-screen.png` - Detailed workout view
- `add-label-screen.png` - Add new label screen

### 2. Open the Website

Simply open `index.html` in your browser to view the website locally.

### 3. Deploy

You can deploy this website to any static hosting service:

- **GitHub Pages**: Push to GitHub and enable Pages in repository settings
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your Git repository
- **Surge**: Run `surge` in the project directory

## File Structure

```
HerculeWebsite/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── images/            # App screenshots
│   ├── calendar-screen.png
│   ├── settings-screen.png
│   ├── log-exercise-screen.png
│   ├── today-log-screen.png
│   ├── label-selection-screen.png
│   ├── workout-detail-screen.png
│   └── add-label-screen.png
└── README.md          # This file
```

## Customization

### Colors
Edit the CSS variables in `styles.css` to match your brand:

```css
:root {
    --primary-orange: #FF5722;
    --dark-orange: #E64A19;
    --dark-bg: #0A0A0A;
    /* ... */
}
```

### Content
- Update text in `index.html` to match your app's features
- Modify download links in the Download section
- Add social media links in the footer

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2025 Hercule. All rights reserved.
