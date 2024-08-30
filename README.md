# Tic-Toc Network Simulation using OMNeT++

## Overview
The Tic-Toc project is a simple network simulation developed using OMNeT++. This project is designed to help beginners understand the basics of network simulations, including creating a simple two-node network, enhancing it, collecting statistics, and visualizing the results using the OMNeT++ Integrated Development Environment (IDE).

## Features
- **Two-node Network Simulation**: A basic simulation that demonstrates message passing between two nodes.
- **Network Enhancement**: Expanding the simulation to a more realistic network setup.
- **Statistics Collection**: Gathering and analyzing data from the simulation.
- **Visualization**: Displaying the network and simulation results using the OMNeT++ IDE.

## Installation

### Prerequisites
- **OMNeT++**: This project requires OMNeT++ to be installed on your system. OMNeT++ is an open-source simulation framework primarily used for simulating communication networks.

### Steps to Install OMNeT++
1. **Download OMNeT++**: 
   - Visit the [OMNeT++ website](https://omnetpp.org/) and download the latest version suitable for your operating system.
   
2. **Install OMNeT++**:
   - Follow the installation instructions provided on the website for your operating system.
   - For Linux, you may need to install additional dependencies like `gcc`, `make`, and `libxml2`.

3. **Set Up the Environment**:
   - After installation, set up your environment variables by sourcing the `setenv` script provided in the OMNeT++ installation directory:
     ```bash
     source /path/to/omnetpp/setenv
     ```

### Running the Tic-Toc Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nicsetty/tictoc-omnet.git
   cd tictoc-omnet
   
## Open the Project in OMNeT++ IDE:

Start the OMNeT++ IDE and import the project by navigating to **File > Import > General > Existing Projects into Workspace**.

## Build the Project:

Right-click on the project in the Project Explorer and select **Build Project**.

## Run the Simulation:

Right-click on the `omnetpp.ini` file and select **Run As > OMNeT++ Simulation**.

## Expected Output

- **Visual Representation**: The simulation will show the network with nodes and message exchanges.
- **Statistics**: Graphs and charts displaying the statistical data collected during the simulation will be generated.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to suggest improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
