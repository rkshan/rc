# Video Editing Portfolio Website

A modern, animated portfolio website for video editors with a stunning UI and smooth animations.

## Features

✨ **Modern UI Design**
- Dark theme with gradient accents
- Smooth animations and transitions
- Responsive design for all devices

🎥 **Hero Section**
- Full-screen video background
- Animated text with gradient effects
- Professional details showcase
- Call-to-action buttons

📂 **Projects Gallery**
- Filterable project grid
- Hover effects with play icons
- Category-based filtering
- Project thumbnails with overlay

👤 **About Section**
- Skills showcase with progress bars
- Tool badges
- Professional bio
- Animated image border

📧 **Contact Section**
- Contact form with validation
- Contact information cards
- Social media links
- Smooth form submission

## Setup Instructions

### 1. Add Your Hero Video
Replace the placeholder video path in `index.html`:
```html
<source src="assets/hero-video.mp4" type="video/mp4">
```

**To add your video:**
1. Create an `assets` folder in the project directory
2. Add your video editing showreel as `hero-video.mp4`
3. Recommended: 1920x1080 resolution, 10-30 seconds long

### 2. Customize Your Details

**Personal Information** (in `index.html`):
- Update your name in the hero title
- Modify statistics (projects completed, years of experience)
- Change email, phone, and location in the contact section
- Update social media links

**About Section**:
- Replace the placeholder image URL with your photo
- Update your bio and description
- Adjust skill percentages in the progress bars
- Modify the tools you use

### 3. Add Your Projects

**For each project**, update in `index.html`:
```html
<div class="project-card" data-category="commercial">
    <div class="project-thumbnail">
        <img src="YOUR_PROJECT_THUMBNAIL.jpg" alt="Project Name">
    ```
    </div>
    <div class="project-info">
        <h3>Your Project Title</h3>
        <p>Project description</p>
        <div class="project-tags">
            <span>Software Used</span>
        </div>
    </div>
</div>
```

### 4. Project Structure

```
VIDEO EDITING PORTFOLIOI/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
├── README.md           # This file
│
└── assets/            # Create this folder
    ├── hero-video.mp4         # Your hero video
    ├── project-1.jpg          # Project thumbnails
    ├── project-2.jpg
    └── your-photo.jpg         # Your photo for about section
```

## How to Use

1. **Open the website:**
   - Simply open `index.html` in your web browser
   - Or use a local server for best results

2. **Using Live Server (Recommended):**
   - Install the "Live Server" extension in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"

## Customization Guide

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;      /* Main brand color */
    --secondary-color: #764ba2;    /* Secondary color */
    --accent-color: #f093fb;       /* Accent highlights */
}
```

### Fonts
Change the font family in `styles.css`:
```css
body {
    font-family: 'Your Font Here', sans-serif;
}
```

### Animations
Adjust animation speeds in `styles.css`:
- Search for `transition` and `animation` properties
- Modify duration values (e.g., `0.3s`, `1s`)

## Browser Support

✅ Chrome (recommended)
✅ Firefox
✅ Safari
✅ Edge
⚠️ IE11 (limited support)

## Tips for Best Results

1. **Video Optimization:**
   - Compress your hero video (keep under 10MB)
   - Use H.264 codec for best compatibility
   - Consider providing a poster image for fallback

2. **Images:**
   - Use high-quality project thumbnails (1200x800px recommended)
   - Optimize images for web (use tools like TinyPNG)
   - Keep file sizes reasonable for faster loading

3. **Performance:**
   - Lazy load images if you have many projects
   - Minimize the number of high-res images
   - Test on mobile devices

## Adding More Sections

You can easily add more sections by following the existing pattern:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <div class="section-header">
            <h2 class="section-title">Section Title</h2>
            <p class="section-subtitle">Subtitle here</p>
        </div>
        <!-- Your content here -->
    </div>
</section>
```

Don't forget to add the navigation link in the header!

## License

Feel free to use this template for your personal or commercial projects!

## Credits

Created with ❤️ for video editors

---

**Need help?** Check the comments in the code files for guidance!

Good luck with your portfolio! 🎬✨
