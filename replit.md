# Shravana Kumar R - Portfolio

## Overview

This is a personal portfolio website for Shravana Kumar R, a Computer Science Engineering student and software developer. The project is a static website built with vanilla HTML, CSS, and JavaScript, designed to showcase professional experience, skills, and projects. The site uses a Python HTTP server for local development and deployment.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Vanilla HTML5, CSS3, and JavaScript (ES6+)
- **Design Pattern**: Single Page Application (SPA) with section-based navigation
- **Styling Approach**: CSS Custom Properties (CSS Variables) for consistent theming
- **Responsive Design**: Mobile-first approach with hamburger menu for mobile navigation
- **Typography**: Inter font family for modern, professional appearance
- **Icons**: Font Awesome 6.4.0 for consistent iconography

### Backend Architecture
- **Server**: Python's built-in HTTP server (`http.server` module)
- **Port**: 5000 (configured for both development and deployment)
- **Architecture**: Static file serving with no backend logic or database

## Key Components

### Navigation System
- Responsive navigation bar with scroll effects
- Mobile hamburger menu implementation
- Active link highlighting based on scroll position
- Smooth scrolling between sections

### User Interface Elements
- Professional avatar created as custom SVG
- Animated skill bars and counters
- Contact form with client-side validation
- Scroll-triggered animations and effects

### Styling System
- CSS Custom Properties for maintainable theming
- Gradient backgrounds and modern visual effects
- Consistent spacing and typography scale
- Box shadow utilities for depth

## Data Flow

### Client-Side Interactions
1. **Navigation**: User clicks nav links → JavaScript smooth scrolls to sections
2. **Mobile Menu**: User clicks hamburger → JavaScript toggles menu visibility
3. **Scroll Effects**: User scrolls → JavaScript updates navbar state and active links
4. **Animations**: Page load/scroll → JavaScript triggers CSS animations
5. **Contact Form**: User submits form → JavaScript validates and handles submission

### Static Asset Delivery
1. User requests page → Python HTTP server serves `index.html`
2. Browser requests assets → Server serves CSS, JS, and SVG files
3. External resources loaded from CDNs (fonts, icons)

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter and JetBrains Mono font families
- **Font Awesome**: Version 6.4.0 for icons

### Development Dependencies
- **Python 3.11**: For HTTP server functionality
- **Node.js 20**: Available in environment (potential future use)

## Deployment Strategy

### Development Environment
- **Platform**: Replit with Nix package management
- **Runtime**: Python HTTP server on port 5000
- **Auto-reload**: Manual refresh required for changes

### Production Deployment
- **Method**: Python HTTP server deployment
- **Command**: `python3 -m http.server 5000`
- **Static Hosting**: All assets served directly from file system
- **No Build Process**: Direct file serving without compilation

### Deployment Considerations
- Lightweight deployment suitable for static hosting platforms
- Can be easily migrated to Nginx, Apache, or cloud storage
- No server-side processing or database requirements

## Changelog

```
Changelog:
- June 23, 2025. Initial setup
```

## User Preferences

```
Preferred communication style: Simple, everyday language.
```