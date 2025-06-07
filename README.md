# Music Composer Portfolio Website

A responsive and accessible portfolio site for a music composer, designed to showcase work and attract commissions. Developed to demonstrate strong front-end skills with a focus on detail, performance, readability, and artistic design.

## 🌐 Live Preview
[Visit the Website](https://gasare55555.github.io/composer-web/) 

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
├── bootstrap/
│   ├── js/
│   └── scss/
├── lite-youtube-embed/
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

---

> ⚙️ This project **intentionally avoids frameworks, builders, and npm-based workflows** in the main logic to showcase a manual, alternative approach to customizing libraries like Bootstrap using Sass. It uses the **Live Sass Compiler** extension in VS Code for compiling `.scss` files and demonstrates strong understanding of folder structure, SCSS imports, internal linking across multiple HTML pages, and how everything integrates in deployment.

---

## 🎨 Design Highlights

- Accessible font sizes (handles browser zoom & font size configuration)
- Mobile-first, responsive down to 320px
- Custom Bootstrap breakpoints and container widths defined through Sass (`rem` units)
- Artistic and clean visual style with consistent spacing
- Thoughtful use of color, typography, and imagery

---

## 📦 Installation

Compile Sass:

```bash
sass scss/styles.scss css/styles.min.css --style=compressed
sass scss/custom-bootstrap.scss css/custom-bootstrap.min.css --style=compressed
```

Or use **Live Sass Compiler** in VS Code.

---

## 🚀 Performance & Accessibility

- `<lite-youtube>` for fast, performant video embeds
- Optimized assets and lightweight SCSS output
- Semantic HTML for screen readers
- SEO-ready meta tags: `description`, `keywords`

---

## 🧪 Version Control

- Git used throughout development
- `.gitignore` includes build artifacts

---

## 📌 Key Qualities

✅ Clean, scalable code  
✅ High readability and maintainability  
✅ Performance-focused design  
✅ Crafted to showcase front-end development skills  

---

## 📝 License

[MIT](LICENSE)
