# Valentine's Day Multi-Page Experience 💝

A romantic three-page interactive website with a Valentine's proposal, puzzle game, and celebration page.

## Pages Overview

### 1. **index.html** - Valentine's Proposal
- Asks "Will you be my Valentine?"
- Interactive "No" button that moves away
- Clicking "Yes" triggers confetti and redirects to the puzzle

### 2. **puzzle.html** - 5x5 Sliding Puzzle
- Upload your own image or use the default romantic design
- 5x5 grid sliding puzzle game
- Move counter and shuffle/reset controls
- Solving the puzzle leads to the final page

### 3. **final.html** - Celebration Page
- Congratulations message
- Floating hearts animation
- Confetti celebrations
- Option to start over

## Setup Instructions

### For GitHub Pages Deployment

1. **Create the repository structure:**
   ```
   your-repo/
   ├── index.html
   ├── puzzle.html
   └── final.html
   ```

2. **Push to GitHub:**
   ```bash
   git add index.html puzzle.html final.html
   git commit -m "Add Valentine's multi-page experience"
   git push origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at: `https://yourusername.github.io/repo-name/`

### Customizing the Puzzle Image

There are two ways to add your custom image:

#### Option 1: Upload via the webpage
- When you load puzzle.html, click the "📷 Upload Your Image" button
- Select any image from your device
- The puzzle will automatically use your image

#### Option 2: Replace the default image in code
In `puzzle.html`, find this line (around line 267):
```javascript
const defaultImage = 'data:image/svg+xml,...';
```

Replace it with a path to your image:
```javascript
const defaultImage = 'your-image.jpg';
```

Then add your image file to the repository:
```bash
git add your-image.jpg
git commit -m "Add custom puzzle image"
git push origin main
```

## Features

### Interactive Elements
- ✨ Animated gradient backgrounds
- 🎊 Confetti celebrations
- 🔊 Sound effects (hover and click)
- 💕 Floating hearts
- 🎯 Sliding puzzle game mechanics

### Responsive Design
- Works on desktop, tablet, and mobile
- Touch-friendly controls
- Adaptive layouts

### Puzzle Game Features
- 5x5 grid (24 tiles + 1 empty space)
- Move counter
- Shuffle and reset buttons
- Hint system
- Win detection
- Custom image upload

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## Tips for Best Experience

1. **Image Selection**: Choose a square image for the puzzle (500x500px or larger)
2. **Image Content**: Pick images with distinct features so puzzle pieces are recognizable
3. **Colors**: Images with good contrast work best for the puzzle

## Troubleshooting

**Puzzle not shuffling?**
- The puzzle auto-shuffles 1 second after page load
- You can manually click "🔀 Shuffle" button

**Image not loading?**
- Make sure the image file is in the same directory as the HTML files
- Check the file path in the code
- Try uploading via the webpage instead

**Page navigation not working?**
- Ensure all three HTML files are in the same directory
- Check that file names match exactly (case-sensitive)

## Personalization Ideas

You can customize:
- Change "Aarathi" to any name in `index.html` and `final.html`
- Modify the final love message in `final.html`
- Adjust colors in the CSS gradient
- Change emojis throughout
- Add more puzzle difficulty levels

## License

Feel free to use and modify for personal romantic purposes! 💕

---

Made with ❤️ for a special Valentine's Day
