# 🎓 Personal Portfolio Website

> A clean, modern, and fully responsive personal portfolio built with **pure HTML5 & CSS3** — no frameworks, no JavaScript, no backend.

---

## 📸 Preview

| Desktop | Mobile |
|--------|--------|
| *(Replace with screenshot)* | *(Replace with screenshot)* |

---

## ✨ Features

- ✅ Fully responsive — works on Desktop, Laptop, Tablet, and all Mobile screens
- ✅ CSS-only mobile hamburger navigation menu (no JavaScript)
- ✅ Smooth scroll and hover animations
- ✅ Hero section with profile image, quick stats, and CTA buttons
- ✅ About Me section with education, interests, and goals
- ✅ Skills section with animated progress bars
- ✅ Projects section with image cards and overlay links
- ✅ Achievements section with timeline layout
- ✅ Contact section with email, phone, GitHub, and LinkedIn links
- ✅ Professional footer with social links
- ✅ Accessible: keyboard navigation, ARIA labels, reduced-motion support
- ✅ GitHub Pages ready — zero configuration needed

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| HTML5     | Page structure and semantic markup |
| CSS3      | Styling, layout (Flexbox/Grid), animations |
| Google Fonts | Typography (Inter + Space Grotesk) |
| Font Awesome 6 | Icons (via CDN) |

> ⚠️ No JavaScript, no React, no Node.js, no database, no paid APIs.

---

## 📁 Folder Structure

```
personal-portfolio/
├── index.html          ← Main HTML file (all sections)
├── style.css           ← All styles (responsive + animations)
├── assets/
│   ├── profile.jpg     ← Your profile photo (replace placeholder)
│   ├── project1.jpg    ← Screenshot of Project 1
│   ├── project2.jpg    ← Screenshot of Project 2
│   └── project3.jpg    ← Screenshot of Project 3
└── README.md           ← This file
```

---

## ✏️ How to Personalise

Open `index.html` and search for `<!-- ✏️` comments — every section has clear markers showing what to change:

| What to edit | Where to find it |
|-------------|-----------------|
| Your name | `hero-name` class + `nav-logo` + footer |
| Short bio | `hero-bio` paragraph |
| Education details | `info-card` inside About section |
| Career interests & goals | `info-card` blocks in About |
| Skills & levels | `skill-bar` `--bar-width` values in Skills |
| Project titles, descriptions, links | `project-card` articles |
| Achievements | `achieve-item` divs |
| Email | Already set: `alvsai825@gmail.com` |
| Phone | Already set: `+91 9666096123` |
| GitHub | Already set: `@alvsai825-bot` |
| LinkedIn | Replace `your-linkedin-username` |

To change profile photo: save your image as `assets/profile.jpg`.

---

## 🚀 Installation & Local Preview

No installation required! Just open the file:

```bash
# Option 1 – Double-click
Open index.html in any browser (Chrome, Firefox, Edge)

# Option 2 – VS Code Live Server
1. Install the "Live Server" extension in VS Code
2. Right-click index.html → "Open with Live Server"
```

---

## 📤 GitHub Pages Deployment (Step-by-Step)

### Step 1 – Create a GitHub Repository

1. Go to [https://github.com](https://github.com) and log in
2. Click the **+** icon → **New repository**
3. Name it: `portfolio` (or `your-username.github.io` for a root site)
4. Set to **Public**
5. Click **Create repository**

### Step 2 – Upload Your Files

**Option A – GitHub Web UI (easiest for beginners):**

1. Open your new repository on GitHub
2. Click **Add file** → **Upload files**
3. Drag and drop the entire `personal-portfolio` folder contents
4. Click **Commit changes**

**Option B – Git Command Line:**

```bash
# Navigate into your project folder
cd personal-portfolio

# Initialise Git
git init

# Add all files
git add .

# First commit
git commit -m "Initial portfolio upload"

# Connect to GitHub (replace YOUR-USERNAME and REPO-NAME)
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git

# Push
git push -u origin main
```

### Step 3 – Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → scroll to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose **Branch: main** and folder **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes, then visit:

```
https://YOUR-USERNAME.github.io/REPO-NAME/
```

✅ Your portfolio is now live on the internet — for free!

---

## 🔗 Live Demo

> Replace this line with your GitHub Pages URL after deployment

---

## 👤 Author

- **Name:** Alvaro Sai
- **Email:** alvsai825@gmail.com
- **GitHub:** [@alvsai825-bot](https://github.com/alvsai825-bot)
- **LinkedIn:** *(Add your LinkedIn URL)*

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

You are free to use, copy, and modify this for your personal portfolio.

---

*Built with ❤️ using HTML5 & CSS3*
