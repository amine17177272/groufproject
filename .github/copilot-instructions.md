# AI Agent Instructions for School Project Platform

## Project Overview
This is a web platform for student project submission, focusing on subjects like English, Arabic, and French. The platform is built with HTML and CSS, emphasizing responsive design and interactive elements.

## Repository Structure
```
/
├── index.html          # Main entry point with term-based navigation
├── css/               
│   ├── styles.css      # Main styles for index page
│   └── about-styles.css # Shared styles for content pages
├── assets/
│   ├── audio/         # Sound effects for interaction
│   ├── imgs & files/  # Project resources and presentations
│   └── vids/         # Video content
└── *.html             # Subject-specific content pages
```

## Key Design Patterns

### Page Structure
- Each content page (`about.html`, `contact.html`, etc.) follows a consistent structure:
  - Subject title
  - Embedded YouTube video
  - Author information footer

### CSS Conventions
- Purple (`#800080`) and black color scheme throughout
- Responsive design breakpoints at 768px for mobile devices
- Interactive elements use consistent hover animations
- Wave animation in `styles.css` for decorative footer

### Interactive Features
- Audio feedback on navigation hover (see `index.html` for implementation)
- Scale animations on interactive elements
- Responsive iframe sizing for embedded content

## Development Guidelines
1. Maintain mobile-first responsive design approach
2. Keep styling consistent using `about-styles.css` for content pages
3. Ensure accessibility with proper meta tags and semantic HTML
4. Test embedded content rendering on different screen sizes

## Common Operations
- Adding a new subject page:
  1. Copy structure from existing content page (e.g., `about.html`)
  2. Link stylesheet: `<link rel="stylesheet" href="./css/about-styles.css" />`
  3. Add navigation link in `index.html` under appropriate term section

## Notes
- Live demo available at: https://amine17177272.github.io/groufproject/
- Project is primarily static HTML/CSS without build tools or dependencies
- Font: 'Caveat' from Google Fonts used for headings