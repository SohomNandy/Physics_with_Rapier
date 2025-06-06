# Physics_with_Rapier

**Physics_with_Rapier** is an experimental project that explores integrating the [Rapier physics engine](https://rapier.rs/) with [Three.js](https://threejs.org/) to create interactive 3D physics simulations in the browser.  
This project serves as a sandbox for experimenting with rigid body dynamics, collision detection, and real-time rendering.

## Demo

You can view a live demo of the project here: [Physics_with_Rapier Demo](https://sohomnandy.github.io/Physics_with_Rapier/)

## Features

- Integration of Rapier physics engine with Three.js
- Simulation of rigid body dynamics
- Basic collision detection and response
- Interactive 3D rendering in the browser
- Modular code structure for easy experimentation

## Getting Started

### Prerequisites

Ensure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox)
- A local web server (for serving the files)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SohomNandy/Physics_with_Rapier.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Physics_with_Rapier
   ```

3. Start a local web server and open `index.html` in your browser.

   For example, using Python's built-in server:
   ```bash
   python -m http.server
   ```

   Then, navigate to `http://localhost:8000` in your browser.

## Project Structure

```
Physics_with_Rapier/
├── envs/              # Environment configurations
├── glb/               # 3D model files
├── getBodies.js       # Script for creating physics bodies
├── getLayer.js        # Script for managing rendering layers
├── index.html         # Main HTML file
├── index.js           # Entry point for the application
├── rad-grad.png       # Texture image used in the scene
```

## Technologies Used

- [Rapier](https://rapier.rs/) - A fast physics engine for games and animations
- [Three.js](https://threejs.org/) - A 3D library that makes WebGL simpler
- JavaScript - Programming language for web development
- HTML/CSS - Markup and styling for the web page

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Rapier](https://rapier.rs/) for the physics engine
- [Three.js](https://threejs.org/) for the 3D rendering library
