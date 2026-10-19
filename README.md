# 🙃 Dinnerbone.css

A Minecraft-inspired utility library to flip your web elements upside down dynamically.

---

## 🚀 What is this project?

Have you ever wanted to completely flip a layout, component, or card upside down for a puzzle game, an anti-pattern design, or a specialized user interface? **Dinnerbone.css** provides highly optimized utility classes to shift the gravity of your HTML elements seamlessly with just one class.

---

## 📦 Installation & Setup

You can integrate this library straight into your modern web applications via package managers:

```bash
npm install dinnerbone.css
```

Or quickly inject it via CDN in your HTML header:

```html
<link rel="stylesheet" href="https://jsdelivr.net">
```

---

## 🛠️ Usage Blueprint

### 1. Absolute Layout Inversion 🔀
Add the core class `.dinnerbone` to any container to turn it and its entire content completely upside down.

```html
<div class="card dinnerbone">
  <h1>I am upside down!</h1>
  <p>Everything inside this container rotates 180 degrees.</p>
</div>
```

### 2. Counter-Flipped Nested Containers (Smart Reading) 🧩
If you want the general card layout to be flipped but want specific elements (like a profile picture, button, or text) to remain readable right side up, use the counter utility:

```html
<div class="card dinnerbone">
  <!-- Flipped card container -->
  <div class="dinnerbone-counter">
    <p>The card container is upside down, but this text stays completely readable!</p>
  </div>
</div>
```

### 3. Hover Trigger Animation 🎮
Create interactive elements that flip smoothly only when the user hovers over them with the mouse:

```html
<button class="dinnerbone-hover-flip">
  Hover over me!
</button>
```

---

## ⚙️ Customization & Global Variables

You can easily override the rotation angles, origins, and physics of the flip directly within your global stylesheet using CSS custom properties:

```css
:root {
  --dinnerbone-rotation: 180deg;
  --dinnerbone-transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}
```

---

## 📄 License

Dinnerbone.css is open-source software licensed under the **MIT License**. Feel free to break the web rules and flip your components!
