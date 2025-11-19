# Friendsgiving 2025 Invitation

A beautiful, interactive Friendsgiving invitation for November 22, 2025 at Angie's and Herberth's place in Katy, TX.

## Event Details

**Date & Time**: Saturday, November 22 at 7:00 p.m.
(Yes, 7 sharp… or you know, Latino-time if you must.)

**Location**: 2443 Grey Reef Drive, Katy, TX 77449
At Angie's and Herberth's (Aka la casa donde siempre hay comida.)

## Features

- 🎨 Elegant vintage Thanksgiving design
- 🎵 Interactive music player with "Hasta Las 15" background music
- ✨ Smooth animations and hover effects
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎭 Bilingual content (English & Spanish)
- ⚡ Fast loading (no frameworks)

## Sections

- **Schedule**: Event timing and details
- **What to Bring**: Potluck guidelines
- **Good Vibes Only**: Kids welcome, dress code info
- **Quick Notes**: Helpful reminders and tips

## Technology

- HTML5
- CSS3 (animations, gradients, flexbox)
- Vanilla JavaScript (music player)
- Font Awesome icons
- Google Fonts (Playfair Display & Montserrat)

## Deployment

This site is deployed on **Vercel** and automatically updates when changes are pushed to GitHub.

### Deploy Your Own
1. Fork or clone this repository
2. Connect to Vercel
3. Deploy with one click

See [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md) for detailed instructions.

## Customization

### Change the Music
Replace `hasta-las-15.mp3` with your song and update the audio source in `index.html`.

### Change Event Details
Edit the following in `index.html`:
- Title and date in the header
- Location details
- Schedule information
- What to bring details
- Quick notes

### Change Colors
Edit the CSS variables in the `<style>` section:
```css
:root {
    --dark-brown: #3D322C;
    --olive-green: #5E6C40;
    /* ... etc */
}
```

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Testing

### Local Testing
```bash
# Option 1: Open directly
open index.html

# Option 2: Use Python server
python3 -m http.server 8000
# Visit http://localhost:8000
```

## Credits

- Design inspired by luxury vintage Thanksgiving aesthetic
- Icons from Font Awesome
- Fonts from Google Fonts
- Hosted on Vercel

---

¡Nos vemos allá! 🍂🎉
