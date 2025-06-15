Neural Network Visualization
A dynamic, interactive web-based tool to visualize and explore a wide range of neural network architectures, built with HTML5 Canvas and JavaScript. This project allows users to create custom neural networks, adjust hidden layers, edit neuron and connection weights, and visualize forward and backpropagation processes.
Features

Custom Architectures: Configure input, hidden, and output layers with adjustable node counts (2-20 nodes per layer, 1-10 hidden layers).
Dynamic Hidden Layer Adjustment: Add or remove hidden layers using intuitive "+" and "–" buttons or numeric input.
Preset Architectures: Choose from a comprehensive set of neural network types:
Multi-Layer Perceptron (MLP)
Deep MLP
Convolutional Neural Network (CNN)
Recurrent Neural Network (RNN)
Long Short-Term Memory (LSTM)
Gated Recurrent Unit (GRU)
Autoencoder
Variational Autoencoder (VAE)
Transformer
Generative Adversarial Network (GAN)
Self-Organizing Map (SOM)
Radial Basis Function Network (RBFN)
Spiking Neural Network (SNN)
ResNet-Style Architecture


Neuron Weight Editing: Assign custom neuronWeight values, visualized as node size scaling, editable via canvas or editor.
Connection Weight Editing: Modify connection weights (feedforward, recurrent, skip, lateral) interactively or through a bulk editor.
Animations: Visualize forward pass and backpropagation with dynamic node activations and connection pulses.
Edit and View Modes: Toggle between editing and viewing modes.
Parameter Counter: Displays total parameters (weights + biases).
Responsive UI: Modern interface with gradient backgrounds and blur effects.

Installation

Clone the repository:git clone https://github.com/your-username/neural-network-visualization.git


Navigate to the project directory:cd neural-network-visualization


Open index.html in a modern web browser (e.g., Chrome, Firefox):
Double-click index.html, or
Serve locally using a tool like http-server:npm install -g http-server
http-server .

Access at http://localhost:8080.



No external dependencies are required.
Usage

Select Architecture:
Choose "Custom" for a custom network or select a preset (e.g., CNN, LSTM, Transformer).


Configure Custom Architecture:
Input Nodes: Set 2-20 nodes.
Hidden Layers: Use "+" or "–" buttons (or numeric input) to set 1-10 layers; specify 2-20 nodes per layer.
Output Nodes: Set 1-20 nodes.


Configure Preset Architecture:
Input Size: Set 1-1000 nodes (e.g., 784 for MNIST).
Output Size: Set 1-100 nodes (e.g., 10 for classification).
Complexity: Choose Small, Medium, or Large.


Generate Network:
Click "Generate Network" to render the network. Invalid inputs trigger alerts.


Edit Weights:
Edit Mode: Click/double-click nodes or connections to edit weights.
Keyboard Shortcuts: Up/Down (±0.1), Delete/Backspace (set to 0), R (randomize).
Bulk Editors: Use "Edit All Weights" or "Edit All Neuron Weights".
Randomize: Click "Randomize Weights" or "Randomize Neuron Weights".


Visualize:
Run "Forward Pass" or "Backpropagation" to animate signal flow.
Node size reflects |neuronWeight|; weights are shown on nodes (e.g., w:0.45) and connections.
Architecture-specific visuals (e.g., LSTM nodes as rectangles, recurrent connections as curves).



Screenshots
Add screenshots to the assets/ folder and update links below.

Custom Architecture Configuration:
LSTM Visualization:
Weight Editor:

Project Structure
neural-network-visualization/
├── index.html        # Main application file
├── README.md         # Project documentation
├── LICENSE           # MIT License
├── .gitignore        # Git ignore file
└── assets/           # Folder for images (e.g., favicon, screenshots)

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a feature branch: git checkout -b feature/your-feature.
Commit changes: git commit -m "Add your feature".
Push to the branch: git push origin feature/your-feature.
Open a Pull Request.

Report issues or suggest features via the Issues tab.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

Built with vanilla JavaScript and HTML5 Canvas.
Inspired by neural network visualization tools like TensorFlow Playground.

