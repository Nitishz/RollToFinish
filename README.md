## Roll To Finish

### Repository Structure
```bash
- RollToFinish/
  - Assets/
    - Scenes/                # Scene files
      - RaceScene.unity      # The race track scene

    - Scripts/               # C# scripts for game logic
      - Player/              # Scripts related to the player
        - BallController.cs  # Controls for ball movement
      
      - Gameplay/            # General gameplay logic
        - FinishLine.cs      # Logic for detecting when the ball reaches the finish line
        - GameManager.cs     # Manages the race state (start, end, etc.)

      - UI/                  # Scripts for menus, leaderboards, etc.

    - Prefabs/               # Reusable game objects
      - Player/              # BallPrefab.prefab
      - Obstacles/           # Prefabs for spikes, moving platforms, etc.
      - PowerUps/            # Prefabs for speed boosts, shields, etc.

    - Art/                   # Visual assets
      - Textures/            # Track and ball textures
      - Sprites/             # 2D sprites (e.g., buttons, obstacles)

    - Audio/                 # All sound effects and music

    - Animations/            # Animation files

  - Tests/                   # Test Scripts

  - CHANGELOG.md           # Tracks changes across versions/releases
  - .gitignore               # Files/folders to ignore
  - README.md                # Project overview and setup instructions

```

### Contribution Guidelines

1. **Do not directly push to the `main` branch.**  
   Always create a new branch and open a Pull Request (PR) for your changes to be reviewed before merging.

2. Create a fork.

3. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
4. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
5. Push to your forked repository:
   ```bash
   git push origin feature-name
   ```
6. Open a pull request.

---