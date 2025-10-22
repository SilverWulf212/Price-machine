# Price Machine Shop Website

## Overview

This is a static website for Price Machine Shop, LLC - an ISO-certified machine shop in Scott, Louisiana specializing in precision machining for the oil and gas industry. The website serves as a digital presence to showcase their CNC machining capabilities, equipment, and services, with a primary focus on lead generation through quote requests. The site features a modern industrial design with a red and black color scheme, emphasizing professionalism and precision manufacturing expertise.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology Stack**: Pure HTML, CSS, and vanilla JavaScript (no frameworks)
- **Page Structure**: Multi-page static site with index.html (homepage) and machines.html (equipment page)
- **Responsive Design**: Mobile-first approach with hamburger navigation for mobile devices
- **Design System**: 
  - Color palette: Firebrick Red (#B22222), Pure Black (#000000), Dark Steel Gray (#444444)
  - Typography: Oswald for headings, Roboto for body text, Montserrat for accents
  - Industrial aesthetic with emphasis on precision and reliability

### Navigation System
- **Desktop**: Standard horizontal navigation menu
- **Mobile**: Hamburger menu with toggle functionality
- **Smooth Scrolling**: Implemented for anchor links within single page
- **Active States**: Visual indicators for current page/section

### Interactive Features
- **Hero Carousel**: Auto-advancing image carousel on homepage with manual controls
  - 5-second interval between slides
  - Clickable indicators for manual navigation
  - Active state tracking for current slide
- **Mobile Menu**: Toggle-based hamburger menu that closes on link click
- **Smooth Scroll**: Anchor-based navigation with smooth scrolling behavior

### Content Strategy
- **SEO Optimization**: 
  - Semantic HTML with proper meta tags
  - Schema.org LocalBusiness structured data
  - Keywords: machine shop lafayette, machine shop acadiana, oil rig parts machining Louisiana
- **Target Audience**: Oil and gas production business owners, energy sector companies
- **Lead Generation Focus**: Multiple CTAs for quote requests throughout site
- **Brand Voice**: Modern, professional, authoritative, customer-focused

### Asset Management
- **Images**: Stored in `attached_assets/` directory
- **Logo**: Custom Price Machine Shop logo (priceLogo-01_1755629947236.png)
- **External Images**: Unsplash CDN for hero/background images
- **Fonts**: Google Fonts CDN (Oswald, Roboto, Montserrat)

### File Organization
- `index.html` - Homepage with hero, about, services, contact sections
- `machines.html` - Equipment showcase page with detailed machinery specifications
- `style.css` - Global styles with responsive breakpoints
- `script.js` - Interactive functionality (navigation, carousel)
- `content.md` - Content strategy and copywriting reference
- `attached_assets/` - Static assets (logo, images)

### Design Principles
- **Industrial Aesthetic**: Bold typography, high contrast, machinery-focused imagery
- **Conversion-Focused**: Clear CTAs, benefit-driven messaging, trust indicators (ISO certification)
- **Performance**: Minimal dependencies, optimized images, clean CSS/JS
- **Accessibility**: Semantic HTML, proper heading hierarchy, keyboard navigation support

## External Dependencies

### Third-Party Services
- **Google Fonts**: Typography delivery (Oswald, Roboto, Montserrat families)
- **Unsplash CDN**: Hero and background imagery for industrial/machining context
- **Schema.org**: LocalBusiness structured data for SEO and local search optimization

### Content Management
- No CMS or database - content is hardcoded in HTML files
- Content strategy documented in `content.md` for reference and updates
- Images managed through `attached_assets/` directory

### Browser APIs
- Standard DOM manipulation for navigation and carousel
- CSS3 for animations and transitions
- HTML5 semantic elements and meta tags

### Development Tools
- No build process or bundler required
- No package manager dependencies
- Direct file editing for updates
- Can be hosted on any static file server