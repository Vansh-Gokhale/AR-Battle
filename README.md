# ⚡ Neon Aura AR (AR-Battle)

![Neon Aura AR](https://img.shields.io/badge/AR-Experience-00ffcc?style=for-the-badge&logo=virtualreality) ![Web-based](https://img.shields.io/badge/Web-Browser-ff00cc?style=for-the-badge&logo=googlechrome) ![MediaPipe](https://img.shields.io/badge/Powered%20By-MediaPipe-blue?style=for-the-badge)

Welcome to **Neon Aura AR** — an immersive, browser-based Augmented Reality hand-tracking battle game! Utilizing MediaPipe's cutting-edge AI, you can engage in high-octane, 30-second battles using nothing but your hands and a webcam. 

Experience real-time reactive audio, explosive particle effects, dynamic neon visuals, and lightning-fast gestures. 

---

## 🎮 Gameplay Mechanics

Battle head-to-head or test your own dexterity! You have **30 seconds** to score as many points as possible using AR hand gestures. 

### 🗡️ Quick Attack: **The Pinch**
* **Action:** Pinch your **Thumb** and **Index Finger** together.
* **Effect:** Triggers a fast shockwave and an electric zap! 
* **Score:** `+1 Point` per pinch.

### 💥 Heavy Attack: **The Plasma Charge**
* **Action:** Squeeze your 4 fingers together (Index, Middle, Ring, Pinky).
* **Effect:** A glowing energy orb forms in your palm. The longer you hold, the larger the charge. Release to unleash a massive shockwave and particle blast!
* **Score:** Up to `+10 Points` based on charge duration.

### ⚡ Cross-Hand Magic
Bring both hands close to each other to trigger dynamic interactions:
* **Arc Lightning:** Electric lightning arcs between your fingertips when they get close.
* **The Mandala:** Perfectly align all 10 fingertips to weave a glowing, rotating Mandala!

---

## 🎨 Immersive Themes & Visuals

Neon Aura AR comes packed with stunning, reactive environments:
- 🌈 **Rainbow** (Default)
- 🤖 **Cyberpunk** (High-contrast Neon Pink & Cyan)
- 🌋 **Lava** (Pulsing fiery Oranges & Reds)
- 🌊 **Ocean** (Deep soothing Blues & Cyans)
- 🌌 **Galaxy** (Shimmering cosmic Purples)

*The background reacts to your hand velocity—move faster to speed up the matrix rain and boost the visual intensity!*

---

## 🔊 Reactive Audio Engine
* **Theremin-style Hum:** The background hum dynamically alters its pitch and volume depending on the distance between your hands. 
* **Synth Zaps:** Responsive 800Hz sawtooth synthesizer zaps activate on every pinch.

---

## 🚀 How to Play

No installation required! Just run it in your browser.

1. Clone the repository:
   ```bash
   git clone https://github.com/Vansh-Gokhale/AR-Battle.git
   ```
2. Open the `index.html` file in any modern web browser.
3. Grant camera permissions.
4. Click **Enter Experience**.
5. Step back, show your hands, and let the battle begin!

---

## 🛠️ Tech Stack
* **HTML5 Canvas** (Dual-layer compositing for motion blur and neon bloom effects)
* **Vanilla JavaScript** (Zero-dependency custom physics engine)
* **MediaPipe Hands API** (Real-time skeleton tracking)
* **Web Audio API** (Procedural sound generation)
* **CSS3** (Glassmorphism UI)

---

*Are you ready to channel your inner aura? Step into the AR-Battle arena now!*
