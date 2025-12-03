# eBook Reader & Library Manager

A modern web-based eBook reader with library management and atmospheric music support.

![Screenshot](screenshot.png)

## Features

- 📚 **Library Management** - Upload and organize your eBook collection
- 📖 **Clean Reader Interface** - Distraction-free reading experience
- 🎵 **Atmospheric Music** - Background music player for immersive reading
- 🎨 **Customizable Themes** - Light, Sepia, and Dark modes
- 💾 **Progress Tracking** - Automatically saves your reading progress
- ⚙️ **Personalization** - Adjustable font size and volume controls

## Tech Stack

- React 18
- Vite
- Tailwind CSS
- Lucide React (icons)
- localStorage for data persistence

## Installation

\`\`\`bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/ebook-reader-app.git
cd ebook-reader-app

# Install dependencies
npm install

# Run development server
npm run dev
\`\`\`

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage

1. **Add Books**: Upload .txt files from the Library view
2. **Add Music**: Upload MP3/WAV files for background atmosphere
3. **Start Reading**: Click on any book to open the reader
4. **Customize**: Adjust settings for font size, theme, and volume

## Building for Production

\`\`\`bash
npm run build
npm run preview
\`\`\`

## Supported File Formats

- **Books**: .txt, .epub
- **Music**: .mp3, .wav, .ogg

## License

MIT License - feel free to use for personal or commercial projects

## Contributing

Pull requests are welcome! For major changes, please open an issue first.
\`\`\`

Add and commit the README:
```bash
git add README.md
git commit -m "Add README"
git push
```

---

## Deploy to GitHub Pages (Optional)

Host your app for free on GitHub Pages:

### Step 1: Install gh-pages
```bash
npm install --save-dev gh-pages
```

### Step 2: Update package.json

Add these lines to `package.json`:
```json
{
  "homepage": "https://YOUR-USERNAME.github.io/ebook-reader-app",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  }
}
```

### Step 3: Update vite.config.js
```javascript
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

export default defineConfig({
  plugins: [react()],
  base: '/ebook-reader-app/'  // Add this line
})
```

### Step 4: Deploy
```bash
npm run deploy
```

Your app will be live at: `https://YOUR-USERNAME.github.io/ebook-reader-app`

Wait a few minutes, then enable GitHub Pages:
1. Go to repository → Settings → Pages
2. Source should be set to "gh-pages" branch
3. Click Save

---

## Useful Git Commands
```bash
# Check status
git status

# See changes
git diff

# Add specific files
git add src/App.jsx

# Commit changes
git commit -m "Update reading interface"

# Push to GitHub
git push

# Create a new branch
git checkout -b feature-name

# Switch back to main
git checkout main

# Pull latest changes
git pull
```

---

## .gitignore File

Make sure you have this `.gitignore` in your project root:
