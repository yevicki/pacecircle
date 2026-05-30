# PaceCircle Landing Page

A modern, dark-themed landing page for [PaceCircle](https://yevicki.github.io/pacecircle/), the fitness calendar app for coordinating group workouts and social circles.

## Overview

This is a single-file HTML application showcasing PaceCircle's core features and use cases. It's built with semantic HTML, vanilla CSS, and plain JavaScript for fast load times and zero dependencies.

## Files & Structure

```
index.html
├── Head (meta, fonts, CSS)
├── Body
│   ├── Navigation (fixed, frosted glass)
│   ├── Background orbs & noise texture
│   ├── Hero section
│   ├── Features section
│   ├── Use cases grid
│   ├── Newsletter CTA
│   └── Footer
└── Script (reveal animations, form handling, mobile nav)
```

## Features

- **Responsive design** that adapts from mobile to desktop
- **Dark mode aesthetic** with a gold accent color palette (`#E8B84B` primary)
- **Smooth scroll animations** using the Intersection Observer API
- **Custom calendar widget** showing multi-circle scheduling
- **Newsletter signup form** (ready to integrate with Resend, Mailchimp, or Google Apps Script)
- **Lightweight** – no build tools or external JavaScript libraries required

## Design Highlights

### Color Palette
- **Background**: `#0E0F14` (deep navy)
- **Text**: `#E0E3F0` (light gray)
- **Accent**: `#E8B84B` (gold)
- **Accent dim**: `rgba(232,184,75,0.12)` (background tint)
- **Secondary colors**: Neon green (`#39FF14`), cyan (`#00D9FF`), red (`#FF4D4D`)

### Typography
- **Primary**: Sora (sans-serif, 300–800 weights)
- **Monospace**: DM Mono (code and labels)
- **Loaded from**: Google Fonts

### Effects
- **Background texture**: Subtle SVG noise overlay
- **Atmosphere**: Three animated gradient orbs (gold, cyan, green) that drift slowly
- **Animations**: Scroll-triggered fade-in reveals with staggered timing
- **Navigation**: Frosted glass backdrop with blur effect

## Accessibility

- Semantic HTML structure (`<nav>`, `<section>`, `<footer>`)
- Color contrast meets WCAG AA standards
- Links have visible hover states
- Form inputs have proper labels

## License

Built for PaceCircle. See footer for copyright.

**Landing page updated**: May 2026  
**PaceCircle launch**: September 2026
