# Ally Visual Media Website

A fast, simple, SEO-friendly static website for Fort Lauderdale's leading video production company.

## Overview

This is a complete rebuild of allyvisualmedia.com as a static HTML site focused on performance, SEO, and clear messaging. The site showcases professional video production services in Fort Lauderdale and Miami.

## Site Structure

```
ally-site/
├── index.html          # Homepage
├── services.html       # Services page  
├── portfolio.html      # Portfolio page
├── about.html          # About page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet (mobile-first)
├── sitemap.xml         # XML sitemap for search engines
├── robots.txt          # Robots.txt file
└── README.md           # This file
```

## Features

### Performance
- Plain HTML + single CSS file
- No JavaScript dependencies
- Mobile-first responsive design
- Optimized for fast loading

### SEO Optimization
- Semantic HTML5 structure
- Per-page title and meta description tags
- Open Graph and Twitter Card meta tags
- JSON-LD LocalBusiness schema on homepage
- Clean URL structure
- XML sitemap for search engines
- Robots.txt for crawling guidelines

### Content Strategy
- Fort Lauderdale / Miami focused copy
- Strong on-page SEO with proper heading hierarchy
- Short paragraphs and bullet points for readability
- Clear value propositions and calls-to-action
- Client testimonials with real quotes
- Service descriptions focused on business outcomes

## Pages

### Home (index.html)
- Hero section with main value proposition
- Services overview
- Client testimonials
- Local area coverage (Fort Lauderdale/Miami)
- JSON-LD LocalBusiness schema

### Services (services.html)  
- Video Production (Pre-production, Production, Post-production)
- Real Estate Media
- Agency Subcontracting
- Process overview

### Portfolio (portfolio.html)
- Featured client success stories
- Project categories and examples
- Success metrics and testimonials
- Industries served

### About (about.html)
- Company mission and approach
- Team expertise and values
- Service area information
- Client commitments

### Contact (contact.html)
- Contact methods (email, phone, location)
- Consultation process explanation
- Project inquiry types
- Service area coverage
- Response time guarantees

## Technical Details

### SEO Implementation
- Primary keywords: "Fort Lauderdale videographer", "Miami video production"
- LocalBusiness schema with Fort Lauderdale location
- Meta descriptions optimized for local search
- Internal linking between related pages

### Responsive Design
- Mobile-first CSS approach
- Breakpoints: Mobile (default), Tablet (768px+), Desktop (1024px+)
- Flexible grid layouts using CSS Grid
- Scalable typography and spacing

### Contact Information
- Email: info@allyvisualmedia.com
- Phone: (954) 998-4082
- Location: Fort Lauderdale, FL
- Service Area: Fort Lauderdale and Miami

## Deployment

### To preview locally:
1. Open `index.html` in a web browser
2. Or use a local server: `python -m http.server 8000` (Python 3) or `python -m SimpleHTTPServer 8000` (Python 2)

### For production deployment:
1. Upload all files to web hosting root directory
2. Ensure index.html is set as default document
3. Update sitemap.xml URLs if domain differs from allyvisualmedia.com
4. Submit sitemap to Google Search Console

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers on iOS and Android
- Graceful degradation for older browsers

## Maintenance

- Update lastmod dates in sitemap.xml when content changes
- Keep contact information current
- Add new portfolio examples as they become available
- Monitor and update local SEO information as needed

## Performance Notes

- CSS is mobile-first for optimal mobile performance
- No external dependencies except for system fonts
- Images should be optimized when added
- Consider adding lazy loading for images if many are added

## License

© 2025 Ally Visual Media. All rights reserved.