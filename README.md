# Monster Adventure Game

A JavaScript-based interactive text adventure game where players explore locations, fight monsters, and upgrade their weapons. The game involves strategic decisions like buying health, upgrading weapons, and fighting or dodging monsters.

---

## Features

- **Explore Different Locations:**
  - Town Square
  - Store
  - Cave
  - Fight monsters (Slime, Fanged Beast, Dragon)

- **Combat System:**
  - Attack monsters using weapons.
  - Dodge attacks.
  - Monsters scale in difficulty, including a final boss (Dragon).

- **Inventory Management:**
  - Upgrade weapons or sell them for gold.
  - Keep track of inventory and gold for strategic choices.

- **Random Events:**
  - Weapon durability can cause items to break.
  - An Easter egg mini-game with a chance to win gold.

- **Game Progression:**
  - Gain XP, health, and gold by defeating monsters.
  - Win the game by defeating the Dragon.
  - Lose the game if your health reaches 0.

---

## Prerequisites

- A modern web browser that supports JavaScript.
- HTML and CSS files for rendering the game UI (not included in this snippet).

---

## Installation

1. Clone the repository or copy the code.
2. Ensure the JavaScript file is linked to an HTML file with the following IDs:
   - Buttons: `#button1`, `#button2`, `#button3`
   - Text areas: `#text`, `#xpText`, `#healthText`, `#goldText`
   - Monster stats: `#monsterStats`, `#monsterName`, `#monsterHealth`

---

## How to Play

1. Open the HTML file in a web browser.
2. Follow the prompts to navigate the locations, purchase items, or engage in combat.
3. Defeat monsters to gain XP and gold.
4. Win by defeating the Dragon or lose if your health reaches 0.

### Controls

- **Button 1:** Action 1 (varies based on the location).
- **Button 2:** Action 2 (varies based on the location).
- **Button 3:** Action 3 (varies based on the location).

---

## Game Logic

### Locations

- **Town Square:** Starting point with options to go to the store, cave, or fight the Dragon.
- **Store:** Buy health or upgrade weapons using gold.
- **Cave:** Fight Slime or Fanged Beast to earn XP and gold.
- **Fight:** Engage in combat with monsters.

### Combat

- Use weapons to attack monsters.
- Dodge attacks to avoid damage.
- Random events like weapon breakage can occur.

### Inventory

- Start with a basic weapon (Stick).
- Upgrade to stronger weapons like a Dagger, Claw Hammer, or Sword.
- Sell weaker weapons for gold.

### Easter Egg

- Play a random number guessing game for a chance to win gold.

---
