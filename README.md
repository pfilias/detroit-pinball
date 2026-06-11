# Detroit Motor City Pinball

A full pinball machine in a single HTML file. No build, no dependencies, no server —
open `index.html` in a browser and play.

![Detroit Motor City Pinball](https://img.shields.io/badge/balls-3-orange) ![](https://img.shields.io/badge/teams-4-blue)

## Play

Open `index.html` in any modern browser. That's it.

| Control | Action |
|---|---|
| `←` / `Z` / `A` | Left flipper |
| `→` / `/` / `L` | Right flipper |
| Hold `SPACE`, release | Plunger (power by hold time) |
| `ENTER` / `R` | New game (after game over) |
| `M` | Music on/off |
| Touch | Left/right half of screen = flippers |

## The machine

Theme: **drive I-75 to the big game in Detroit.** Lions, Tigers, Red Wings, Pistons.

- **I-75 freeway ramp** — elevated overpass crossing the whole playfield. Value
  ladder 1,500 → 3,000 → 5,000 → 7,500. Consecutive ramps within 6s = **WOODWARD
  RUN** combo (2x/3x). Every 3rd ramp starts **RUSH HOUR**, a 25,000 hurry-up that
  drains before your eyes — shoot the ramp again to collect.
- **Multiball** — light all 4 team bumpers to light **LOCK** at the Pit Stop
  saucer. Two locked balls = 3-ball multiball, everything 2x, and the ramp becomes
  a 25,000 **JACKPOT** (relight via any team bumper). Saucer adds a ball, once.
- **313 lanes** — Detroit's area code across the top. Complete for 3,130; flippers
  rotate the lit lanes; a flashing lane at launch is the 5,000 skill shot.
- **D-E-T-R-O-I-T drop targets** — complete the bank to raise the bonus
  multiplier (to 5x, shown on the tachometer needle). Resets every ball.
- **Pit Stop saucer** — locks balls when lit; otherwise 2,500 + lights the
  one-shot outlane **KICKBACK**.
- **Outlanes** — yes, you can drain there. That's pinball.
- **End-of-ball bonus** — bumpers, 313s, and ramps tally up × your multiplier.

## Music

Drop a `lose-yourself.mp3` (or any `music.mp3`) next to `index.html` and it plays
looped. No file? An original chiptune loop plays instead. Audio files are
gitignored — bring your own.

## Credits / disclaimers

Personal fan project. Not affiliated with, endorsed by, or sponsored by the
Detroit Lions, Detroit Tigers, Detroit Red Wings, Detroit Pistons, their leagues,
or any rights holder. Team names and logos are trademarks of their respective
owners, used here in a non-commercial fan context.

Board design audited and revised by way of a three-designer review process
(Stern-school flow audit, Bally/Williams-school art audit, lead-designer
synthesis). Built with Claude Code.
