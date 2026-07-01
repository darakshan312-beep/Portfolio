# Darakhshan Arshad - Personal Portfolio Website

> My personal portfolio website built from scratch using only HTML, CSS, and JavaScript. No frameworks used.

---

##  About This Project

This is my personal portfolio website where I showcase my skills, projects, and learning journey as a Computer Science student. I built everything from scratch, no templates, no frameworks, just plain HTML, CSS, and JavaScript.

The website has a dark theme with blue and purple colors, smooth animations, and works well on phones, tablets, and computers.

---

##  Features

- **Dark Mode Design** — easy on the eyes, looks clean and modern
- **Typing Animation** — the hero section types out different roles automatically
- **Animated Particles** — floating dots in the background of the hero section
- **Smooth Scroll Animations** — sections fade in as you scroll down
- **Skill Progress Bars** — visually show skill levels
- **Project Cards** — each project has its own card with tech badges
- **Learning Journey Timeline** — shows what I completed, what I'm learning, and what's coming next
- **Contact Form** — visitors can fill out a message form
- **GitHub Section** — includes a contribution graph and repository list
- **Responsive Layout** — looks good on all screen sizes (mobile, tablet, desktop)
- **Back to Top Button** — appears when you scroll down
- **Mobile Menu** — a slide-in menu for phones

---

##  Folder Structure

```
portfolio/
│
├── index.html              ← main HTML file (all the content)
├── style.css               ← all the styling and design
├── script.js               ← animations and interactivity
│
└── assets/
    ├── images/
    │   └── portfolio-banner.svg    ← project banner image
    └── icons/                      ← (for future icons)
```

---

##  Built With

| Technology | What it does |
|---|---|
| HTML5 | Structure and content of the website |
| CSS3 | Design, colors, animations, layout |
| JavaScript | Typing effect, scroll animations, particles |

No libraries. No frameworks. No npm. Just three files.

---

##  How to Run This Project Locally

You do not need to install anything special. Just follow these steps:

### Option 1 — Simplest Way (just double click)

1. Download all the files
2. Make sure the folder looks like this:
```
portfolio/
├── index.html
├── style.css
├── script.js
└── assets/
    └── images/
        └── portfolio-banner.svg
```
3. Double click `index.html`
4. It will open in your browser 

---

### Option 2 — Using Python (recommended)

If you have Python installed on your computer:

**Step 1** — Open your terminal or command prompt

**Step 2** — Go to your portfolio folder
```bash
cd path/to/portfolio
```


**Step 3** — Open your browser and go to
```
http://localhost:8000
```

That's it! 

---

### Option 3 — Using VS Code (easiest for beginners)

1. Open the portfolio folder in **VS Code**
2. Install the **Live Server** extension (search for it in Extensions tab)
3. Right click on `index.html`
4. Click **"Open with Live Server"**
5. Your browser will open automatically 

---

##  How to Customize It

Here are the most common things you might want to change:

### Change your name or text
Open `index.html` and search (Ctrl+F) for the text you want to change. For example, search `Darakhshan Arshad` and replace it with your name.

### Change colors
Open `style.css` and look for these lines near the top:
```css
--accent-blue: #5b8cff;
--accent-purple: #9b6bff;
```
Change the color codes to any color you like.

### Add a project
Find the **Projects Section** in `index.html` (search for `<!-- PROJECTS -->`). Copy one project card block and paste it, then change the title, description, and tech badges.

### Add your resume
Put your resume PDF inside the `assets/` folder and name it:
```
Darakhshan_Arshad_Resume.pdf
```
The Download Resume button will work automatically.

### Add your real links
Search for these in `index.html` and replace with your actual links:
- `https://github.com/` → your GitHub profile link
- `https://linkedin.com/` → your LinkedIn profile link
- `darakhshan.arshad@example.com` → your real email


---

## 🌐 Live Demo

Coming soon — will be deployed on GitHub Pages.

---


*Built with curiosity and a lot of learning - Darakhshan Arshad*