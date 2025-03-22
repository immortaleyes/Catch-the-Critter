# Catch the Critter!

## Overview

Catch the Critter! is a simple and engaging web-based game where players try to click on a moving critter as many times as possible within a time limit. This game is designed to be fun and easy to play, with increasing difficulty as the player's score rises.

## Features

* **Engaging Gameplay**: Players click on a moving critter to score points.
* **Dynamic Difficulty**: The critter moves faster as the player scores more points.
* **Time Limit**: Each game lasts for 20 seconds.
* **Score Tracking**: The game displays the player's score.
* **Power-ups**:
    * Slow Power-up: снижает скорость движения криттера.
    * Multiplier Power-up: увеличивает множитель очков.
* **Levels**: The game speed increases slightly every 5 seconds, making it progressively more challenging.
* **Visual Enhancements**:
    * Particles: When the critter is clicked, small particles are emitted, providing visual feedback.
* **New Critter Design**: The critter is now a simple, animated shape instead of an image.
* **Soundtrack**: A simple background music loop is added.
* **Mute Button**: Players can mute sound effects.
* **Responsive Design**: The game adapts to different screen sizes.

## How to Play

1.  **Start the Game**: Click the "Start Game" button.
2.  **Catch the Critter**: Click on the moving critter as many times as possible.
3.  **Score Points**: Each successful click increases your score.
4.  **Time Limit**: The game ends after 20 seconds.
5.  **Game Over**: Your final score will be displayed.

## Technical Details

* **HTML**: Provides the structure for the game.
* **CSS**: Styles the game with a retro gaming aesthetic, a clean layout, and interactive effects.
* **JavaScript**: Implements the game logic, including:
    * Random critter movement.
    * Score tracking.
    * Game timer.
    * Sound effects using Tone.js.
    * Power-up mechanics.
    * Particle effects.
    * Music playback.
* **Font**: Uses the "Press Start 2P" font for a retro gaming look.
* **Sound Effects**: Uses the Tone.js library for sound effects.

## How to Add This Game to Your GitHub Page

1.  **Create a Repository**: Create a new repository on your GitHub account.
2.  **Upload Files**:
    * Upload the `index.html` file (or the name you saved the game as) to your repository.
    * Make sure that all linked assets (like sound files, if you add any) are also uploaded and the paths in the HTML file are correct.
3.  **Enable GitHub Pages**:
    * In your repository, go to "Settings".
    * Scroll down to the "GitHub Pages" section.
    * Select the "main" branch (or the branch where you uploaded your files) and click "Save".
    * Your GitHub Pages site will be live at `https://<your-username>.github.io/<your-repository-name>/`

## Customization

* **Styling**: The look of the game can be easily changed by modifying the CSS in the `<style>` section of the HTML file.
* **Game Mechanics**: The game logic can be altered by editing the JavaScript code. For example, you can change the game duration, critter speed, or scoring system.
* **Sound Effects**: You can replace or add sound effects by modifying the `playSound()` function and adding sound files.
* **Music**:  You can change the background music by modifying the `musicNotes` array and the `playMusic()` function.

## Credits

* Game Design: Ajay Shriram Kushwaha
* Development: Ajay Shriram Kushwaha
* Re-created by: Ajay Shriram Kushwaha
* Font: "Press Start 2P"
* Sound Effects: Tone.js
