# Webly's Bakery

This is a fully optimized solution to the Bitdegree Front-end web development course, featuring modern web development best practices.

## Overview

"Here comes the fun part! Mr. and Mrs. Webly have been running a local bakery called Webly's Bakery for an odd 25-30 years.

Their nephew made a website for them in 1995 which is not responsive. This is a problem for them since nobody can use their website easily. This means when they navigate their website, users have trouble finding their phone number or location easily. Neither can users see their bakery items because the images are either too big or small.

All in all their website is a mess and needs to be redone. They've hired a professional this time which is you and not their nephew. Your job is to make a responsive website for Webly's Bakery."

### The Challenge

- Plan the layout of the website
- The website must be responsive which means it must look great on phones, tablets, laptops and PCs
- Decide on the design of the website
- Code the website
- Use Responsive Design Mode to test the website on different screen sizes

### Links

- Live Site URL: https://dutatiberiu.github.io/Webly-s-Bakery/

## Built With

- **Semantic HTML5 markup** - Proper use of section, nav, footer, and heading hierarchy
- **CSS Custom Properties (Variables)** - For consistent theming and easy maintenance
- **Flexbox** - For flexible layouts
- **CSS Grid** - For complex product gallery layouts
- **Mobile-First Responsive Design** - 4 breakpoints (360px, 480px, 767px, 1024px)
- **JavaScript** - For smooth scroll, back-to-top button, and form handling

## Features & Optimizations

### ✅ SEO Optimizations
- Meta description and keywords for search engines
- Open Graph tags for social media sharing (Facebook, Twitter)
- JSON-LD structured data for local business schema
- Semantic HTML5 with proper heading hierarchy
- Descriptive alt text for all images

### ✅ Performance Optimizations
- Lazy loading for below-the-fold images
- Optimized YouTube embed with privacy-enhanced mode
- Responsive images with width/height attributes (prevents layout shift)
- CSS variables for reduced file size
- Aspect-ratio for iframe responsive sizing

### ✅ Accessibility (A11y)
- ARIA labels for navigation and buttons
- Semantic HTML elements (nav, section, footer)
- Proper form labels with required attributes
- Keyboard-friendly navigation
- Color contrast optimized for readability

### ✅ Security
- `rel="noopener noreferrer"` on external links
- YouTube privacy-enhanced embed (youtube-nocookie.com)
- Proper iframe sandboxing

### ✅ User Experience (UX)
- **Smooth scroll** - Clicking navigation links smoothly scrolls to sections
- **Back-to-top button** - Appears after scrolling 300px down
- **Contact form** - Functional form with validation
- **Hover effects** - Interactive animations on images and buttons
- **Responsive navigation** - Mobile-friendly menu
- **Click-to-call** phone number - Direct dialing on mobile devices
- **Click-to-email** email address - Opens default email client

### ✅ Responsive Design
Multiple breakpoints for optimal viewing on all devices:
- **Desktop** (1024px+) - Full layout with all features
- **Tablet** (768px - 1023px) - Adjusted grid and spacing
- **Mobile Landscape** (481px - 767px) - Stacked navigation
- **Mobile Portrait** (≤480px) - Single column layout
- **Small Devices** (≤360px) - Optimized for smallest screens

### ✅ CSS Architecture
- **CSS Variables** for colors, spacing, fonts, and transitions
- **DRY principle** - Eliminated duplicate code
- **Mobile-first approach** - Base styles for mobile, enhanced for desktop
- **Modular sections** - Well-organized and commented
- **Consistent naming** - BEM-inspired class names

### ✅ Modern Features
- Aspect-ratio for responsive videos
- CSS transitions and transforms for smooth animations
- Flexbox and Grid for modern layouts
- Custom form styling
- Box-shadow for depth and visual hierarchy

## What Was Improved

### HTML Fixes
- ❌ `<quote>` → ✅ `<q>` (valid HTML5)
- ❌ `alt` on `<div>` → ✅ `alt` on `<img>`
- ❌ `allowfullscreens` → ✅ `allowfullscreen`
- ❌ "bussines" → ✅ "business"
- ❌ "birday" → ✅ "birthday"
- Added `lang="en"` attribute to `<html>`
- Added structured data for SEO
- Improved heading hierarchy (h1 → h2 → h3)

### CSS Improvements
- Added 33 CSS variables for consistency
- Eliminated duplicate selectors
- Refactored repetitive code (avatars, social icons)
- Added 4 responsive breakpoints (vs original 1)
- Implemented smooth transitions
- Created reusable component styles

### New Features Added
- Contact form with validation
- Back-to-top button
- Smooth scroll navigation
- Clickable phone and email links
- Enhanced footer with copyright
- Social media ARIA labels
- Image hover effects
- Form focus states

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

Potential improvements for future versions:
- Add favicon and app icons
- Implement actual form backend (PHP/Node.js)
- Add image optimization (WebP format)
- Implement CSS animations for page load
- Add testimonials carousel
- Create a menu/products page
- Add online ordering system
- Implement dark mode toggle

## Author

Created as part of the Bitdegree Front-end Web Development Course

## License

This project is open source and available for educational purposes.