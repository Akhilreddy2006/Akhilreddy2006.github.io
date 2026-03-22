# Akhil Reddy Surapureddy — Portfolio Website

> Lab Assignment | 23CSE113 User Interface Design | Amrita Vishwa Vidhyapeetham

---

## Overview

A single-page responsive portfolio website showcasing education, skills, projects and certifications. Built using HTML and CSS concepts from the course, with JavaScript for interactivity.

---

## Sections

| # | Section | What's Inside |
|---|---------|---------------|
| 1 | **Home** | Name, tagline, intro paragraph, View Projects button |
| 2 | **About** | Personal info table, resume download button |
| 3 | **Education** | B.Tech, Intermediate and Secondary details with scores |
| 4 | **Skills** | Languages, tools, web & database, soft skills |
| 5 | **Projects** | 5 projects with tech tags, linked to GitHub |
| 6 | **Certifications** | 9 certificates in a responsive grid |
| 7 | **Contact** | Contact info + message form (EmailJS) |

---

## Technologies Used

**HTML & CSS** — all core concepts from course PPTs
- Box model, float layout, selectors, hover effects
- `linear-gradient` and `radial-gradient` backgrounds
- `font-family`, `letter-spacing`, `text-shadow`, `text-transform`
- Responsive `@media` queries (768px, 480px, 360px)

**JavaScript** — for enhanced interactivity
- Scroll reveal using `IntersectionObserver`
- `@keyframes` animations on page load
- `transition` and `transform` on hover
- EmailJS for contact form email delivery

---

## Setting Up the Contact Form

The form uses **EmailJS** — free, no backend needed.

1. Sign up at [emailjs.com](https://www.emailjs.com)
2. Connect your Gmail under **Email Services**
3. Create a template — use variables `{{from_name}}` `{{from_email}}` `{{subject}}` `{{message}}`
4. Replace these three values in `index.html`:

```
YOUR_PUBLIC_KEY    →  Account → General → Public Key
YOUR_SERVICE_ID    →  Email Services → Service ID
YOUR_TEMPLATE_ID   →  Email Templates → Template ID
```

---

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages → Branch: main → Save**
4. Live at: `https://your-username.github.io/repo-name`

---

## Files

```
index.html   →  Complete website (CSS, JS, images all embedded)
README.md    →  This file
```

> All certificate images and resume PDF are embedded as base64 inside `index.html` — no extra files needed.

---

**Akhil Reddy Surapureddy**  
akhilreddy.surapureddy@gmail.com | [LinkedIn](https://linkedin.com/in/Akhil-reddy-surapureddy) | [GitHub](https://github.com/Akhilreddy2006)
