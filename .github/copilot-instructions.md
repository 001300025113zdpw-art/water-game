# Repository guidance

## Game style and structure

- `mizu-game.html` is the visual and interaction reference for this repository. Preserve its Japanese retro pixel-art game feel when extending it or creating another game here: dark, high-contrast framing; crisp low-resolution canvas graphics; compact HUD bars; and in-game title/result panels.
- Keep browser games self-contained in a single HTML file unless the user asks for a different structure. Draw game scenes on a canvas with pixelated rendering; keep HUD, instructions, and menus as HTML overlays where appropriate.
- Keep the interface and player-facing game text in Japanese. Add Japanese comments for non-obvious game logic, following the existing reference.
- Preserve the reference's playable-at-a-glance controls and status feedback. The current game uses keyboard input, a camera-following world, a HUD, and title/day-end/game-over panels; retain the relevant interaction patterns when adapting the game.
- Keep educational scenarios clearly framed as simplified simulations. Do not present invented locations, characters, or mechanics as factual accounts.

## Build, test, and lint

No build, test, or lint commands are currently defined. Open the standalone HTML file directly in a browser to play. There is no configured automated browser-test command.
