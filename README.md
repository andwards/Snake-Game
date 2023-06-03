# Snake Game

This is a simple implementation of the classic Snake game using Java Swing. The game allows you to control a snake and eat apples to increase your score. The game ends if the snake collides with itself or the game border.

## Game Mechanics

1. **Snake Movement**: The snake moves on a grid, consisting of horizontal and vertical cells. You can control the snake's movement using the arrow keys. Pressing the left arrow key makes the snake move left, the right arrow key makes it move right, the up arrow key makes it move up, and the down arrow key makes it move down.
2. **Eating Apples**: The game grid contains randomly placed apples. When the snake's head touches an apple, it consumes it, and the score increases. The snake's body grows longer with each apple eaten.
3. **Game Over Conditions**: The game ends if one of the following conditions is met:
    - The snake collides with its own body: If the snake's head touches any part of its body, the game ends as the snake cannot intersect itself.
    - The snake collides with the game borders: If the snake's head touches the boundaries of the game grid, it results in a collision, and the game ends.
4. **Scoring**: The score increases by one each time the snake eats an apple. The player's objective is to achieve the highest possible score.

## Game Features

1. **Game Panel**: The game interface is displayed on a graphical panel, allowing for an interactive and visually appealing gameplay experience.
2. **Score Display**: The current score is shown on the game panel, allowing players to track their progress.
3. **Random Apple Placement**: Apples are randomly placed on the game grid, ensuring that each game session offers a unique challenge.
4. **Collision Detection**: The game continuously checks for collisions between the snake's head, body, and the game borders, determining if the game should end.

## Game Flow

1. The game starts with a snake consisting of a head and a single body part. The initial score is set to zero.
2. The player controls the snake's movement using the arrow keys.
3. The snake moves continuously in the direction set by the player. With each movement, the snake's head advances to the adjacent cell in the chosen direction, and the body follows.
4. The game checks for collisions at each movement step, including collisions with the snake's own body and the game borders.
5. If the snake's head collides with an apple, the snake grows longer by adding a new body part, and the score increases.
6. If a collision is detected, the game ends, and the final score is displayed.

## Game Controls

Use the arrow keys to control the snake's direction:

- Left Arrow: Move the snake to the left.
- Right Arrow: Move the snake to the right.
- Up Arrow: Move the snake upwards.
- Down Arrow: Move the snake downwards.

## Contributors

- [Andrew Edwards](https://github.com/andwards)