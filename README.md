# Matrix Code Face Visualizer

A real-time audio-visualizer featuring a robotic face composed of Matrix-style code that responds to microphone or tab audio input.

## Features

- **Matrix-style robotic face**: Face composed entirely of falling code characters
- **Audio reactivity**: Face pulsates, eyes dilate, and mouth opens based on audio intensity
- **RGB waveform**: Full-width audio waveform at the bottom with color gradients
- **Dual input support**: Works with microphone or tab audio capture
- **Responsive design**: Adapts to different screen sizes
- **Customizable sensitivity**: Adjust audio response intensity

## How to Use

1. Open the HTML file in a modern browser (Chrome/Firefox recommended)
2. Click either "Microphone" or "Tab Audio" button to start visualization
3. Adjust sensitivity slider to control audio response intensity
4. Watch the code face pulse and react to audio input
5. Click "Stop" to end audio capture

### Controls

- **Microphone**: Captures system audio input
- **Tab Audio**: Captures audio from other browser tabs (Chrome/Edge only)
- **Sensitivity Slider**: Controls how strongly the face responds to audio
- **Hide Menu**: Toggles control panel visibility

## Technical Details

- Built with vanilla JavaScript and Canvas API
- Uses Web Audio API for real-time audio analysis
- Implements FFT for frequency analysis
- Features custom Matrix-style character set
- Optimized for 60fps performance

## Browser Compatibility

- Chrome/Edge: Full functionality including tab audio capture
- Firefox/Safari: Microphone capture supported
- Mobile browsers: Limited functionality

## Requirements

- Modern browser with Web Audio API support
- User permission for microphone access (when using mic input)
- For best experience: Chrome/Edge with latest updates

## Troubleshooting

- If waveform only appears on left side: Check that audio is playing/stereo
- If face doesn't respond: Verify audio input is active and sensitivity is adjusted
- For tab audio issues: Ensure Chrome/Edge is used and audio is playing in another tab
