# Western Zombie Town

A playable western zombie town prototype built as a single-file Three.js game.

## Files

- `index.html` — playable game prototype
- `assets/sprites/` — optional folder for automatic sprite loading

## Sprite names

For automatic loading, add these PNG files:

```text
assets/sprites/cowboy_idle.png
assets/sprites/cowboy_walk.png
assets/sprites/cowboy_shoot.png
assets/sprites/cowboy_hurt.png
assets/sprites/cowboy_die.png

assets/sprites/zombie_idle.png
assets/sprites/zombie_walk.png
assets/sprites/zombie_hurt.png
assets/sprites/zombie_die.png
```

## Backup upload system

The game keeps the in-game **SPRITES** panel. If the files are not in `assets/sprites/`, tap **SPRITES** and batch upload the named PNGs.

The batch uploader checks file names and reports matched, skipped, and missing sheets.

## Controls

Desktop:

- Move: WASD / Arrow Keys
- Aim: Mouse
- Shoot: Click / Space
- Restart: R

Mobile / iPad:

- Left joystick: move
- SHOOT button: fire
- RESET button: restart
- PAUSE button: pause/resume
