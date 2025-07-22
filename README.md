# ⚡ Reaction Time Tester

A simple, web-based game to test and improve your reaction time. Built with vanilla HTML, CSS, and JavaScript.

## 🎮 How to Play

1. **Start the Game**: Click the red box that says "Click here to start!"
2. **Wait**: The box will turn red and display "Wait for green..."
3. **Be Ready**: After a random delay (2-5 seconds), the box will turn green
4. **React Fast**: Click the green box as quickly as possible when it appears
5. **See Results**: Your reaction time will be displayed in milliseconds

## 🚀 Features

- **Precise Timing**: Measures reaction time in milliseconds using `performance.now()`
- **Statistics Tracking**: 
  - Last reaction time
  - Average reaction time across all attempts
  - Best (fastest) reaction time
  - Total number of attempts
- **Attempt History**: Shows your last 10 reaction times
- **Too Early Detection**: Penalizes clicking before the green signal
- **Reset Function**: Clear all statistics and start fresh
- **Responsive Design**: Works on desktop and mobile devices

## 🎯 Getting Started

### Option 1: Direct File Access
1. Download or clone this repository
2. Double-click `index.html` to open in your browser

### Option 2: Browser Address Bar
1. Navigate to the file location
2. Type in browser: `file:///path/to/your/Reaction Time Tester/index.html`

### Option 3: Local Server (Optional)
```bash
# If you have Python installed
python -m http.server 8000

# Then visit http://localhost:8000
```

## 🎨 Design Features

- **Modern UI**: Glassmorphism design with gradient backgrounds
- **Visual Feedback**: Color-coded states (red = wait, green = go, orange = too early)
- **Smooth Animations**: CSS transitions for state changes
- **Accessibility**: High contrast colors and clear typography

## 📊 Understanding Your Results

- **Good Reaction Time**: 150-200ms
- **Average Reaction Time**: 200-250ms
- **Needs Improvement**: 250ms+

*Note: Professional gamers often achieve reaction times under 150ms*

## 🛠️ Technical Details

- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **Cross-Browser Compatible**: Works in all modern browsers
- **Lightweight**: Single file under 10KB
- **Offline Ready**: No internet connection required

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

Feel free to submit issues or pull requests to improve the game!

## 📄 License

This project is open source and available under the MIT License.