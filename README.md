# English Game - MDS Project

A comprehensive landing page for the English Game challenge, featuring a multi-section layout with navigation, schedule calendar, project cards, learning videos, and footer.

## Features

- **Responsive Navigation**: Sticky header with menu items and user profile (desktop only, mobile shows logo and actions)
- **Hero Section**: Welcome message with video player and wave border transition
- **Benefits Section**: Three-column grid showcasing program benefits (single column on mobile)
- **Schedule Calendar**: Interactive weekly schedule with color-coded events and horizontal scroll on mobile
- **Project Cards**: Deliverable tracking with upload functionality (stacked on mobile)
- **Learning Videos**: Video library with categorized content (single column on mobile)
- **Footer**: Multi-column footer with comprehensive links (responsive grid)
- **Wave Borders**: Smooth curved transitions between sections for visual flow

## Mobile Optimizations

- **Navigation**: Simplified mobile header with logo and essential actions only
- **Calendar**: Horizontal scrolling for weekly schedule with visual scroll hint
- **Typography**: Responsive font sizes that scale down on mobile
- **Spacing**: Reduced padding and margins for better mobile fit
- **Touch-friendly**: Larger tap targets and smooth scrolling
- **Single column layouts**: All grids collapse to single column on mobile

## Project Structure

```
├── assets/
│   ├── icons/          # SVG icons
│   ├── mds.png         # Logo
│   ├── video.png       # Video thumbnails
│   └── *.png           # Illustrations
├── styles/
│   ├── main.scss       # Main stylesheet (organized by sections)
│   ├── _variables.scss # Design tokens (colors, spacing)
│   ├── _typography.scss # Typography system
│   ├── _reset.scss     # CSS reset
│   └── main.css        # Compiled CSS
├── index.html          # Main HTML file
└── package.json        # Dependencies
```

## SCSS Architecture

The SCSS has been refactored for better readability and maintainability:

### Organization
- **Clear section comments**: Each major component is clearly labeled
- **Logical grouping**: Related styles are grouped together
- **Consistent naming**: BEM methodology for class names
- **Responsive design**: Mobile-first approach with media queries

### Key Sections
1. Base Styles
2. Navigation Header
3. Hero Section
4. Benefits Section
5. Schedule Section
6. Project Section
7. Learning Section
8. Footer

### Design System
- **Colors**: Primary (teal), Secondary (yellow), Neutral palette
- **Spacing**: 8px base unit system ($spacing-1 to $spacing-10)
- **Typography**: Inter font family with defined scales
- **Breakpoints**: Responsive at 640px, 768px, 968px, 1024px

## Development

### Install Dependencies
```bash
npm install
```

### Compile SCSS
```bash
npm run sass
```

### Watch Mode (auto-compile on save)
```bash
npm run sass:watch
```

### Local Server
```bash
npm run serve
```

## Design Highlights

- **Color-coded schedule**: Different event types use distinct colors for easy scanning
- **Card-based layout**: Consistent card design across sections
- **Smooth interactions**: Hover states and transitions throughout
- **Accessibility**: Semantic HTML and ARIA labels
- **Visual hierarchy**: Clear typography scale and spacing system

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support required
- Responsive design for mobile, tablet, and desktop

## Credits

Made by MyDigitalSchool
