# Contra-Style Shooter Game 🎮

A retro-styled browser-based shooter game inspired by the classic Contra series. Built with HTML5 Canvas and JavaScript, featuring pixel-perfect graphics and smooth gameplay.

## 🎯 Features

- **Retro Pixel Art Style**: Classic 8-bit aesthetic with "Press Start 2P" font
- **Smooth Player Movement**: WASD or arrow key controls with multi-directional movement
- **Dynamic Shooting System**: Spacebar to shoot bullets in movement direction
- **Intelligent Enemy AI**: Enemies spawn from random edges and chase the player
- **Collision Detection**: Precise hit detection for bullets and enemies
- **Scoring System**: Earn 10 points for each enemy destroyed
- **Game Over Screen**: Shows final score with restart functionality
- **Responsive Design**: Canvas automatically adjusts to window size (16:9 aspect ratio)
- **Glowing Effects**: Green neon border and retro styling

## 🎮 How to Play

### Controls
- **Movement**: Use `WASD` keys or `Arrow Keys` to move your character
- **Shooting**: Press `Spacebar` to fire bullets
- **Restart**: Click the "Restart" button when game is over

### Gameplay
1. You control the green player character in the center of the screen
2. Red enemies spawn from random edges of the screen and move toward you
3. Shoot yellow bullets to destroy enemies and earn points
4. Avoid contact with enemies - touching them ends the game
5. Try to achieve the highest score possible!

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or server required

### Installation
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start playing immediately!

### Running the Game
```bash
# Simply open the HTML file in your browser
# On Windows:
start index.html

# On macOS:
open index.html

# On Linux:
xdg-open index.html
```

## 📁 Project Structure

```
Contra-style Shooter Game/
├── index.html          # Main game file (HTML, CSS, JavaScript)
└── README.md          # This file
```

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas**: For game rendering and graphics
- **JavaScript ES6**: Game logic and mechanics
- **CSS3**: Styling and animations
- **Tailwind CSS**: Utility-first CSS framework (loaded via CDN)
- **Google Fonts**: "Press Start 2P" retro font

### Game Constants
- Player Size: 20px
- Bullet Size: 5px
- Enemy Size: 15px
- Player Speed: 4 pixels/frame
- Bullet Speed: 7 pixels/frame
- Enemy Speed: 1 pixel/frame
- Enemy Spawn Interval: 1000ms (1 second)

### Key Features Implementation
- **Game Loop**: Uses `requestAnimationFrame` for smooth 60fps gameplay
- **Collision Detection**: Euclidean distance calculation for precise hit detection
- **Enemy AI**: Simple pathfinding using `Math.atan2` for angle calculation
- **Responsive Canvas**: Dynamic resizing while maintaining aspect ratio
- **Input Handling**: Multi-key press support for diagonal movement

## 🎨 Customization

You can easily customize the game by modifying the constants at the top of the JavaScript section in `index.html`:

```javascript
const PLAYER_SIZE = 20;        // Player character size
const BULLET_SIZE = 5;         // Bullet size
const ENEMY_SIZE = 15;         // Enemy size
const PLAYER_SPEED = 4;        // How fast the player moves
const BULLET_SPEED = 7;        // How fast bullets travel
const ENEMY_SPEED = 1;         // How fast enemies move
const ENEMY_SPAWN_INTERVAL = 1000; // Time between enemy spawns (ms)
```

### Color Scheme
- Player: `#00ff00` (Green)
- Bullets: `#ffff00` (Yellow)
- Enemies: `#ff0000` (Red)
- Background: `#000000` (Black)
- UI Elements: Various retro colors

## 🐛 Known Issues

- None currently reported

## 🔄 Future Enhancements

Potential features that could be added:
- Power-ups and special weapons
- Multiple enemy types with different behaviors
- Sound effects and background music
- High score persistence
- Mobile touch controls
- Particle effects for explosions
- Multiple levels or waves
- Boss enemies

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📞 Support

If you encounter any issues or have questions, please create an issue in the repository.

---

**Enjoy the game and happy shooting!** 🎯
