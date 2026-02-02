# 🎄 Christmas Pacman 🎅

A festive twist on the classic Pacman game! Play as Santa collecting presents while avoiding snowman ghosts.

![Christmas Pacman](https://img.shields.io/badge/Game-Christmas%20Pacman-red?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Ready-brightgreen?style=for-the-badge)

## 🎮 Play the Game

[**Play Now on GitHub Pages**](#) *(Add your GitHub Pages URL here after deployment)*

## ✨ Features

- 🎅 **Play as Santa** - Navigate the maze as jolly old Saint Nick
- ☃️ **Snowman Ghosts** - Four unique colored snowmen chase you through the maze
- 🎁 **Collect Presents** - Gather all the gifts to win
- ⭐ **Power-Ups** - Grab golden presents to turn the tables on the ghosts
- 🎨 **Christmas Theme** - Festive colors and white background
- 📱 **Responsive Design** - Clean, modern interface

## 🕹️ How to Play

### Controls
- **Arrow Keys** - Move Santa up, down, left, or right
- Collect all the red presents (dots) to win
- Grab gold power pellets to eat the ghosts
- Avoid the snowman ghosts or you'll lose a life!

### Scoring
- 🎁 Small present (dot): **10 points**
- ⭐ Large present (power pellet): **50 points**
- ☃️ Eating a ghost (during power-up): **200 points**

### Game Rules
- You start with **3 lives**
- Touching a ghost costs 1 life
- During power-up mode, you can eat ghosts for bonus points
- Collect all presents to win the game!

## 🚀 Deploying to GitHub

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository** on GitHub
   ```
   Repository name: christmas-pacman
   Description: A festive Pacman game with Christmas theme
   Public ✓
   ```

2. **Upload files**
   - `christmas-pacman.html`
   - `README.md`
   - `TEST_CASES.md`

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click Save
   - Your game will be available at: `https://yourusername.github.io/christmas-pacman/christmas-pacman.html`

4. **Optional: Set as index page**
   - Rename `christmas-pacman.html` to `index.html`
   - Your game will be available at: `https://yourusername.github.io/christmas-pacman/`

### Option 2: Using Git Command Line

```bash
# Clone your repository
git clone https://github.com/yourusername/christmas-pacman.git
cd christmas-pacman

# Add files
git add christmas-pacman.html README.md TEST_CASES.md

# Commit and push
git commit -m "Initial commit: Christmas Pacman game"
git push origin main

# Enable GitHub Pages in repository settings
```

### Option 3: Quick Deploy (No Git Required)

1. Go to https://github.com/new
2. Create a new repository
3. Click "uploading an existing file"
4. Drag and drop all files
5. Click "Commit changes"
6. Enable GitHub Pages in Settings > Pages

## 📁 Project Structure

```
christmas-pacman/
│
├── christmas-pacman.html    # Main game file (self-contained)
├── README.md                # This file
└── TEST_CASES.md           # Complete test suite documentation
```

## 🧪 Testing

The game includes a comprehensive test suite covering:
- ✅ 54 total test cases
- ✅ Game initialization
- ✅ Player movement and controls
- ✅ Scoring mechanics
- ✅ Ghost AI behavior
- ✅ Collision detection
- ✅ Power-up mechanics
- ✅ Win/lose conditions
- ✅ Visual elements
- ✅ Performance

See [TEST_CASES.md](TEST_CASES.md) for detailed test documentation.

## 🛠️ Technical Details

- **Built with**: Pure HTML5, CSS3, and JavaScript
- **No dependencies**: Completely self-contained single file
- **Canvas-based rendering**: Smooth 60 FPS gameplay
- **Browser compatibility**: Works on all modern browsers
  - Chrome ✓
  - Firefox ✓
  - Safari ✓
  - Edge ✓

## 🎨 Design Choices

- **Color Scheme**
  - White background for clean, snowy feel
  - Christmas red (#c41e3a) for Santa and borders
  - Forest green (#165b33) for maze walls
  - Gold (#ffd700) for power-ups
  
- **Characters**
  - Santa: Red with white hat and animated mouth
  - Ghosts: Snowmen with carrot noses and coal buttons
  
- **Game Balance**
  - Medium difficulty with smart ghost AI
  - Power-ups last approximately 5 seconds
  - Classic Pacman maze layout adapted for Christmas

## 📝 Future Enhancements

Potential features for future versions:
- [ ] Touch controls for mobile devices
- [ ] Sound effects and background music
- [ ] High score persistence (localStorage)
- [ ] Multiple difficulty levels
- [ ] Pause functionality
- [ ] Level progression with increasing difficulty
- [ ] Leaderboard system

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## 📄 License

This project is open source and available under the MIT License.

## 🎄 Credits

Created with festive spirit! Inspired by the classic Pacman game with a Christmas makeover.

---

**Merry Christmas and Happy Gaming! 🎅🎄☃️**

Enjoy collecting presents and eating snowmen!
