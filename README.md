# Pegfall

A peg-bouncing arcade game that runs entirely in the browser: one self-contained `index.html`, no build step and no dependencies.

Aim the launcher, fire a ball and clear every orange peg before you run out of balls. Light up green pegs to trigger your Peg Pal's special power, catch balls in the sliding tray for free balls, and finish each level with a fever bonus run.

## Play

Open `index.html` in any modern browser. To play from GitHub, turn on **Settings → Pages → Deploy from branch → main / root**, and the game will be served at `https://<your-username>.github.io/Pegfall/`.

## Controls

| Action | Mouse | Keyboard |
|---|---|---|
| Aim | Move the mouse over the board | ← / → (hold Shift for fine aim) |
| Fire | Left click | Space or Enter |
| Speed up (between shots) | Hold right-click | Hold F |
| Pause | Purple-blue button, bottom left | Esc |

## Modes

- **Adventure**: 55 levels in 11 stages. Each stage introduces a new Peg Pal, and the Grand Finale mixes them.
- **Quick Play**: pick any board and any pal.
- **Challenges**: five special-rule challenges.
- **Duel**: two players take turns on one board.

## Peg Pals and green-peg powers

| Pal | Power |
|---|---|
| Ollie the Octopus | Multiball: a second ball joins the shot |
| Captain Pip | Super Guide: a longer bouncing aim guide for 3 shots |
| Chilli | Fireball: your next ball is a giant fireball that burns through pegs |
| Wisp the Ghost | Spooky Ball: the ball drops back in from the top once |
| Puff the Pufferfish | Blast: the green peg explodes and lights nearby pegs |
| Mags the Crab | Magnet: the ball is pulled toward orange pegs |
| Tank the Tortoise | Mega Ball: the ball doubles in size |
| Zap the Jellyfish | Chain Lightning: lightning leaps across the 6 nearest pegs |
| Tubs the Frog | Big Bucket: the catcher is twice as wide for 3 shots |
| Luna the Moth | Moon Gravity: gravity drops to a third |

## Scoring

- Blue peg 10, orange 100, purple 500, green 10, multiplied by the score multiplier.
- Each peg in a shot scores more than the last.
- The multiplier rises to 2x, 3x, 5x and 10x as you clear orange pegs.
- Free balls at 25,000, 75,000 and 125,000 points in a single shot, or by landing in the catcher.
- Style bonuses include Long Haul, Double Green, Orange Rush, Rim Shot and Bucket Kick.

## Notes

All artwork is drawn in code at runtime, and all music and sound effects are synthesised with the Web Audio API. Progress and audio settings are saved in the browser's local storage.
