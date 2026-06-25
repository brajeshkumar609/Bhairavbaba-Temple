# 🙏 Bhairav Baba Temple - Divine Website 🙏

## Overview

A stunning, modern, and highly interactive single-page website for the historic **Bhairav Baba Temple** located in Areraj, East Champaran, Bihar. The website combines spiritual elegance with cutting-edge web technologies, featuring:

- ✨ Smooth scroll animations powered by AOS library
- 🎨 Captivating parallax effects on the hero section
- 🌟 Glowing hover effects and divine animations
- 📱 100% mobile-responsive design
- 🎭 Culturally resonant color scheme (Crimson Red, Gold, Dark Charcoal)
- 🔍 SEO-optimized structure

---

## 📂 Directory Structure

```
Bhairavbaba-Temple/
├── index.html                 # Main HTML file
├── css/
│   └── styles.css            # All styling and responsive design
├── js/
│   └── script.js             # JavaScript functionality
├── images/
│   └── hero-bhairav.jpg      # Hero section background image (add your own)
├── photos/                   # Gallery images folder (add your temple photos here)
│   ├── temple1.jpg
│   ├── temple2.jpg
│   └── ...
└── README.md                 # This file
```

---

## 🎨 Design System

### Color Palette
- **Crimson Red**: `#8B0000` - Represents divine power of Bhairav
- **Saffron**: `#FF4500` - Sacred and auspicious
- **Dark Charcoal**: `#121212` - Premium, modern backdrop
- **Gold/Amber**: `#FFD700` - Divine accents and highlights
- **White**: `#ffffff` - Clean, spiritual clarity

### Typography
- **Headings**: Playfair Display, Cinzel (elegant serif fonts)
- **Body Text**: Poppins, Inter (clean sans-serif fonts)

---

## ✨ Features

### 1. **Navigation Bar**
   - Fixed, responsive navbar with golden border
   - Smooth scroll navigation
   - Mobile hamburger menu
   - Animated logo with floating icon

### 2. **Hero Section**
   - Full-screen immersive background with parallax effect
   - Powerful headline: "Experience the Divine Protection of Kaal Bhairav Baba, Areraj"
   - Floating divine icons with animations
   - Engaging CTA button with glowing effects

### 3. **About & History Section**
   - Dual-column layout with cards
   - Spiritual content with cultural significance
   - 3D hover effects and smooth transitions
   - AOS scroll animations

### 4. **Divine Gallery**
   - Responsive masonry-style grid
   - Lazy loading support
   - Dynamic image loading from `photos/` folder
   - Lightbox functionality for full-screen viewing
   - Fallback placeholder design

### 5. **Contact & Location Section**
   - Contact information cards
   - Email link: brajeshkumar609@gmail.com
   - Location: Areraj, East Champaran, Bihar, India
   - Google Map placeholder (ready for embed)

### 6. **Animations**
   - Smooth fade-in/slide-up reveals
   - Parallax scrolling on hero
   - Glowing effects on hover
   - Floating icon animations
   - Button ripple effects
   - AOS library integration

---

## 🚀 Getting Started

### 1. **Setup**

Clone or download the repository:
```bash
git clone https://github.com/yourusername/Bhairavbaba-Temple.git
cd Bhairavbaba-Temple
```

### 2. **Add Your Assets**

**Hero Image:**
- Replace `images/hero-bhairav.jpg` with your hero background image
- Recommended size: 1920x1080px or larger

**Gallery Photos:**
- Add your temple photos to the `photos/` folder
- Name them: `temple1.jpg`, `temple2.jpg`, etc.
- Recommended size: 600x600px (square aspect ratio)
- Supported formats: JPG, PNG, WebP

### 3. **Add Google Map**

Open `index.html` and find the map placeholder section (around line 179):

```html
<!-- Replace the placeholder with actual Google Map embed: -->
<iframe src="https://www.google.com/maps/embed?pb=..." width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```

Get your embed code from: [Google Maps Embed API](https://developers.google.com/maps/documentation/embed/get-started)

### 4. **Deploy**

Optional: Deploy to your hosting platform:

- **GitHub Pages**: Push to `gh-pages` branch
- **Netlify**: Connect your GitHub repo
- **Vercel**: Import project from GitHub
- **Traditional Hosting**: Upload files via FTP/SFTP

---

## 📱 Responsiveness

The website is fully responsive across all devices:

- **Desktop**: Full animations and parallax effects
- **Tablet**: Optimized grid layouts and touch-friendly buttons
- **Mobile**: Single-column layouts, hamburger menu, optimized animations

Breakpoints:
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px

---

## 🔍 SEO Optimization

✅ **Implemented Best Practices:**
- Semantic HTML5 structure
- Meta tags for title, description, keywords
- Open Graph tags for social sharing
- Alt attributes on all images
- Proper heading hierarchy (H1, H2, H3)
- Mobile viewport configuration
- Fast loading with optimized assets

---

## 📚 Technologies Used

- **HTML5**: Semantic structure
- **CSS3**: Modern styling with flexbox, grid, animations
- **JavaScript (Vanilla)**: Interactive functionality
- **AOS Library**: Scroll animations
- **Google Fonts**: Premium typography
- **Responsive Design**: Mobile-first approach

---

## 🛠️ Customization

### Change Colors

Edit CSS variables in `css/styles.css` (lines 8-21):

```css
:root {
    --crimson-red: #8B0000;    /* Modify here */
    --saffron: #FF4500;        /* Modify here */
    --dark-charcoal: #121212;  /* Modify here */
    --gold: #FFD700;           /* Modify here */
    /* ... other variables ... */
}
```

### Modify Content

Edit `index.html` to update:
- Hero headline and description (lines 100-108)
- About section text (lines 137-150)
- Contact information (lines 212-225)

### Adjust Animations

Modify AOS settings in `js/script.js` (line 18):

```javascript
AOS.init({
    duration: 800,      // Animation duration in ms
    easing: 'ease-in-out',
    once: false,        // Animate every scroll
    mirror: true,       // Reverse animation on scroll up
    offset: 100,        // Trigger offset from viewport
});
```

---

## 📞 Contact & Support

**Email**: brajeshkumar609@gmail.com

**Location**: Areraj, East Champaran, Bihar, India

---

## 📄 License

This website template is created for the Bhairav Baba Temple, Areraj. All content and design are protected.

---

## 🙏 Blessing & Acknowledgments

This website is built with deep spiritual reverence for **Kaal Bhairav Baba** and is dedicated to all devotees seeking divine protection and blessings.

**May the divine light of Bhairav Baba guide and protect us all.**

---

## 📌 Quick Tips

1. **Performance**: Compress images before adding to `photos/` folder
2. **SEO**: Update meta descriptions and keywords in `<head>` section
3. **Analytics**: Add Google Analytics tracking code (optional)
4. **SSL**: Enable HTTPS on your hosting for security
5. **Backup**: Regularly backup your photos and content

---

**Last Updated**: 2024  
**Version**: 1.0  
**Status**: Production Ready ✅
