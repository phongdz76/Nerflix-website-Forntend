# Netflix Website Frontend Clone

A responsive Netflix-style streaming website frontend built with modern web technologies. This project replicates the user interface and user experience of Netflix with custom design elements and animations.

## 🎯 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI/UX**: Netflix-inspired interface with smooth animations and transitions
- **Video Player**: Custom video player implementation
- **Interactive Elements**: Hover effects, carousels, and dynamic content sections
- **Multiple Sections**:
  - Hero slider with featured content
  - Trending movies and shows
  - Top 10 content
  - Episodes showcase
  - Popular content
  - Favorite collections
  - TV Thrillers section

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and DOM manipulation
- **Bootstrap 4**: Responsive grid system and components
- **jQuery**: Enhanced JavaScript functionality
- **Font Awesome**: Icon library for social media and UI icons
- **Slick Carousel**: Image and content sliders
- **Owl Carousel**: Touch-enabled carousel
- **Animate.css**: CSS animations
- **Magnific Popup**: Lightbox functionality
- **Select2**: Enhanced select dropdowns

## 📁 Project Structure

```
├── index.html              # Main HTML file
├── style.css              # Custom CSS styles
├── main.js                # Main JavaScript functionality
├── css/                   # CSS libraries and frameworks
│   ├── bootstrap.min.css
│   ├── animate.min.css
│   ├── slick.css
│   └── ...
├── js/                    # JavaScript libraries
│   ├── jquery-3.4.1.min.js
│   ├── bootstrap.min.js
│   ├── slick.min.js
│   └── ...
├── images/                # Image assets
│   ├── logo.png
│   ├── episodes/
│   ├── trending/
│   ├── popular/
│   └── ...
└── video/                 # Video assets
    └── trailer.mp4
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for best experience)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/phongdz76/Netflix-Website-Frontend.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Netflix-Website-Frontend
   ```

3. **Open the project**
   - Option 1: Open `index.html` directly in your browser
   - Option 2: Use a local server (recommended)
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using Live Server extension in VS Code
     ```

4. **View the website**
   - Direct: Open `index.html` in your browser
   - Local server: Navigate to `http://localhost:8000`

## 🎨 Key Features Implementation

### Responsive Navigation
- Mobile-friendly hamburger menu
- Smooth toggle animations
- Brand logo integration

### Hero Section
- Full-width background slider
- Overlay content with call-to-action buttons
- Responsive video background support

### Content Carousels
- Multiple content sections with horizontal scrolling
- Touch/swipe support for mobile devices
- Lazy loading for better performance

### Interactive Elements
- Hover effects on movie/show cards
- Modal popups for content details
- Smooth scroll navigation

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 🔧 Customization

### Adding New Content
1. Add new images to the appropriate folder in `/images/`
2. Update the HTML structure in `index.html`
3. Modify styles in `style.css` if needed

### Changing Colors and Themes
- Edit CSS custom properties in `style.css`
- Modify Bootstrap variables if using SCSS

### Adding New Sections
- Follow the existing HTML structure pattern
- Add corresponding CSS styles
- Initialize any JavaScript functionality in `main.js`

## 📊 Performance Optimization

- Minified CSS and JavaScript files
- Optimized image assets
- Lazy loading implementation
- Responsive images for different screen sizes

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Netflix for design inspiration
- Bootstrap team for the responsive framework
- Font Awesome for the icon library
- All contributors and open-source libraries used

## 📞 Contact

**Author**: phongdz76  
**Project Link**: [https://github.com/phongdz76/Netflix-Website-Frontend](https://github.com/phongdz76/Netflix-Website-Frontend)

---

### 📋 Development Notes

**Font Awesome Setup**: 
Make sure to include the Font Awesome CDN link in your HTML to enable all social media and UI icons:
```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
```

**File Dependencies**: 
The main files (`index.html`, `style.css`, `main.js`) work together to create the complete user experience. Make sure all three files are properly linked and loaded.

---

⭐ **Star this repository if you found it helpful!**


