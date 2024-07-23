# Carton Box Measurement App

An Android application for calculating dimensions and weights of carton boxes and boards.

## Features

- **Box Calculation**: Calculate weights for carton boxes.
- **Board Calculation**: Calculate weights for boards.
- **Box Shape Calculation**: Computes the load ability for carton boxes based on dimensions provided by the user.
- **Cylinder Shape Calculation**: Computes the load ability for cylindrical shapes with user-defined diameter and height.
- **Unit Conversion**: Supports multiple units of measurement including CM, INCH, FEET, and METER.
- **Dynamic UI**: Responsive layout adjusts for various screen sizes and orientations.
- **ViewModel Integration**: Utilizes ViewModel architecture for managing UI-related data.
- **Navigation**: Implements Jetpack Navigation for seamless screen transitions.
- **Snackbar Notifications**: Displays messages using Material Design's Snackbar.
- **Future Database Integration**: Plans to store calculations and user data in a Room database for persistent storage.

## Screenshots
![carton box measurment App](https://github.com/user-attachments/assets/0d5511d3-4ecf-4c6e-bb58-da3f5a627c07)


## Technologies Used

- **Jetpack Compose**: Modern UI toolkit for building native UIs in Android.
- **Material3**: Material Design components and theming for a cohesive user experience.
- **Hilt**: Dependency injection framework for simplifying DI in Android.
- **Room Database**: SQLite database abstraction for local data storage (planned for future).

## Architecture

- **Clean Architecture**: Ensures separation of concerns, making the codebase more modular and testable. It follows the principles of presenting, domain, and data layers.
- **Dependency Injection**: Managed through Hilt to provide necessary dependencies and manage their lifecycles.
- **Room Database**: Used for storing user data and calculations.

## Installation

1. Download the repository:
2. Extract the file
3. Open the project in Android Studio.
4. Run the app on an emulator or physical device.

## Usage
- Describe briefly how to use the app. For example:
- Enter dimensions and other required details.
- To find the container (20 feet ,40 feet,40 feet high cube) load ability -> Square shape and cylinder shape product.
- Automatically "Calculated" to see results below.


