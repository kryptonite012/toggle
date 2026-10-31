# 🌗 Dark Mode Toggle UI

A modern, animated **Dark Mode Toggle Interface** built using pure **HTML, CSS, and JavaScript**. This project demonstrates how to implement a visually rich theme switcher with smooth transitions, persistent user preferences, and interactive UI elements.

---

## ✨ Features

* 🌞🌙 **Light & Dark Mode Toggle**

  * Switch between light and dark themes with a smooth animated toggle.

* 💾 **Persistent Theme Storage**

  * Saves user preference using `localStorage`.
  * Automatically restores the last selected theme on reload, before the page paints (no flash of the wrong theme).
  * Follows live system theme changes until you choose a theme yourself.



* 🎨 **Beautiful UI Design**

  * Soft gradients, blur blobs, and grain texture
  * Clean typography using **Syne** and **DM Mono**
  * Smooth transitions and micro-interactions

* ⚡ **Interactive Animations**

  * Toggle ripple effect
  * Pulsing storage indicator
  * Smooth theme transitions

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling, animations, variables
* **JavaScript (Vanilla)** – Logic & interactivity
* **localStorage API** – Persistence

---

## 📂 Project Structure

```
📁 Dark-Mode-Toggle
 ├── index.html   # Main file (HTML + CSS + JS)
```

## 🧠 Key Concepts Used

* CSS Variables (`:root`, `[data-theme="dark"]`)
* DOM Manipulation
* Event Listeners
* localStorage Handling
* Responsive UI Design
* Micro-interactions & Animations

---

## 📸 Preview

* Light Mode ☀️ → Clean, soft background
* Dark Mode 🌙 → Deep, low-light friendly UI
* Smooth toggle animation with ripple effect

---

## 📈 Possible Improvements

* Add **system auto-sync toggle**
* Add **more themes (e.g., sepia, neon)**
* Store data in backend (for logged-in users)
* Add **keyboard shortcut (e.g., "D" for dark mode)**
* Integrate into a larger app (dashboard, portfolio, etc.)

---

## 💡 Use Cases

* Portfolio websites
* Dashboards / admin panels
* Web apps with accessibility support
* UI/UX learning projects

---

## Run locally

Open `index.html` in any modern browser. No install or build step is needed. To serve it over HTTP instead:

```bash
python3 -m http.server 8000
```

## Deploy

This repository includes a GitHub Pages workflow (`.github/workflows/pages.yml`).

1. Go to **Settings → Pages** and set **Source** to **GitHub Actions**.
2. Push to the default branch. The site is published at `https://<username>.github.io/toggle/`.

Any static host (Netlify, Vercel, Cloudflare Pages) also works: publish the repository root with no build command.

---

## 🏁 Conclusion

This project is a great example of combining **design + functionality**. It not only toggles themes but also enhances user experience with animations, persistence, and clean UI design.

