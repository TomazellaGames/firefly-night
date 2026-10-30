# Firefly Night

> *"It only comes out at night."*

You are a lovesick **male firefly**. You have **3 days** to win the heart of the female who glows above the pumpkin grove. By day, sneak past a hungry frog. By night, copy her light dance to win her over.

Made by [Tomazella Games](https://tomazellagames.itch.io/) for the [GoedWare Halloween Game Jam #3](https://itch.io/jam/goedware-game-jam-halloween-3), with help from [Claude Code](https://claude.com/claude-code).

## How to play

The game runs in a browser. Nothing to install or build:

- **Online:** play it on the jam / itch.io page.
- **Locally:** clone this repo and open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari). It works on desktop and on mobile (touch buttons are on screen).

## Controls

| Action | Keyboard | Touch / mouse |
| --- | --- | --- |
| Move / dance direction | `W` `A` `S` `D` or arrow keys | On-screen arrow pad |
| Short flash (night) | Tap a direction | Tap a button |
| Long flash (night) | Hold a direction for ½ second | Hold a button |
| Confirm dialogs | `Enter` / `Space` | Click the button |
| Toggle music | `M` | ♪ button |
| Volume | — | Slider under the stage |

Your volume and music settings are remembered between sessions.

## Gameplay

Each of the 3 days has two parts: a **day** stage and a **night** stage.

### ☀ Day: sneak past the frog

Fly **right** (`A`/`D` or `←`/`→`) from the left side of the grove to the **big leaf** on the far right.

- A frog sits on a stump in the middle. While it **dozes** (`z z z`), keep flying.
- When it **croaks** and its throat swells, it's about to open its eyes. Get **under a leaf** right away.
- While it's **watching** (`!`), stay hidden until it falls back asleep.
- If it spots you outside a leaf, it eats you and **everything restarts from Day 1**.
- On Days 2 and 3, some leaves hold **water** 💧. They give way and fall when you get close or fly past them, so that hiding spot is gone.
- Each day the frog wakes up more often, and its warnings get shorter.

### ☾ Night: copy her light dance

The female firefly flashes a pattern of directions, each with its own musical note. Repeat it with the same directions.

- **Short flash**: tap the direction.
- **Long flash** (shown as `→━`): hold the direction for half a second. A chime plays when the flash becomes long.
- Each step scores **full** for the right direction and length, **half** for the right direction with the wrong length, and **zero** for the wrong direction.
- **Night 1** leaves a faded copy of the pattern on screen while you play it. On **Nights 2 and 3** you play it **from memory**.
- Later challenges chain several patterns in a row, and patterns get longer each night.

### Winning her heart ♥

The heart meter at the top shows her **likeness**. Each night adds to it based on your performance, and later nights are worth more (Night 1: 25%, Night 2: 30%, Night 3: 45%).

- Reach **75%** by the end of Night 3 to win. Scoring about 60% on every night is just enough.
- If you do poorly on a night, the next day is **easier**: the frog fills up on another firefly first and stays drowsy longer.

### Endings

| Likeness after Night 3 | Ending |
| --- | --- |
| Below 75% | **Bad Ending: Alone** |
| 75% or more | **Good Ending: Together ♥** |
| 100% | **Best Ending: Perfect Match ✨** |

Perfection is rewarded...

## Tips

- Leaf hopping: wait under a leaf until the frog dozes off, then dash to the next one.
- Listen to the notes as well as watching the flashes. Each direction always has the same pitch (↑ highest, ← lowest).
- For long flashes, wait for the chime before you let go.

## Tech

Everything is in one `index.html` file in plain HTML, CSS and JavaScript. Graphics are drawn with SVG, and all music and sound effects are made live with the Web Audio API. There are no libraries, image files or audio files.

## Credits

- Game design and development: [Tomazella Games](https://tomazellagames.itch.io/)
- Built with help from [Claude Code](https://claude.com/claude-code)
- Made for the [GoedWare Halloween Game Jam #3](https://itch.io/jam/goedware-game-jam-halloween-3)

## License

[MIT](LICENSE) © 2026 Tomazella Games
