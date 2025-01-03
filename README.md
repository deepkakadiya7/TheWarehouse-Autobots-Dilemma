# Project-1_TheWarehouse-Autobots-Dilemma

Project Overview : The Autobots Warehouse Simulation project aims to develop a smart system to control autonomous robots (autobots) within a grid-based warehouse environment. The autobots are tasked with moving products from designated starting points (A) to destination points (B) while avoiding obstacles (X) and each other. The simulation provides a realistic approach to managing multiple bots, ensuring efficient and collision-free movement.  Key Features • Dynamic Grid Layout: The warehouse is represented as a 2D grid with free cells (.), obstacles (X), and designated starting (A) and destination points (B). • Movement Commands: Autobots can execute a set of simple movement commands: Forward, Reverse, Left, Right, and Wait. • Collision Avoidance: The simulation ensures that no two bots occupy the same cell at the same time. • Parallel Movement: Bots can move simultaneously while intelligently avoiding collisions. • Command Logging: Detailed logs of each bot's movement commands are recorded throughout the simulation. • Performance Metrics: The simulation calculates the total time taken and the total number of commands issued.

CODE IS :

. . . . . B4

B1 . A2 . X .

. . . . . B2

. . B3 A3 . .

X . . . X .

A4 . . . A1 .

 Prerequisites : • Python 3.6 or higher • Required libraries (if any) • numpy • matplotlib (if using for graphical output)

• Installation Clone this repository:

bash git clone https://github.com/your-username/autobots-simulation.git cd autobots-simulation

Install required dependencies:

bash pip install -r requirements.txt Usage To run the simulation, execute the following command in your terminal:

bash python autobot_simulation.py Follow the prompts to input the grid size, starting and ending points, and obstacles.

 How to Run the Simulation Upon executing the script, you will be prompted to enter the grid dimensions and configurations for each autobot, including their starting and ending points. The simulation will then execute the commands for each autobot, displaying their movements step-by-step. At the end of the simulation, you will receive a summary of the performance metrics, including total time and command counts. Performance Metrics The simulation will report:

Total Time: The cumulative time taken for all autobots to reach their destination, including time spent on Wait commands.  Total Commands: The number of movement commands issued to each bot during the simulation. • Collision Avoidance Logic The autobots operate based on a set of movement rules to prevent collisions. The logic checks: If two bots are about to occupy the same cell, one will wait until the path is clear. Paths are dynamically adjusted based on obstacles and the position of other bots.  Wait Command Management The autobots can issue Wait commands to prevent collisions. This is particularly useful in tight spaces or when two bots are heading toward the same cell. The Wait command is intelligently managed to allow the bots to safely navigate around each other.
 Testing To ensure the functionality of the simulation, run the following tests: • Unit Tests: Implement unit tests to verify individual functionalities such as movement commands and collision detection. • Integration Tests: Verify that multiple bots can navigate the grid correctly under various scenarios. • Contributing Contributions are welcome! If you would like to contribute to this project, please fork the repository and create a pull request with your changes.
