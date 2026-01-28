# Zombie Survival: Operation Antidote 🧟‍♂️🔫

A fast-paced, browser-based zombie survival shooter game with unlimited ammo! Fight through endless waves of zombies, switch between weapons, and see how long you can survive in this action-packed HTML5 canvas game.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Canvas API](https://img.shields.io/badge/Canvas_API-HTML5-orange)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)

## 🎮 Play Now

Simply open the HTML file in any modern web browser and start playing immediately.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Gameplay](#gameplay)
- [Controls](#controls)
- [Game Mechanics](#game-mechanics)
- [Weapons](#weapons)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Technical Details](#technical-details)
- [Browser Compatibility](#browser-compatibility)


## 🎯 Overview

**Zombie Survival: Operation Antidote** is an intense top-down shooter where you must survive against endless waves of zombies. With unlimited ammunition and multiple weapons at your disposal, test your reflexes and strategic thinking as the zombie hordes grow increasingly difficult.

### Game Highlights:
- 🔫 **Unlimited Ammo** - Focus on survival, not resource management
- 🧟 **Endless Waves** - Increasingly difficult zombie spawns
- 🎯 **Multiple Weapons** - Pistol and Shotgun with different characteristics
- 🎨 **Retro Graphics** - Classic top-down shooter aesthetic
- 🕹️ **Smooth Controls** - Responsive keyboard and mouse gameplay
- 📊 **Three Difficulty Levels** - Easy, Normal, and Hard modes

## ✨ Features

### Core Gameplay Features:
- ✅ **Smooth Canvas-Based Graphics** - 60 FPS gameplay
- ✅ **Dynamic Zombie Spawning** - Enemies spawn from all sides
- ✅ **Auto-Fire Support** - Hold space or mouse for continuous shooting
- ✅ **Weapon Switching** - Quick switch between pistol and shotgun
- ✅ **Health System** - Player HP with visual feedback
- ✅ **Wave Timer** - 3-minute countdown per wave
- ✅ **Difficulty Selection** - Choose your challenge level
- ✅ **Player Name Entry** - Personalize your game session
- ✅ **Responsive Design** - Adapts to different screen sizes

### UI/UX Features:
- 🎨 **Professional Menu System** - Clean, modern interface
- 📊 **HUD Elements** - Real-time health, ammo, wave, and weapon display
- 🎯 **Visual Feedback** - Projectile trails and hit detection
- 🌙 **Dark Theme** - Easy on the eyes during long sessions

## 🎮 Gameplay

### Objective:
Survive as long as possible against endless waves of zombies. Each wave becomes progressively more challenging with faster and potentially more numerous zombies.

### Win/Lose Conditions:
- **Survival Goal:** Last as long as possible through multiple waves
- **Game Over:** When your health reaches 0
- **Score:** Based on zombies killed and waves survived

### Difficulty Levels:

| Difficulty | Zombie Speed | Zombie Spawn Rate | Player Challenge |
|------------|-------------|-------------------|------------------|
| **Easy** | Slower | Lower | Beginner-friendly |
| **Normal** | Standard | Moderate | Balanced experience |
| **Hard** | Faster | Higher | Expert challenge |

## 🎯 Controls

### Keyboard Controls:

**Movement:**
- `W` or `↑` - Move Up
- `A` or `←` - Move Left
- `S` or `↓` - Move Down
- `D` or `→` - Move Right

**Combat:**
- `SPACE` - Shoot (hold for auto-fire)
- `1` - Switch to Pistol
- `2` - Switch to Shotgun

### Mouse Controls:
- **Move Mouse** - Aim weapon direction
- **Click & Hold** - Auto-fire at cursor location
- **Button Clicks** - Navigate menus

### Pro Tips:
- 💡 Use WASD for movement while aiming with the mouse
- 💡 Hold space or mouse button for continuous fire
- 💡 Strafe around zombies to avoid getting surrounded
- 💡 Switch weapons based on the situation
- 💡 Keep moving - standing still is death!

## ⚙️ Game Mechanics

### Player Mechanics:
- **Health Points:** 100 HP (maximum)
- **Movement Speed:** 5 units per frame
- **Size:** 40x40 pixels (collision box)
- **Directional Facing:** Follows movement or aim direction

### Zombie Mechanics:
- **Health Points:** 50 HP per zombie
- **Movement Speed:** 2 units per frame (base speed)
- **Spawn Timer:** Every 2 seconds
- **Spawn Location:** Random edges of the screen
- **Behavior:** Direct path-finding toward player
- **Size:** 40x40 pixels

### Projectile System:
- **Speed:** 8 units per frame
- **Lifetime:** 1000ms (1 second)
- **Collision Detection:** 30-pixel radius
- **Visual:** Yellow 4x4 pixel bullets

### Wave System:
- **Wave Duration:** 3 minutes (180 seconds)
- **Wave Progression:** Difficulty increases each wave
- **Timer Display:** Real-time countdown in HUD

## 🔫 Weapons

### 1. Pistol 🔫
**Default Weapon**
- **Damage:** 20 HP per shot
- **Fire Rate:** 300ms cooldown (~3.3 shots/second)
- **Ammo:** Unlimited
- **Best For:** Consistent damage, good for single targets
- **Strategy:** Rapid fire, precision aiming

### 2. Shotgun 💥
**Power Weapon**
- **Damage:** 50 HP per shot
- **Fire Rate:** 800ms cooldown (~1.25 shots/second)
- **Ammo:** Unlimited
- **Best For:** High damage, close-range combat
- **Strategy:** Powerful shots, requires better timing

### Weapon Comparison:

| Feature | Pistol | Shotgun |
|---------|--------|---------|
| **Damage** | 20 | 50 |
| **Fire Rate** | Fast | Slow |
| **DPS** | ~66 | ~62.5 |
| **Range** | Same | Same |
| **Best Use** | Groups, Distance | Single, Close |

## 📦 Installation

### Option 1: Direct Download
```bash
# Download the HTML file
# Open in any web browser - that's it!
```

### Option 2: Clone Repository
```bash
# Clone the repository
git clone https://github.com/yourusername/zombie-survival-game.git

# Navigate to directory
cd zombie-survival-game

# Open the HTML file
# Double-click index.html or right-click > Open With > Browser
```

### Option 3: Host on Web Server
```bash
# Using Python's built-in server
python -m http.server 8000

# Or using Node.js http-server
npx http-server

# Then visit http://localhost:8000
```

### Requirements:
- ✅ Modern web browser (Chrome, Firefox, Safari, Edge)
- ✅ JavaScript enabled
- ✅ Canvas API support (all modern browsers)
- ✅ Mouse and keyboard input
- ✅ Internet connection (for external image assets)

## 🚀 How to Play

### Getting Started:

1. **Launch the Game**
   - Open the HTML file in your web browser
   - You'll see the main menu

2. **Enter Your Name**
   - Type your player name (up to 20 characters)
   - This personalizes your game session

3. **Select Difficulty**
   - Click Easy, Normal, or Hard
   - Normal is selected by default

4. **Start Playing**
   - Click "Start Game" button
   - Game begins immediately

### During Gameplay:

1. **Move Your Character**
   - Use WASD or Arrow keys to navigate
   - Keep moving to avoid zombie attacks

2. **Aim and Shoot**
   - Point mouse cursor where you want to shoot
   - Hold Space or Click mouse to fire
   - Bullets travel toward your cursor

3. **Switch Weapons**
   - Press `1` for Pistol (fast, lower damage)
   - Press `2` for Shotgun (slow, high damage)
   - Choose based on the situation

4. **Monitor Your Stats**
   - **HP (Top Left):** Your health
   - **Ammo (Top Right):** Shows unlimited (∞)
   - **Wave Info (Top Center):** Current wave and time
   - **Weapon (Bottom Center):** Current weapon equipped

5. **Survive the Wave**
   - Eliminate zombies before they reach you
   - Survive until the timer runs out
   - Prepare for the next wave

### Survival Tips:

🎯 **Movement is Life**
- Never stop moving
- Circle strafe around zombie groups
- Use screen edges strategically

🎯 **Weapon Strategy**
- Use Pistol for steady damage
- Switch to Shotgun for tough encounters
- Learn weapon cooldowns

🎯 **Positioning**
- Stay in open areas
- Don't get cornered
- Maintain distance from zombie spawns

🎯 **Resource Management**
- With unlimited ammo, focus on accuracy
- Don't waste shots on missed targets
- Plan your firing patterns

## 🛠️ Technical Details

### Technologies Used:

**Frontend:**
- **HTML5** - Structure and canvas element
- **CSS3** - Styling and UI design
- **Vanilla JavaScript** - Game logic and mechanics
- **Canvas API** - Rendering and graphics

### Architecture:

```
Game Loop (60 FPS)
├── Update Logic
│   ├── Player Movement
│   ├── Zombie AI & Spawning
│   ├── Projectile Physics
│   ├── Collision Detection
│   └── Game State Management
└── Render Logic
    ├── Canvas Clearing
    ├── Player Rendering
    ├── Zombie Rendering
    └── Projectile Rendering
```

### Key Components:

**1. Game State Management:**
```javascript
gameState = {
  running: boolean,
  paused: boolean,
  wave: number,
  waveTimer: number,
  score: number
}
```

**2. Player Object:**
```javascript
player = {
  x, y: position,
  width, height: dimensions,
  speed: movement speed,
  hp, maxHp: health,
  dir: {x, y} direction
}
```

**3. Weapon System:**
```javascript
weapons = {
  pistol: {damage, cooldown, lastShot, unlimitedAmmo},
  shotgun: {damage, cooldown, lastShot, unlimitedAmmo}
}
```

**4. Entity Arrays:**
- `zombies[]` - Active zombie entities
- `projectiles[]` - Active bullets/projectiles

## 🌐 Browser Compatibility

### Fully Supported:
- ✅ **Google Chrome** 90+ (Recommended)
- ✅ **Mozilla Firefox** 88+
- ✅ **Microsoft Edge** 90+
- ✅ **Safari** 14+
- ✅ **Opera** 76+

### Mobile Browsers:
- ⚠️ **Limited Support** - Touch controls not fully implemented
- 🔄 **Future Update** - Mobile controls planned

### Requirements:
- JavaScript enabled
- HTML5 Canvas support
- ES6+ JavaScript support
- Mouse and keyboard input

## 🎨 Customization

### Easy Modifications:

**1. Adjust Difficulty:**
```javascript
// Change zombie spawn rate
if(now-lastSpawn>2000) // Change 2000 to desired milliseconds

// Change zombie speed
zombies.push({x,y,hp:50,speed:2}); // Change speed value

// Change zombie health
zombies.push({x,y,hp:50,speed:2}); // Change hp value
```

**2. Modify Weapons:**
```javascript
let weapons = {
  pistol:{damage:20, cooldown:300, ...}, // Adjust damage/cooldown
  shotgun:{damage:50, cooldown:800, ...}  // Adjust damage/cooldown
};
```

**3. Change Player Stats:**
```javascript
let player = {
  speed:5,      // Movement speed
  hp:100,       // Starting health
  maxHp:100     // Maximum health
};
```

**4. Customize Colors:**
```css
/* Change theme colors in CSS */
--primary-color: #556B2F;
--danger-color: #8B0000;
--accent-color: #FFD700;
```

**5. Adjust Wave Duration:**
```javascript
let gameState = {
  waveTimer: 180  // Change to desired seconds
};
```

#### Game Modes:
- [ ] **Survival Mode** (Current)
- [ ] **Time Attack** - Kill X zombies in time limit
- [ ] **Defense Mode** - Protect a position
- [ ] **Boss Rush** - Fight only boss zombies
- [ ] **Multiplayer Co-op** - Team survival

#### UI/UX Improvements:
- [ ] **Better HUD**
  - Damage indicators
  - Kill counter
  - Combo system
  - Mini-map

- [ ] **Pause Menu**
  - Resume/Restart options
  - Settings menu
  - Controls guide

- [ ] **Settings Menu**
  - Volume controls
  - Graphics quality
  - Control customization
  - Color blind mode

## 🎓 Learning Resources

This project demonstrates:
- HTML5 Canvas API usage
- JavaScript game loops
- Object-oriented game design
- Collision detection algorithms
- Event-driven programming
- CSS animations and transitions
- Responsive UI design

### Useful References:
- [Canvas API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [Game Development Patterns](https://gameprogrammingpatterns.com/)
- [JavaScript Performance](https://developers.google.com/web/fundamentals/performance)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### How to Contribute:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Contribution Ideas:
- Add new weapons
- Implement sound effects
- Create new zombie types
- Improve mobile controls
- Add achievements
- Enhance visual effects
- Write unit tests
- Improve documentation

### Code Style Guidelines:
- Use meaningful variable names
- Comment complex logic
- Follow existing code structure
- Test thoroughly before submitting


⭐ **If you enjoyed this game, please give it a star!**

---
- [Request a Feature](https://github.com/yourusername/zombie-survival-game/issues)

**Happy Zombie Hunting! 🧟‍♂️💀**
