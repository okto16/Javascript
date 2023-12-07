# React Counter App

This is a simple React counter application that allows users to increment, decrement, and reset a counter. The project is built using React and Babel for JSX compilation. The application consists of three components: `MyButton`, `MyCounter`, and `MyApp`.

## Features

- Increment the counter by clicking the '+' button.
- Decrement the counter by clicking the '-' button.
- Reset the counter to 0 by clicking the 'Reset!' button.
- The buttons are disabled when the counter is outside the range of 0 to 9.
- Visual indication of the counter status with appropriate styles.

## Components

### 1. MyApp

The main component that manages the state of the counter and renders the other components.

### 2. MyButton

A reusable button component that takes text, click handler, and counter as props. It dynamically adjusts its behavior and style based on the provided text and the counter value.

### 3. MyCounter

A component that displays the current counter value. If the counter is outside the range of 0 to 9, it displays 'done!' instead.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/okto16/react-counter-app.git
