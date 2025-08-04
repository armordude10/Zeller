# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML website for "Builty" - appears to be a construction/building company website. It's a frontend-only project with multiple HTML pages, CSS styling, and JavaScript functionality.

## Architecture

### File Structure
- **HTML Pages**: Multiple themed pages (index.html, index-2.html, index-3.html) plus various content pages (about.html, services.html, contact.html, etc.)
- **Assets Directory**: Contains all static resources
  - `css/`: Stylesheets including Bootstrap, custom styles, and third-party libraries
  - `js/`: JavaScript files including jQuery, Bootstrap, and custom scripts
  - `images/`: Brand assets, icons, and imagery
  - `videos/`: Video content (video.mp4)

### Key Components
- **Main Stylesheet**: `assets/css/style.css` - Contains comprehensive styling with organized sections
- **Dark Theme**: `assets/css/style-dark.css` - Alternative dark theme styling
- **JavaScript**: `assets/js/custom.js` - Main custom functionality
- **Third-party Libraries**: Bootstrap, jQuery, AOS (Animate On Scroll), Owl Carousel, Fancybox

### Page Types
- **Home Pages**: index.html, index-2.html, index-3.html (different homepage variants)
- **Company Pages**: about.html, history.html, core-values.html, leadership.html, our-team.html
- **Service Pages**: services.html, service-detail.html
- **Project Pages**: our-projects-1.html, our-projects-2.html, project-detail.html
- **Product Pages**: our-products.html, product-detail.html, product-grid.html, product-list.html
- **Blog Pages**: our-blog-1.html, our-blog-2.html, blog-detail.html
- **E-commerce**: cart.html, checkout.html, login.html
- **Contact**: contact.html

## Development Notes

- This is a static HTML project with no build process or package management
- All dependencies are included as static files in the assets directory
- No server-side functionality - pure frontend HTML/CSS/JavaScript
- Uses Bootstrap framework for responsive design
- Multiple JavaScript libraries for enhanced functionality (carousels, animations, etc.)

## File Editing Guidelines

- HTML files follow a consistent structure with similar head sections and asset references
- CSS is organized with a detailed table of contents in style.css
- JavaScript functionality is primarily in custom.js with library dependencies loaded separately
- Images and branding assets are centralized in assets/images/
- When editing, maintain consistency with existing naming conventions and file organization