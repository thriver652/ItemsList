A simple React Native app with an add Item List feature, including a search bar and a plus button to add items.

## Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)

## Demo



https://github.com/thriver652/ItemsList/assets/74093651/44ac3bbe-fdb3-4d88-9ba9-8e6aca20f3cb



## Installation

Follow these steps to set up and run the project locally.

1. **Open Your Terminal**

2. **Install dependencies:**

    ```bash
    npm install -global expo-cli
    # or
    yarn install -global expo-cli
    # and
    expo init ItemsList
    # and
    cd ItemsList
    ```

3. **Run the app:**

    ```bash
    npm start
    # or
    npx react-native run-android
    # or
    npx react-native run-ios
    ```

    Make sure you have the necessary development environment set up for React Native.

## Usage

1. Launch the app on your emulator or device.
2. Use the search bar to enter a task.
3. Press the plus button to add the task to the to-do list.
4. View your tasks in the vertical list.

## Folder Structure

```plaintext
|-- .expo/         # Expo Installation
|-- .vscode/             # VS code
|-- assets/    # Node.js modules and dependencies
|-- src/             # React Native source code
|   |-- components/  # React components
|   |   |-- Task.js  # Task component
|   |-- screens/     # App screens
|   |   |-- HomeScreen.js  # Main screen component
|   |-- App.js       # Main app component
|-- .gitignore       # Git ignore file
|-- package.json     # Node.js dependencies and scripts
|-- README.md        # Project README file
