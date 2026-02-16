# English Game - MDS Project

A pixel-perfect implementation of the English Game landing page using HTML and SCSS.

## Tech Stack

- HTML5
- SCSS (Sass)
- No JavaScript
- No CSS frameworks

## Design System

- **Font**: Inter (400, 600, 800)
- **Colors**: Primary (teal), Secondary (yellow/orange), Neutral
- **Spacing**: 8px grid system
- **Responsive**: Mobile-first approach

## Quick Start

### 1. Install Dependencies

```bash
npm install
```

### 2. Compile SCSS

Development mode (auto-compile on save):
```bash
npm run dev
```

Or single compilation:
```bash
npm run sass
```

### 3. View the Site

Simply open `index.html` in your browser, or use a local server:

```bash
# Using npx serve
npm run serve

# Or using Python
python -m http.server 8000

# Or using VS Code Live Server extension
```

## Project Structure

```
├── assets/
│   ├── icons/          # SVG icon components (TSX)
│   ├── mds.png         # Logo
│   ├── video.png       # Video thumbnail
│   └── *.png           # Illustrations
├── maquette/           # Design mockups
├── styles/
│   ├── _variables.scss # Colors, spacing, breakpoints
│   ├── _reset.scss     # CSS reset
│   ├── _typography.scss # Typography system
│   ├── main.scss       # Main styles & components
│   └── main.css        # Compiled CSS (generated)
├── index.html          # Main HTML file
├── package.json        # NPM configuration
└── README.md
```

## Features

- ✅ Pixel-perfect implementation based on maquette
- ✅ Fully responsive (desktop & mobile)
- ✅ Semantic HTML5
- ✅ BEM methodology for CSS
- ✅ 8px spacing grid system
- ✅ Modern SCSS with @use syntax
- ✅ Accessible markup

## Development

The SCSS is organized into modular files:

- `_variables.scss` - All design tokens (colors, spacing, breakpoints)
- `_reset.scss` - CSS reset for consistent cross-browser styling
- `_typography.scss` - Complete typography system
- `main.scss` - Component styles and layout

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Git Workflow

```bash
# Initialize git (if not already done)
git init

# Add files
git add .

# Commit
git commit -m "Initial commit: HTML/SCSS implementation"

# Add remote and push
git remote add origin <your-repo-url>
git push -u origin main
```
