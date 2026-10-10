# 🚀 Hamza Shabbir — Personal Portfolio

A modern, responsive portfolio website built with vanilla HTML, CSS, and JavaScript. Featuring a sleek dark theme, interactive particle background, smooth animations, and a premium glassmorphism design.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Dark Theme** | Premium dark mode with cyan & purple gradient accents |
| 🌌 **Particle Background** | Interactive particle network that reacts to mouse movement |
| ⌨️ **Typewriter Effect** | Animated text cycling through skills in the hero section |
| 🪟 **Glassmorphism** | Frosted-glass card components with blur and transparency |
| 📊 **Animated Counters** | Stats that count up when scrolled into view |
| 🎭 **Scroll Animations** | Fade-in reveal animations triggered by Intersection Observer |
| 📱 **Fully Responsive** | Optimized for desktop, tablet, and mobile devices |
| 🧭 **Smart Navbar** | Sticky navigation with blur backdrop & active section highlighting |
| 🍔 **Mobile Menu** | Animated hamburger menu for smaller screens |

---

## 📁 Project Structure

```
portfolio/
├── index.html      # Main HTML structure
├── style.css       # All styles, animations & responsive design
├── script.js       # Particles, typewriter, scroll animations & interactivity
├── hamza.png       # Profile photo
└── README.md       # Project documentation
```

---

## 🖥️ Sections

1. **Hero** — Name, animated typewriter, call-to-action buttons, scroll indicator
2. **About** — Profile photo with gradient border, bio, and animated stat cards
3. **Skills** — Languages, Frontend, Backend, and Tools categorized in tag cards
4. **Projects** — Featured project cards with descriptions and tech stacks
5. **Education** — Timeline layout with BSCS & Intermediate details
6. **Contact** — Email CTA button and social media links

---

## 🚀 Getting Started

### Prerequisites

No build tools or dependencies required — just a modern web browser.

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/portfolio.git
   ```

2. **Open in browser**
   ```bash
   cd portfolio
   open index.html
   ```
   Or simply double-click `index.html` to open it.

---

## 🎨 Customization

### Update Personal Info
- Edit `index.html` to update your name, bio, skills, projects, and education
- Replace `hamza.png` with your own profile photo

### Change Colors
Edit the CSS custom properties in `style.css`:
```css
:root {
    --accent-cyan: #06b6d4;
    --accent-purple: #a855f7;
    --accent-blue: #3b82f6;
    --accent-pink: #ec4899;
    --gradient-primary: linear-gradient(135deg, #06b6d4, #a855f7);
}
```

### Update Typewriter Words
Edit the `words` array in `script.js`:
```javascript
const words = [
    'web applications.',
    'elegant UIs.',
    'RESTful APIs.',
    'creative solutions.',
    'scalable software.',
];
```

---

## 📬 Contact

- **Email:** [hamzahrb288@gmail.com](mailto:hamzahrb288@gmail.com)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Designed & Built with ❤️ by <strong>Hamza Shabbir</strong>
</p>
