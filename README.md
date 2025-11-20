# Microphone Quality Tester

A simple web-based tool to test and compare microphone quality using WebRTC technology.

## Features

- 🎤 **Up to 60-second audio recording** directly in your browser
- ⏹️ **Stop recording anytime** with manual stop button
- ▶️ **Instant playback** to evaluate microphone quality
- ⬇️ **Download recordings** for further analysis
- 📱 **Mobile & desktop compatible**
- 🔒 **Privacy-first**: all processing happens locally, no server required
- 🎨 **Clean, modern interface**

## Use Cases

Perfect for comparing:
- Wired vs wireless microphones
- Built-in vs external mics
- Different headset models
- Audio quality across devices

## How to Use

1. Open the page in your browser
2. Click "Start Recording" and allow microphone access
3. Speak for up to 60 seconds (or stop earlier with the stop button)
4. Listen to the playback to evaluate quality
5. Download the recording if needed

## Technical Details

- **Technology**: WebRTC API (MediaRecorder)
- **Audio Format**: WebM with Opus codec
- **Sample Rate**: 48 kHz
- **Max Duration**: 60 seconds (manually stoppable)
- **Processing**: No echo cancellation, noise suppression, or auto-gain (raw audio)

## Demo

[View Live Demo](https://your-username.github.io/mic-test/)

## Installation

Simply open `index.html` in any modern browser. No build process or dependencies required.

## Browser Compatibility

Works on all modern browsers supporting WebRTC:
- Chrome/Edge (desktop & mobile)
- Firefox
- Safari (iOS 14.3+)

## License

MIT License - Feel free to use and modify as needed.
