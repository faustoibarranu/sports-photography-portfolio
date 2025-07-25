# Ibarra Photography - Sports Portfolio Website

A modern, responsive sports photography portfolio website built with HTML, CSS, and JavaScript. This website showcases professional sports photography across seven different sports with beautiful galleries, smooth animations, and comprehensive media coverage sections.

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, modern design with smooth animations and hover effects
- **Navigation**: Fixed navigation bar with mobile hamburger menu
- **Sports Galleries**: Individual pages for each sport (Baseball, Basketball, Swimming, Tennis, Track & Field, Wrestling, Gymnastics)
- **About Page**: Information about the photographer and services offered
- **Media Coverage**: Three-section media page featuring Social Media Coverage, Photo Galleries, and Recent Press Coverage
- **Image Optimization**: Lazy loading, compressed hero images, and placeholder styles for better performance
- **Horizontal Layout**: Card-based design with horizontal layouts matching the homepage style

## Project Structure

```
sports-photography-portfolio/
├── index.html                 # Homepage with featured sports cards
├── css/
│   ├── style.css             # Main styles and homepage layout
│   ├── gallery.css           # Gallery page styles
│   ├── about.css             # About page styles
│   └── media.css             # Media coverage page styles with horizontal layout
├── js/
│   └── script.js             # JavaScript functionality and navigation
├── pages/
│   ├── baseball.html         # Baseball gallery (9 photos)
│   ├── basketball.html       # Basketball gallery (9 photos)
│   ├── swimming.html         # Swimming gallery (9 photos)
│   ├── tennis.html           # Tennis gallery (9 photos)
│   ├── track-field.html      # Track & Field gallery (9 photos)
│   ├── wrestling.html        # Wrestling gallery (9 photos)
│   ├── gymnastics.html       # Gymnastics gallery (9 photos)
│   ├── about.html            # About page
│   └── media.html            # Media coverage page with three sections
├── images/                   # Image directory (you'll add your images here)
└── README.md                 # This file
```

## Website Sections

### Homepage
- **Hero Section**: Eye-catching introduction with call-to-action
- **Featured Sports**: Seven sport cards with hover effects and overlay information
- **Navigation**: Links to all sport pages, media coverage, and about page

### Sport Pages
Each sport has its own dedicated page with:
- **Hero Image**: Large featured image for the sport
- **Photo Gallery**: Grid layout with 9 images per sport
- **Sport Description**: Information about the sport and photography approach
- **Consistent Navigation**: Same header and footer across all pages

### Media Coverage Page
The media coverage page features three distinct sections:

#### 1. Social Media Coverage
- **Instagram Highlights**: Featured posts and engagement metrics
- **Twitter Recognition**: Viral tweets and reach statistics
- **Facebook Features**: Major sports page features and reactions

#### 2. Photo Galleries
- **Stanford Men's Water Polo vs Air Force**: Complete coverage with external gallery link
- **Stanford Men's Basketball vs Oregon**: Game highlights with gallery access
- **Stanford Artistic Swimming vs Ohio State**: Artistic swimming showcase

#### 3. Recent Press Coverage
- **The New York Times**: Feature articles and technical analysis
- **BBC Sports**: International coverage and global recognition
- **Photo District News**: Technical photography insights

### About Page
- **Photographer Information**: Background and experience
- **Services Offered**: Photography packages and specialties
- **Contact Information**: Professional contact details

## Adding Your Images

To add your sports photography images, follow these steps:

### 1. Homepage Images (7 featured sports)
Place these images in the `images/` folder:
- `Baseball-hero.jpg` - Featured baseball image for homepage
- `Basketball-hero.jpg` - Featured basketball image for homepage
- `Swimming-hero.jpg` - Featured swimming image for homepage
- `Tennis-hero.jpg` - Featured tennis image for homepage
- `Track-field-hero.jpg` - Featured track & field image for homepage
- `Wrestling-hero.jpg` - Featured wrestling image for homepage
- `Gymnastics-hero.jpg` - Featured gymnastics image for homepage

### 2. Sport Gallery Images
For each sport, add 9 images in the `images/` folder:

**Baseball:**
- `baseball-1.jpg` through `baseball-9.jpg`

**Basketball:**
- `basketball-1.jpg` through `basketball-9.jpg`

**Swimming:**
- `swimming-1.jpg` through `swimming-9.jpg`

**Tennis:**
- `tennis-1.jpg` through `tennis-9.jpg`

**Track & Field:**
- `track-field-1.jpg` through `track-field-9.jpg`

**Wrestling:**
- `wrestling-1.jpg` through `wrestling-9.jpg`

