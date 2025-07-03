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

> ⚙️ This project **intentionally avoids JavaScript frameworks, builders, and build pipelines like Webpack or Vite** to showcase a manual, alternative approach to front-end development. Bootstrap library is customized directly using Sass, and the project uses the **Live Sass Compiler** extension in VS Code to generate the final CSS files. This setup demonstrates clear understanding of:
> 
> - Folder structure
> - SCSS importing and modularization
> - Internal linking between multiple HTML pages
> - Deployment structure and file organization  
> 
> ✅ This approach is suitable for **hosting services like GitHub Pages that don’t support build tools such as Vite or Webpack, nor environments like Node.js —** delivering deploy‑ready static output with zero extra build steps.

---

## 🎨 Design Highlights

- Accessible font sizes (handles browser zoom and user font-size settings while maintaining layout integrity and responsiveness)
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
- SEO-ready: meta tags (`description`, `keywords`) and a clear `h1–h6` heading hierarchy to enhance search engine indexing.

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
