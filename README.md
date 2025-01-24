# 🎯 Sefed: Ethiopian Quick Tap Challenge 🎯

Sefed is an engaging target-shooting game inspired by Ethiopian culture, featuring dynamic visuals, levels of increasing difficulty, and a fun gameplay loop that challenges your speed and accuracy.

---

## 🌟 Features
- **Cultural Inspiration**: The game design and visuals are inspired by Ethiopian cultural elements, reflected in the color palette and braided patterns.
- **Three Difficulty Levels**: Test your skills with three levels—Level 1 (Easy), Level 2 (Medium), and Level 3 (Hard)—each with faster target spawning.
- **Interactive Gameplay**: Tap on targets as quickly as possible to score points and achieve a high score.
- **Dynamic Background**: Immerse yourself with a background inspired by the traditional Ethiopian *Sefed* weaving.
- **High Score Tracking**: Your highest score is saved locally to push your skills to the limit.

---

## 🕹️ How to Play
1. Launch the game in your browser.
2. Select your desired difficulty level:
   - **Level 1**: Targets spawn every second.
   - **Level 2**: Targets spawn every 0.75 seconds.
   - **Level 3**: Targets spawn every 0.5 seconds.
3. Click on the targets as quickly and accurately as you can before they disappear.
4. Keep track of your score and remaining time displayed on the screen.
5. Try to beat your high score before the timer runs out!

---

## 📂 Installation & Usage
1. Clone or download this repository to your local machine.
2. Open `index.html` in your web browser.
3. Enjoy the game!

---

## 🚀 Technologies Used
- **HTML5**: For structuring the web application.
- **CSS3**: For styling the game interface and background.
- **JavaScript**: For interactive gameplay mechanics and animations.
- **Canvas API**: For rendering the targets and handling dynamic visual updates.

---

## 🎨 Game Design
The targets in Sefed are inspired by the intricate patterns of traditional Ethiopian *Sefed* (woven baskets). These colorful and circular designs are reflected in the gameplay, creating a culturally rich and visually appealing experience.

---

## 📖 Gameplay Mechanics
- **Targets**: Each target consists of concentric circles with alternating colors and zigzag braided patterns, simulating the *Sefed* design.
- **Click Detection**: Clicking inside a target's radius increases your score and triggers a color flood-fill animation.
- **Countdown Timer**: The game lasts 30 seconds. Use this time to score as many points as possible.

---

## 🛠️ Configuration
- **Levels**: Modify the target spawn interval in the `setLevel` function inside `game.js`:
  ```javascript
  const spawnTimes = {
    1: 1000, // Level 1
    2: 750,  // Level 2
    3: 500,  // Level 3
  };
