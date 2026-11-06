# ❤️ Glowing Beating Heart Project

This is the viral animated glowing heart trend built with HTML5 Canvas, mathematical parametric curves, and neon particle bloom.

## 🚀 How to View It
1. **Directly in Browser:** Double-click [`index.html`](./index.html) to open it in Chrome, Edge, or Safari.
2. **VS Code Live Server (Optional):** Right-click `index.html` in VS Code and select **"Open with Live Server"**.
3. **Full Screen:** Press **F11** in your browser for the full aesthetic effect!

## ✏️ How to Customize in VS Code

Open [`index.html`](./index.html) in VS Code:

- **Change the Name:**
  Find lines ~68-71:
  ```html
  <div class="name-title" id="nameText">YOUR NAME</div>
  <div class="subtitle" id="subText">Forever & Always ❤️</div>
  ```
  Replace `YOUR NAME` with whoever you want to dedicate it to.

- **Change Colors:**
  Look at lines ~83-89:
  ```javascript
  baseColor: '#ff2d75',    // Main neon glow
  accentColor: '#ff94b8',  // Secondary highlight
  ```
  Try:
  - **Purple/Lavender:** `#a855f7` & `#d8b4fe`
  - **Cyan/Ice Blue:** `#00e5ff` & `#a7f3d0`
  - **Golden Glow:** `#f59e0b` & `#fde68a`

- **Interactive:**
  Clicking anywhere on the screen bursts glowing spark particles!
