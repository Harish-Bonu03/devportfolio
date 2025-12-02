# DevPortfolio - Quick Start Guide

## Option 1: EASIEST - Clone & Run (Recommended)

```bash
# Clone the repository
git clone https://github.com/Harish-Bonu03/devportfolio.git
cd devportfolio

# Install all dependencies
npm install

# Start the development server
npm start
```

Your portfolio will open at `http://localhost:3000` automatically!

---

## Option 2: Manual Setup with All Files

### Step 1: Create React App
```bash
npx create-react-app devportfolio
cd devportfolio
```

### Step 2: Install Dependencies
```bash
npm install react-router-dom react-icons
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### Step 3: Replace Files
Copy ALL files from this GitHub repo into your project:
- `package.json` - Dependencies
- `tailwind.config.js` - Tailwind CSS configuration
- `postcss.config.js` - PostCSS configuration
- `public/index.html` - HTML template
- `src/index.css` - Global styles
- `src/index.js` - Entry point
- `src/App.jsx` - Main app component
- `src/components/Navbar.jsx` - Navigation
- `src/components/Hero.jsx` - Hero section
- `src/components/About.jsx` - About section
- `src/components/Skills.jsx` - Skills section
- `src/components/Projects.jsx` - Projects page
- `src/components/Contact.jsx` - Contact section
- `src/components/Footer.jsx` - Footer

### Step 4: Run
```bash
npm start
```

---

## Download as ZIP

### From GitHub:
1. Click the green `<> Code` button
2. Click `Download ZIP`
3. Extract the ZIP file
4. Run: `npm install && npm start`

### Create ZIP from Cloned Repo:
```bash
# Windows
Compress-Archive -Path devportfolio -DestinationPath devportfolio.zip

# Mac/Linux
zip -r devportfolio.zip devportfolio/
```

---

## Features
✅ React 18 with Hooks
✅ React Router for multi-page navigation
✅ Tailwind CSS for styling
✅ Dark/Light mode toggle
✅ Fully responsive design
✅ Project showcase with filtering
✅ Search functionality
✅ Contact form
✅ Smooth animations
✅ Production-ready code

---

## Build for Production
```bash
npm run build
```

This creates an optimized build in the `build/` folder.

---

## Deploy Options

### Vercel (Recommended - Free)
```bash
npm install -g vercel
vercel
```

### Netlify
1. Run `npm run build`
2. Drag & drop the `build` folder to https://netlify.com

### GitHub Pages
```bash
npm run build
# Push to gh-pages branch
```

---

## Customization

### Edit Personal Information
- Update text in each component file (src/components/)
- Replace project data in `Projects.jsx`
- Update contact links in `Contact.jsx`
- Modify skills in `Skills.jsx`

### Change Colors
Edit `tailwind.config.js`:
```js
theme: {
  extend: {
    colors: {
      primary: '#00d4ff', // Change to your color
      dark: '#0a0e27',
      darkSecondary: '#1a1f3a',
    },
  },
}
```

---

## Support
For issues or questions, refer to the component files or create an issue on GitHub.

Happy coding! 🚀
