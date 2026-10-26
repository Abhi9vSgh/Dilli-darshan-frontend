# 🏛️ DilliDarshan AI — Frontend

A clean, responsive, and lightweight client interface for **DilliDarshan AI**, an intelligent digital tour companion designed to help tourists and locals explore Delhi's monuments, heritage sites, food walks, and metro routes.

Built with vanilla web technologies for zero-dependency speed, native browser compatibility, and local asset rendering.

---

## 🚀 Key Features

* **Real-Time Interactive Tour Chat:** Clean message thread interface supporting user inputs, instant suggestions, and context badges.
* **Offline Asset Support:** Local monument imagery and UI iconography loaded directly from the `assets/` directory without requiring external CDN requests.
* **Backend Health Monitoring:** Real-time visual badge (`● FastAPI Connected` / `● Offline`) reflecting API connectivity status.
* **Source Attribution Badges:** Displays verifiable retrieval sources (e.g., `Guide Source: Lal Qila Archives (ChromaDB)`) under verified answers.
* **Quick Query Chips:** One-tap shortcut chips for popular Delhi destinations (e.g., *Red Fort timings*, *Qutub Minar Metro*, *Chandni Chowk food trail*, *India Gate visit*).
* **Zero-Build Lightweight Setup:** Pure HTML5, CSS3, and modern JavaScript—no bundlers, Webpack, or npm build steps required.

---

## 🛠️ Tech Stack

* **Structure:** HTML5 Semantic Elements
* **Styling:** Modern CSS3 (CSS Variables, Flexbox, CSS Grid, Dark Theme Palette)
* **Logic & Networking:** JavaScript (ES6+, Fetch API, Async/Await)
* **Media & Graphics:** Local static assets (Images, SVGs, Monument Photos)
* **Backend Protocol:** REST API communicating with FastAPI (`http://127.0.0.1:8000`)

---

## 📁 File Structure

```text
Dilli-Darshan/
│
├── assets/            # Offline static media (monument photos, icons, banners)
│   ├── monuments/     # High-res offline monument pictures (Red Fort, Qutub Minar, etc.)
│   └── icons/         # UI icons and logo badges
│
├── index.html         # Main chat interface and layout
├── style.css          # Responsive design, theme variables, and chat bubbles
└── app.js             # API communication, DOM handling, and dynamic rendering# Dilli-darshan-frontend
welcoming page of dilli darshan
