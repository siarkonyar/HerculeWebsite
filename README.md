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

### 1. Screenshots

The gallery is wired to the latest uploaded screenshots in `assets/images`:

- `dashboard-screen.png` - Main dashboard
- `profile-screen.png` - Profile and label overview
- `calendar-screen.png` - Calendar view
- `log-exercise-screen.png` - Exercise search and logging screen
- `edit-exercise-screen.png` - Edit exercise screen
- `share-day-screen.png` - Shareable workout summary image

### App Store

Hercule is published on the App Store: https://apps.apple.com/gb/app/hercule-fitness-tracker/id6755726344

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
│   ├── dashboard-screen.png
│   ├── profile-screen.png
│   ├── calendar-screen.png
│   ├── log-exercise-screen.png
│   ├── edit-exercise-screen.png
│   ├── share-day-screen.png
│   └── IMG_0368.PNG
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
