# E-N-E-R-G-Y
# Optimal Energy Calculation for Floor Containing Server Rooms, Labs, and Open Areas

This project calculates the optimal energy usage for a floor containing server rooms, laboratories, and open areas. It estimates the energy consumption for both lighting and cooling systems over a period of 10.5 hours.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Results](#results)
- [License](#license)

## Introduction

In modern building design, energy efficiency is crucial to reduce costs and improve sustainability. This project aims to calculate the energy consumption of various systems such as lighting and cooling in different types of spaces (server rooms, laboratories, and open areas). By determining the optimal energy values, we can improve the overall efficiency of the systems in use.

## Project Overview

This project focuses on estimating the energy consumption of the following:

- **Server Rooms**: Heavy computing systems requiring intensive cooling.
- **Laboratories (Labs)**: Research environments where both lighting and cooling are significant factors.
- **Open Areas**: General office spaces with moderate energy requirements for lighting and cooling.

The calculations are based on specific assumptions for each type of space regarding power consumption and operating conditions. These are considered for a time span of 10.5 hours.

## How It Works

The project includes the following key components:
1. **Lighting Energy Calculation**: The lighting energy consumption is calculated by considering the number of lights, their power rating, and the duration they are used.
2. **Cooling Energy Calculation**: The cooling energy consumption is calculated based on factors such as the size of the room, the number of systems operating, and the temperature control requirements.
3. **Time Span**: The energy consumption is calculated for a duration of 10.5 hours to simulate typical daily usage.
4. **Optimization**: The system suggests optimal values for lighting and cooling to minimize energy usage without compromising functionality.

### Formulae Used:
- For lighting: `Energy = Power (W) * Time (h)`
- For cooling: `Energy = Cooling Load (kW) * Time (h)`

## Usage

To use this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/optimal-energy-calculation.git
    ```
2. Navigate to the project folder:
    ```bash
    cd optimal-energy-calculation
    ```
3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the script to calculate the energy usage:
    ```bash
    python energy_calculator.py
    ```

5. The results will be displayed for each room type (Server Rooms, Labs, Open Areas) and for each energy consumption type (lighting, cooling).

## Dependencies

This project uses the following Python packages:

- `numpy`
- `pandas`
- `matplotlib` (for visualizing results)

You can install the required dependencies using the command:

```bash
pip install -r requirements.txt
