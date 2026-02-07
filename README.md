# 🎵 Grok Neural Pulse Visualizer

A stunning, browser-based audio visualizer powered by Grok with multiple visualization modes and a sleek cyberpunk aesthetic.

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

- **Multiple Visualization Modes**
  - **Bars** - Classic frequency bar visualization with gradient effects
  - **Circles** - Concentric circles that pulse with the audio
  - **Wave** - Dynamic multi-layer waveform visualization
  - **Particles** - Swirling particles that react to audio intensity
  - **Neural** - Network-style visualization with pulsing nodes and connections

- **Audio Controls**
  - Play/Pause functionality
  - Volume control
  - Progress bar with seek support
  - Time display (current/total)

- **Modern UI**
  - Cyberpunk-inspired design with neon gradients
  - Fullscreen mode support
  - Ambient floating particles background
  - Responsive layout

## 🚀 Getting Started

### Option 1: Direct Browser Usage
Simply open `visualizer.html` in any modern web browser.

### Option 2: Local Server (Recommended)
For the best experience, serve the file using a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if http-server is installed)
npx http-server
```

Then open `http://localhost:8000/visualizer.html` in your browser.

## 📋 Usage

1. Click **"Upload Audio"** to select an audio file (MP3, WAV, OGG, etc.)
2. The audio will auto-play once loaded
3. Use the **mode buttons** at the bottom to switch visualization styles
4. Control playback with the **Play/Pause** button
5. Adjust volume using the **slider**
6. Click **Fullscreen** for an immersive experience

## 🛠️ Technologies

- **HTML5 Canvas** - Rendering visualizations
- **Web Audio API** - Audio analysis and frequency data
- **Vanilla JavaScript** - No dependencies required
- **CSS3** - Animations and gradients

## 🌐 Browser Support

Works on all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## 📄 License

MIT License - feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

---

<p align="center">Made with 💜 and 🎧</p>
