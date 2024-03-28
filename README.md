

# Game Options

## 1. Shooter

For this option, imagine a 2d grid with enemies advancing from all sides. The player moves with wasd and shoots using the arrow keys. Enemies spawn from the north, south, east, and west. The player has three lives, and loses a life when an enemy gets too close, after that it's game over.

- Create a class to represent the **Player**.
    - Implement methods for **shooting** that create Bullet objects.
    - Implement methods for **moving** triggered by the wasd keys.

- Create a class to represent a **Bullet**. 
    - Bullets move in a straight line starting from the player's position when the Bullet is created. 
    - If a bullet touches an Enemy, the Enemy disappears.

- Create a class to represent **Enemies**.
    - Implement a method **move**. Enemies move towards the Player.

## 2. Space Invaders

For this option

## 3. Match

For this option 

## 4. Snake

For this option, imagine a 2d grid for the snake to move through. Apples randomly spawn throughout the map. The player uses wasd to control a snake and collect apples. Each time the snake eats an apple, its length grows by one. If the snake runs into the outmost walls or itself, it's game over.

- Create a class that represents a **SnakePart**.
    - Each SnakePart should store the **next SnakePart** in an instance variable, unless it is the end of the snake.
    - Implement a method **move** which moves the SnakePart to the next space AND calls move on the next SnakePart. The next SnakePart should move to the location of the previous SnakePart.
    - Implement a method **grow** which in a manner similar to move calls grow on the next SnakePart until it reaches the end of the snake. Add a new SnakePart to the end of the Snake by storing it in the previously unused instance variable.
    
- Create a class **SnakeHead** that inherits from SnakePart. This represents the head of the snake.
    - The SnakeHead should have a different color from the rest of the snake.
    - Override the **move** method so that wasd controls the direction the SnakeHead moves

- Create a class **Apple** to represent food for the snake to eat.

## 5. Your Own