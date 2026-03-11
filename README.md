# Cheng Kai Jie — Portfolio

A clean, minimal personal portfolio website built with HTML, CSS, and vanilla JavaScript. Hosted on GitHub Pages.

## 🚀 Live Site

> **[https://chengkaijie0.github.io/portfolio/]**  
> *(Replace `your-username` with your GitHub username after deploying)*

---

## 📁 Project Structure

```
portfolio/
├── index.html          ← Main portfolio page (everything is here)
├── resume.pdf          ← Your resume (add this file)
├── assets/             ← Optional: project files, images
│   ├── your-report.pdf
│   ├── your-pitch.pptx
│   └── ...
└── README.md
```

---

## ✏️ How to Customise

### 1. Update Personal Info
Open `index.html` and search for these placeholders:

| Placeholder | Replace with |
|---|---|
| `kaijie@email.com` | Your real email |
| `your-linkedin` | Your LinkedIn username |
| `your-username` | Your GitHub username |
| `resume.pdf` | Path to your resume file |

### 2. Add / Edit Projects
Each project is a `<div class="project-card">` block. Copy one and update these `data-` attributes:

```html
<div class="project-card reveal" data-type="code"
  data-title="Your Project Title"
  data-desc="Full description shown in the modal popup."
  data-tech="Python, React, SQL"
  data-github="https://github.com/your-username/repo"
  data-live="https://your-demo-link.com"
  data-file="assets/your-file.pdf">
```

**Project types:** `code` | `report` | `ppt` | `design`

### 3. Add Your Files
Place your PDF, PPTX, DOCX files in the `assets/` folder and link them via `data-file="assets/filename.pdf"`.

### 4. Update Skills
Find the `.skills-grid` section and edit the `data-width` values (0–100) and skill tag text.

---

## 🌐 Deploy to GitHub Pages (Step-by-Step)

1. **Create a new GitHub repository** named `your-username.github.io`  
   *(This is the magic name — it auto-publishes to GitHub Pages)*

2. **Clone the repo locally:**
   ```bash
   git clone https://github.com/your-username/your-username.github.io
   cd your-username.github.io
   ```

3. **Copy your portfolio files** into this folder (`index.html`, `resume.pdf`, `assets/`)

4. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial portfolio launch 🚀"
   git push origin main
   ```

5. **Visit your site** at `https://your-username.github.io` — it goes live in ~1 minute!

---

## 🛠 Features

- ✅ Filterable project gallery (Code / Reports / PPT / Design)
- ✅ Click-to-open project detail modals
- ✅ Smooth scroll-reveal animations
- ✅ Animated skill bars
- ✅ Responsive — works on mobile, tablet, desktop
- ✅ Zero dependencies — pure HTML/CSS/JS
- ✅ Fast — no frameworks, no build step needed

---

## 📬 Contact

**Cheng Kai Jie** · Final Year Undergraduate · Open to Full-Time Roles  
[LinkedIn](https://linkedin.com/in/your-linkedin) · [GitHub](https://github.com/your-username) · [Email](mailto:kaijie@email.com)
