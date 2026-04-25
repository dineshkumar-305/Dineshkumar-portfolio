# Dineshkumar G — Personal Portfolio

A responsive, dark-themed personal e-portfolio built with pure HTML, CSS, and JavaScript.

---

## 📁 File Structure

```
dineshkumar_portfolio.html   ← Single-file portfolio (open in any browser)
README.md                    ← This file
```

---

## 🚀 Getting Started

No build tools or dependencies required. Just open the file:

```bash
# Option 1 — Double-click the file in your file manager

# Option 2 — Open via terminal
open dineshkumar_portfolio.html        # macOS
start dineshkumar_portfolio.html       # Windows
xdg-open dineshkumar_portfolio.html   # Linux
```

---

## ✨ Features

- **Single-file** — everything (HTML, CSS, JS) in one `.html` file
- **Dark theme** — deep navy background with teal and purple accents
- **Smooth animations** — scroll-triggered fade-ins on every section
- **Responsive** — works on desktop, tablet, and mobile
- **Sticky navigation** — fixed top nav with smooth scrolling
- **No frameworks** — zero dependencies, no npm, no build step

---

## 📄 Sections

| Section | Description |
|---|---|
| Hero | Name, role, stats (projects, certifications, CGPA) |
| About | Bio, contact info, languages |
| Education | Timeline — SRM IST, Class XII, Class X |
| Projects | 4 projects with tech stack tags |
| Skills | 6 skill groups (languages, web, DB, IoT, etc.) |
| Certifications | Google AI-ML, AWS, MongoDB, HackerRank, MATLAB, Paper |
| Contact | Email, phone, LinkedIn, location |

---

## 🎨 Design

| Property | Value |
|---|---|
| Theme | Dark |
| Primary accent | `#5DCAA5` (Teal) |
| Secondary accent | `#AFA9EC` (Purple) |
| Display font | Playfair Display (Google Fonts) |
| Body font | DM Sans (Google Fonts) |
| Mono font | DM Mono (Google Fonts) |

> Fonts are loaded from Google Fonts CDN — an internet connection is required for correct font rendering on first load.

---

## ✏️ Customisation

All content is plain HTML — no configuration files needed.

**To update your LinkedIn URL**, find this line and replace the `href`:
```html
<a href="https://linkedin.com" target="_blank" class="contact-link">
```

**To change the accent color**, update the CSS variable near the top:
```css
--accent: #5DCAA5;
```

**To add a new project**, copy a `.project-card` block inside `#projects` and edit the content.

---

## 🌐 Deployment

The portfolio can be hosted on any static hosting platform:

- **GitHub Pages** — push to a repo, enable Pages in Settings
- **Netlify** — drag and drop the `.html` file at netlify.com/drop
- **Vercel** — `vercel --name portfolio`

---

## 👤 Owner

**Dineshkumar G**  
B.Tech, Computer Science and Engineering  
SRM IST-Trichy · Graduating 2027  
dk8862@srmist.edu.in · +91 9345194748
