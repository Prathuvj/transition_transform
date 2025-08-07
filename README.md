# 3D Flip Card

## DESCRIPTION

An interactive 3D flip card built with pure HTML and CSS that demonstrates advanced CSS transforms and transitions. The card features a smooth 180° rotation animation on hover, revealing additional content on the back face. This project showcases modern web design techniques including 3D transforms, glassmorphism effects, and responsive design principles.

The card displays a professional profile on the front with an image, name, and tagline, then flips to reveal detailed information including a description, skills, and a call-to-action button on the back.

## NAME

**Prathu Vijayvargiya (RA2211003011827)**

## FEATURES

### Core Functionality
- **3D Flip Animation**: Smooth 180° horizontal rotation around the Y-axis
- **Hover Interaction**: Card flips on mouse hover and returns on mouse out
- **Dual-Face Design**: Distinct front and back faces with different content and styling

### Technical Features
- **Pure CSS Implementation**: No JavaScript required - uses only CSS transforms and transitions
- **3D Perspective**: Utilizes CSS `perspective` property for realistic 3D depth
- **Smooth Transitions**: 0.6s ease transition for natural animation feel
- **Backface Visibility**: Proper handling of card face visibility during rotation

### Visual Design
- **Modern Glassmorphism**: Backdrop blur effects on interactive elements
- **Clean Typography**: Poppins font family with optimized hierarchy
- **Responsive Design**: Adapts to different screen sizes and devices
- **Subtle Shadows**: Soft box-shadows for depth without overwhelming the design
- **Professional Color Palette**: Clean whites and gradients for modern aesthetic

### Content Structure
- **Front Face**: Profile image, name, and professional tagline
- **Back Face**: Detailed description, skill tags, and interactive button
- **Semantic HTML**: Proper use of semantic elements for accessibility

## FILE STRUCTURE

```
3d-flip-card/
│
├── index.html          # Main HTML structure with semantic markup
├── styles.css          # Complete CSS styling with 3D transforms
└── README.md          # Project documentation
```

### File Details

**index.html**
- Semantic HTML structure using `<main>`, `<article>`, `<h3>`, `<p>`, `<img>`, `<button>`
- Google Fonts integration (Poppins)
- Dual-face card structure with front and back content
- Professional profile image from Unsplash
- Accessible markup with proper alt attributes

**styles.css**
- CSS reset and base styles
- 3D transform properties and perspective setup
- Flip animation using `transform: rotateY(180deg)`
- Glassmorphism effects with backdrop-filter
- Responsive design with mobile-first approach
- Clean, minimal styling with modern aesthetics

## USAGE

### Getting Started

1. **Clone or Download**: Get the project files to your local machine
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **Interact**: Hover over the card to see the 3D flip animation

### Browser Compatibility

- **Chrome**: Full support for all features
- **Firefox**: Full support for all features  
- **Safari**: Full support for all features
- **Edge**: Full support for all features

### Customization Options

#### Modify Content
```html
<!-- Update the profile information in index.html -->
<h3>Your Name</h3>
<p class="tagline">Your Title</p>
<p class="description">Your description here...</p>
```

#### Adjust Animation Timing
```css
/* Change flip speed in styles.css */
.flip-card-inner {
    transition: transform 0.6s ease; /* Modify duration here */
}
```

#### Customize Colors
```css
/* Update color scheme */
.flip-card-front {
    background: #your-color; /* Front face background */
}

.flip-card-back {
    background: linear-gradient(135deg, #color1, #color2); /* Back face gradient */
}
```

#### Modify Card Dimensions
```css
/* Adjust card size */
.flip-card {
    width: 300px;  /* Card width */
    height: 420px; /* Card height */
}
```

### Integration

This flip card can be easily integrated into larger projects:

- **Portfolio Websites**: Showcase team members or projects
- **Business Cards**: Digital business card presentations  
- **Product Showcases**: Display product features and details
- **Educational Content**: Interactive learning materials

### Performance Notes

- **Lightweight**: Pure CSS implementation with minimal overhead
- **GPU Accelerated**: Uses CSS transforms for smooth hardware acceleration
- **No Dependencies**: No external libraries or frameworks required
- **Fast Loading**: Optimized for quick page load times

### Accessibility Features

- Semantic HTML structure for screen readers
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- High contrast color combinations