# website
A site dedicated to people in relationships.
# 💖 Our Eternal Story — A Journey of Love

A luxury, interactive single-page romantic web experience designed to preserve memories, display shared moments, and track time spent together in real-time.

---

## ✨ Features

- 🔒 **Interactive Lock Screen:** Unlocks by entering a special anniversary date, which dynamically initializes the love counter.
- ⏳ **Real-Time Love Counter:** Live timer counting elapsed days, hours, minutes, and seconds from the entered date.
- 📸 **Polaroid Gallery:** Responsive photo grid featuring classic polaroid frames, subtle tilt angles, and an interactive zoom lightbox.
- ✉️ **Secret Love Letter:** Unveils a heartfelt letter with a smooth typewriter animation when the wax seal is clicked.
- 🎵 **Ambient Music Player:** Floating audio controller with Web Audio API synthesis fallback in case no external MP3 is supplied.
- 🌸 **Floating Canvas Hearts:** Lightweight ambient floating hearts background with click/tap particle bursts.

---

## 🚀 Live Deployment via GitHub Pages

1. **Create a Repository:** Create a new repository on GitHub.
2. **Rename Main File:** Ensure the main HTML file is named `index.html` (rename it from `romantic_story_application.html`).
3. **Upload Assets:** Place your media files in the repository root:
   - Images named `1.jpg` through `16.jpg`.
   - Audio file named `music.mp3` (optional).
4. **Enable GitHub Pages:**
   - Go to **Settings** > **Pages** in your repository.
   - Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
   - Click **Save**.
5. Your live site URL will be generated within a minute.

---

## 🛠️ Customization

Open `index.html` and edit the `CONFIG` object inside the `<script>` tag near the bottom:

```javascript
const CONFIG = {
  musicUrl: "music.mp3", // Path to background audio
  coupleNames: "Our Eternal Story",
  loveLetter: "Type your personal romantic letter here...",
  galleryImages: [
    { url: "1.jpg", caption: "Photo Caption", date: "Special Date", rotate: "-2deg" },
    // Customize your 16 memories here
  ]
};
