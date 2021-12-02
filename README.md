# Caves - A Phaser 3 RPG Game

---

Hyper Island - If this, then that Module - Brief 3.

- [LIVE DEMO](https://harry-yates.github.io/PhaserGame-RPG-Caves/)

### :video_game: The Game:

A keyboard is required to play this game. Player movement controls mapped to:

- W: Move forward
- A: Move left
- S: Move back
- D: Move right

To start/reset the game.

- E: (on relevant scenes.)

There is a different Easter Egg SFX on each scene mapped to:

- Q: Play hidden sound effect.

### :open_file_folder: The Brief:

- Create a game using the Phaser 3 framework.

### :hourglass_flowing_sand: Time spent / Deadline:

3 weeks.

### :dart: Goals:

- Build a Game with Phaser 3.
- Develop strong teamwork patterns - Agile Development, Scrum methods.
- JavaScript functions.
- User Firebase to store the scores.

### :mechanical_arm: Solution:

We decided to create a top-down RPG style game, the concept inspired by Squid Games requires the player to select between caves, some of which are safe, others lead to player death.

There are particle emitting angel statues around each scene that offer clues on which cave is safe. The player has to find the correct cave under the duress of troll and golem attacks.

Building the game gave us solid learnings working with Phaser. Including building scenes, physics engines (Matter Physics), custom classes, working with Atlas packers, creating animations with sprite sheets and particle emitters, designing with Figma and pulling it together with JavaScript.

### :man_student: Learnings:

- Javascript
  - ES6
  - Custom classes
  - Arrays
  - Functions
  - Objects
- Phaser 3 & Matter Physics
  - Audio
  - Mouse & Keyboard Input Handling
  - Basic Enemy AI
- Working with Tiled
  - Animation
  - Spritesheets
  - Object layers

### :interrobang: Future Improvements & Current Bugs:

Event Listener Bug

- We have a bug that is caused by event listener duplication when the game resets. When the game is reset, the enemies don't know who to attack at the game crashes.

Angel Crash Bug

- On occasion, an angel will fire the text box destroy() function on inital collision. This can happen before the text box is called, and this can cause the game to crash.

Treasure Score Bug

- Sometimes the score is not counted on treasure collection. This seems to be caused in instances when there are a lot of colliders.

### :computer: Tech used in this specific repository:

- Figma
- Git Hub
- HTML
- JavaScript
- [Phaser 3](https://phaser.io/phaser3)
- Matter Physics
- [Tiled - Tilemap editor](https://www.mapeditor.org/)
- [GammaFP - Atlas Packer & Animator tools](https://gammafp.com/tools)
