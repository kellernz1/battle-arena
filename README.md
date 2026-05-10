# ⚔️ Battle Arena

A lightweight, turn-based RPG battle arena game built entirely with Vanilla JavaScript, HTML5, and Tailwind CSS.

This project demonstrates core game design logic, state management, DOM manipulation, and CSS animations without relying on heavy frameworks. It features a roguelite progression system where players battle enemies, collect coins, and buy permanent upgrades.

---

## 🎮 Demo

> **Play it live:** https://your-demo-link.vercel.app

---

## ✨ Features

### ⚔️ Turn-Based Combat Engine
Manage strategic turns between the Hero and AI-controlled monsters.

### ❤️ Dynamic UI & Health Bars
Real-time health updates with visual color changes when HP reaches critical levels.

### 💥 Advanced Combat Mechanics

#### 🗡️ Basic Attack
- Randomized damage system
- 15% Critical Hit chance

#### 🔥 Special Attack
- Massive damage output
- 3-turn cooldown system

#### 💚 Heal Ability
- Sacrifice your turn to restore HP
- Essential for long survival runs

### 🛒 Roguelite Shop System
Defeated enemies drop coins that can be used to purchase:
- Permanent base damage upgrades
- Maximum HP upgrades
- Healing items

### ✨ Game Juice & Visual Feedback
Custom CSS animations make combat feel impactful:
- Attack lunges
- Damage screen shake
- Healing glow effects
- Upgrade animations

---

## 🛠️ Technologies Used

- **HTML5 & CSS3**
  - Semantic structure
  - Custom keyframe animations

- **JavaScript (Vanilla ES6)**
  - Game logic
  - State management
  - Damage calculations
  - DOM manipulation

- **Tailwind CSS (CDN)**
  - Responsive layouts
  - Utility-first styling
  - Rapid UI development

---

## 🚀 How to Run

Because this project uses Vanilla JavaScript and Tailwind CSS via CDN, there are no build tools or package managers required.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/shonen-survival.git
cd shonen-survival
```

### 2. Open the project

Simply open the `index.html` file in any modern web browser.

---

## 📂 Project Structure

```text
/battle-arena
├── index.html
└── README.md
```

---

## 🧠 What I Learned

This project was built to practice and showcase several important programming concepts.

### 🧩 State Management
Tracking persistent game variables such as:
- `heroHP`
- `coins`
- `baseDamageBonus`
- `specialCooldown`

### ⏱️ Asynchronous Flow
Using `setTimeout()` to create natural delays between:
- Player actions
- Enemy counter-attacks
- Combat animations

### 🧱 Separation of Concerns
Writing modular functions like:
- `updateUI()`
- `executeDamageAnimation()`
- `enemyTurn()`

This keeps logic and interface responsibilities separated.

### 🎨 UX/UI Design
- Disabling buttons during enemy turns
- Visual feedback for cooldowns
- Responsive combat interface
- Preventing accidental spam actions

---

## 🔮 Future Improvements

- [ ] 🎵 Add background music and sound effects (SFX)
- [ ] 👾 Dynamic enemy generator for endless gameplay
- [ ] 💾 Save progression using `localStorage`
- [ ] 🖼️ Replace emoji graphics with pixel art sprites
- [ ] 🧪 Add status effects (Poison, Burn, Shield)
- [ ] 🏆 Achievement and progression system

---

## 📄 License

This project is open-source and available under the **MIT License**.

Feel free to fork it, study the code, and create your own RPG adventures.

---

## 👨‍💻 Author

Developed by **Keller Nz**

---

## ⭐ Support

If you enjoyed this project, consider giving it a ⭐ on GitHub!
