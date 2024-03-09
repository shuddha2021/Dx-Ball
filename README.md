# JavaScript DX Ball Game

A fun-to-play JavaScript DX Ball game.

## Introduction

This DX Ball game is developed using HTML5 canvas and JavaScript. It's a simple yet addictive game where the player controls a paddle to bounce a ball and break bricks. The goal is to clear all the bricks on the screen by bouncing the ball off the paddle without letting it fall off the bottom of the screen.

## How it Works

### HTML

The game is built using HTML5 `<canvas>` element to render graphics on the web page. The canvas serves as the game board where all the game elements are drawn.

### CSS

Basic CSS styles are applied to the canvas element to center it on the page and provide a background color.

### JavaScript

JavaScript is used to implement the game logic and handle user input. Here's a breakdown of the key components and functionalities:

- **Ball Movement**: The ball moves in a given direction and bounces off the walls and paddle.
- **Paddle Control**: The player controls the paddle using the left and right arrow keys to prevent the ball from falling off the screen.
- **Brick Collision**: When the ball collides with a brick, it destroys the brick and changes direction.
- **Score and Lives**: The game keeps track of the player's score and remaining lives, updating them as the game progresses.
- **Game Over**: The game ends when all bricks are destroyed or the player runs out of lives.

## How to Play

1. Open the [DX Ball Game](https://dxball.vercel.app/) in a web browser.
2. Use the left and right arrow keys to move the paddle.
3. Bounce the ball off the paddle to destroy the bricks.
4. Try to clear all the bricks without letting the ball fall off the bottom of the screen.

## Development

### Prerequisites

- Web browser with HTML5 support

### Running the Game

Simply open the `index.html` file in a web browser to play the game.

### Modifying the Game

You can customize the game by tweaking the JavaScript code to change aspects such as ball speed, paddle size, brick layout, and more. The possibilities for enhancements and variations are endless!

## Credits

This game is inspired by the classic DX Ball game and is created for educational and entertainment purposes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
