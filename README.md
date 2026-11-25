# isoRRT

A relational reasoning trainer where you build the answer instead of judging it.

**Play it:** https://hidinglake.github.io/iso-rrt/

You get three statements about three terms, such as *"MEH is Directly Above SUN"*, *"MEH is East of LUL"* and *"LUL is Above and West of SUN"*. You don't answer true or false. You place three coloured tiles on a small isometric board so that every statement holds. The board keeps turning while you work, and one compass label is your only fixed reference.

There are two modes. **Simple** is the question above. **Complex** moves to a larger board with a fourth term, and adds a statement that compares distances (*"SUN is Closer to MEH than LUL is"*).

---

## What it's for

Relational reasoning is the work of holding several "X is to Y" relations in mind and combining them into one picture: where things are, which comes first, what follows from what. You use it when you follow directions, read a floor plan, picture a room from someone else's description, or work out a plan with several constraints.

Most relational reasoning trainers (RRTs) practise this with true-or-false questions built from long chains of premises. That trains something real. But much of the difficulty comes from holding a long list in memory and decoding wording, and a 50% guess rate hides how much you actually worked out. isoRRT tries to train the part that carries over to everyday reasoning: **building a mental model of how things relate, from a viewpoint you have to work out yourself.**

## How it aims for transfer

Transfer from any brain-training task to everyday thinking is not guaranteed, and the research on "far transfer" from cognitive training is mixed at best. isoRRT can't promise it. What it can do is shape the practice so the skill being trained looks as much as possible like the skill you use day to day. Each design choice below serves that aim.

### 1. You construct the answer, you don't judge it

In everyday reasoning nobody hands you a conclusion to mark right or wrong. You have to come up with the arrangement yourself. isoRRT makes you build the layout, which means forming a full mental model of how the terms sit together. You can't get it right by spotting a pattern in the wording or by guessing. A wrong answer shows exactly which statements you broke.

### 2. There is usually more than one right answer

Any layout that satisfies all three statements is accepted, and most questions have many. That rewards understanding the constraints rather than finding one memorised solution. It is how real problems work: you look for *a* layout that fits, not *the* one.

### 3. The viewpoint keeps changing

Every time you place, move, lift or clear a tile, the board swings to one of eight angles and the compass label changes. "Up the screen" almost never means North. You have to re-anchor from the one label shown and work out the other directions from it, the way you orient yourself with a map that isn't facing north or picture a route from someone else's point of view. The true orientation never changes during a question, so your work stays valid. Only your view of it moves.

The label always shows a direction that none of the statements use. You can never read the answer straight off it; you always have to work out the directions you need from it.

### 4. Words mean what they mean in plain English

"Above" means higher, nothing more. "Directly Above" also means in the same spot. "North-East" means north and east by any amount. This mirrors everyday language, where "the café is above the shop" and "the lamp is directly above the table" say different things. Reading precisely, and not adding meaning that isn't there, is part of the skill.

### 5. Few items, more dimensions

Everyday relational problems rarely involve ten items in a chain. They usually involve a handful of things related in several ways at once: position, height, order. isoRRT keeps it to three or four terms and three to five statements, but combines a height dimension with a compass dimension. Complex mode adds distance: a single statement that compares three terms at once. The challenge is integrating relations across dimensions, not memorising a long list.

### 6. Nothing to lean on but the relations

Terms are random three-letter names with no meaning, so you can't use what you already know about them. Each term has a colour that follows it everywhere: its name in the statements, its button and its tile. On the board, tiles carry no text. You match by colour and hold the relations in mind instead of reading labels off the board.

### 7. Steady practice over speed

Practice comes in sessions of a length you choose. The clock sets the length of the session, not of a question: nothing rushes an individual answer. Accuracy is always visible, and the session ends on a result screen, so the measure you watch is whether you're getting it right. You can also turn the two kinds of shuffling off while you learn the rules, then back on.

---

## Sessions

Every visit opens on the session settings:

| Setting | What it does |
|---|---|
| Mode | Simple or Complex (see below) |
| Session duration | How long the session runs, in minutes. Tap the number to type a new one. |
| Grid shuffle | On: the board swings to a new angle each time you place, move, lift or clear a term. Off: the board always sits the same way up. |
| Direction shuffle | On: the compass label changes to another unused direction each time you place, move, lift or clear a term. Off: the label stays put for the whole question. |

**Start** begins the session with the clock running. The settings are remembered for next time. The screen is laid out as Mode, Grid shuffle, Direction shuffle, then the minutes and Start side by side.

During play the timer sits at the top left (beside the name on a phone), with **Abort** under it.

- **❚❚** pauses the clock. While it is paused the board is hidden and "Start timer to continue" stands in its place; **▶** brings it back.
- **Abort** ends the session early.
- When the clock runs out, the question you are on is not cut short: the clock reads 00:00 in red, and the session ends once you check that answer.
- The result screen (also shown after Abort) gives the session's accuracy, how many you got right, the time spent, the average time per question, and a list of every question with ✓ or ✕ and the time it took. Pauses are left out of the times. **Next** returns to the settings.

## Modes

| Mode | Board | Terms | Statements |
|---|---|---|---|
| Simple | 3 × 3 | 3 | height, compass, and one that combines the two |
| Complex | 5 × 5 | 4 (three drawn names plus **REF**, in white) | five: height, compass, Closer / Farther third, a fourth that combines height with compass, and a fifth compass direction |

