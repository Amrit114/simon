<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
</div>

# 🎮 Simon Says Game

A classic memory game built with HTML, CSS, and JavaScript where players must repeat sequences of colored button flashes.

## 🎮 How to Play

1. **Start the Game**: Press any key to begin
2. **Watch the Sequence**: The game will flash a colored button
3. **Repeat the Pattern**: Click the button that flashed
4. **Level Up**: Each level adds one more button to the sequence
5. **Game Over**: If you click the wrong button, the game ends and shows your final score

## 🚀 Features

- **Progressive Difficulty**: Each level adds one more step to the sequence
- **Visual Feedback**: Different flash effects for game hints and user clicks
- **Responsive Design**: Works on desktop and mobile devices
- **Score Tracking**: Displays your current level and final score
- **Modern UI**: Gradient background with glowing button effects

## 📁 Project Structure

```
simon-says-game/
├── index.html          # Main HTML structure
├── style.css           # Styling and animations
├── app.js             # Game logic and functionality
└── README.md          # This file
```

## 🛠️ Installation & Setup

1. **Clone or Download**: Get all project files in the same directory
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **No Dependencies**: Pure vanilla JavaScript - no additional libraries required

## 🎯 Game Controls

- **Any Key**: Start the game
- **Mouse Click**: Select colored buttons during gameplay

## 🎨 Visual Elements

### Button Colors
- **Red**: Top-left button
- **Yellow**: Top-right button  
- **Green**: Bottom-left button
- **Purple**: Bottom-right button

### Flash Effects
- **White Glow**: Game showing the sequence
- **Green Glow**: User input feedback

## 🔧 Technical Details

### JavaScript Features Used
- Event listeners for keyboard and mouse input
- DOM manipulation for visual updates
- Array methods for sequence management
- Timeout functions for timing control
- Random number generation for sequences

### CSS Features
- CSS Grid/Flexbox for responsive layout
- CSS animations and keyframes
- CSS variables for easy theming
- Media queries for mobile responsiveness
- Box shadows and transforms for 3D effects

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🐛 Known Issues

- Random color selection uses `Math.floor(Math.random() * 3)` which only selects from first 3 colors (red, yellow, purple) - green is never selected
- Consider changing to `Math.floor(Math.random() * 4)` to include all 4 colors

## 🚀 Future Enhancements

- [ ] Sound effects for button presses
- [ ] High score persistence using localStorage
- [ ] Difficulty levels (speed variations)
- [ ] Customizable color themes
- [ ] Touch gesture support
- [ ] Game statistics tracking

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

---

**Enjoy playing Simon Says!** 🎉
