# 2048: Fruit Market

A fruit-themed reskin of the classic 2048 puzzle game, built as a single self-contained `index.html` file (no build step, no dependencies).

## How to play

- Use the **arrow keys** (desktop) or **swipe** (touch devices) to slide all tiles in one direction.
- Tiles with the same fruit merge into the next fruit in the progression when they collide.
- Reach the **Golden Mango** (2048) to win — or keep playing past it to grow an even higher score.
- The board is full and no merges are possible? Game over. Click **New Game** to start over.

## Fruit progression

| Value | Fruit |
|---|---|
| 2 | 🍒 Cherry |
| 4 | 🍓 Strawberry |
| 8 | 🍇 Grape |
| 16 | 🍋 Lemon |
| 32 | 🍊 Orange |
| 64 | 🍎 Apple |
| 128 | 🍐 Pear |
| 256 | 🍍 Pineapple |
| 512 | 🍉 Watermelon |
| 1024 | 🥝 Kiwi |
| 2048 | 🥭 Golden Mango |

## Running it

Just open `index.html` in a browser — everything (markup, styles, and game logic) lives in that one file. Your best score is saved locally via `localStorage`.

## Tech

Plain HTML, CSS, and vanilla JavaScript. Fonts (`Fraunces`, `Karla`) are loaded from Google Fonts.
