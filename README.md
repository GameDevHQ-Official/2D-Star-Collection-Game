# 2D Star Collection Game

## Objective

Create a 2D star collection game in Unity using C# to test your ability to solve problems using the Unity API, the legacy input system, and other fundamental programming concepts.

## Requirements

### Player Movement

- Create a controllable 3D cube that can move in four directions (up, down, left, right) using arrow keys or WASD.
- The cube should not move outside the playable area. Determine a way to restrict its movement within specific screen bounds.

### Coin Collection

- Implement a system where a coin (or another object) randomly appears on the screen within the playable area.
- The coin should be collectible by the player. Determine how to detect the collision between the cube and the coin.
- If the coin is not collected within 5 seconds, it should disappear, and a new coin should appear randomly on the screen.

### Game Duration

- The game should last for 60 seconds. Implement a countdown timer visible on the screen.
- Track how many coins the player collects during this time.

### UI

- Display the player's score (how many coins have been collected) and the remaining time in the top left corner of the screen.

---

## Steps

### 1. Set Up Project

- Set up a new Unity project using the 2D template.
- Create a simple 2D environment with a player-controlled 3D cube.
- You will need to add UI elements to display the score and time remaining.

### 2. Implement Player Movement

- Think about how you will control the cube's movement in four directions.
- Consider how you will limit the player's movement within certain bounds to prevent the cube from leaving the screen.

### 3. Implement Coin Behavior

- Randomly place a coin on the screen, ensuring it appears within the playable area.
- Make sure the coin can be collected by the player. Think about how you'll detect when the player touches the coin.
- After 5 seconds, if the coin has not been collected, make it disappear and spawn a new one.

### 4. Track Game Time and Score

- Implement a system that counts down from 60 seconds, updating the UI to display the remaining time.
- Keep track of how many coins the player collects during the game. Display the player's score on the screen.

### 5. Final Considerations

- Ensure that the game stops once the 60-second timer reaches zero. Display the final score when the game is over.
- Consider how to structure your code to make it clean and maintainable. How would you organize different systems such as player movement, coin behavior, and UI updates?

---

## Submission Details

1. Complete the project and ensure it functions as described.
2. Add the completed project to your GitHub repository.
3. Submit the link to your repository through your program dashboard.
4. A code review will be processed once the submission is received.

---

### Notes for the Students

- This is an open-ended project. There are multiple ways to solve each problem, so think about which approach works best for each task.
- Be mindful of how you structure your code. Aim for clarity and maintainability.
- Don't be afraid to explore the Unity documentation if you're unsure how to implement a specific feature.
