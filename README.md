# Traffic Light System Using D Flip-Flops

## Project Overview

This project implements a digital traffic light system using D flip-flops, basic logic gates, and a clock. The traffic light cycles through the standard sequence of green, yellow, and red lights, simulating a real-world traffic signal operation.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Project Components](#project-components)
- [Circuit Design](#circuit-design)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)

## Features

- **Three-phase signal cycle**: Green, yellow, and red lights cycle in sequence.
- **Timed control**: Clocked operation to switch states at specific intervals.
- **Reset functionality**: Option to reset the system to the initial state.

## Project Components

- **D Flip-Flops**: Used to store the current state of the traffic lights.
- **Logic Gates**: AND, OR, and NOT gates are used to implement state transition logic.
- **Clock Signal**: Provides a timed pulse to trigger state changes.
- **Traffic Light**: Represent the green, yellow, and red lights in the traffic signal.

## Circuit Design

The design uses three D flip-flops to manage the traffic light states, which transition in sequence based on the clock signal. Logic gates define the conditions for each state transition. The system follows a repetitive sequence:

1. **Green Light**: Remains on for a set duration.
2. **Yellow Light**: Turns on briefly after green to indicate caution.
3. **Red Light**: Signals to stop before returning to green.

## How It Works

1. **Initial State**: The green light is on initially.
2. **State Transition**: With each clock pulse, the state transitions:
    - Green -> Yellow -> Red -> Green (repeating).
3. **Clock Control**: The clock signal drives each transition at a predefined rate.

## Getting Started

### Prerequisites

To run this circuit on a simulator, you may need software like:
- **Proteus** for digital logic circuit design
- Basic understanding of digital logic and flip-flop operation

### Running the Circuit

1. **Set up the Circuit**: Follow the schematic diagram and connect the D flip-flops, logic gates, and clock accordingly.
2. **Run the Clock Signal**: Start the clock to see the traffic lights cycle through green, yellow, and red.

