# Prime Staff Augmentation Website

Static website for Prime Staff Augmentation services, deployed on Cloudflare Pages.

## Project Overview

This is a modern, responsive website for Prime Staff Augmentation, targeting Canadian companies seeking IT and development professionals for temporary and contract positions.

## Website Structure

### Main Pages
- **index.html** - Homepage with hero section, services overview, and company information
- **candidates.html** - Page for potential candidates to join the network (includes placeholder for CV submission link)
- **contact.html** - Contact page with form and company contact information
- **environmental-policy.html** - Environmental policy page
- **quality-policy.html** - Quality policy page
- **cookies-policy.html** - Cookies policy page
- **privacy-policy.html** - Privacy policy page

### Assets
- `/public/images` - Image assets (logo, favicon, etc.)
- `/public/fonts` - Custom fonts (if needed)
- `/public/documents` - PDFs and downloadable documents

### Source Files
- `/src/css/styles.css` - Main stylesheet with responsive design
- `/src/js/main.js` - JavaScript for mobile menu, form handling, and interactions

## Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Modern, professional UI/UX
- ✅ Mobile-friendly navigation menu
- ✅ Contact form (frontend only - needs backend integration)
- ✅ SEO-friendly structure
- ✅ Accessible markup
- ✅ Fast loading and optimized for Cloudflare Pages

## Important Notes

### Application Link
The candidates page includes a placeholder for the CV submission link. Update the `application-link` button in `candidates.html` with the actual URL when provided by the client.

### Contact Form
The contact form is currently frontend-only. For production, you'll need to:
1. Set up a backend service to handle form submissions
2. Update the form submission handler in `src/js/main.js`
3. Consider using Cloudflare Workers or a third-party service

### Policy Pages
The policy pages contain standard content. Review and update them to match the exact policies from the main Prime Consulting site if needed.

## Deployment

This site is configured for Cloudflare Pages deployment:

1. Connect your repository to Cloudflare Pages
2. Set build command: (none needed for static site)
3. Set output directory: `/` (root)
4. Deploy!

## Contact Information

- **Email:** info@prime-consulting.ca
- **Phone:** +1 (514) 881-9888
- **Address:** 6500 Trans-Canada Hwy Suite 400, Pointe-Claire, Quebec, Canada H9R 0A5

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

