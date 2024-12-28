# Memory Game

## Overview
This Memory Game is an interactive web application where players match pairs of cards with identical images. The goal is to find all matching pairs in the shortest time and with the fewest moves.

---

## Features
1. **Dynamic Gameplay**:
   - Cards are shuffled randomly every time the game loads.
   - Flip two cards at a time to reveal their images.
   - Matched cards remain flipped, while unmatched ones are flipped back after a delay.

2. **Timer**:
   - A timer starts on the first move and tracks the time taken to complete the game.

3. **Win Condition**:
   - The game alerts the player with a congratulatory message and displays the total moves taken upon matching all card pairs.

4. **Responsive Design**:
   - The gameboard is visually appealing, with styled cards and a background image.

---

## File Structure
1. **HTML File**:
   - Contains the structure of the game, including the gameboard, cards, and timer display.

2. **CSS Styles**:
   - Inline styles manage the appearance of the game elements, such as the cards, background, and timer.

3. **JavaScript Logic**:
   - Handles card shuffling, flipping, matching logic, timer updates, and game completion alerts.

---

## How to Play
1. Open the HTML file in a browser.
2. Click on any card to flip it and reveal the image.
3. Flip another card to find a match:
   - If the cards match, they stay flipped.
   - If they don’t match, they will flip back after a 2-second delay.
4. Continue matching pairs until all cards are flipped.
5. Upon completion, an alert will display your total moves and time taken.

---

## Code Breakdown
### HTML:
- A `div` with `id="gameboard"` acts as the container for dynamically generated cards.
- A timer display (`id="timer"`) shows elapsed time.

### CSS:
- The gameboard uses `grid` for layout with flexible columns.
- Cards have rounded corners, styled borders, and hidden images until flipped.
- Background is set to a visually appealing image.

### JavaScript:
- **Card Shuffling**: Uses `Array.sort` with a random comparator.
- **Event Handling**: Listens for clicks on cards to manage flipping and matching.
- **Timer**: Tracks elapsed time starting from the first move.
- **Game Completion**: Displays a congratulatory message upon finding all pairs.

---

## Requirements
- A modern browser with JavaScript enabled.
- Internet connection (to load card images from external URLs).

---

## Future Enhancements
1. Add a **restart button** to reset the game without reloading the page.
2. Implement a **move counter** that updates dynamically during gameplay.
3. Enhance **responsive design** to optimize for smaller screens.
4. Include **accessibility features** like keyboard navigation and ARIA roles.
5. Provide a score or leaderboard system to track performance across multiple games.

---

## License
This project is open-source and available for personal or educational use.

