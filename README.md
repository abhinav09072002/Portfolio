# Abhinav Verma — Portfolio Website

A clean, dark-themed personal portfolio built with pure HTML, CSS, and JavaScript. No frameworks, no build tools — just drop it on GitHub Pages and go live instantly.

## 🚀 Deploy to GitHub Pages (5 minutes)

1. Create a new GitHub repository named exactly: `yourusername.github.io`  
   *(Replace `yourusername` with your actual GitHub username)*

2. Upload all files from this zip into that repository.

3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**

4. Your site will be live at: `https://yourusername.github.io`

## 📁 File Structure

```
portfolio/
├── index.html        ← Main portfolio page (edit this)
├── resume.pdf        ← Add your resume PDF here (for download button)
└── README.md         ← This file
```

## ✏️ How to Customize

### Update your GitHub links
Search for `abhinav09072002` in `index.html` and replace with your actual GitHub username.

### Update your LinkedIn
Search for `abhinavverma09` and replace with your LinkedIn handle.

### Add your resume PDF
Place your `resume.pdf` file in the same folder as `index.html`.  
The "Download Resume" button will automatically serve it.

### Update project links
Find each `project-links` section and add your real GitHub repo URLs.

### Change your name or info
All personal details are in `index.html` — search and replace as needed.

## 🎨 Tech Stack

- Pure HTML5, CSS3, Vanilla JavaScript
- Google Fonts (DM Serif Display, DM Sans, JetBrains Mono)
- Zero dependencies — works offline after first load
- Mobile responsive
- Smooth scroll + fade-in animations
- ATS-compatible resume download

## 📬 Contact Form

The contact form currently shows a success state on submit but doesn't send emails (no backend). To wire it up:
- Use [Formspree](https://formspree.io) — free, just change the form `action` attribute
- Or use [EmailJS](https://emailjs.com) with a small JS snippet

## License

Free to use and modify for personal portfolios.
