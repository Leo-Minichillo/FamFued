# Thanksgiving Face-Off

A survey-style game show for the family TV. One file, no install. Open `index.html` in Chrome or Edge.

It runs as **two tabs**:
- **Host tab (laptop):** your control panel. Shows every answer, plus simple buttons to run the game.
- **TV tab:** just the game board. Answers only appear after you reveal them.

## Setup (do this before the family is watching)

1. Plug in the TV and set the display to **Extend**, not mirror.
   - Windows: `Win + P` → Extend
   - Mac: System Settings → Displays → use the TV as an extended display
2. Open `index.html` on the laptop. Edit team names and questions if you want.
3. Click **📺 Open TV screen**. Drag that new tab out of the window and onto the TV.
4. Click once on the TV screen to make it fullscreen.
5. Back on the laptop, click **Start new game**. The host screen shows "📺 TV screen connected" in green when the two tabs are talking.

If the button doesn't open a tab, open the same file in a new tab yourself and add `#tv` to the end of the address.

## Running a round (laptop)

- Click an answer to reveal it on the TV (click again to hide it).
- **✕ Wrong answer** adds a strike and shows the big X. **Face-off miss** shows one X without counting a strike.
- **Give round points to** a team. If the other team steals, just click their button and the points move over.
- **Next round ▶** when you're done. Rounds can be double or triple points.
- **🏆 Show winner** puts the winner screen on the TV.
- Click **edit** under a score to fix it by hand.

Optional keys: `1`-`8` reveal, `X` wrong, `Q` / `P` give points, `N` next.

## Fast Money

Click **💰 Fast Money** on the host screen.
1. **Start 20s** for Player 1 (25s for Player 2).
2. Type what they said. Click the matching survey answer under each question to fill in the points (or **Not on list · 0**).
3. Click **Show answer**, then **Show points**, one row at a time. The TV total updates live.
4. **Hide on TV** hides Player 1's answers while Player 2 plays. **Buzzer** is for repeat answers.
5. Hitting 200 sets off the winner screen.

## Question format

```
Name something you're thankful for. x2
Family 42
Health 19
Friends 12
```

Blank line between rounds. `x2` / `x3` at the end of a question doubles or triples the points. Up to 8 answers per round. The sample point values are made up.

## Notes

- Sounds play from the laptop tab, through whatever the laptop's audio output is. With HDMI that's usually the TV.
- Everything saves in the browser, so refreshing either tab is safe.
- The fun font needs internet; offline it falls back to a plain bold font.
