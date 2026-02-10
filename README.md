# Portfolio Feed

A clean, minimal portfolio website showcasing design and product work in a feed-style layout.

## Overview

This is a static portfolio website built with HTML, CSS, and vanilla JavaScript. It features a modern, mobile-responsive design with a feed-based content layout inspired by social media platforms.

## Features

- **Feed-style Layout**: Main page displays projects in a chronological feed format
- **Case Studies**: Detailed case study pages for featured projects (Mapbox, Shopify)
- **About Page**: Personal information and background
- **Responsive Design**: Mobile-first approach with optimized layouts for all screen sizes
- **Accessibility**: Skip links for keyboard navigation and semantic HTML structure
- **Dynamic Content**: Projects loaded from JSON data file

## Project Structure

```
portfolio-feed/
├── index.html              # Main feed page
├── about.html              # About page
├── case-study-mapbox.html  # Mapbox case study
├── case-study-shopify.html # Shopify AI chat case study
├── posts.json              # Project data
└── project-images/         # Project images and assets
    ├── Agents-on-Mobile/
    ├── Shopify/
    └── mapbox/
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with responsive design
- **JavaScript**: Vanilla JS for dynamic content loading
- **Google Fonts**: Inter font family

## Design Features

- **Color Scheme**: Clean background (#f5f5f6) with dark text (#140700)
- **Typography**: Inter font family for consistent, modern look
- **Layout**: Centered content with max-width of 600px
- **Responsive**: Breakpoints for mobile devices (max-width: 600px)
- **Avatar Sizing**: Standardized 40px × 40px avatars

## Getting Started

This is a static website that can be served with any web server.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/oriolson/portfolio-feed.git
   cd portfolio-feed
   ```

2. Open with a local server (e.g., using Python):
   ```bash
   python -m http.server 8000
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

### Deployment

Deploy the project to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any web server with static file hosting

## Featured Projects

The portfolio currently showcases:

1. **Bringing Agents to GitHub Mobile** (Oct 2025) - Agentic workflows for GitHub Mobile
2. **Fine Tuned Models** (Sept 2024) - Enterprise experience for custom fine-tuned models
3. **Copilot Extensions** (Aug 2024) - Chat experience for GitHub's extensibility platform
4. **AI Storefront Chat** (April 2023) - Shopify Inbox's AI-powered customer chat
5. **Dashboard and Onboarding** (Feb 2021) - Mapbox dashboard redesign

## Customization

To add or modify projects:

1. Edit the `posts.json` file with your project data
2. Add project images to the `project-images/` directory
3. Reference the images in the JSON file

Example post structure:
```json
{
  "id": "1",
  "title": "Project Title",
  "date": "Month Year",
  "image": "project-images/folder/image.jpg",
  "likeCount": "Optional metric",
  "content": "Project description",
  "link": "link-to-details.html"
}
```

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- IE11 and older browsers are not supported

## License

This project is personal portfolio work. All rights reserved.

## Contact

For inquiries about the work showcased in this portfolio, please reach out via the contact information on the About page.
