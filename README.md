# Vehicle Builder Command-Line Application

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

## Description

This TypeScript command-line application allows users to create and manage different types of vehicles: cars, trucks, and motorbikes. Users can create new vehicles, select existing vehicles, and perform various actions with the selected vehicle. The application leverages the Inquirer package for user input.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Video Walkthrough](#video-walkthrough)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/vehicle-builder.git
    cd vehicle-builder
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Run the application:
    ```sh
    npm start
    ```

## Usage

Upon running the application, you will be prompted with a menu to create a new vehicle or select an existing one. Follow the prompts to enter the necessary details for each vehicle type (car, truck, or motorbike).

### Creating a Vehicle

- Select "Create a new vehicle".
- Choose the type of vehicle (car, truck, motorbike).
- Enter the requested details:
  - **Car**: Color, Make, Model, Year, Weight, Top Speed
  - **Truck**: Color, Make, Model, Year, Weight, Top Speed, Towing Capacity
  - **Motorbike**: Color, Make, Model, Year, Weight, Top Speed, Front Wheel Diameter, Front Wheel Brand, Rear Wheel Diameter, Rear Wheel Brand

### Selecting an Existing Vehicle

- Select "Select an existing vehicle".
- Choose a vehicle from the list of existing vehicles.
- Perform actions such as printing details, starting the vehicle, accelerating, decelerating, stopping, turning, reversing, towing (for trucks), or performing a wheelie (for motorbikes).

### Performing Actions

After selecting a vehicle, you can perform various actions. The available actions depend on the type of vehicle.

## Features

- Create and manage different types of vehicles: cars, trucks, motorbikes.
- Perform specific actions with each vehicle type.
- Truck-specific action: towing another vehicle.
- Motorbike-specific action: performing a wheelie.
- Persistent vehicle selection for continuous interaction until the user decides to exit.

## Video Walkthrough

Watch the video walkthrough to see the application in action:

[Vehicle Builder Walkthrough](./src/walkthrough/Module08-Vehicle-Builder-Walkthrough.mov)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Author**: Bjorn Johansson

**GitHub**: [Bbbjrn](https://github.com/Bbbjrn)
