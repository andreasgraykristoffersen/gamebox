# 🎮 GameBox

A Steam-style game launcher that is **one single HTML file**. No install, no server, no downloads — open it and play.

**▶ Play it here: https://andreasgraykristoffersen.github.io/gamebox/**

## 48 games — every one of them different

No duplicate cards, no filler. Each entry in the store is its own game with its own code.

| | | | |
|---|---|---|---|
| 🐍 Snake Dash | 🧱 Brick Buster | 🚀 Rocket Flap | 👾 Star Blaster |
| 🟦 Tetra Stack | 🔢 2048 Merge | 🐼 Critter Memory | ⭕ Tic Tac Duel |
| 🐹 Mole Smash | 🏓 Pong Duel | 🦖 Dino Dash | ⛏️ Block Craft |
| 🍄 Jump Kingdom | 🗡️ Hero Quest | 🏎️ Turbo Racer | 💥 Tank Duel |
| 🌀 Maze Runner | ☄️ Rock Dodger | 🎵 Copy Cat | 🧩 Slide Puzzle |
| 🎯 Target Blitz | 🏗️ Tower Stacker | 🐸 Road Cross | 🪨 Asteroid Field |
| ☁️ Sky Hopper | 💎 Gem Crush | 💣 Mine Finder | 🔴 Four in a Row |
| 📦 Box Pusher | 🎨 Flood It | 🔤 Word Guess | 🚁 Cave Flyer |
| 🍬 Candy Clicker | 🖌️ Paint Studio | 🏒 Air Hockey | 🏰 Tower Defense |
| 🫧 Bubble Pop | 🎶 Beat Tapper | 🎣 Big Catch | 🔡 Mini Sudoku |
| 🟡 Chomp Maze | ⛳ Mini Golf | 🍉 Fruit Slice | 🚀 City Defense |
| 💡 Lights Out | ⚫ Checkers | ⌨️ Typing Rush | ⚽ Penalty Kicks |

**Block Craft** is a proper sandbox: mine blocks, build towers, dig caves, find coal and gold, watch day turn to night — and the world saves itself when you leave.

## Skins are options, not extra games 🎨

Open any game and you get a picker:

- **🎨 Skin** — 26 colour packs (Neon, Lava, Arctic, Jungle, Candy, Galaxy, Toxic, …) that change the colours *and* the characters.
- **⚡ Speed** — Chill, Classic or Turbo.
- **✨ Twist** — rules that genuinely change the game.

There's a **🎨 Skin** button inside every game too, so you can change it mid-session, and a **🎲 Surprise skin** button if you can't decide.

### Some of the twists

| Game | Twist | What changes |
|---|---|---|
| Snake | Bombs | Every 3rd apple drops a bomb on the board |
| Snake | Portals | No walls — leave one edge, appear at the other |
| Snake | Starving | A hunger bar drains; eat or die |
| Bricks | Multiball | Two balls from the first serve |
| Bricks | Creeping | The brick wall marches down at you |
| Flappy | Wavy | The gaps drift up and down as you fly |
| Blaster | Shooters | The aliens shoot back |
| Maze | Blackout | Pitch dark — you see a small circle around you |
| Maze | Keys | Find 3 keys or the exit stays locked |
| Pong | Two Balls | Two balls at once |
| Runner | Moon | Low gravity, floaty jumps |
| Tetris | Junk Rising | A junk row pushes up from the bottom |

## Play online against a friend 🌐

**Tank Duel** and **Air Hockey** work over the internet:

1. Both of you open the link above
2. Start the game and pick **🌐 Online vs a Friend**
3. One taps **Make a Room** and reads out the 4-letter code
4. The other taps **Join a Room** and types it in

The browsers talk **directly to each other** over WebRTC — game data never touches a game server. A free public PeerJS broker handles only the tiny "find each other" handshake. No accounts, no sign-up, no chat.

Also: **Same Screen** (two players, one keyboard) and **Two Windows** for Tank Duel.

## Features

- Store + **My Library** with playtime, high scores and play counts
- Search, 19 genre filters, and a 🎲 Surprise Me button
- Keyboard, mouse and touch — every game has on-screen buttons
- Scores, skin choices and Block Craft worlds save in your browser
- Zero dependencies (PeerJS loads only if you choose online play). One file. Works offline.

## Run it yourself

Download `index.html` and double-click it. That's the whole thing.
