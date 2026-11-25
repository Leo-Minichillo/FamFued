# Face-Off Game Night

A survey-style game show for the family TV, with 3 games built in:

1. **Thanksgiving Face-Off** (8 rounds + Fast Money)
2. **2026 Face-Off** (8 rounds + Fast Money, built on real 2026 events: the World Cup, Super Bowl LX, the Winter Olympics, the year's big movies, shows and music)
3. **Game 3**: an empty slot for your own questions

Pick a game with the tabs on the setup screen. Each game keeps its own questions and title; team names are shared. One file, no install. Open `index.html` in Chrome or Edge.

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

- Each round starts with the question **hidden on the TV** (it shows "🎤 Face-off!") so you can read it out loud for the face-off. Click **🙈 Question hidden... click to show** (or press `V`) when you want it up. It also appears automatically on the first **Wrong answer** or when you give the round points to a team. **Face-off miss** doesn't reveal it.
- Click an answer to reveal it on the TV (click again to hide it).
- **✕ Wrong answer** adds a strike and shows the big X. **Face-off miss** shows one X without counting a strike.
- **Give round points to** a team. If the other team steals, just click their button and the points move over.
- **Next round ▶** when you're done. Rounds can be double or triple points.
- **🏆 Show winner** puts the winner screen on the TV.
- Click **edit** under a score to fix it by hand.

Optional keys: `1`-`8` reveal, `X` wrong, `Q` / `P` give points, `N` next.

## Fast Money (head-to-head)

Each team picks one player. The team that's ahead going into Fast Money goes first with **30 seconds**; the other team goes second with **40 seconds**. (On a tie, use **⇄ Swap who goes first**.)

1. Click **💰 Fast Money**, then **Set 30s** for the first team. That puts 30 on the TV without starting it. Press **▶ Start** (or `Space`) when the player is ready; the same button pauses and resumes.
2. Type what they said. Click the matching survey answer under each question to fill in the points (or **Not on list · 0**).
3. Click **Show answer**, then **Show points**, one row at a time.
4. Send the second player out of the room while the first one plays. Click **Hide on TV** before bringing them back, then **Set 40s** and **▶ Start**. Both players can give the same answers, and every Fast Money question has a close top two so going first is not a big edge.
5. **🏆 Show winner** on the Fast Money screen announces whichever team scored more in Fast Money.

## Question format

```
Name something you're thankful for. x2
Family 42
Health 19
Friends 12
```

Blank line between rounds. `x2` / `x3` at the end of a question doubles or triples the points. Up to 8 answers per round, and up to 8 per Fast Money question. Lines starting with `#` are ignored. Each question's points should add up to 100; the setup screen warns you if one doesn't. Questions with a `# Source:` line get their points from real data (box office, Nielsen ratings, polls, game history) and the host screen shows that source. The rest are estimates.

## Notes

- Sounds play from the laptop tab, through whatever the laptop's audio output is. With HDMI that's usually the TV.
- Everything saves in the browser, so refreshing either tab is safe.
- The fun font needs internet; offline it falls back to a plain bold font.
