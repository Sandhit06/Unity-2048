<h1 align="center"><b>🎮 2048 - Unity Edition 🎮</b></h1>

<p align="center">
A smooth, modern take on the classic puzzle game <b>2048</b>, built using <b>Unity</b> for rich graphics and <b>.NET</b> for scalable backend logic.
</p>

![Game Image](/2048.jpg)

---

## Features:

- [x] 🧠 **Classic 2048 Mechanics** — Merge tiles to reach the magical 2048 tile!
- [x] 🎮 **Built in Unity** — Crisp animations, drag/swipe support, smooth performance.
- [x] 🌐 **.NET Backend** — Tracks scores, sessions, and can connect to a leaderboard.
- [x] 💾 **Save & Resume** — Resume your game anytime with persistent state saving.
- [x] 📈 **Leaderboard Ready** — Optional cloud sync and high score tracking.
- [x] 🌓 **Dark/Light Themes** — Aesthetic switch for player preference.

---

## High-Level Architecture

- **Frontend**: Developed with Unity (C#), delivering fluid animations and clean UX for desktop/mobile.
- **Backend**: .NET Core handles score tracking, game state management, and future multiplayer extensions.
- **Data Storage**: JSON-based local saves and optional online database (e.g., Firebase or SQL).
- **Platform Support**: WebGL, Windows, Android builds supported.

---

## Core Components

- **GameManager**: Controls the main game logic (tile merging, movement, win/loss state).
- **BoardManager**: Initializes and manages the 4x4 grid system.
- **InputHandler**: Listens for player swipe/arrow inputs and triggers tile movement.
- **ScoreManager**: Tracks current and best scores, updates UI.
- **SaveSystem**: Serializes game state locally; optionally syncs to cloud.
- **UIManager**: Controls menus, restart buttons, end game popups, and animations.

---

## Gameplay Flow

### 1. Start New Game
- Launch the game and initialize a fresh 4x4 board.
- Two tiles spawn randomly (2 or 4).

### 2. Player Input
- Arrow keys / swipes move tiles in a direction.
- Identical tiles merge and add up.

### 3. Game Progression
- New tile spawns after each move.
- Score increases with merges.
- Game ends when no valid moves remain.

### 4. Resume or Restart
- Player can restart anytime or continue from a saved session.

---

## Optimization Techniques

- **Object Pooling**: Improves performance by reusing tile objects.
- **Serialized Data**: Efficient save/load mechanism using JSON serialization.
- **Mobile Input**: Optimized touch gestures for a responsive feel.
- **Frame Independent Movement**: Smooth animations on all devices.

---

## Setup & Run Locally

1. Clone the repo:
```bash
git clone https://github.com/Sandhit06/Unity-2048.git
```
2. Open the project in Unity (Unity 2021.3.x or higher recommended).
3. Run the game in the Unity editor or build to platform of choice.

## Build Targets
- ✅ Unity Editor

- ✅ Windows Executable

- ✅ WebGL (playable in browser)
  
- ✅ Android APK (touch support)

## Demo

https://github.com/user-attachments/assets/ba182f69-730f-4220-8f0d-0659dd6ce0e4


## Still need help?
Open an issue on our GitHub repository, and we will help you as soon as possible.

Enjoy exploring and extending this project! Feel free to contribute and suggest improvements.

## Contact

If you want to contact me you can reach me at [Twitter](https://x.com/SandhitK).

## Developer
<table>
    <tr align="center">
        <td>
        Sandhit Karmakar
        <p align="center">
            <img src = "https://avatars.githubusercontent.com/u/90787826?v=4" width="150" height="150" alt="Dhruv Shah">
        </p>
            <p align="center">
                <a href = "https://github.com/Sandhit06">
                    <img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
                </a>
                <a href = "https://www.linkedin.com/in/sandhit-karmakar/" target="_blank">
                    <img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
                </a>
                <a href = "mailto:sandhitkarmakar@gmail.com" target="_blank">
                    <img src = "https://www.iconninja.com/files/312/807/734/share-send-email-chat-circle-message-mail-icon.svg" width="36" height="36" alt="Email"/>
                </a>
            </p>
        </td>
    </tr>
</table>

<p align="center">
    Made with ❤️ by <a href="https://github.com/Sandhit06">Sandhit Karmakar</a>
</p>
