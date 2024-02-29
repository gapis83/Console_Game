The project aims to create a retro-style game reminiscent of classic Java mobile games, where the player navigates a map filled with obstacles and enemies while trying to reach a target point.

Key aspects:
- Procedural map generation: The game dynamically generates a square map with obstacles and randomly positions the player, enemies, and target point.
- Turn-based movement: The player and enemies take turns moving in one of four directions (left, right, up, down).
- Enemy AI: Enemies pursue the player using a pathfinding algorithm that incorporates the target position.
- Different game modes (production and development) can be chosen, affecting visual elements and player interaction.
- Customization: The game utilizes configuration files to customize characters, walls, and map elements with specific symbols and colors.

Maven in this project provides convenient dependency management. It consists of two Maven projects:
- game logic;
- pursuit algorithm.

Maven allows you to use configuration files to change the appearance of the game and other parameters.
Overall, using Maven makes the project more convenient for development, building, and using.

Overall, the project emphasizes nostalgic gameplay, procedural generation, and enemy AI, offering a challenging and engaging experience within a classic game design framework.


The goal of the project is to develop a game in Java. It includes procedural map generation, turn-based movement, and an enemy AI with pathfinding. The game allows for customization through configuration files. Maven is used for convenient dependency management.