In Complex, three of the terms are tied together in a loop by three compass statements, so they have to be worked out together and not one after another. Every term has a statement about its tier. Every statement matters: questions are only used where Closer / Farther rules out at least half of the layouts that satisfy the rest, and each other statement at least a quarter.

The fourth term is always called **REF** and is always white. It starts on the board, on a square it never leaves, and its button (the last one in the list, or the bottom right on a phone) carries a small padlock. You can still choose it and move it up or down a tier with ▲ ▼, but tapping a square won't move it and Clear puts it back on tier 1. It is your reference point: the other three terms are placed around it.

On a phone, the five Complex statements are a list you scroll: three are in view, with arrows to the rest. After a wrong answer the list moves to the first broken statement.

Accuracy is counted per session.

## How to play

1. Read the statements. Each one relates two of the terms (a Closer / Farther statement relates three).
2. Choose a term from the term buttons. The first unplaced term is chosen for you.
3. Tap a square on the board to place that term's tile. If the square already has a tile, the new one goes onto the lowest free tier.
4. Use ▲ and ▼ on the chosen term to move it up or down a tier. Moving into a taken tier swaps the two tiles.
5. When every term is placed, press **✓** to check.

A correct answer moves on to the next question by itself. A wrong one marks each statement with a green ✓ or a red ✕ and waits. **👁** shows one layout that fits, and **→** goes to the next question.

## What the words mean

| Wording | Tier | Square |
|---|---|---|
| Above / Below | higher / lower | any |
| Directly Above / Directly Below | higher / lower | the same square |
| North, East, South or West of | any | straight along that compass line |
| North-East, South-East, South-West or North-West of | any | both directions, by any amounts |
| Above and North-East of (and the like) | higher / lower | as for the compass direction |
| A is Closer to B than C is (Complex) | any | A's square is nearer to B's than C's square is |
| A is Farther from B than C is (Complex) | any | A's square is farther from B's than C's square is |

For the direction words, only direction counts, never distance.

**Closer** and **Farther** compare straight-line distance across the board. Height doesn't count: a tile two tiers up on the same square is as close as it can be. A tie is neither closer nor farther. The word is underlined in the statement; point at it or tap it for a reminder. Questions are only built from layouts where the comparison is clear however you count the distance.

In Simple, each pair of terms is related exactly once.

## The board

- **3 × 3 squares (5 × 5 in Complex), 3 tiers.** Both have a centre square, so every compass line runs through the middle of a square. A tile on tier 1 lies on its square. Higher tiers float a step above, so a stack reads as separate plates. Empty tiers under a raised tile show as dashed outlines.
- **One compass label.** A single direction (any of the eight) is shown beside the board, with a thin line pointing to its spot on the board's edge.
- **The view changes as you build.** With grid shuffle and direction shuffle on, placing, moving, lifting or clearing a tile swings the board to a new angle and changes the label. Moving a tile up or down a tier does not. Either shuffle can be turned off in the session settings.
- **Height turns with the board.** Tiers rise along the board's own "up", which is not always up the screen.
- **Terms are chosen from the buttons only.** Tiles on the board can't be tapped, so you can't select the wrong one by accident.

After you check, all eight compass points appear around the board.

## Controls

| Action | Mouse or touch | Keyboard |
|---|---|---|
| Start a session | **Start** on the settings screen | Enter |
| Pause / carry on | ❚❚ / ▶ | |
| End the session | **Abort** | |
| Choose a term | Tap its button | |
| Place the chosen term | Tap a square | |
| Move up / down a tier | ▲ / ▼ on the chosen term | ↑ / ↓, or 1–3 to set the tier |
| Take the chosen term off the board | | Backspace or Delete |
| Clear the board | ✕ | |
| Check / next question | ✓ / → | Enter |
| Show a layout that fits (after a wrong answer) | 👁 | |

## Accuracy

Accuracy sits at the top right as a percentage and counts the current session. The square button next to it resets it. The result screen at the end of the session shows the final figure.

## How questions are made

Questions are generated at random, so there is no fixed set to run out of or memorise. For each question the trainer picks:

- which of eight ways North points on the board,
- a hidden layout of the terms that the statements describe,
- whether the height statement says "Directly",
- in Complex, which three terms the Closer / Farther statement compares, and whether it says Closer or Farther,
- whether the compass statement is straight (North, East, South, West) or diagonal,
- which way round each statement is told ("A is Above B" or "B is Below A"),
- the names, from a list of letter-only three-letter names, and which colour each gets.

## Running it yourself

The whole trainer is one file, `index.html`. There's nothing to build or install.

- **Locally:** download `index.html` and open it in a browser.
- **On GitHub Pages:** put `index.html` at the top level of a repository. In Settings → Pages, choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
- **Updating:** replace `index.html` with the new version.

Notes:

- It works in current Chrome, Edge, Firefox and Safari, on desktop and on phones. On a phone the whole trainer fits one screen without scrolling.
- Fonts load from Google Fonts. Offline, the page still works with the device's own fonts.
- Your session settings are kept in your browser's local storage on your own device. Nothing is sent anywhere.

## Acknowledgements

Inspired by direction-based relational reasoning trainers such as Syllogimous.
