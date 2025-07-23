# 🔥 Flame Runner

A fast-paced browser-based runner game where you control a flame character through challenging obstacles and collect power-ups.

## Features

- 🎮 Smooth HTML5 Canvas gameplay
- 🏆 Global leaderboard system
- 🎵 Dynamic background music
- 📱 Mobile-responsive controls
- 🌟 Progressive difficulty levels
- ⚡ Speed boost mechanics
- 🔐 Anti-cheat validation

## Quick Start

### For Development
1. Clone the repository
2. Install server dependencies: `npm run install-server`
3. Start the server: `npm start`
4. Open `client/index.html` in your browser

### For Production (Render.com)
- **Root Directory**: `/`
- **Build Command**: `npm run install-server`
- **Start Command**: `npm start`
- **Environment**: Node.js

## Project Structure

```
flame-runner/
├── client/              # Frontend files
│   ├── index.html      # Main game page
│   ├── game.js         # Game logic
│   ├── *.png           # Game assets
│   └── *.mp3           # Audio files
├── server/             # Backend Node.js server
│   ├── server.js       # Express server
│   ├── package.json    # Server dependencies
│   └── *.db           # SQLite database
└── package.json        # Root package.json
```

## Game Controls

- **Jump**: W, ↑ Arrow, or Tap (mobile)
- **Shoot**: Space, Click, or Tap shoot button (mobile)
- **Double Jump**: Press jump key twice quickly

## Tech Stack

- **Frontend**: HTML5 Canvas, JavaScript, CSS3
- **Backend**: Node.js, Express, SQLite
- **Audio**: HTML5 Audio API
- **Storage**: LocalStorage + Server persistence

Enjoy the game! 🔥