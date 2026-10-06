# Hercule - Fitness App Promotional Website

A modern, responsive promotional website for the Hercule fitness tracking app.

## Features

- 🎨 Beautiful dark theme with orange accents matching the app design
- 📱 Fully responsive design for all devices
- ⚡ Fast and lightweight (pure HTML & CSS)
- 🖼️ Image gallery showcasing app features
- 📋 Workout-program feature card and updated program screenshots
- ✨ AI gym coach as the main hero, with a visible Beta badge and program creation workflow
- 🎯 Clear call-to-action sections
- 💫 Smooth scrolling and hover transitions that respect reduced-motion preferences

The original website design is retained. The AI coach leads the page, followed by feature cards for programs and workout tracking, the screenshot gallery, and downloads. The opening section has no Beta badge. The website states that all features are free during beta and no subscription is required. Update this copy when availability changes.

## Setup Instructions

### 1. Screenshots

The gallery is wired to the latest uploaded screenshots in `assets/images`:

- `dashboard-screen.png` - Main dashboard with today's workout program
- `programs-screen.png` - Saved programs and program selection
- `ai-coach-screen.png` - AI coach beta chat with a proposed workout program
- `profile-screen.png` - Profile and label overview
- `calendar-screen.png` - Calendar view
- `log-exercise-screen.png` - Exercise search and logging screen
- `edit-exercise-screen.png` - Edit exercise screen
- `share-day-screen.png` - Shareable workout summary image

### App Store

Hercule is published on the App Store: https://apps.apple.com/gb/app/hercule-fitness-tracker/id6755726344

### 2. Open the Website

Simply open `index.html` in your browser to view the website locally.

For a local HTTP preview, run `python3 -m http.server 8766 --bind 127.0.0.1` from this directory and open `http://127.0.0.1:8766`.

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
├── assets/
│   ├── images/        # App screenshots, including programs and AI coach
│   ├── logo/          # Hercule SVG logo
│   └── buttons/       # App Store and Google Play download badges
└── README.md          # This file
```

## Customization

### Colors
CSS variables in `styles.css` retain the original website palette:

```css
:root {
    --primary-orange: #FF5722;
    --dark-bg: #0A0A0A;
    --card-bg: #1A1A1A;
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
