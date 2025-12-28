# Particle Gesture Control

An interactive 3D particle system controlled by hand gestures using webcam input. This project combines computer vision, 3D graphics, and gesture recognition to create an immersive experience where users can manipulate virtual particles through natural hand movements.

## Features

### Gesture Controls
- **Open Hand**: Creates a cyan sphere formation
- **Fist**: Forms a green cube structure
- **OK Sign**: Generates a purple Saturn-like shape with rings
- **Index Finger**: Creates a red half-heart shape
- **Two Hands Touching**: Forms a complete red heart
- **Thumbs Up**: Locks the current shape in place
- **Three Fingers (Grab)**: Allows repositioning of locked shapes
- **Clap**: Triggers a supernova explosion effect

### Visual Effects
- Real-time 3D particle rendering with Three.js
- Dynamic color transitions based on shapes
- Smooth morphing animations with spring physics
- Camera zoom control based on hand proximity
- HUD overlay with gesture status and lock progress
- Webcam feed display for gesture feedback

### Technical Features
- Hand tracking using MediaPipe Hands API
- WebGL-accelerated 3D graphics
- Responsive design that adapts to window size
- Real-time gesture recognition and processing
- Particle physics simulation

## How to Use

1. **Setup**: Open `index.html` in a modern web browser that supports WebGL and camera access
2. **Permissions**: Grant camera access when prompted
3. **Start**: Click the "Start Camera" button to begin hand tracking
4. **Interact**: Use the gestures listed above to control the particle system
5. **Lock Shapes**: Hold thumbs up for 2 seconds to lock a shape, then use grab gesture to reposition it

## Browser Requirements

- Modern web browser with WebGL support (Chrome, Firefox, Safari, Edge)
- Camera access permissions
- Internet connection for loading MediaPipe libraries

## Technical Stack

- **Three.js**: 3D graphics and particle system
- **MediaPipe Hands**: Hand tracking and gesture recognition
- **HTML5 Canvas**: Webcam video processing
- **CSS3**: Styling and HUD interface
- **JavaScript (ES6+)**: Application logic and physics

## Project Structure

```
particle-gesture-control/
├── index.html          # Main application file
└── README.md          # This file
```

## Development

The entire application is contained within a single HTML file for simplicity. The code is organized into the following main sections:

- **HTML Structure**: Basic page layout and UI elements
- **CSS Styling**: HUD interface and visual styling
- **JavaScript**:
  - MediaPipe initialization and hand tracking
  - Three.js scene setup and particle system
  - Shape generation algorithms
  - Gesture recognition logic
  - Physics simulation and rendering loop

## Performance Notes

- Optimized for 10,000 particles with smooth 60fps rendering
- Uses efficient WebGL instancing for particle rendering
- Hand tracking runs at camera frame rate for responsive interaction
- Memory usage is managed through object pooling and efficient data structures

## Future Enhancements

Potential areas for expansion:
- Additional gesture shapes and effects
- Multi-user collaborative mode
- Sound-reactive particle behavior
- VR/AR integration
- Mobile device support with touch gestures
- Custom shape creation tools

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this project and submit pull requests with improvements or new features!</content>
<parameter name="filePath">c:\Users\modib\OneDrive\Desktop\partical project\README.md