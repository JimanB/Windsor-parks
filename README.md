# Windsor Parks Website

## Overview

This project is a responsive website showcasing five beautiful parks in Windsor, Ontario, Canada. The website features clean design, accessibility considerations, and City of Windsor branding with a modern, user-friendly interface.

## Features

- **Park Information Display**: Detailed pages for five major Windsor parks with descriptions and images
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Accessibility Features**: Semantic HTML and proper contrast ratios
- **Modern Styling**: Clean CSS with City of Windsor color scheme
- **Navigation System**: Easy-to-use navigation between all park pages
- **Image Gallery**: High-quality park images with proper attribution
- **Sticky Footer**: Consistent footer positioning across all pages

## Website Structure

### Park Pages Included

1. **Coventry Gardens (Reaume Park)** - Iconic riverfront park with Peace Fountain
2. **Jackson Park** - Formal gardens with memorials and seasonal light displays
3. **Ojibway Park** - Natural wilderness area within Ojibway Prairie Complex
4. **Willistead Park** - Historic park surrounding Willistead Manor
5. **Sandpoint Beach Park** - Former public beach on Lake St. Clair

### Page Components

- Park addresses and location information
- Multiple high-quality images per park
- Detailed descriptions and historical context
- Photo credits and attribution
- Navigation links between parks
- Contact information for Windsor Parks and Recreation

## Technical Implementation

### Files Structure

```
midterm_2707/
├── index.html              # Homepage with park overview and table of contents
├── park1.html             # Coventry Gardens page
├── park2.html             # Jackson Park page
├── park3.html             # Ojibway Park page
├── park4.html             # Willistead Park page
├── park5.html             # Sandpoint Beach page
├── parks.css              # Main stylesheet
├── images/                # Image directory
│   ├── coventry_gardens.jpg
│   ├── jackson_park.jpg
│   ├── jackson_park_1.jpg
│   ├── ojibway_park.jpg
│   ├── willistead_manor.jpg
│   ├── willistead_park.jpg
│   ├── windsor_pic.png
│   ├── sandpoint_beach_park.jpg
│   ├── sandpoint_beach_park_1.jpg
│   └── smt.jpeg
└── README.md              # Project documentation
```

### HTML Structure

Each park page follows consistent semantic HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags for character encoding and responsive design -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Park description for SEO">
    <title>Park Name - Windsor Parks</title>
    <link rel="stylesheet" href="parks.css">
</head>
<body>
    <header>
        <h1>Windsor's Beautiful Parks</h1>
    </header>
    <nav>...</nav>
    <main>
        <section>
            <h2>Park Name</h2>
            <p><strong>Address:</strong> Park location</p>
            <img src="images/park_image.jpg" alt="description" class="park-image">
            <p class="photo-credit">Image attribution</p>
            <p>Detailed park description...</p>
            <div class="park-nav">Navigation links</div>
        </section>
    </main>
    <footer>Contact information</footer>
</body>
</html>
```

### CSS Features (parks.css)

**Typography & Layout**
- Google Fonts: Lato for modern, readable typography
- Flexbox layout for sticky footer implementation
- Responsive design with percentage-based widths

**Color Scheme**
- Primary: #005596 (Windsor blue)
- Secondary: #003a66 (Dark blue accent)
- Neutral: #e9ecef, #f8f9fa, #333333

**Visual Elements**
- Gradient overlays on header images
- Box shadows and border-radius for modern cards
- Hover effects on navigation links
- Background images with semi-transparent overlays

**Responsive Design**
```css
/* Mobile-first responsive approach */
main {
    max-width: 1000px; /* Optimal reading width */
    margin: 20px auto;
    width: 90%; /* Responsive width */
}

.park-image {
    max-width: 100%; /* Prevent overflow */
    height: auto; /* Maintain aspect ratio */
}
```

## Installation & Usage

### 1. Local Development Setup

Clone or download the project files and maintain the directory structure:

```
project-folder/
├── index.html
├── park1.html
├── park2.html
├── park3.html
├── park4.html
├── park5.html
├── parks.css
└── images/
    └── [all image files]
```

### 2. Viewing the Website

Open `index.html` in a web browser to access the homepage. All internal links and images will work correctly when files are kept in their relative positions.

### 3. Navigation Flow

- **Homepage** (`index.html`): Overview and table of contents
- **Individual Park Pages**: Detailed information for each park
- **Navigation Menu**: Consistent across all pages
- **Park-to-Park Navigation**: Sequential navigation between parks

## Browser Compatibility

Tested and optimized for modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Design Principles

### Accessibility
- Semantic HTML5 elements
- Proper heading hierarchy
- Alt text for all images
- Sufficient color contrast ratios
- Keyboard-navigable interface

### Performance
- Optimized image sizes
- Efficient CSS with minimal redundancy
- Clean, valid HTML markup
- External stylesheet for caching benefits

### Maintainability
- Consistent naming conventions
- Modular CSS structure
- Clear code comments
- Separation of concerns (HTML/CSS)

## Customization

### Adding New Parks

1. Create new HTML file following existing structure
2. Add navigation link to all pages
3. Update table of contents in `index.html`
4. Add park images to `images/` directory

### Styling Modifications

Key CSS variables for quick customization:
```css
/* Primary brand colors */
#005596  /* Windsor blue */
#003a66  /* Dark blue accent */

/* Typography */
font-family: 'Lato', 'Arial', sans-serif;

/* Layout */
max-width: 1000px  /* Content width */
```

## Contact Information

Website includes contact details for:
- **Email**: parkrec@citywindsor.ca
- **Phone**: (519) 253-2300
- **Ojibway Park Specific**: ojibway@citywindsor.ca, (519) 966-5852

## Author

**Jimaan Singh Bajwa**  
*Date: June 11, 2025*  

## Notes

- All images are properly attributed to their respective sources
- Design follows municipal website best practices
- Code maintains accessibility and web standards compliance
- Project demonstrates responsive web design principles
