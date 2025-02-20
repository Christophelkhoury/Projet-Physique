# Quantum Experiment Simulation

## Overview
This project is a Flask-based web application that visualizes a theoretical quantum experiment. It demonstrates the behavior of photons and electrons under different quantum theories, including Schrödinger's Cat, Young's Double-Slit Experiment, and Electron Movement. The simulation is built using **Three.js** for 3D visualization and **GSAP** for animations.

## Features
- **3D Quantum Machine Model:** Simulates a multi-layered quantum experiment.
- **Photon Path Simulation:** Light beams interact probabilistically with a double-slit metal panel.
- **Electron Interaction:** Electrons absorb photons, increasing their energy and speed.
- **Quantum Theories Representation:** Implements key quantum mechanics principles.
- **Observer Effect:** The experiment dynamically changes based on the presence of an observer.
- **Interactive Controls:** Rotate the simulation, control animation speed, and toggle observer mode.
- **Dynamic Energy Graph:** Visualizes energy changes in electrons.
- **Text Annotations:** Displays explanatory text for each stage of the experiment.

## Technologies Used
- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS, JavaScript
- **3D Graphics:** Three.js
- **Animations:** GSAP
- **Data Visualization:** D3.js (for energy graph)

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip
- Virtual environment (optional but recommended)

### Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/quantum-simulation.git
   cd quantum-simulation
   ```
2. Create and activate a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Flask application:
   ```sh
   python app.py
   ```
5. Open a browser and go to `http://127.0.0.1:5000/` to view the simulation.

## Usage
- Use the interactive controls to rotate and zoom into the 3D experiment.
- Adjust animation speed to observe photon and electron behavior in detail.
- Toggle observer mode to see how it affects the quantum experiment.

## Future Enhancements
- Implement real-time interaction using WebSockets.
- Improve UI/UX with additional quantum visualization features.
- Add more complex quantum effects, such as entanglement simulation.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss potential changes.

## Contact
For questions or suggestions, reach out via email at [elkhourychristophe2121@gmail.com] or open an issue on GitHub.
