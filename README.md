# AfriPath Website

A multi-page website structure for the AfriPath platform with separated HTML, CSS, and JavaScript files.

## Folder Structure

```
afripath-website/
├── css/
│   └── style.css          # All website styles
├── js/
│   └── main.js            # JavaScript functionality
├── Home.html              # Homepage - hero and intro
├── About.html             # About page - mission and story
├── Services.html          # Services page - all four platform features
├── Contact.html           # Contact page - contact form and info
└── README.md              # This file
```

## Files Overview

### HTML Pages

- **Home.html** - Homepage with hero section, journey overview, and call-to-action
- **About.html** - About page with problem statement, digital passport, and success story timeline
- **Services.html** - Services page featuring all four integrated platforms:
  - Opportunities Finder
  - Skills Builder
  - Experience Builder
  - Employer Hub
- **Contact.html** - Contact page with contact form, communication channels, and contact information

### CSS
- **css/style.css** - Contains all styling for the website including:
  - Color variables and design tokens
  - Component styles (buttons, cards, badges, etc.)
  - Layout and responsive design
  - Animations and transitions
  - Mobile menu styles and responsive breakpoints

### JavaScript
- **js/main.js** - Contains:
  - Mobile menu toggle functionality
  - Smooth scrolling navigation
  - Mobile menu closing on navigation
  - Form handling utilities

## Getting Started

1. Open any of the HTML files in a web browser
2. All pages are interconnected with navigation links
3. The CSS file automatically applies to all HTML pages
4. The JavaScript enhances interactivity and navigation

## Navigation

All pages link to each other through:
- Top navigation bar
- Mobile menu (hamburger menu)
- Footer links
- Call-to-action buttons

## Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly hamburger menu
- ✅ Contact form with validation
- ✅ Consistent branding across all pages
- ✅ Accessible HTML structure

## Color Scheme

- **Green** (#0e5b3f) - Primary brand color
- **Gold** (#f2a91d) - Accent color
- **Cobalt** (#2456e6) - Secondary color
- **Teal** (#0f9d8f) - Tertiary color
- **Dark Ink** (#101820) - Text color
- **Light Background** (#fbfaf7) - Page background

## Responsive Breakpoints

- Desktop: 900px+
- Tablet: 560px - 900px
- Mobile: < 560px

## Customization

To customize the website:

1. **Colors**: Update CSS variables in `css/style.css` under `:root`
2. **Content**: Edit text in individual HTML files
3. **Functionality**: Add more JavaScript in `js/main.js`
4. **Styles**: Modify CSS classes and rules in `css/style.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Notes

- All HTML files reference the same external CSS and JS files
- The website uses Google Fonts (Sora and Inter)
- No external dependencies or frameworks required
- Forms use vanilla JavaScript validation
