# Kigali Road Simulation

## Project Overview

This project is a Python-based self-driving car simulation developed for ALU's Individual Coding Lab 1, **"FSD, but on Kigali roads."**

The simulation models a journey from ALU Rwanda to the Kigali Convention Center. It demonstrates how a vehicle responds to speed limits, zebra crossings, and bus segments while navigating a customizable road.

## Features

- Validates road signs and speed limits.
- Adjusts vehicle speed through acceleration and braking.
- Stops at zebra crossings.
- Handles bus segments and lane changes.
- Allows users to add, insert, and replace road signs.
- Displays a browser-based visualization of the journey.
- Generates a trip report containing journey statistics.

## Technologies Used

- Python 3
- HTML and JavaScript (provided visualization)
- Python standard library

No external Python packages are required.

## Project Structure

```text
lab1_Isimbisunny/
├── road_simulation.py
├── transit_program.py
├── engine.py
├── index.html
├── Readme.md
└── .gitignore
```

`road_simulation.py` contains the implemented lab functions. The other Python and HTML files provide the simulation engine, program flow, and visualization.

## How to Run

1. Open a terminal in the project directory.
2. Run:

   ```bash
   python3 road_simulation.py
   ```

3. Enter a driver name.
4. Use the road editor to modify the road or select option `5` to start driving.
5. Open `http://127.0.0.1:8008` in a browser.
6. Press Enter in the terminal to begin the simulation.
7. Observe the journey and review the final trip report.

## Road Editor

| Option | Action |
|---|---|
| 1 | Add a sign at the end |
| 2 | Insert a sign at a specified position |
| 3 | Replace an existing sign |
| 4 | Display the current road |
| 5 | Start driving |

Supported signs include `bus`, `zebra`, and speed limits from 20 to 100 km/h.

Each road segment represents 100 meters.

## Testing

The project was tested through:

- Python syntax compilation.
- Invalid road-sign validation.
- Adding, inserting, and replacing road signs.
- Checking road segment and sign counts.
- Completing the full driving simulation.

The original 34-segment road was successfully completed, with the car arriving at the Kigali Convention Center.

## Author

GitHub: [Isimbisunny](https://github.com/Isimbisunny)

Developed as part of ALU's Individual Coding Lab 1.