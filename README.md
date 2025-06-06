# Music Composer Portfolio Website

A responsive and accessible portfolio site for a music composer, designed to showcase work and attract commissions. Developed to demonstrate strong front-end skills with a focus on detail, performance, readability, and artistic design.

## 🌐 Live Preview
[Visit the Website](#) <!-- Add your deployed URL here -->

---

## 📁 Project Structure

```
.
├── index.html
├── pages/
│   ├── albums.html
│   ├── commission.html
│   ├── about.html
│   └── contact.html
├── css/
│   ├── styles.min.css
│   └── custom-bootstrap.min.css
├── scss/
│   ├── styles.scss
│   ├── custom-bootstrap.scss
│   ├── _navbar.scss
│   ├── _albums.scss
│   └── ...
├── assets/
├── node_modules/
├── package.json
├── .gitignore

```

---

## 🛠️ Tech Stack

- **HTML5**, **CSS3**, **JavaScript (ES6)**
- **Sass** (modular SCSS files, custom Bootstrap theme)
  - `styles.scss` → `styles.min.css`
  - `custom-bootstrap.scss` → `custom-bootstrap.min.css`
- **Bootstrap** (Navbar, Carousel, Grid utilities)
- **Lite YouTube Embed** ([Paul Irish](https://github.com/paulirish/lite-youtube-embed))
- **AOS (Animate On Scroll)** for scroll animations
- **Node.js** for dependency management

---

## 🎨 Design Highlights

- Accessible font sizes (handles browser zoom & system scaling)
- Mobile-first, responsive down to 320px
- Custom Bootstrap grid breakpoints and container widths (`rem` units)
- Artistic and clean visual style with consistent spacing
- Thoughtful use of color, typography, and imagery

---

## 📦 Installation

```bash
npm install
```

Compile Sass:

```bash
sass scss/styles.scss css/styles.min.css --style=compressed
sass scss/custom-bootstrap.scss css/custom-bootstrap.min.css --style=compressed
```

---

## 🚀 Performance & Accessibility

- `<lite-youtube>` for fast, performant video embeds
- Optimized assets and lightweight SCSS output
- Semantic HTML for screen readers
- SEO-ready meta tags: `description`, `keywords`

---

## 🧪 Version Control

- Git used throughout development
- `.gitignore` includes node_modules and build artifacts

---

## 📌 Key Qualities

✅ Clean, scalable code  
✅ High readability and maintainability  
✅ Performance-focused design  
✅ Crafted to showcase front-end development skills  

---

## 📝 License

[MIT](LICENSE)
