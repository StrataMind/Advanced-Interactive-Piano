# 🎹 Advanced Interactive Piano

A feature-rich, web-based piano application built with HTML5, CSS3, and JavaScript using the Web Audio API.

## Features

### 🎵 Core Piano Functionality
- Interactive piano with white and black keys
- Keyboard shortcuts for easy playing
- Multiple octave support with octave switching
- Real-time note display

### 🎛️ Sound Controls
- **Volume Control**: Adjustable master volume
- **Instrument Selection**: Choose from Piano, Organ, Synth, or Music Box sounds
- **Reverb Effect**: Adjustable reverb for spatial sound
- **Octave Switching**: Navigate between different octaves (1-7)

### 🎼 Musical Features
- **Chord Player**: Built-in chord library with major, minor, and 7th chords
- **Recording**: Record your performances
- **Playback**: Play back recorded sessions
- **Audio Export**: Save recordings as WAV files

### 🎨 Visual Effects
- **Audio Visualizer**: Real-time frequency visualization
- **Key Animations**: Ripple effects and press animations
- **3D Piano Effect**: Perspective transforms on hover
- **Theme Toggle**: Dark and light mode support

### 📱 Responsive Design
- Mobile-friendly interface
- Touch support for mobile devices
- Adaptive layout for different screen sizes

## How to Use

### Keyboard Controls
- **White Keys**: A, S, D, F, G, H, J, K, L
- **Black Keys**: W, E, T, Y, U, O, P

### Mouse Controls
- Click any piano key to play the corresponding note
- Use the control panels to adjust settings

### Recording
1. Click the "Record" button to start recording
2. Play your music
3. Click "Stop" to end recording
4. Use "Play" to listen to your recording
5. Use "Save" to download as a WAV file

### Chord Playing
- Select a chord from the dropdown menu
- The chord will play automatically with visual feedback

## Technical Details

### Technologies Used
- **HTML5**: Structure and layout
- **CSS3**: Styling, animations, and responsive design
- **JavaScript**: Interactive functionality and audio processing
- **Web Audio API**: Real-time audio synthesis and effects

### Audio Features
- Oscillator-based sound synthesis
- Convolution reverb using impulse responses
- Real-time audio visualization
- Audio buffer to WAV conversion for file export

### Browser Compatibility
- Modern browsers with Web Audio API support
- Chrome, Firefox, Safari, Edge (latest versions)

## Getting Started

1. Open `index.html` in a modern web browser
2. Allow audio permissions if prompted
3. Start playing by clicking keys or using keyboard shortcuts
4. Experiment with different instruments and effects

## File Structure
```
Interactive Piano/
├── index.html          # Main application file
└── README.md          # This documentation
```

## Features Overview

### Control Panels
- **Volume**: Master volume control (0-100%)
- **Instrument**: Sound type selection
- **Reverb**: Spatial effect intensity (0-100%)
- **Octave**: Pitch range selection (1-7)

### Recording System
- Real-time note capture with timing
- Playback with visual key animations
- WAV file export functionality

### Chord Library
- C Major, C Minor, C7
- G Major, G Minor
- F Major, D Major
- A Major, E Major

## Performance Notes
- Audio context initialization on first user interaction
- Efficient memory management for audio nodes
- Optimized visualizer updates at 50ms intervals

Enjoy making music with your Advanced Interactive Piano! 🎵