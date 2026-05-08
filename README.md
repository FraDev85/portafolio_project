# 🌐 Personal Portfolio — Francesco Comunale

A clean, responsive personal portfolio website built with vanilla HTML, CSS, and Bootstrap 5. Designed to showcase projects, skills, and a contact form — with a personality.

---

## ✨ Features

- **Smooth scroll navigation** with animated underline hover effects
- **Hero section** with a custom squircle-clipped avatar
- **Project showcase** with image-hover zoom and alternating card layout
- **Skills carousel** powered by Bootstrap 5
- **Contact form** integrated with [Web3Forms](https://web3forms.com) (no backend needed)
- **Animated footer** with social links and pulse-glow effects
- **Responsive design** — fully adapted for mobile (`≤560px`) and 4K (`≥2160px`) screens

---

## 🛠️ Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Markup     | HTML5                             |
| Styling    | CSS3 (custom) + Bootstrap 5.3.8   |
| Icons      | Font Awesome 7                    |
| Fonts      | Google Fonts (Cherry Swash, Raleway, Roboto, Syne) |
| Forms      | Web3Forms API                     |
| Hosting    | GitHub Pages                      |

---

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Custom styles
├── assets/
│   └── img/            # Images used in the project
│       ├── thinking.png
│       ├── html.png
│       ├── css.webp
│       ├── lazy-2048.png
│       ├── rp.png
│       ├── Node.js_logo.svg.png
│       └── React-icon.svg.png
├── README.md
└── LICENSE.txt
```

---

## 🚀 Getting Started

No build tools required. Just clone and open.

```bash
git clone https://github.com/FraDev85/portfolio_project.git
cd portfolio_project
# Open index.html in your browser
```

Or simply visit the live version on GitHub Pages.

---

## 📬 Contact Form Setup

The contact form uses **Web3Forms** for serverless email delivery.

If you fork this project, replace the access key in `index.html`:

```html
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE" />
```

Get your free key at [web3forms.com](https://web3forms.com).

---

## 📱 Responsive Breakpoints

| Breakpoint     | Behavior                                      |
|----------------|-----------------------------------------------|
| `≤ 560px`      | Stacked nav, single-column project cards, full-width inputs |
| Default        | Two-column project layout, centered carousel  |
| `≥ 2160px`     | Wider margins, scaled typography, larger form fields |

---

## 🔗 Live Projects Featured

- [**Lazy 2048**](https://fradev85.github.io/Lazy-2048/) — Physics-based 2048 puzzle game (vanilla JS, ES6 modules)
- [**Pomodoro & Duck**](https://fradev85.github.io/Pomodoro_rubber_duck/) — Productivity timer with Rubber Duck Debugging and WebAudio API

---

## 📄 License

This project is licensed under the [MIT License](LICENSE.txt).

---

## 🙋 About Me

I'm Francesco Comunale, a web developer based in Sicily. Passionate about JavaScript and its ecosystem, with a background in farming and a passion for history and economics.

Find me on:
- [GitHub](https://github.com/FraDev85)
- [LinkedIn](https://www.linkedin.com/in/francesco-comunale-3880635a)
- [Instagram](https://www.instagram.com/francesco_comunale85/)
