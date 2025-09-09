# RTOS Task Schedule Simulation

This repository simulates task scheduling in a Real-Time Operating System (RTOS) environment. The project showcases popular scheduling algorithms and demonstrates their effect on task execution and system performance.

## Features

- **Task Scheduling Algorithms**: Supports Round Robin, Priority Scheduling, and other RTOS scheduling methods.
- **Task Simulation**: Define custom tasks with parameters such as arrival time, burst time, period, and priority.
- **Visualization**: Graphical or textual output showing Gantt charts or scheduling tables.
- **Configurable Parameters**: Easily modify task details and algorithm settings to observe different behaviors.

## Getting Started

### Prerequisites

- C/C++ compiler (e.g., GCC)
- [Optional] Python 3.x for visualization scripts

### Repository Structure

```
├── src/              # Source code for RTOS simulation
├── examples/         # Sample task sets and usage examples
├── visualization/    # Scripts to visualize scheduling results
├── README.md         # Project documentation
├── LICENSE           # License file
```

### Building and Running

1. Clone the repository:
    ```bash
    git clone https://github.com/Saivivek2106/RTOS-Task-Schedule-Simulation.git
    cd RTOS-Task-Schedule-Simulation
    ```
2. Build the simulation (example using GCC):
    ```bash
    gcc src/main.c -o rtos_sim
    ```
3. Run the simulation:
    ```bash
    ./rtos_sim
    ```

4. [Optional] Use visualization scripts:
    ```bash
    python3 visualization/gantt_chart.py results.txt
    ```

## Usage

Edit the task set in `src/tasks.c` or provide your own input file. Select your desired scheduling algorithm within the code or via command-line options (if implemented).

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- Saivivek2106

## Acknowledgements

- Inspiration from other RTOS simulation projects
- Academic references on scheduling algorithms
