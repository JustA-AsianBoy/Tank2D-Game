# 🚀 Pilot Ur Own Tank: Make Yourself a Hero

A high-intensity, 1-minute arcade shooter built with **Phaser 3**. Test your reflexes, survive the onslaught, and leave your legacy on the leaderboard.

## 🎮 Play the Game
[https://justa-asianboy.github.io/Tank2D-Game/]

---

## 🎖️ The Challenge
You have **60 seconds** to score as many points as possible. 
Incoming enemies will attempt to intercept you. Can you survive the minute and become a legendary pilot?

## 🛠️ Key Features
* **Adrenaline Timer:** A strict 60-second limit that forces fast-paced decision making.
* **Smart Pause System:** Press `P` to pause. Logic ensures the game timer and physics freeze perfectly in sync.
* **Hero Recovery (I-Frames):** Taking damage grants 3 seconds of invincibility and transparency to allow for tactical repositioning.
* **Local Leaderboard:** Persistent Top-5 high scores saved via the Browser's `localStorage` API.
* **Visual Polish:** Cyan laser muzzle flashes and synchronized explosion sound effects.

## 🕹️ Controls
* **Arrow Keys:** Pilot your Tank (Up, Down, Left, Right)
* **Spacebar:** Fire Laser Cannon
* **P Key:** Pause or Resume Game
* **R Key:** Restart (After Game Over)

---

## 💻 Technical Stack
* **Core Engine:** Phaser 3 (Arcade Physics)
* **Language:** JavaScript (ES6+)
* **Frontend:** HTML5 / CSS3
* **Storage:** Web Storage API (Local Storage)

## 🐞 Bug Fixes & Development Highlights
* **Timer Sync:** Developed a `timeOffset` logic to prevent the countdown from running while the game is paused.
* **Performance Optimization:** Implemented automatic sprite destruction for off-screen bullets to prevent memory leaks.
* **Collision Balancing:** Designed a custom debounce system to prevent single-frame health depletion during enemy overlaps.

---

## 🚀 Future Roadmap
* **Cloud Competition:** Integration with Firebase for global real-time leaderboards.
* **Elite Enemies:** Introduction of Boss battles at specific score milestones.
* **Power-Ups:** Collectible items for Triple-Shot, Shielding, and Time-Extension.

---
Created by [JustA-AsianBoy] as a Technical Showcase Project.
