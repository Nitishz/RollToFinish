## Roll To Finish

### Features
- See the [design doc](./Docs/design_doc.md).

### Repository Structure
```bash
- RollToFinish
  - Assets/
    - Scenes/                # Scene files
      - RaceScene.unity      # The race track scene

    - Scripts/               # C# scripts for game logic
      - BallController.cs    # Controls for ball movement
      - FinishLine.cs        # Logic for detecting when the ball reaches the finish line
      - GameManager.cs       # Manages the race state (start, end, etc.)

    - Prefabs/               # Reusable game objects
      - BallPrefab.prefab    # Prefab for the player balls
  
    - Art/                   # Textures for the balls and track
    - Audio/                 # All sound effects and music

  - Docs/
    - design_doc.md          # Design ideas and documentation

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