# HVAC Stadium Simulation

## Overview
This is an interactive simulation of a stadium's HVAC (Heating, Ventilation, and Air Conditioning) system. The visualization demonstrates how crowd density, outside temperature, and airflow affect temperature distribution and air circulation in a sports stadium environment.

## Features

- **Interactive Controls**:
  - Adjust crowd density (0-100%)
  - Set outside temperature (20-45°C)
  - Control airflow rate (1-10 m³/s)

- **Visual Elements**:
  - Stadium with pitch and seating areas
  - Crowd represented as heat-emitting dots
  - Dynamic heat zones that affect local temperature
  - Airflow visualization showing ventilation patterns
  - Temperature trend graph showing changes over time
  - Heat distribution legend

- **AI Recommendations**:
  - System provides real-time airflow recommendations based on current conditions
  - Visual indicators show when adjustments are needed

## Technical Details

- Built with HTML5 Canvas and vanilla JavaScript
- Uses particle systems to simulate airflow
- Implements heat zones that affect both people and airflow
- Includes interactive sliders for parameter adjustment
- Features a responsive design that updates in real-time

## How It Works

1. The simulation creates a stadium structure with seating areas around a central pitch
2. Air vents are positioned around the stadium to provide ventilation
3. Heat zones are randomly generated in seating areas to simulate concentrated heat sources
4. People are distributed based on crowd density and affected by nearby heat zones
5. Air particles flow from vents and are influenced by heat zones
6. The system tracks temperature trends and provides recommendations

## Usage

Simply open the HTML file in a modern browser. Use the sliders on the left to adjust simulation parameters and observe how changes affect the stadium environment.

The simulation runs continuously, with occasional random regeneration of heat zones to demonstrate dynamic conditions.
