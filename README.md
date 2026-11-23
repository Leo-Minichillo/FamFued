# Thanksgiving Face-Off

A survey-style game show board for the family TV. One file, no install: open `index.html` in Chrome or Edge on a laptop connected to the TV.

## Running the game

1. Open `index.html` and edit the questions and team names on the setup screen (do this before people are watching, since the answers are visible here).
2. Click **Print host answer sheet** so you can see the answers while the TV shows the board.
3. Click **Start new game**, then press `F` for fullscreen and `H` to hide the button bar.

Everything saves in the browser, so a refresh or a closed tab won't lose the scores. Hit **Resume** on the setup screen.

## Host keys (main board)

| Key | Does |
|---|---|
| `1`-`8` | Reveal an answer (`Shift` + number hides it again) |
| `X` / `Z` | Add / remove a strike |
| `B` | Buzzer + single X, no strike counted (face-off misses, failed steals) |
| `Q` / `P` | Give the round's points to the left / right team |
| `R` | Reveal the rest of the board (no points added) |
| `N` or `→` / `←` | Next / previous round |
| `W` | Final scores and winner screen |
| `G` | Switch to Fast Money and back |
| `F` `M` `H` `?` `S` | Fullscreen, mute, hide buttons, help, setup |

Click a team's score to fix it by hand. Pressing `Q` then `P` moves the points to the other team (handy after a steal).

## Fast Money

- `T` starts a 20s timer, `Y` a 25s timer, `Space` pauses.
- `E` / `R` opens the screen to type Player 1 / Player 2 answers and their points from the host sheet.
- `1`-`5` reveal Player 1's rows (press once for the answer, again for the points), `6`-`0` for Player 2.
- `V` hides Player 1's answers while Player 2 plays. `X` plays the buzzer for a duplicate answer.
- Hitting 200 total triggers the winner celebration.

## Question format

```
Name something you're thankful for. x2
Family 42
Health 19
Friends 12
```

Blank line between rounds. `x2` / `x3` at the end of a question doubles or triples the points. Up to 8 answers per round.
