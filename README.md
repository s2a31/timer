# JavaScript Timer Project

## Overview

This project is a simple, visually appealing JavaScript Timer that includes start and pause functionalities. Designed with flexibility in mind, it allows users to set a timer duration and visually see the countdown through an animated SVG circle. The timer is perfect for anyone needing a straightforward countdown for activities or tasks.

## Features

- **Customizable Timer Duration:** Users can input their desired timer duration.
- **Start/Pause Functionality:** Control the timer with start and pause buttons.
- **Visual Feedback:** An animated SVG circle provides a visual representation of the remaining time.
- **Callbacks for Custom Actions:** Developers can hook into `onStart`, `onTick`, and `onComplete` events for custom behaviors.

## Setup

1. **Clone the Repository**

    Start by cloning this repository to your local machine:

    ```bash
    git clone https://github.com/s2a31/timer.git
    ```

2. **Open `index.html`**

    Navigate to the project directory and open the `index.html` file in your browser to see the timer in action.

## Usage

The timer is straightforward to use:

1. **Set Duration:** Enter the desired duration (in seconds) in the input field at the center of the timer.
2. **Start Timer:** Click the play button to start the countdown.
3. **Pause Timer:** Click the pause button to temporarily halt the countdown.

## Code Structure

- **HTML (`index.html`):** Contains the structure of the timer, including input fields for duration and start/pause buttons.
- **CSS (`style.css`):** Provides styling for the timer, making it visually appealing.
- **JavaScript:**
  - **`timer.js`:** Defines the `Timer` class, responsible for the timer's functionality.
  - **`index.js`:** Initializes the timer with user-defined settings and binds it to the HTML elements.

## Customization

Developers can customize the timer by modifying the `Timer` class callbacks in `index.js` for specific actions on timer start, tick, and completion.

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this project. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source and available under MIT License.