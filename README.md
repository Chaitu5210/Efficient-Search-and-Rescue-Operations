# Search and Rescue Operations

## Project Overview
This project aims to improve the efficiency of search and rescue operations during natural disasters such as earthquakes, floods, and tsunamis. By leveraging a combination of swarm robots and drones, the system can cover large disaster areas, identify victims, and provide real-time data to rescuers. The goal is to minimize response time and ensure that areas with higher casualty risks are prioritized.

## System Features
- **Swarm Robotics**: Multiple autonomous robots coordinate to cover large areas efficiently.
- **Drones**: Equipped with cameras and sensors for aerial surveillance and victim detection.
- **Real-time Data Sharing**: Data from robots and drones is shared in real-time with a command center.
- **Multi-start Heuristic Algorithm**: Used to optimize path navigation and maximize area coverage.
- **Sector Assignment**: Probabilistic method to prioritize high-casualty zones.

## Tools and Technologies
- **Python** for algorithm development
- **ROS (Robot Operating System)** for swarm robot coordination
- **OpenCV** for image and video processing
- **GPS and Sensor Integration** for location tracking and victim detection
- **Machine Learning** for casualty assessment (injured, non-injured, deceased)

## Project Workflow
1. **Initial Setup**: The disaster zone is divided into sectors based on priority and difficulty.
2. **Swarm Deployment**: Robots are deployed to traverse the sectors, avoiding any overlap.
3. **Drone Surveillance**: Drones are sent to areas that are hard to reach on foot or by ground robots.
4. **Victim Detection**: Drones and robots identify human beings using image processing techniques.
5. **Real-time Reporting**: The data collected is transmitted to rescue teams for immediate action.

## Key Algorithms
- **Multi-start Heuristic Algorithm**: Optimizes the path for swarm robots to ensure maximum coverage.
- **Sector Assignment Algorithm**: Assigns robots and drones to high-priority sectors based on probability and casualty data.

## Results
The system demonstrated enhanced efficiency in search coverage and quicker victim identification. Initial simulations suggest that the multi-start heuristic approach outperforms traditional grid-based search methods in terms of search time.

## Future Enhancements
- Integration of more advanced AI for better victim classification.
- Collaboration with local authorities to deploy the system in real-life scenarios.
- Improved drone battery life and range.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/Chaitu5210/Efficient-Search-and-Rescue-Operations.git
