# isoRRT

A relational reasoning trainer where you build the answer instead of judging it.

**Play it:** https://hidinglake.github.io/iso-rrt/

You get three statements about three terms, such as *"MEH is Directly Above SUN"*, *"MEH is East of LUL"* and *"LUL is Above and West of SUN"*. You don't answer true or false. You place three coloured tiles on a small isometric board so that every statement holds. The board keeps turning while you work, and one compass label is your only fixed reference.

---

## What it's for

Relational reasoning is the work of holding several "X is to Y" relations in mind and combining them into one picture: where things are, which comes first, what follows from what. You use it when you follow directions, read a floor plan, picture a room from someone else's description, or work out a plan with several constraints.

Most relational reasoning trainers (RRTs) practise this with true-or-false questions built from long chains of premises. That trains something real. But much of the difficulty comes from holding a long list in memory and decoding wording, and a 50% guess rate hides how much you actually worked out. isoRRT tries to train the part that carries over to everyday reasoning: **building a mental model of how things relate, from a viewpoint you have to work out yourself.**

## How it aims for transfer

Transfer from any brain-training task to everyday thinking is not guaranteed, and the research on "far transfer" from cognitive training is mixed at best. isoRRT can't promise it. What it can do is shape the practice so the skill being trained looks as much as possible like the skill you use day to day. Each design choice below serves that aim.

### 1. You construct the answer, you don't judge it

In everyday reasoning nobody hands you a conclusion to mark right or wrong. You have to come up with the arrangement yourself. isoRRT makes you build the layout, which means forming a full mental model of how the three terms sit together. You can't get it right by spotting a pattern in the wording or by guessing. A wrong answer shows exactly which statements you broke.

### 2. There is usually more than one right answer

Any layout that satisfies all three statements is accepted, and most questions have many. That rewards understanding the constraints rather than finding one memorised solution. It is how real problems work: you look for *a* layout that fits, not *the* one.

### 3. The viewpoint keeps changing

Every time you place, move, lift or clear a tile, the board swings to one of eight angles and the compass label changes. "Up the screen" almost never means North. You have to re-anchor from the one label shown and work out the other directions from it, the way you orient yourself with a map that isn't facing north or picture a route from someone else's point of view. The true orientation never changes during a question, so your work stays valid. Only your view of it moves.

The label always shows a direction that none of the statements use. You can never read the answer straight off it; you always have to work out the directions you need from it.

### 4. Words mean what they mean in plain English

"Above" means higher, nothing more. "Directly Above" also means in the same spot. "North-East" means north and east by any amount. This mirrors everyday language, where "the café is above the shop" and "the lamp is directly above the table" say different things. Reading precisely, and not adding meaning that isn't there, is part of the skill.

### 5. Few items, more dimensions

Everyday relational problems rarely involve ten items in a chain. They usually involve a handful of things related in several ways at once: position, height, order. isoRRT keeps it to three terms and three statements, but combines a height dimension with a compass dimension, and one statement uses both. The challenge is integrating relations across dimensions, not memorising a long list.

### 6. Nothing to lean on but the relations

Terms are random three-letter names with no meaning, so you can't use what you already know about them. Each term has a colour that follows it everywhere: its name in the statements, its button and its tile. On the board, tiles carry no text. You match by colour and hold the relations in mind instead of reading labels off the board.

### 7. Steady practice over speed

The timer is a plain countdown for a practice session. It never locks the board or rushes a question. Accuracy is always visible and carries over between visits, so the measure you watch is whether you're getting it right.

---

## How to play

1. Read the three statements. Each one relates two of the three terms.
2. Choose a term from the term buttons. The first unplaced term is chosen for you.
3. Tap a square on the board to place that term's tile. If the square already has a tile, the new one goes onto the lowest free tier.
4. Use ▲ and ▼ on the chosen term to move it up or down a tier. Moving into a taken tier swaps the two tiles.
5. When all three are placed, press **✓** to check.

A correct answer moves on to the next question by itself. A wrong one marks each statement with a green ✓ or a red ✕ and waits. **👁** shows one layout that fits, and **→** goes to the next question.

## What the words mean

| Wording | Tier | Square |
|---|---|---|
| Above / Below | higher / lower | any |
| Directly Above / Directly Below | higher / lower | the same square |
| North, East, South or West of | any | straight along that compass line |
| North-East, South-East, South-West or North-West of | any | both directions, by any amounts |
| Above and North-East of (and the like) | higher / lower | as for the compass direction |

Only direction counts, never distance.

Every question has one statement about height, one about compass direction, and one that combines the two. Each pair of terms is related exactly once.

## The board

- **3 × 3 squares, 3 tiers.** A tile on tier 1 lies on its square. Higher tiers float a step above, so a stack reads as separate plates. Empty tiers under a raised tile show as dashed outlines.
- **One compass label.** A single direction (any of the eight) is shown beside the board, with a thin line pointing to its spot on the board's edge.
- **The view changes as you build.** Placing, moving, lifting or clearing a tile swings the board to a new angle and changes the label. Moving a tile up or down a tier does not.
- **Height turns with the board.** Tiers rise along the board's own "up", which is not always up the screen.
- **Terms are chosen from the buttons only.** Tiles on the board can't be tapped, so you can't select the wrong one by accident.

After you check, all eight compass points appear around the board.

## Controls

| Action | Mouse or touch | Keyboard |
|---|---|---|
| Choose a term | Tap its button | |
| Place the chosen term | Tap a square | |
| Move up / down a tier | ▲ / ▼ on the chosen term | ↑ / ↓, or 1–3 to set the tier |
| Take the chosen term off the board | | Backspace or Delete |
| Clear the board | ✕ | |
| Check / next question | ✓ / → | Enter |
| Show a layout that fits (after a wrong answer) | 👁 | |

## Accuracy and timer

- **Accuracy** sits at the top right as a percentage. It is remembered between visits. The square button next to it resets it.
- **Timer** sits under the title on desktop, or in the top row on a phone. Tap the minutes to type a new number (the box clears when you tap it). Press ▶ to start, ❚❚ to pause (▶ again to resume), and ■ to stop and go back to the start. It shows minutes and seconds, and runs separately from the questions.

## How questions are made

Questions are generated at random, so there is no fixed set to run out of or memorise. For each question the trainer picks:

- which of eight ways North points on the board,
- a hidden layout of the three terms that the statements describe,
- whether the height statement says "Directly",
- whether the compass statement is straight (North, East, South, West) or diagonal,
- which way round each statement is told ("A is Above B" or "B is Below A"),
- three names from a list of letter-only three-letter names, and which colour each gets.

## Running it yourself

The whole trainer is one file, `index.html`. There's nothing to build or install.

- **Locally:** download `index.html` and open it in a browser.
- **On GitHub Pages:** put `index.html` at the top level of a repository. In Settings → Pages, choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
- **Updating:** replace `index.html` with the new version.

Notes:

- It works in current Chrome, Edge, Firefox and Safari, on desktop and on phones. On a phone the whole trainer fits one screen without scrolling.
- Fonts load from Google Fonts. Offline, the page still works with the device's own fonts.
- Your accuracy and timer setting are kept in your browser's local storage on your own device. Nothing is sent anywhere.

## Acknowledgements

Inspired by direction-based relational reasoning trainers such as Syllogimous.
