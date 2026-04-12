# Dipak Kalaskar – Personal Portfolio Website

A clean, responsive personal portfolio website built with HTML, CSS, and vanilla JavaScript. Showcases professional experience, projects, skills, and contact information.

---

## 🔗 Live Preview

> Deploy on GitHub Pages, Netlify, or Vercel and add your live link here.

---

## 📁 Project Structure

```
portfolio/
├── index.html                  # Main HTML file
├── README.md                   # Project documentation
└── assets/
    ├── css/
    │   └── style.css           # All styles
    ├── js/
    │   └── script.js           # Navigation, modal, filter logic
    ├── images/
    │   ├── my-avatar.png       # Your profile photo
    │   ├── logo.ico            # Favicon
    │   ├── avatar-1.svg        # Skill card icons
    │   ├── avatar-2.svg
    │   ├── avatar-3.svg
    │   ├── avatar-4.svg
    │   ├── icon-design.svg     # Service section icons
    │   ├── icon-dev.svg
    │   ├── icon-app.svg
    │   ├── icon-photo.svg
    │   └── icon-quote.svg      # Modal quote icon
    └── Dipak_Kalaskar_Resume.pdf   # ⚠️ Add your resume PDF here
```

---

## ✨ Features

- **Responsive Design** – Works on mobile, tablet, and desktop
- **Sidebar with Contact Info** – Toggle-able on mobile with Show Contacts button
- **3-Tab Navigation** – About, Resume, Contact tabs with smooth switching
- **About Tab** – Bio, services/skills overview, and scrollable technical skill cards
- **Resume Tab** – Education, professional experience, key projects, and skill progress bars
- **Contact Tab** – Embedded Google Map (Pune) and a working contact form via Web3Forms
- **Download Resume Button** – Direct PDF download from the sidebar
- **Social Links** – GitHub, LinkedIn, Twitter, Instagram, YouTube

---

## 🚀 Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/dipakkalaskar/portfolio.git
cd portfolio
```

Or simply download the ZIP and extract it.

### 2. Add Your Profile Photo

Replace `assets/images/my-avatar.png` with your own photo. Keep the filename the same or update the `src` in `index.html`.

### 3. Add Your Resume PDF

Place your resume PDF at:

```
assets/Dipak_Kalaskar_Resume.pdf
```

This is linked to the **Download Resume** button in the sidebar. If you rename the file, update the `href` in `index.html`:

```html
<a href="./assets/YOUR_FILE_NAME.pdf" download="YOUR_FILE_NAME.pdf" class="resume-download-btn">
```

### 4. Open in Browser

No build tools or dependencies needed. Just open `index.html` directly in your browser:

```bash
open index.html
# or double-click index.html in your file explorer
```

---

## 📬 Contact Form Setup

The contact form uses **Web3Forms** (free service). The access key is already set in `index.html`:

```html
<input type="hidden" name="access_key" value="69ad5cad-959a-4c94-a26c-8318d2bcd345">
```

To use your own key:
1. Go to [https://web3forms.com](https://web3forms.com)
2. Enter your email to get a free access key
3. Replace the `value` in the hidden input above

---

## 🌐 Deployment

### GitHub Pages

1. Push the project to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://yourusername.github.io/repository-name/`

### Netlify

1. Go to [https://netlify.com](https://netlify.com)
2. Drag and drop your project folder onto the Netlify dashboard
3. Your site is instantly live with a public URL

### Vercel

1. Go to [https://vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Click Deploy — no configuration needed

---

## 🛠️ Customization

| What to change | Where |
|---|---|
| Name, title, location | `index.html` – sidebar section |
| Profile photo | `assets/images/my-avatar.png` |
| Social media links | `index.html` – `.social-list` |
| About bio text | `index.html` – `.about-text` section |
| Experience / Projects | `index.html` – `.timeline` sections in Resume article |
| Skill percentages | `index.html` – `.skill-progress-fill` `style="width: X%"` |
| Resume PDF | `assets/Dipak_Kalaskar_Resume.pdf` |
| Map location | `index.html` – `<iframe src="...">` in Contact article |
| Colors / fonts | `assets/css/style.css` – `:root` CSS variables |

---

## 📦 Tech Stack

- **HTML5** – Semantic markup
- **CSS3** – Custom properties, Grid, Flexbox, animations
- **JavaScript (ES6)** – DOM manipulation, event handling
- **Ionicons** – Icon library (loaded via CDN)
- **Google Fonts** – Poppins font family
- **Web3Forms** – Contact form backend (free tier)

---

## 📄 License

This project is open source and free to use for personal portfolios.

---

## 👤 Author

**Dipak Waman Kalaskar**
- 📧 dipakk.sit.comp@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/dipakkalaskar/)
- 🐙 [GitHub](https://github.com/dipakkalaskar)
- 🌐 Portfolio – this project!
