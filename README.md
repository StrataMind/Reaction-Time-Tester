# ⚡ Reaction Time Tester

A sleek, web-based game designed to test and improve your reaction time with precision timing and beautiful glassmorphism UI. Built with vanilla HTML, CSS, and JavaScript for optimal performance.

## 🌟 Live Demo

Try it now: [Reaction Time Tester](https://stratamind.github.io/Reaction-Time-Tester/)

## 📸 Screenshot

![Reaction Time Tester Interface](screenshot.png)

## 🎮 How to Play

1. **Start the Game**: Click the red box that says "Click here to start!"
2. **Wait**: The box will turn red and display "Wait for green..."
3. **Be Ready**: After a random delay (2-5 seconds), the box will turn green
4. **React Fast**: Click the green box as quickly as possible when it appears
5. **See Results**: Your reaction time will be displayed in milliseconds

## 🚀 Features

- **⚡ Precise Timing**: High-accuracy measurement using `performance.now()` for millisecond precision
- **📊 Advanced Statistics**:
  - Real-time reaction time display
  - Running average across all attempts
  - Personal best tracking
  - Total attempts counter
  - Detailed performance analytics
- **📈 Attempt History**: Visual timeline of your last 10 reaction times
- **🚫 Smart Detection**: Anti-cheat system prevents early clicking
- **🔄 Reset Function**: Clean slate with one-click statistics reset
- **📱 Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **🎨 Modern UI**: Beautiful glassmorphism design with smooth animations
- **🌐 Offline Ready**: Works without internet connection
- **⚡ Lightning Fast**: Zero dependencies, pure vanilla JavaScript

## 🎯 Getting Started

### 🚀 Quick Start
```bash
# Clone the repository
git clone https://github.com/StrataMind/Reaction-Time-Tester.git

# Navigate to the directory
cd Reaction-Time-Tester

# Open in browser
open index.html
```

### 📦 Installation Options

#### Option 1: Direct Download
1. Click the green "Code" button → "Download ZIP"
2. Extract and double-click `index.html`

#### Option 2: Local Development Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with live-server)
npx live-server

# Using PHP
php -S localhost:8000
```

#### Option 3: GitHub Pages
Visit the live demo: [https://stratamind.github.io/Reaction-Time-Tester/](https://stratamind.github.io/Reaction-Time-Tester/)

## 🎨 Design Features

- **Modern UI**: Glassmorphism design with gradient backgrounds
- **Visual Feedback**: Color-coded states (red = wait, green = go, orange = too early)
- **Smooth Animations**: CSS transitions for state changes
- **Accessibility**: High contrast colors and clear typography

## 📊 Understanding Your Results

| Range | Classification | Description |
|-------|----------------|-------------|
| < 150ms | 🏆 **Excellent** | Professional gamer level |
| 150-200ms | 🥇 **Very Good** | Above average reflexes |
| 200-250ms | 🥈 **Good** | Average human reaction time |
| 250-300ms | 🥉 **Fair** | Room for improvement |
| > 300ms | 📈 **Practice Needed** | Keep training! |

### 🧠 Factors Affecting Reaction Time
- **Age**: Reaction time typically slows with age
- **Fatigue**: Being tired significantly impacts performance
- **Practice**: Regular training can improve your scores
- **Health**: Overall fitness affects neural response time
- **Environment**: Good lighting and ergonomics help

## 🛠️ Technical Stack

- **Frontend**: Pure HTML5, CSS3, Vanilla JavaScript
- **Timing**: High-resolution `performance.now()` API
- **Storage**: Local storage for persistent statistics
- **Design**: CSS Grid, Flexbox, Glassmorphism effects
- **Performance**: Single file, ~10KB, zero dependencies
- **Compatibility**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile**: Touch events, responsive design

## 🎯 Tips to Improve

1. **Focus**: Keep your eyes on the center of the box
2. **Relax**: Tension can slow your reactions
3. **Practice**: Regular practice improves reaction time
4. **Consistency**: Try to maintain the same clicking technique
5. **Environment**: Good lighting and comfortable seating help

## 📝 Game States

| State | Color | Description |
|-------|-------|-------------|
| Waiting | Red | Initial state or waiting for green signal |
| Ready | Green | Click now for reaction time measurement |
| Too Early | Orange | Clicked before green signal appeared |

## 🤝 Contributing

We welcome contributions! Here's how you can help:

- 🐛 **Report bugs** via [Issues](https://github.com/StrataMind/Reaction-Time-Tester/issues)
- 💡 **Suggest features** for future versions
- 🔧 **Submit pull requests** with improvements
- 📖 **Improve documentation**
- ⭐ **Star the repository** if you find it useful

### Development Setup
```bash
git clone https://github.com/StrataMind/Reaction-Time-Tester.git
cd Reaction-Time-Tester
# Start local server for development
python -m http.server 8000
```

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/StrataMind/Reaction-Time-Tester?style=social)
![GitHub forks](https://img.shields.io/github/forks/StrataMind/Reaction-Time-Tester?style=social)
![GitHub issues](https://img.shields.io/github/issues/StrataMind/Reaction-Time-Tester)
![GitHub license](https://img.shields.io/github/license/StrataMind/Reaction-Time-Tester)

## 🌟 Acknowledgments

- Inspired by Human Benchmark reaction time tests
- Built with modern web standards
- Designed for optimal user experience

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**[⭐ Star this repo](https://github.com/StrataMind/Reaction-Time-Tester)** • **[🐛 Report Bug](https://github.com/StrataMind/Reaction-Time-Tester/issues)** • **[💡 Request Feature](https://github.com/StrataMind/Reaction-Time-Tester/issues)**

Made with ❤️ by [StrataMind](https://github.com/StrataMind)

</div>