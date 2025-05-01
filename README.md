# 🎮 2048 game

This is implementation of the 2048 game. It is a popular game where you need to merge tiles with numbers to get the highest score. The game is written in JavaScript and uses HTML and CSS for the user interface.

The game consists of two main parts:

- game logic written in `src/modules/Game.class.js` module that exports `Game` class
- game UI written in `src/index.html` with `main.js` script that need to use `Game` class instance

# Overview

- Implemented the game logic in `src/modules/Game.class.js` module
- Created the user interface in `src/index.html` and `src/styles/main.scss`
- Added the score counter
- Added the win and game over messages
- Added the restart button
- Added the ability to hide the start message when the game starts
- Added the ability to change the `Start` button to `Restart` after the first move

# Technologies Used

- HTML
- CSS
- Java Script

# Links

- View demo: [GutHub Pages](https://HryniukTaras.github.io/js_2048_game/)

# How to run the project locally

1. Clone the repository by running `git clone https://github.com/HryniukTaras/2048-game.git`
2. Navigate to the project folder by running `cd 2048-game`
3. Install the dependencies by running `npm install` or `yarn install`
4. This project was developed using **Node.js v20**. You can check your current version by running `node -v`.
5. Run the project by running `npm start` or `yarn start`
6. Open the `http://localhost:8080` in your browser to see the game
