# 🛍️ Amazon Clone - Pure HTML & CSS Implementation

![Amazon Clone Banner](https://img.shields.io/badge/Amazon%20Clone-HTML%20%26%20CSS-FF9900?style=for-the-badge&logo=amazon&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-28B463?style=for-the-badge&logo=responsive&logoColor=white)

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1000&color=FF9900&center=true&vCenter=true&width=600&lines=Pure+HTML+%26+CSS+Amazon+Clone;No+JavaScript+Required;Responsive+Design;Modern+CSS+Animations;Pixel-Perfect+UI" alt="Typing SVG">
</div>

## 📋 Project Overview

A fully responsive Amazon homepage clone built using only **HTML5** and **CSS3**. This project demonstrates modern web design techniques, CSS animations, and responsive layouts without any JavaScript.

### ✨ Live Preview
🌐 **View Live:** [Amazon Clone Demo](https://sumitkolgire23.github.io/Amazon-Clone/)  
*(Note: This is a front-end only static implementation)*

## 📸 Screenshots & Animations

### 🎨 Main Interface
| Desktop View | Mobile View |
|--------------|-------------|
| ![Desktop Screenshot](https://via.placeholder.com/600x400/232F3E/FFFFFF?text=Desktop+View+Full+Width) | ![Mobile Screenshot](https://via.placeholder.com/300x500/232F3E/FFFFFF?text=Mobile+Responsive+View) |

### 🎭 Interactive Elements
| Hover Effects | Animations |
|---------------|------------|
| ![Hover Demo](https://via.placeholder.com/400x250/232F3E/FFFFFF?text=Button+Hover+Effects) | ![Animation Demo](https://via.placeholder.com/400x250/232F3E/FFFFFF?text=CSS+Animations) |

## 🚀 Features

### 🎯 Visual Features
| Feature | Status | Description |
|---------|--------|-------------|
| ✅ | **Responsive Navbar** | Adapts to all screen sizes |
| ✅ | **Hero Banner** | Full-width animated banner |
| ✅ | **Product Grid** | CSS Grid layout system |
| ✅ | **Hover Effects** | Interactive product cards |
| ✅ | **Footer Sections** | Multi-column responsive footer |
| ✅ | **CSS Animations** | Smooth transitions and effects |

### ⚡ CSS Techniques Used
- 🎨 **Flexbox & Grid** - Modern layout systems
- 🌀 **CSS Animations** - Keyframe animations
- 🎯 **Pseudo-classes** - :hover, :focus effects
- 📱 **Media Queries** - Mobile-first responsive design
- 🎨 **CSS Variables** - Consistent color scheme
- 🌈 **Gradients & Shadows** - Visual enhancements

## 🛠️ Tech Stack

### 🎨 Frontend Technologies
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Responsive Design](https://img.shields.io/badge/Responsive-Design-28B463?style=flat-square&logo=responsive&logoColor=white)

### 🔧 Development Tools
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github-pages&logoColor=white)

## 📁 Project Structure

```
Amazon-Clone/
├── 📄 index.html              # Main HTML file
├── 🎨 style.css               # Main stylesheet
├── 📁 assets/                 # Images and icons
│   ├── 📁 images/
│       ├── banner.jpg
│       ├── bike1.jpg
│       ├── bike2.jpg
│       └── ...       
│       
│       
├── 📁 screenshots/            # Project screenshots
├── 📄 README.md               # This file
└── 📄 .gitignore              # Git ignore file
```

## 🎨 Design Elements

### Color Palette
```css
:root {
    --amazon-orange: #FF9900;
    --amazon-blue: #146EB4;
    --amazon-dark: #131921;
    --amazon-light: #232F3E;
    --amazon-gray: #EAEDED;
    --text-dark: #0F1111;
    --text-light: #FFFFFF;
}
```

### Animations Showcase
```css
/* Example of CSS animation used */
@keyframes slideIn {
    from { transform: translateY(-20px); opacity: 0; }
    to { transform: translateY(0); opacity: 1; }
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    transition: all 0.3s ease;
}
```

## 🚀 Quick Start

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code, Sublime Text, etc.)
- Basic understanding of HTML/CSS

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sumitkolgire23/Amazon-Clone.git
   cd Amazon-Clone
   ```

2. **Open the project**
   - Open `index.html` in your browser
   - Or use a live server extension in VS Code

3. **For development**
   - Open the project in your code editor
   - Make changes to HTML/CSS files
   - Refresh browser to see changes

### Local Development Server
If you have Python installed:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then visit `http://localhost:8000`

## 🎮 Usage Guide

### For Viewers
1. Open `index.html` in any web browser
2. Resize browser to see responsive design
3. Hover over product cards to see effects
4. Scroll to view all sections

### For Developers
1. **Modify HTML** - Edit `index.html` for structure
2. **Update CSS** - Edit `style.css` for styling
3. **Add Images** - Place images in `assets/images/`
4. **Test Responsiveness** - Use browser dev tools

## 📱 Responsive Breakpoints

```css
/* Example media queries used */
@media (max-width: 768px) {
    .navbar { flex-direction: column; }
    .product-grid { grid-template-columns: repeat(2, 1fr); }
}

@media (max-width: 480px) {
    .product-grid { grid-template-columns: 1fr; }
    .hero-banner { height: 200px; }
}
```

## 🎯 Learning Objectives

This project demonstrates:
1. ✅ **HTML5 Semantic Elements**
2. ✅ **CSS3 Flexbox & Grid**
3. ✅ **Responsive Web Design**
4. ✅ **CSS Animations & Transitions**
5. ✅ **Hover Effects & Pseudo-classes**
6. ✅ **Media Queries**
7. ✅ **Modern CSS Techniques**

## 📊 Project Stats

<div align="center">

![GitHub Repo Size](https://img.shields.io/github/repo-size/Sumitkolgire23/Amazon-Clone)
![GitHub Languages](https://img.shields.io/github/languages/top/Sumitkolgire23/Amazon-Clone)
![GitHub Last Commit](https://img.shields.io/github/last-commit/Sumitkolgire23/Amazon-Clone)
![GitHub Issues](https://img.shields.io/github/issues/Sumitkolgire23/Amazon-Clone)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/Sumitkolgire23/Amazon-Clone)

</div>

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### 🛠️ How to Contribute
1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit with descriptive message (`git commit -m 'Add new feature'`)
5. Push to your branch (`git push origin feature/improvement`)
6. Create a Pull Request

### 💡 Suggested Improvements
- Add more CSS animations
- Improve mobile responsiveness
- Add dark/light mode toggle
- Enhance product card designs
- Add loading animations

## 📝 Code Quality

### HTML Structure
```html
<!-- Example of semantic HTML used -->
<header class="navbar">
    <nav class="nav-main">
        <div class="nav-logo">...</div>
        <div class="nav-search">...</div>
        <div class="nav-items">...</div>
    </nav>
</header>

<main class="content">
    <section class="hero-banner">...</section>
    <section class="product-grid">...</section>
</main>

<footer class="footer">...</footer>
```

### CSS Organization
```css
/* Organized CSS structure */
/* 1. Variables & Reset */
/* 2. Global Styles */
/* 3. Navigation */
/* 4. Hero Banner */
/* 5. Products Section */
/* 6. Footer */
/* 7. Animations */
/* 8. Media Queries */
```

## 🎓 Learning Resources

### Related Technologies
- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS-Tricks](https://css-tricks.com/)
- [FreeCodeCamp](https://www.freecodecamp.org/)

### Recommended Tools
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
- [CSS Grid Generator](https://cssgrid-generator.netlify.app/)
- [Flexbox Froggy](https://flexboxfroggy.com/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Design inspiration from [Amazon.com](https://amazon.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Images from [Unsplash](https://unsplash.com)
- Color palette from Amazon's official design

## 📞 Contact & Support

<div align="center">

### **Sumit Kolgire**
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sumitkolgire23)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sumitkolgire)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white)](https://sumitkolgire.dev)

**⭐ Star this repo if you like it!**

![Visitor Count](https://komarev.com/ghpvc/?username=Sumitkolgire23&color=orange&style=for-the-badge)

</div>

---

<div align="center">
  
**Happy Coding! 🎨**

</div>

## 📈 Project Progress

| Component | Status | Details |
|-----------|--------|---------|
| Navigation Bar | ✅ Complete | Responsive with hover effects |
| Hero Banner | ✅ Complete | Animated slideshow |
| Product Grid | ✅ Complete | CSS Grid layout |
| Footer | ✅ Complete | Multi-section responsive |
| Animations | ✅ Complete | CSS keyframes & transitions |
| Responsive Design | ✅ Complete | Mobile-first approach |

*Last Updated: December 2025*
