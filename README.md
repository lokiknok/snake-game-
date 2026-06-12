# snake-game-
🐍 A modern, high-performance, responsive Snake game built with HTML5 Canvas and vanilla JavaScript. Features a realistic organic snake design, fluid keyboard/swipe controls, wrap-around screen boundaries, and a customizable high score dashboard. Optimized for PC and Mobile.
# 🐍 Snake Reborn

A premium, modern rewrite of the classic arcade Snake game. Built entirely using a single highly-optimized file of vanilla HTML5, CSS3, and JavaScript. 

This version introduces an **organic snake aesthetic**, **wrap-around screen physics**, and native **hybrid controls** engineered to deliver a seamless experience on both Desktop PCs and Mobile touchscreen devices.

---

## ✨ Features

* **🎨 Organic Visual Design:** The snake features a smooth gradient body that dynamically tapers towards the tail, glowing neon accents, and directional eyes.
* **🌐 Wrap-Around Boundaries:** Hitting the outer walls won't kill you! The snake seamlessly warps to the opposite side of the screen.
* **💥 Custom Collision Rules:** You only die if the snake bites its own tail. 
* **📱 Hybrid Input System:** * **PC:** Arrow keys or `W`, `A`, `S`, `D` keys.
  * **Mobile:** Intuitive, full-screen **Swipe Gestures** (no ugly, bulky buttons blocking your view).
* **⚙️ Interactive Settings Panel:** Tweak your scoreboard parameters by setting a custom **High Score Ante** or completely wiping the data clean.
* **💾 Local Storage Persistence:** Your highest score stays saved in your browser even if you close or refresh the page.

---

## 🕹️ How to Play

1. **Start the Game:** Open the page and click/tap **START**.
2. **Steer the Snake:**
   * **On Desktop:** Use your keyboard arrows or `W` (up), `A` (left), `S` (down), `D` (right).
   * **On Phone:** Swipe your thumb anywhere on the game board in the direction you want to turn.
3. **Objective:** Eat the glowing red apples to grow and score points. Avoid crashing into your own tail!

---

## 🛠️ Installation & Setup

Because this entire game is self-contained in a single optimized file, deploying it takes less than 30 seconds:

1. Clone or download this repository.
2. Double-click the `index.html` file to launch it instantly in any web browser.

*Alternatively, you can turn on **GitHub Pages** in your repository settings to host it as a free playable website link!*

---

## 🚀 Optimization Details

* **Anti-Direction Lock:** Prevents the rapid double-tap exploit that causes snakes in lesser engines to accidentally crash backwards into their own necks.
* **Viewport Resizing:** Uses dynamic CSS and Javascript bounds-checking to scale down perfectly for small mobile screens (`320px`) up to ultra-wide desktop monitors.
* **Zero Mobile Bounce:** Utilizes `touch-action: none;` to ensure fast swiping on mobile screens doesn't accidentally scroll or shake the browser page.
