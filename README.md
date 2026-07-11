# Car Race

A 2D car dodging game built with Flutter and Flame.

## Overview

Car Race is a lightweight arcade-style game where the player chooses a car, starts a run, and survives as long as possible by steering left and right to avoid incoming enemy vehicles. The game uses a simple endless-score loop and a polished overlay-based UI.

## Gameplay

The current gameplay flow is:

1. Open the main menu and choose a car model.
2. Press Start to begin the race.
3. Move the player car left or right to avoid enemy cars.
4. Keep the run going to increase your score.
5. If you collide with an enemy, the game ends and a replay button is shown.

## Features

- Car selection screen with vehicle options
- Keyboard and touch-friendly left/right movement
- Score tracking during gameplay
- Pause and resume controls during the run
- Game-over overlay with Play Again support
- Flame-powered 2D rendering and collision handling

## Controls

- Desktop / web: use the left and right arrow keys
- Touch-friendly overlay: tap the left and right arrow buttons shown on the game screen
- Pause: use the pause button in the top-right overlay

## Run the project locally

```bash
flutter pub get
flutter run
```

## Project stack

- Flutter
- Flame game engine
- Material 3 UI styling
- Google Fonts for the visual theme

## Notes

This repository is currently a playable prototype rather than a full racing simulation. The game focuses on the arcade loop: dodge, survive, score, and replay.

