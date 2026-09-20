# 🌟 Personal "About Me" Website

A clean, modern, and beginner-friendly personal portfolio / "about-me" website built with pure HTML5 and CSS3. Zero complex dependencies or build tools needed.

---

## 📁 File Structure

```text
anity/
├── index.html               # Main website structure and content
├── style.css                # Visual styling, colors, and layout
├── avatar-placeholder.svg   # Vector avatar placeholder (no external image needed)
└── README.md                # Quick-start instructions & customization guide
```

---

## 🚀 How to View the Website

You don't need any server installed to test this website:

1. Locate `index.html` in your file explorer (`c:\Users\viainfo\OneDrive\Documents\anity`).
2. **Double-click `index.html`** or right-click and choose **"Open with"** -> **Google Chrome**, **Microsoft Edge**, or your favorite browser.
3. The website will immediately load!

---

## 🛠️ Beginner Customization Guide

### 1. Change Your Name and Bio (`index.html`)
Open `index.html` in any code editor (such as VS Code or Notepad):
- Search for **`Alex Morgan`** and replace it with your full name.
- Update the `<p class="profile-title">` to match your profession or hobby (e.g. *Frontend Engineer*, *Data Scientist*, *Student*).
- Edit the text inside `<section class="card bio-card">` to tell your own personal story and background.

### 2. Replace the Photo Placeholder (`avatar-placeholder.svg`)
- Copy your photo (e.g. `profile.jpg` or `profile.png`) into this project folder.
- In `index.html`, find:
  ```html
  <img src="avatar-placeholder.svg" alt="Profile photo placeholder" ...>
  ```
- Change `avatar-placeholder.svg` to your file name:
  ```html
  <img src="profile.jpg" alt="Profile photo of [Your Name]" ...>
  ```

### 3. Update Social & Portfolio Links (`index.html`)
Look for `<div class="links-grid">` in `index.html`. Replace the placeholder links:
- Update `href="https://example.com/portfolio"` with your actual portfolio URL.
- Update `href="https://github.com"` with your GitHub profile (e.g. `https://github.com/yourusername`).
- Update `href="https://linkedin.com"` with your LinkedIn profile link.
- Update `href="mailto:your.email@example.com"` with your actual contact email.

### 4. Customize Theme Colors (`style.css`)
Open `style.css` and check lines 16–29 under `:root`:
- `--primary-color`: The main accent color (defaults to indigo `#4f46e5`). Change it to your favorite color (e.g., `#0ea5e9` for sky blue, `#10b981` for emerald green, or `#ec4899` for pink).
- The website automatically includes **Dark Mode support** that adjusts to the visitor's device settings.

---

## 🌐 Next Steps: Publishing Online (Free)
When you're ready to share your site with the world:
1. **GitHub Pages**: Upload these files to a GitHub repository and turn on Pages in repository settings.
2. **Netlify or Vercel**: Drag and drop this folder for instant, free static hosting with a custom domain.
