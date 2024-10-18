
# Emoji Catcher Game

The **Emoji Catcher Game** is a fun and interactive web-based game where players try to catch falling emojis within a limited time. The game challenges players to improve their reflexes and aim as they attempt to score points by clicking on the emojis that appear randomly on the screen.


## Features
- **Interactive Gameplay**: Catch emojis that appear in different squares on the grid.
- **Score Tracking**: Keep track of your score as you catch emojis.
- **Timer**: Play against the clock, with a countdown to add excitement.
- **Simple and Clean UI**: Easy-to-navigate interface for a smooth gaming experience.

---

## How to Play
1. Open the `index.html` file in your web browser.
2. Emojis will appear randomly in a grid of squares. Click on the squares containing emojis to score points.
3. Keep an eye on the timer! The game lasts for 60 seconds.
4. Your score will be displayed at the top. At the end of the game, an alert will show your final score.

---

## File Structure
```
emoji-catcher-game/
│
├── index.html          # The main HTML file containing the game structure
├── style.css           # CSS file for styling the game layout and elements
└── app.js              # JavaScript file containing the game logic
```

---

## Technologies Used
- **HTML5**: For structuring the game layout and elements.
- **CSS3**: For styling the game and enhancing the visual appeal.
- **JavaScript**: For implementing the game logic, including the scoring system and timer.

---

## Customization
You can easily customize this game to enhance your experience:
- **Change Emojis**: Update the `app.js` file to change the emojis displayed in the game. Replace the emoji class in the CSS to use different emoji images or styles.
- **Modify Game Duration**: Change the `currentTime` variable in `app.js` to adjust how long the game lasts:
  ```javascript
  let currentTime = 60; // Set the time limit (in seconds)
  ```
- **Add More Squares**: To increase the game's difficulty, add more squares in the HTML by duplicating the square divs within the `.grid` container.

---

Have fun catching emojis and enjoy playing the **Emoji Catcher Game**! 🎉😊