# Sum of Big Numbers with Web Worker

This project demonstrates the use of a web worker in JavaScript to asynchronously compute the sum of numbers. The computation happens off the main thread, improving UI responsiveness, and results are streamed back in real time.

## Project Structure

- **`index.html`**: The main HTML file containing buttons for theme switching and initiating the computation, along with the output display section.
- **`worker.js`**: The web worker script responsible for computing the sums asynchronously.
- **`index.js`**: The main JavaScript file that manages interactions with the DOM, posts messages to the worker, and handles responses.
- **`style.css`**: A basic stylesheet for styling the page and theme switching (light/dark mode).

## Features

- **Web Worker**: The web worker computes sums asynchronously to prevent UI blocking during large number computations.
- **Theme Switching**: The user can toggle between light and dark themes for the UI.
- **Real-time Results**: Each computation result is streamed to the UI as soon as it completes.

## How to Use

1. Click the "Start Processing" button to start the sum calculations.
2. The output will display the sum of numbers in real-time as each computation completes, along with the time taken.
3. Use the **Light** and **Dark** buttons to toggle between themes.
