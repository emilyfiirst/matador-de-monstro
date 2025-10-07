# 🧟‍♂️ Monster Slayer

A small interactive game built with **HTML**, **CSS**, and **Vue.js**, where the player faces a monster in a battle of attacks, healing, and strategy until one of them runs out of health.

---

## 🕹️ Features

- 🎮 **Start Game:** begins a new match, restoring both health bars to 100%.
- ⚔️ **Attack:** the player deals damage to the monster, which counterattacks immediately.
- 💥 **Special Attack:** deals more damage than a normal attack but also triggers a counterattack.
- 💚 **Heal:** the player restores part of their health, followed by a monster attack.
- 🚪 **Give Up:** ends the current match.
- 🧾 **Action Log:** displays a detailed list of actions performed by both the player and the monster.

---

## 🧩 Project Structure

```
📁 matador-de-monstro
│
├── index.html      # Main structure of the application
├── style.css       # Visual styles of the game
└── app.js          # Game logic (Vue.js)
```

---

## 💻 Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vue.js 2)**

---

## ⚙️ How to Run

1. Download or clone this repository:
   ```bash
   git clone https://github.com/emilyfiirst/matador-de-monstro.git
   ```

2. Open the `index.html` file in any modern browser.

3. Click **Start Game** and have fun! 🕹️

---

## 📱 Game Interface

- **Health Bar**: shows the current health percentage of both the player and the monster.
- **Action Buttons**: control attacks, healing, and giving up.
- **Log Panel**: displays real-time actions during the battle.

---

## 🧠 Game Logic (Overview)

- Both the player and the monster start with 100 health points.
- Each attack inflicts random damage within a set range.
- The special attack adds extra damage.
- Healing restores the player’s health up to a maximum of 100.
- When either health reaches 0, the game ends automatically.

---

## 🏆 Objective

Defeat the monster before it defeats you!
Manage your attacks and healing wisely to win the battle.

---

## 👨‍💻 Autor
Developed as a practical **Vue.js** exercise to learn about reactivity and front-end state management.