**Gymnastics:**
- `gymnastics-1.jpg` through `gymnastics-9.jpg`

### 3. Media Coverage Images (Optional)
The media coverage page currently uses styled placeholder images with:
- **Social Media**: Platform-specific gradient backgrounds with icons
- **Photo Galleries**: Purple theme with camera and trophy icons
- **Press Coverage**: Professional dark theme with newspaper icons

You can replace these with actual images by adding:
- `social-instagram.jpg`, `social-twitter.jpg`, `social-facebook.jpg`
- `gallery-championship.jpg`, `gallery-behind-scenes.jpg`, `gallery-portraits.jpg`
- `press-nyt.jpg`, `press-bbc.jpg`, `press-pdn.jpg`

## Image Requirements

- **Format**: JPG or PNG recommended
- **Size**: 
  - Hero images: 1200x800px minimum (compressed for mobile performance)
  - Gallery images: 800x600px minimum
  - Media coverage: 400x600px minimum
- **Quality**: High resolution for professional appearance
- **Optimization**: Compressed images for web use to maintain fast loading times

## Design Features

### Layout & Spacing
- **Horizontal Card Layout**: Media coverage uses flexbox for horizontal arrangement
- **Consistent Spacing**: 6rem padding between sections for better visual separation
- **Alternating Backgrounds**: White and light gray backgrounds for section distinction
- **Responsive Grid**: Cards adapt from horizontal to vertical on mobile

### Visual Elements
- **Gradient Backgrounds**: Modern gradients for hero sections and placeholders
- **Hover Effects**: Smooth transitions and scaling animations
- **Icon Integration**: Font Awesome icons for social media and navigation
- **Typography**: Inter font family for clean, modern appearance

### Color Scheme
- **Primary Blue**: `#3498db` - Links and accents
- **Dark Blue**: `#2c3e50` - Headers and text
- **Accent Orange**: `#f39c12` - Highlights and awards
- **Background Gray**: `#f8f9fa` - Section backgrounds
- **Gradient Purple**: `#667eea` to `#764ba2` - Hero sections

## Customization

### Content Updates
- **Photographer Info**: Update `pages/about.html` with your information
- **Sport Descriptions**: Modify content in each sport gallery page
- **Contact Details**: Update footer sections across all pages
- **Media Coverage**: Customize content in `pages/media.html`

### Styling Changes
- **Colors**: Modify CSS variables in style files
- **Fonts**: Change Google Fonts import in HTML head
- **Layout**: Adjust grid and flexbox properties in CSS
- **Animations**: Modify transition and transform properties

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- **Lazy Loading**: Images load as they come into view
- **Compressed Hero Images**: 98%+ size reduction for faster mobile loading
- **CSS Animations**: Smooth transitions and hover effects
- **Responsive Images**: Optimized for different screen sizes
- **Minimal JavaScript**: Lightweight interactions
- **Font Awesome Icons**: Scalable vector icons
- **Placeholder Images**: Styled placeholders for missing images

## Testing Your Website

### Method 1: Direct File Opening
```bash
open index.html
```

### Method 2: Local Server (Recommended)
```bash
python3 -m http.server 8000
```
Then open: http://localhost:8000

### What to Test:
1. **Homepage**: Hero section, sport cards, navigation
2. **Sport Pages**: Individual galleries for each sport (9 photos each)
3. **About Page**: Photographer information and services
4. **Media Coverage**: Three sections with horizontal layouts
5. **Mobile Responsive**: Test on different screen sizes
6. **Navigation**: Test hamburger menu on mobile
7. **Hover Effects**: Card animations and transitions
8. **Image Loading**: Check compressed hero images load quickly

## Deployment

The website consists of static files and can be deployed to any web hosting service:

- **GitHub Pages**: Upload to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your repository for automatic deployment
- **Traditional hosting**: Upload files via FTP to your web server

## Recent Updates

- **Expanded Galleries**: All sport pages now feature 9 photos each
- **New Gymnastics Page**: Added complete gymnastics gallery with 9 photos
- **Updated Navigation**: All pages now include gymnastics in navigation menu
- **Compressed Hero Images**: 98%+ size reduction for improved mobile performance
- **Enhanced Media Coverage**: Updated with Stanford sports events and external links
- **Improved Mobile Performance**: Faster loading times with optimized images
- **Cross-Browser Compatibility**: Enhanced support for Chrome and Safari

## Support

For questions or customization help, refer to the HTML and CSS comments for guidance on modifying specific sections. The code is well-commented and organized for easy customization.

## License

This template is provided as-is for portfolio use. Customize freely for your sports photography business.
