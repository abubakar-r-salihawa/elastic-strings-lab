# Elastic Strings Lab

Elastic Strings Lab is an interactive physics simulation for exploring elastic-string behavior through gesture input and real-time visualization.

## Overview

This project lets users simulate elastic strings under tension and visualize their motion and vibration using intuitive gestures. By dragging and moving the string with the mouse or touch input, you can see how elastic materials respond to different forces and constraints.

## Features

- **Real-time physics simulation** of elastic strings and tension.
- **Interactive gesture control**: grab, pull and flick the string to watch it oscillate.
- **Parameter adjustment**: tune string stiffness, damping and length to explore different behaviors.
- **Visual output**: see displacement and velocity over time via dynamic plots.
- **Extensible architecture**: built with modular code to allow new input devices or physics models.

## Getting Started

### Installation

1. Clone this repository.
2. Install the required dependencies:

```
pip install -r requirements.txt
```

### Usage

Run the main script to start the simulation:

```
python src/main.py
```

Use your mouse or touchscreen to interact with the string. Adjust parameters via keyboard shortcuts or on-screen controls.

## Project Structure

```
elastic-strings-lab/
├── README.md
├── LICENSE
├── requirements.txt
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── .gitignore
├── src/
│   ├── __init__.py
│   ├── main.py
│   └── physics/
│       ├── __init__.py
│       ├── string_simulation.py
│       └── utils.py
└── docs/
    └── ...
```

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Security

If you discover a security vulnerability, please see [SECURITY.md](SECURITY.md) for instructions on how to report it responsibly.
