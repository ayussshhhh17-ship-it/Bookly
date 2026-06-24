# 📚 Bookly — Online Book Store Website

A fully responsive online book store website built with pure HTML, CSS, and JavaScript. Features a modern design with smooth sliders, animated sections, a login form, and a mobile-friendly layout.

---

## 🌐 Live Demo

🔗 [View Live Site](https://YOUR_USERNAME.github.io/bookly-website/)

> Replace the link above with your actual GitHub Pages URL after deployment.

---

## 📸 Preview

![Bookly Website Preview](image/banner-bg.jpg)

---

## ✨ Features

- **Responsive Design** — Works seamlessly on mobile, tablet, and desktop
- **Hero Slider** — Auto-rotating book showcase using Swiper.js
- **Featured Books** — Interactive carousel with navigation arrows
- **New Arrivals** — Dual-row sliding product section with star ratings
- **Deal of the Day** — Promotional banner section
- **Client Reviews** — Testimonial slider with user avatars
- **Blog Section** — Scrollable blog card carousel
- **Login / Sign In Form** — Slide-in modal with email & password fields
- **Search Bar** — Toggle search with smooth animation
- **Sticky Navigation** — Header that activates on scroll
- **Bottom Navbar** — Mobile-friendly bottom navigation bar
- **Newsletter Subscription** — Email subscription form
- **Loader Animation** — Page preloader with GIF animation
- **Footer** — Multi-column footer with locations, links, and social icons

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure and content |
| CSS3 | Styling, animations, and responsive layout |
| JavaScript (Vanilla) | Interactive features and DOM manipulation |
| [Swiper.js v7](https://swiperjs.com/) | Touch-friendly sliders and carousels |
| [Font Awesome 5](https://fontawesome.com/) | Icons throughout the site |

---

## 📁 Project Structure

```
bookly-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles and responsive rules
├── js/
│   └── script.js       # Swiper config and UI interactions
└── image/
    ├── banner-bg.jpg   # Hero section background
    ├── book-1.png      # Book product images (1–10)
    ├── blog-1.jpg      # Blog section images (1–5)
    ├── pic-1.png       # Reviewer avatars (1–6)
    ├── deal-img.jpg    # Deal of the day image
    ├── loader-img.gif  # Page preloader animation
    ├── stand.png       # Book display stand
    └── worldmap.png    # Footer world map
```

---

## 🚀 Getting Started

### View Locally

No installation or build tools needed — just open the file in a browser:

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/bookly-website.git

# Navigate into the folder
cd bookly-website

# Open in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Deploy to GitHub Pages

1. Fork or upload this repository to your GitHub account
2. Go to **Settings → Pages**
3. Set Branch to **main** and folder to **/ (root)**
4. Click **Save** — your site will be live in 1–3 minutes at:
   `https://YOUR_USERNAME.github.io/bookly-website/`

---

## 📱 Responsive Breakpoints

| Screen Size | Layout |
|-------------|--------|
| 0px+ (Mobile) | Single column, bottom navbar visible |
| 450px+ | 2 slides visible in featured slider |
| 768px+ | 2–3 slides, top navbar shown |
| 1024px+ | Full desktop layout, 3–4 slides |

---

## 🔧 Customization

**Change the brand name:**
In `index.html`, find `bookly` in the header logo and update it.

**Update book images:**
Replace files in the `image/` folder — keep the same filenames (`book-1.png` through `book-10.png`).

**Change slider speed:**
In `js/script.js`, update the `delay` value inside each Swiper config (default: `9500` ms).

**Edit colors/theme:**
All CSS variables and colors are in `css/style.css` at the top of the file.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**RS**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)

---

⭐ If you found this project helpful, please give it a star on GitHub!
