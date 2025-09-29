# Flappy Rajini 🚀

A Flappy Bird AI game using NEAT (NeuroEvolution of Augmenting Topologies) with Rajinikanth themed graphics! Watch as AI agents learn to play Flappy Bird through genetic evolution.

## 🎮 About the Project

This project combines the classic Flappy Bird game with artificial intelligence using the NEAT algorithm. The AI learns to navigate through pipes by evolving neural networks over multiple generations, all while featuring themed graphics inspired by Rajinikanth.

## ✨ Features

- **AI Learning**: Uses NEAT algorithm to evolve neural networks
- **Rajinikanth Theme**: Custom graphics and characters
- **Real-time Evolution**: Watch generations improve in real-time
- **Genetic Algorithm**: Survival of the fittest in action
- **Visual Feedback**: See fitness scores and generation progress

## 🛠️ Technologies Used

- Python 3.x
- Pygame
- NEAT-Python
- Genetic Algorithms

## 📦 Installation

### Prerequisites
- Python 3.6 or higher
- Pip package manager

### Steps
1. Clone the repository:
   
git clone https://github.com/yourusername/flappy-rajini.git
cd flappy-rajini

2. Install required packages:

pip install pygame neat-python

3. Run the game:

python game.py

🎯 How It Works
Initialization: Starts with a population of 50 AI birds with random neural networks

Training: Each generation, birds attempt to navigate through pipes

Fitness Evaluation: Birds are rewarded for:

Staying alive (+0.1 per frame)

Passing pipes (+5 points)

Penalized for hitting pipes (-1 point)

Evolution: Best performers are selected for reproduction with mutations

Convergence: After multiple generations, AI masters the game!

🎮 Game Controls
The AI plays automatically using neural networks

You can watch the learning process in real-time

Game automatically stops when a winner is found (score > 10)

📁 Project Structure
text
flappy-rajini/
├── game.py              # Main game file
├── config.txt           # NEAT configuration
├── imgs/               # Image assets
│   ├── rajini1.png
│   ├── rajini2.png
│   ├── rajini3.png
│   ├── pipe.png
│   ├── base.png
│   └── bg.png
└── README.md
⚙️ NEAT Configuration
The config.txt file contains parameters for the NEAT algorithm:

Population size: 50

Activation function: Tanh

Network structure: Evolving topologies

Fitness threshold: 100

📊 Training Progress
Generation 0: Random behavior

Generation 5-10: Starts learning basic navigation

Generation 15-20: Consistently achieves scores 5+

Generation 25+: Masters the game (scores 10+)

🎯 Results
After training, the AI can:

Navigate through tight spaces

Time jumps perfectly

Achieve high scores consistently

Adapt to different pipe configurations

🤝 Contributing
Feel free to contribute to this project by:

Adding new features

Improving the AI

Enhancing graphics

Optimizing performance

👨‍💻 Author
NARENDREN S V

GitHub: Naren1704

Project Link: https://github.com/Naren1704/AI-Flappy-RAJINI

🙏 Acknowledgments
NEAT-Python library for the neuroevolution implementation

Pygame community for game development resources

Inspired by Flappy Bird and Rajinikanth fandom

⭐ Don't forget to star this repository if you like it!

text

## Quick README.md for immediate use:

# Flappy Rajini

AI learns to play Flappy Bird using NEAT algorithm with Rajinikanth theme!

## Requirements
- Python 3.x
- Pygame
- NEAT-Python

## How to Run

pip install pygame neat-python
python game.py
Features
AI learns through genetic evolution

Rajinikanth themed graphics

Real-time training visualization
