# Portfolio Feed

A minimalist, feed-style portfolio website showcasing product design and development work. The site features a clean, mobile-responsive design with a focus on case studies and project highlights.

## Overview

This static portfolio website presents work in a feed-like layout, making it easy for visitors to browse through projects and case studies. The design emphasizes readability and accessibility with a consistent visual style across all pages.

## Features

- **Feed-style Layout**: Projects displayed in a chronological feed format
- **Case Studies**: Detailed project breakdowns with images and metrics
- **Dynamic Content**: Projects loaded from a JSON data file for easy updates
- **Responsive Design**: Optimized for mobile and desktop viewing
- **Accessibility**: Built with semantic HTML and skip links for keyboard navigation
- **Clean UI**: Minimal design with consistent typography and spacing

## Project Structure

```
portfolio-feed/
├── index.html              # Main portfolio feed page
├── about.html              # About page
├── case-study-mapbox.html  # Mapbox case study
├── case-study-shopify.html # Shopify case study
├── posts.json              # Project data (dynamically loaded)
└── project-images/         # Image assets
    ├── Agents-on-Mobile/
    ├── Shopify/
    └── mapbox/
```

## Technology Stack

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Custom styles with responsive design
- **JavaScript**: Dynamic content loading from JSON
- **Google Fonts**: Inter font family for typography

## Getting Started

### Prerequisites

No build tools or dependencies required. This is a static website that can be served directly.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/oriolson/portfolio-feed.git
   cd portfolio-feed
   ```

2. Serve the files using any static file server:
   
   **Using Python:**
   ```bash
   python -m http.server 8000
   ```
   
   **Using Node.js (http-server):**
   ```bash
   npx http-server
   ```
   
   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

3. Open your browser and navigate to `http://localhost:8000`

### Deployment

Deploy to any static hosting service:

- **GitHub Pages**: Push to `gh-pages` branch or configure in repository settings
- **Netlify**: Connect repository and deploy automatically
- **Vercel**: Import project and deploy with zero configuration
- **AWS S3**: Upload files to an S3 bucket configured for static website hosting

## Customization

### Adding New Projects

Edit `posts.json` to add new portfolio entries:

```json
{
  "id": "6",
  "title": "Your Project Title",
  "date": "Month Year",
  "image": "project-images/folder/image.jpg",
  "likeCount": "Optional metric or achievement",
  "content": "Project description",
  "link": "case-study-page.html or external URL"
}
```

### Updating Styles

All styles are embedded in `<style>` tags within each HTML file. Key style features:

- **Color Scheme**: Background `#f5f5f6`, text `#140700`
- **Typography**: Inter font family (400, 500, 600 weights)
- **Layout**: 600px max-width, centered content
- **Responsive Breakpoint**: 600px for mobile optimization

### Adding Case Studies

1. Create a new HTML file (e.g., `case-study-your-project.html`)
2. Use existing case study files as templates
3. Update image paths in `project-images/your-project/`
4. Link from the main feed via `posts.json`

## Design Principles

- **Consistency**: Uniform styling across all pages
- **Accessibility**: Semantic HTML, skip links, and proper heading hierarchy
- **Performance**: Minimal dependencies, optimized images
- **Mobile-First**: Responsive design that works on all devices

## Browser Support

Modern browsers with support for:
- CSS Grid and Flexbox
- ES6 JavaScript (for JSON fetching)
- Google Fonts API

## License

This project is a personal portfolio website. Please contact the owner for usage permissions.

## Contact

For questions or feedback about this portfolio, please reach out through the contact information provided on the website.
