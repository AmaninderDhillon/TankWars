# Project Title- TankWars


## Description
TankWars is a tank battle-themed arcade game developed using MonoGame in Visual Studio. The player controls a user tank, navigating through levels while battling enemy tanks, avoiding obstacles, and collecting power-ups. The game features three levels with increasing difficulty and a leaderboard to track high scores.

## Features

🎮 Three Levels: Each level introduces more enemy tanks, walls, and challenges.

💥 Exploding Walls: Walls are destructible when hit by bullets.

🔋 Power-Ups: Level 3 includes health-restoring power-ups.

🏆 Scoring System: Players gain points by destroying enemy tanks and walls.

📊 Leaderboard: Displays the highest scores achieved by players.

## User Controls:

Move tank: ⬆️ ⬇️ ⬅️ ➡️ Arrow keys

Shoot: Space bar

Navigate menus:

M for Main Menu

H for Help

A for About

Enter name for the leaderboard after game over

## Installation and Execution

Currently, the game requires Visual Studio with the MonoGame extension installed to run. The following steps will guide you through running the game:

1. Clone the repository git clone https://github.com/yourusername/TankWars.git

2. Open the project in Visual Studio

3. Ensure MonoGame is installed

4. Build and run the project

A desktop shortcut is under development to allow direct execution without opening Visual Studio.

## Class Diagram

The game is structured with the following key classes:

Game: Manages the game loop, state transitions, and overall gameplay.

Tank: Represents both the player and enemy tanks, handling movement and health.

Bullet: Handles bullet behavior, including collision detection.

Wall: Defines destructible wall blocks.

PowerUp: Manages power-ups that restore health in Level 3.

MainMenu: Displays the main menu and provides navigation options.

## Future Enhancements

🖥️ Implement a desktop shortcut for direct game execution.

🔊 Add sound effects and background music.

🎨 Introduce additional tank skins and visual upgrades.

⚡ Expand the power-up system with different abilities.

## License

This project is licensed under the MIT License. See LICENSE for details.
Reason: The MIT License is a good choice for most open-source projects because it provides flexibility while still requiring attribution.

## Credits

Developed by Amaninder Singh Dhillon. Powered by MonoGame and Visual Studio.
