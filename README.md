The Warehouse-Autobots Dilemma

🚀 Project Overview

The Warehouse-Autobots Simulation project aims to develop a smart system to control autonomous robots (autobots) within a grid-based warehouse environment. The autobots are tasked with moving products from designated starting points (A) to destination points (B) while avoiding obstacles (X) and each other. This simulation provides a realistic approach to managing multiple bots, ensuring efficient and collision-free movement.

🔑 Key Features

Dynamic Grid Layout: A 2D grid representing the warehouse with free cells (.), obstacles (X), starting points (A), and destination points (B).

Movement Commands: Autobots can execute simple commands: Forward, Reverse, Left, Right, and Wait.

Collision Avoidance: Ensures no two bots occupy the same cell simultaneously.

Parallel Movement: Bots move simultaneously while intelligently avoiding collisions.

Command Logging: Records detailed logs of each bot's movement commands.

Performance Metrics: Calculates total time taken and number of commands issued for efficiency evaluation.

🗂️ Project Structure

Warehouse-Autobots-Dilemma/
├── autobot_simulation.py
├── requirements.txt
└── README.md

⚙️ Prerequisites

Python 3.6 or higher

Required Libraries:

numpy

tkinter (for GUI visualization)

📥 Installation

git clone https://github.com/deepkakadiya7/TheWarehouse-Autobots-Dilemma.git
cd TheWarehouse-Autobots-Dilemma
pip install -r requirements.txt

🚀 How to Run the Simulation

python autobot_simulation.py

Input the grid size, starting/ending points, and obstacles when prompted.

The simulation will execute, displaying bot movements step-by-step.

📊 Performance Metrics

Total Time: Cumulative time taken for all autobots to reach their destinations.

Total Commands: Number of movement commands issued, including Wait commands.

🤖 Collision Avoidance Logic

If two bots are about to occupy the same cell, one will Wait until the path is clear.

Paths adjust dynamically based on obstacles and the positions of other bots.

🕰️ Wait Command Management

Bots issue Wait commands to prevent collisions in tight spaces.

The command is managed intelligently for smooth navigation.

✅ Testing

Unit Tests: Verify functionalities like movement commands and collision detection.

Integration Tests: Ensure multiple bots navigate correctly under different scenarios.

🤝 Contributing

Fork the repository

Create a new branch (git checkout -b feature-branch)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature-branch)

Open a Pull Request

📧 Contact

For queries, feel free to reach out or open an issue on the repository.

Happy Coding! 🚀
