# 💎 FinPal — Next-Gen Personal Finance Tracker & AI Assistant

FinPal is a futuristic, Gen Z-inspired web application that turns boring money management into an immersive visual experience. Built with high-performance 3D vector graphics, interactive spring physics, and an AI-driven data layer, FinPal makes tracking investments, analyzing text data, and observing market inflation as engaging as scrolling through your favorite media feeds.

---

## 🧭 The Tech Stack: Explained for a 5-Year-Old 🧸

How does FinPal work under the hood? Let's break down the magic tools we used:

* **⚛️ React 19:** Think of React as a box of Lego bricks. Instead of building a whole castle out of one massive piece of plastic, React lets us build small, reusable bricks (like a login card, a button, or a menu item) and snap them together seamlessly.
* **⚡ Vite:** Imagine you are drawing a picture. Old tools make you wait for the ink to dry completely before you can see your changes. Vite is like a magic pencil—the exact millisecond you change a line of code, it instantly appears on your screen without reloading.
* **🎨 CSS Keyframes & Glassmorphism:** We used special styling stylesheets to make the app look like it is made of frosted glass glowing with neon lights. It uses the computer's graphics card to stay fast and shiny.
* **🛸 Three.js (The 3D Engine):** Normal websites are flat, like a piece of paper. Three.js gives the browser a pair of 3D glasses! It allows us to create real math-based shapes (like spheres and cylinders), paint them with shiny metallic textures, and light them up with digital spotlights.
* **🎬 Framer Motion (The Physics Engine):** Usually, digital animations look robotic. Framer Motion acts like invisible rubber bands and springs attached to your UI blocks. When a window pops up, it bounces and slides naturally, obeying the laws of virtual physics.
* **📊 Chart.js & React-Chartjs-2:** This tool takes messy piles of numbers (like your daily expenses) and paints them into beautiful, easy-to-read colorful pie charts and line graphs instantly.

---

## 🏗️ Folder Structure Blueprint 🗺️

Here is how the project map is organized. It’s like a house with designated rooms:

```text
finpal/
├── 📁 node_modules/         # The heavy toy chest filled with pre-made tools we downloaded.
├── 📁 public/               # The front porch where we keep open public assets.
├── 📁 src/                  # The main kitchen where we cook all of our code!
│   ├── 📁 assets/           # Digital artwork, fonts, and images.
│   ├── 📁 components/       # Our specialized Lego bricks:
│   │   ├── 🪙 FloatingCoinsHero.jsx # Renders the spinning, floating 3D coins on login.
│   │   ├── 🃏 Card3D.jsx            # The interactive dashboard block that tilts.
│   │   └── 🌐 TransactionGlobe.jsx  # The spinning wireframe 3D matrix globe.
│   ├── 📝 index.css         # The master coloring book where all neon animations are defined.
│   ├── 🚀 main.jsx          # The ignition switch that starts the entire engine.
│   └── 📱 App.jsx           # The master layout that connects all pages together.
├── 📄 index.html            # The skeleton outline framework of our webpage.
├── 📄 package.json          # The shopping list that remembers every tool our app needs.
└── 📄 vite.config.js        # The instruction manual telling Vite how to run our project fast.
