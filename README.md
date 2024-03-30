# Robust and Decentralized Reinforcement Learning for UAV Path Planning in IoT Networks

---

## Introduction

This project aims to develop a robust and decentralized reinforcement learning (RL) system for UAV path planning in IoT networks. The primary goal is to create a simulation environment in 2D where drones connect to nearby IoT devices efficiently using a reinforcement learning algorithm. The RL algorithm is trained and saved as a `model.pkl` file, which is then loaded into the main program for execution.

## Features

- **Simulation Environment**: Generates a 2D simulation environment based on user-defined parameters such as grid size, number of UAVs, and number of IoT devices.
- **Reinforcement Learning**: Utilizes a decentralized RL algorithm to enable UAVs to learn optimal paths to connect with nearby IoT devices.
- **Model Persistence**: Trained RL model is saved as `model.pkl` for future use and loaded into the main program for seamless execution.
- **Dynamic Drone Management**: Allows users to add or remove drones from the simulation environment.
- **Auto-Reconnection**: Automatically connects disconnected IoT devices to neighboring drones in case of drone removal.

## Getting Started

1. Clone the repository: git clone https://github.com/your/repository.git

2. Install dependencies:

3. Run the main program:

4. Follow the on-screen instructions to interact with the simulation environment.

## Usage

- Upon running the program, the user will be prompted to input parameters such as grid size, number of UAVs, and number of IoT devices.
- The simulation environment will be generated based on the provided parameters.
- Users can interact with the environment by using predefined commands:
- `move`: Move drones within the environment.
- `remove`: Remove a drone from the environment.
- Disconnected IoT devices will automatically attempt to connect to neighboring drones.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [Harish Sasikumar](https://github.com/2003)(https://www.linkedin.com/in/harish-sasikumar-488100285/) for developing this project.



