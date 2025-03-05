# Whispery 3 - Voice Messer

Whispery 3 is a web-based audio recording and manipulation tool that allows users to record 3-second audio clips, process them with random playback speed modifications, visualize the audio waveform, and download the result.

## Features

- Record 3-second audio clips using your microphone
- Process recordings with random playback speed (0.5x to 2x)
- Real-time waveform visualization
- Download processed audio as WAV files
- Responsive design with animated particle effects
- Modern UI with custom styling and hover effects

## Prerequisites

- Modern web browser (Chrome, Firefox, Edge, etc.)
- Microphone access enabled in browser
- Internet connection (for loading Bootstrap CDN)

## Installation

1. Clone or download this repository
2. Open `index.html` in a web browser
3. Grant microphone permissions when prompted

No additional installation or dependencies are required as the project uses:
- Bootstrap 5.3.0-alpha1 via CDN
- Pure vanilla JavaScript
- Web Audio API (built into modern browsers)

## Usage

1. Click "Record (3s)" to start recording
   - Recording automatically stops after 3 seconds
   - Click "Stop" to end recording early
2. Click "Process Audio" to transform the recording
   - Applies random playback speed modification
   - Plays the processed audio
   - Displays waveform visualization
3. Click "Download" to save the processed audio as a WAV file

## Technical Details

### HTML Structure
- Single `index.html` file
- Responsive container with button group
- Waveform visualization area
- Particle animation background

### CSS
- Custom color scheme using CSS variables
- Gradient background
- Animated button effects
- Pulsing recording indicator
- Particle float animation
- Responsive design with Bootstrap integration

### JavaScript
- Web Audio API for recording and processing
- MediaRecorder API for audio capture
- OfflineAudioContext for audio manipulation
- Custom WAV file generation
- Real-time waveform visualization
- Particle animation system

## File Structure
whispery-3/
│
└── index.html    # Main HTML file containing all code


## Limitations

- Recording limited to 3 seconds
- Requires microphone permission
- Audio processing limited to playback speed modification
- WAV file output only
- Browser compatibility dependent on Web Audio API support

## Credits

Created by Yµn ^…^ ƒ(x)  
Website: [yunusemrevurgun.com](https://yunusemrevurgun.com/)

## License

This project is open-source and available under the MIT License.

---
Last Updated: March 06, 2025
