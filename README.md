# Solar System Orbit Simulation

This project is a Python script that generates an animated simulation of the solar system using `matplotlib` and `numpy`. It accurately models the orbital periods and relative sizes of the planets, and includes an asteroid belt for a more complete picture of our solar system. The simulation is interactive, allowing for real-time adjustments to the viewing area and the speed of the simulation.

## Features

- **Accurate Orbital Periods:** Planets orbit the sun based on their real-world orbital periods.
- **Interactive Controls:**
    - **Zoom:** A slider to zoom in and out of the solar system.
    - **Time Control:** A slider to control the speed of the simulation (days per frame).
- **Asteroid Belt:** A visually represented asteroid belt between Mars and Jupiter.
- **Planet Data:** The script prints the orbital velocity and period of each planet to the console upon execution.
- **Dark Theme:** A visually appealing dark background for the simulation.

## Requirements

To run this simulation, you need to have Python installed, along with the following libraries:

- `numpy`
- `matplotlib`

You can install these libraries using pip:
```bash
pip install numpy matplotlib
```

## Running the Simulation

To run the simulation, simply execute the `orbits` script from your terminal:

```bash
python orbits
```

This will open a new window displaying the animated solar system.

## Customization

You can customize the simulation by editing the `orbits` script. For example, you can add new planets or other celestial bodies by adding a new dictionary to the `planets` list. Each planet's dictionary should contain the following keys: `name`, `radius` (in AU), `orbital_period` (in Earth years), `color`, and `radius_km`.
