# Cauldron Catch 🎃

A cute 60-second Halloween arcade game. Slide a little cauldron to catch falling treats, dodge the spiders and bats, and chase the high score.

**Play it:** open `index.html` in any browser. No build step, no dependencies.

## How to play

- Move with your mouse, your finger, or the `←` `→` keys (`A` / `D` work too).
- You have **3 lives** and **60 seconds**.
- Catch 5 treats in a row to raise your multiplier, up to **×5**. Letting a treat drop resets it.

| Falling thing  | Effect   |
| -------------- | -------- |
| Wrapped candy  | +10      |
| Candy corn     | +10      |
| Lollipop       | +20      |
| Golden pumpkin | +50      |
| Spider         | −1 life  |
| Bat            | −1 life  |

## Leaderboard

The shared "Haunted Hall of Fame" runs when the game is opened as a Claude artifact, using the artifact's shared database. Opened anywhere else, the game still plays and remembers your best score on that device.

## Tech

One self-contained HTML file: canvas drawing, Web Audio sound effects, and Google Fonts (Sniglet and Nunito).
