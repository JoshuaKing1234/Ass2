# Club Simulation

This is a Java simulation of a club environment using a grid-based model. The simulation allows you to explore the movement of clubgoers within the club, their interactions, and how they navigate the space.

## Features

- Simulates the movement of clubgoers within a club environment.
- Grid-based model representing the club layout.
- Entrance, exit, and bar areas.
- Dynamic visualization using Java Swing.

## Requirements

- Java Development Kit (JDK) 7 or higher.
- Git (for cloning the repository).

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/joshuaking123/club-simulation.git
   cd club-simulation
   ```

2. Compile the Java code:
   ```bash
   javac -d bin -sourcepath src src/clubSimulation/*.java
   ```

3. Run the simulation:
   ```bash
   java -cp bin clubSimulation.ClubSimulation
   ```

4. Follow on-screen instructions to start, pause, and exit the simulation.

## Customization

- You can customize the club layout by modifying the `ClubGrid` class in `src/clubSimulation/ClubGrid.java`.
- Adjust simulation parameters and settings in the `ClubSimulation` class in `src/clubSimulation/ClubSimulation.java`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

