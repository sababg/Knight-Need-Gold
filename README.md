"# Knight-Need-Gold" 

Knight Needs Gold

Simple 2D platformer built in Godot

🎮 Overview

Knight Need Gold is a lightweight platformer experience featuring a playable hero, enemy characters, moving platforms, and collectible coins. The goal is to guide the knight through levels, avoid or defeat enemies, traverse dynamic platforms, and gather gold coins to complete the stage.

🧰 Features
- Player character with movement controls (run, jump, etc.)
- Enemy units with simple behaviors
- Moving platforms that add dynamic traversal challenges
- Coins (gold) scattered for collection
- Levels/scenes defined in Godot (GDScript)
- Designed for rapid iteration and fun, simple gameplay

📁 Project Structure
```bash
assets/               → art, audio, sprites, icons  
scenes/               → Godot scene files (levels, player, enemies)  
scripts/              → GDScript files (player controller, enemy AI, platform logic)  
.project.godot        → Godot project file  
icon.svg              → Game icon  
README.md             → This document  
```

🚀 Getting Started
1. Install [Godot Engine] (version 3.x or whichever version you used).
2. Clone the repo:
```bash
git clone https://github.com/sababg/Knight-Need-Gold.git
```
3. Open the project in Godot:
- Launch Godot
- Choose “Import” or “Open existing project”
- Navigate to the project. godot file
4. Press Play to run the default scene or open a specific level from scenes/.
5. Explore code in scripts/ to customize movement, behavior, or add new features.

🛠️ Customization / Development Notes
- Player movement can be found in scripts/player.gd (or equivalent) — adjust speed, jump height, gravity settings.
- Enemy behavior is located in scripts/enemy.gd — you may expand with patrol logic, chase player, etc.
- Moving platforms logic is encapsulated in scripts/platform_moving.gd — adjust path, speed, ease/tweening.
- Coin collection: look at scripts/coin.gd and Scenes for how coins are set up and collected; you can add scoring UI or audio feedback.
- You might want to add UI elements (score, lives) in a new scenes/ui/ folder or integrate it in the main scene.
- Consider expanding levels: duplicate existing scenes and add more platforms/enemies/coins.
- Since the project is in GDScript 100% (per repo language stats) GitHub, it’s easy to read and modify.

🧩 Why this Project Matters
This project is a great sandbox for:
- Learning platformer mechanics in Godot
- Prototyping quick game ideas (moving platforms, coin/collectible logic)
- Demonstrating game logic fundamentals (collision detection, enemy AI, scene management). It can also be a portfolio piece showing your ability to work with game frameworks — a nice complement to your full-stack web-dev experience.

✅ Next Steps / Roadmap Ideas
- Add more levels or a level‐select screen
- Introduce player/enemy animations (idle, walk, attack)
- Add sound effects and music (coin collect, jump, enemy hit)
- Include UI: start menu, pause menu, score/lives display
- Power‐ups: e.g., “double jump”, “invincibility”
- Save system / high scores
- Polish visuals: parallax background, particle effects
- Package/export the game (desktop, web, mobile)

📝 License & Credits
Feel free to use the code and assets in this repo under the terms you choose. If you reuse or adapt assets/code, attribution is appreciated.
If there are any third-party assets (sprites, audio) included, you may want to note their licenses and credits here.

Thank you for checking out Knight Need Gold — have fun building and playing!
If you have questions or improvements, you’re welcome to open an issue or pull request.

Saba Beigi
Full-stack / Frontend Engineer
