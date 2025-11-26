Tennjs – Simple Pong Game (JavaScript + Canvas)

This project is a minimalist Pong-style game built using plain
JavaScript and an HTML5 <canvas> element.
The game features a player-controlled paddle, an AI paddle, ball
physics, score tracking, and a game-over condition.

How It Works

Canvas Drawing

-   The ball, paddles, and score numbers are drawn each frame.
-   Rendering updates on a loop using setTimeout.

Game Mechanics

-   The right paddle follows your mouse movements.
-   The left paddle is a computer opponent with a maximum tracking
    speed.
-   The ball bounces off walls and paddles.
-   Scoring occurs when the ball exits the left or right side.
-   Game ends when either player reaches a score of 10.

Files Included

index.html

    <!DOCTYPE html>
    <html>
        <head>
            <title>Tennjs</title>
        </head>
        <body>
            <canvas id="canvas" width="300" height="300"></canvas>
            <script src="script.js"></script>
        </body>
    </html>

script.js

Contains all JavaScript logic, including: - Ball initialization
- Paddle movement logic
- Collision detection
- Drawing to the canvas
- Main game loop

Controls

Move your mouse up or down over the page to control the right paddle.

Getting Started

1.  Add index.html and script.js to your folder.
2.  Open index.html in any browser.
3.  The game starts automatically.

Customization

You can modify values in script.js to adjust gameplay.

Known Issues

-   In update(), vertical movement uses ballPosition.y += xSpeed instead
    of += ySpeed.
-   Canvas had a typo (widht instead of width) in your original HTML.
