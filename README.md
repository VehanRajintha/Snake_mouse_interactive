# Snake_mouse_interactive

# 🦎 Procedural Creature Generator 🎮

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> An interactive physics-based creature generator that creates unique procedural creatures you can control with your mouse! 🖱️

![Creature Demo](https://github.com/VehanRajintha/Snake_mouse_interactive/raw/main/snake.gif)

## 🌟 Features

- 🎲 Randomly generated creatures with customizable parameters
- 🏃‍♂️ Physics-based movement and limb control
- 🖱️ Interactive mouse control
- 🦿 Procedural leg and joint system
- 🎨 Smooth HTML5 Canvas rendering
- ⚡ Real-time animation at 30 FPS

## 🚀 Live Demo

Try it out here: [Live Demo](your-demo-link-here)

## 🛠️ Installation

1. Clone the repository:
```bash
https://github.com/VehanRajintha/Snake_mouse_interactive.git
```

2. Open `index.html` in your web browser

## 💻 Usage

The simulation starts automatically and creates a random creature with:
- Random number of legs (1-12)
- Physics-based movement
- Mouse-following behavior

### 🎮 Controls

- Move your mouse to control the creature's movement
- The creature will automatically follow your cursor
- Left-click to interact (if enabled in the specific setup)

## 🔧 Configuration

You can customize the creature by modifying the setup parameters:

```javascript
setupLizard(
    size,      // Size multiplier
    legCount,  // Number of legs
    tailLength // Length of the tail
);
```

### Available Presets:

- `setupSimple()` - Basic string creature
- `setupTentacle()` - Single tentacle following mouse
- `setupLizard()` - Multi-legged creature (current default)
- `setupTestSquid()` - Spider-like creature

## 🧪 Technical Details

The simulation uses several key components:

- `Segment` class - Handles individual body segments
- `LimbSystem` class - Manages limb movement
- `LegSystem` class - Controls leg placement and movement
- `Creature` class - Main creature controller

### Physics Parameters

- Forward Acceleration
- Rotational Friction
- Movement Resistance
- Angular Thresholds
- Joint Stiffness

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by procedural animation techniques
- Built with vanilla JavaScript and HTML5 Canvas
- Physics system based on verlet integration

## 🐛 Known Issues

- Performance may vary with high segment counts
- Mobile touch controls not yet implemented
- Some browser compatibility issues in older versions

## 📞 Contact

Your Name - [@vehanrajintha](https://www.linkedin.com/in/vehanrajintha/)

Project Link: [https://github.com/yourusername/procedural-creature-generator](https://github.com/VehanRajintha/Snake_mouse_interactive/)

---
Made with ❤️ by [Vehan Rajintha]
