# Valentine's Day Website 💕

A romantic Valentine's Day website with interactive elements and music.

## Features

- 💝 Interactive "Will you be my Valentine?" button game
- 🎵 Spotify-style music player (bottom-right corner)
- 💕 Beautiful animated background with hearts
- 🧸 Teddy bear stickers
- 📅 Memory timeline
- 💌 Love letter section
- ✨ Confetti celebration effects

## How to Deploy

### Option 1: GitHub Pages

1. Create a new repository on GitHub
2. Upload all files from this zip
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and root folder
6. Click Save
7. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify

1. Go to [Netlify](https://www.netlify.com/)
2. Drag and drop this folder or zip file
3. Your site will be live instantly!

### Option 3: Vercel

1. Go to [Vercel](https://vercel.com/)
2. Import the project
3. Deploy

### Option 4: Any Web Host

Simply upload the `index.html` file to your web hosting via FTP or file manager.

## Customization

### Change the Music

Replace the audio file URLs in the `<audio>` tag (around line 11):
```html
<source src="YOUR_MUSIC_FILE.mp3" type="audio/mpeg">
```

### Change Names/Text

Edit the text content directly in the HTML file:
- Hero section (line ~1249)
- Love letter (line ~1270)
- Timeline events (line ~1400)

### Adjust Spotify Player Position

Modify the `.spotify-player` CSS (around line 769):
```css
bottom: 20px;  /* Distance from bottom */
right: 20px;   /* Distance from right */
```

## Browser Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

## Notes

- Music autoplay may be blocked by browsers - users can click play button
- Best viewed on desktop or tablet
- Mobile responsive design included

## Credits

Created with love ❤️

---

Made for Raxuu 💕
