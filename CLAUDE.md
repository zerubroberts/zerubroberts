# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This is a modern portfolio website for Zerub Roberts, showcasing 8+ years of experience as a Data Scientist and Senior Data Analyst.

## Development Setup
- Static HTML/CSS/JavaScript site
- No build process required
- Can be run locally by opening index.html or using a local server

## Project Structure
```
github-portfolio/
├── index.html          # Main HTML file with all content sections
├── styles.css          # Complete styling with animations and responsive design
├── script.js           # JavaScript for interactivity and animations
├── README.md           # Project documentation
└── CLAUDE.md          # This file
```

## Common Commands
- **Local development**: Open index.html in browser or run `python -m http.server 8000`
- **Deploy to GitHub Pages**: Push to GitHub and enable Pages in repository settings

## Architecture Notes
- **Design Philosophy**: Modern, dark-themed design with gradient accents
- **CSS Architecture**: Uses CSS custom properties for theming, Flexbox/Grid for layouts
- **JavaScript**: Vanilla JS for performance, includes typing animation, scroll effects, intersection observers
- **Responsive Design**: Mobile-first approach with breakpoint at 768px
- **Performance**: Optimized animations using transforms, lazy loading with Intersection Observer

## Key Features
- Animated hero section with typing effect
- Skills categorized by domain (BI, ML, Data Engineering, Cloud, Programming, Tools)
- Timeline-based experience section
- Project cards with hover effects
- Smooth scroll navigation with active link highlighting
- Mobile-responsive hamburger menu

## Customization Points
- Color scheme defined in CSS variables (`:root` in styles.css)
- Content sections in index.html are clearly labeled and easy to update
- Projects and experience can be added/modified in their respective sections