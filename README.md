# The Warehouse-Autobots Dilemma

🚀 **Project Overview**

The Warehouse-Autobots Simulation project aims to develop an intelligent system to control autonomous robots (autobots) within a grid-based warehouse environment. The autobots are responsible for transporting products from designated starting points (A) to destination points (B) while avoiding obstacles (X) and each other. This simulation offers a realistic approach to managing multiple bots, ensuring efficient and collision-free operations.

🔑 **Key Features**

- **Dynamic Grid Layout:** A 2D grid representing the warehouse with free cells (.), obstacles (X), starting points (A), and destination points (B).
- **Movement Commands:** Autobots can execute simple commands: Forward, Reverse, Left, Right, and Wait.
- **Collision Avoidance:** Ensures no two bots occupy the same cell simultaneously.
- **Parallel Movement:** Bots move simultaneously while intelligently avoiding collisions.
- **Command Logging:** Records detailed logs of each bot's movement commands.
- **Performance Metrics:** Calculates total time taken and the number of commands issued to evaluate efficiency.

🗂️ **Project Structure**

```
Warehouse-Autobots-Dilemma/
├── autobot_simulation.py
├── requirements.txt
└── README.md
```

⚙️ **Prerequisites**

- Python 3.6 or higher
- Required Libraries:
  - `numpy`
  - `tkinter` (for GUI visualization)

📥 **Installation**

```bash
git clone https://github.com/deepkakadiya7/TheWarehouse-Autobots-Dilemma.git
cd TheWarehouse-Autobots-Dilemma
pip install -r requirements.txt
```

🚀 **How to Run the Simulation**

```bash
python autobot_simulation.py
```

- Input the grid size, starting/ending points, and obstacles when prompted.
- The simulation will execute, displaying bot movements step-by-step.

📊 **Performance Metrics**

- **Total Time:** The cumulative time taken for all autobots to reach their destinations, including time spent on Wait commands.
- **Total Commands:** The number of movement commands issued, including Wait commands.

🤖 **Collision Avoidance Logic**

- If two bots are about to occupy the same cell, one will Wait until the path is clear.
- Paths are dynamically adjusted based on obstacles and the positions of other bots.

🕰️ **Wait Command Management**

- Autobots issue Wait commands to prevent collisions in tight spaces.
- The Wait command is intelligently managed to ensure smooth navigation.

✅ **Testing**

- **Unit Tests:** Verify functionalities such as movement commands and collision detection.
- **Integration Tests:** Ensure multiple bots navigate correctly under different scenarios.

🤝 **Contributing**

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request.

📧 **Contact**

For queries, feel free to reach out or open an issue on the repository.

Happy Coding! 🚀

