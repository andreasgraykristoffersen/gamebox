# 🎮 GameBox

A Steam-style game launcher that is **one single HTML file**. No install, no server, no downloads — open it and play.

**▶ Play it here: https://andreasgraykristoffersen.github.io/gamebox/**

## What's inside

**40 hand-built game engines**, plus themed variant packs with real rule twists on top — **2380 games in the store** in total.

Every variant is a real, different game: its own speed, board size, rules, colours and characters. Nothing is a dead card.

### The hand-built games

| | | |
|---|---|---|
| 🐍 Snake Dash | 🧱 Brick Buster | 🚀 Rocket Flap |
| 👾 Star Blaster | 🟦 Tetra Stack | 🔢 2048 Merge |
| 🐼 Critter Memory | ⭕ Tic Tac Duel | 🐹 Mole Smash |
| 🏓 Pong Duel | 🦖 Dino Dash | ⛏️ Block Craft |
| 🍄 Jump Kingdom | 🗡️ Hero Quest | 🏎️ Turbo Racer |
| 💥 Tank Duel | 🌀 Maze Runner | ☄️ Rock Dodger |
| 🎵 Copy Cat | 🧩 Slide Puzzle | 🎯 Target Blitz |
| 🏗️ Tower Stacker | 🐸 Road Cross | 🪨 Asteroid Field |
| ☁️ Sky Hopper | 💎 Gem Crush | 💣 Mine Finder |
| 🔴 Four in a Row | 📦 Box Pusher | 🎨 Flood It |
| 🔤 Word Guess | 🚁 Cave Flyer | 🍬 Candy Clicker |
| 🖌️ Paint Studio | 🏒 Air Hockey | |

**Block Craft** is a proper little sandbox: mine blocks, build towers, dig caves, find coal and gold, watch day turn to night — and the world saves itself when you leave.

## Play online against a friend 🌐

**Tank Duel** and **Air Hockey** can be played against a friend anywhere in the world:

1. Both of you open https://andreasgraykristoffersen.github.io/gamebox/
2. Start Tank Duel or Air Hockey and pick **🌐 Online vs a Friend**
3. One of you taps **Make a Room** and reads out the 4-letter code
4. The other taps **Join a Room**, types the code, and you're playing

The two browsers talk **directly to each other** over WebRTC — the game data doesn't go through any game server. A free public PeerJS broker is used only for the tiny "find each other" handshake (it sees a random room code, nothing else). No accounts, no sign-up, no chat.

Also available: **Same Screen** (two players, one keyboard) and, for Tank Duel, **Two Windows** on one computer.

## Features

- Store + **My Library** with playtime, high scores and how many times you played each game
- Search, genre filters, and a 🎲 **Surprise Me** button
- Works with keyboard, mouse and touch — every game has on-screen buttons
- High scores and Block Craft worlds save in your browser
- Zero dependencies. One file. Works offline.

## Run it yourself

Download `index.html` and double-click it. That's the whole thing.
