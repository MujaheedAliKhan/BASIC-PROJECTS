# Countdown Timer

A simple web-based countdown timer that allows users to set a specific date and time, displays the remaining time, and notifies when the countdown reaches zero.

## Features
- Set a custom target date and time using a datetime input field.
- Displays the countdown in days, hours, minutes, and seconds.
- Provides options to start and reset the countdown.
- User-friendly interface with real-time updates.

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS**: Styling of the countdown timer.
- **JavaScript**: Core functionality for countdown logic.

## File Structure
```
Countdown Timer/
|-- index.html       // Main HTML file
|-- style.css        // CSS for styling the page
|-- script.js        // JavaScript logic for the countdown
|-- README.md        // Documentation for the project
```

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/countdown-timer.git
   cd countdown-timer
   ```

2. **Open in Browser**:
   Open the `index.html` file in your favorite web browser.

3. **Set Countdown**:
   - Enter a date and time in the provided input field.
   - Click the **Start** button to begin the countdown.

4. **Reset Countdown**:
   - Click the **Reset** button to clear the input and reset the timer.

## Code Overview

### HTML (`index.html`)
- Contains the structure for the timer interface.
- Includes input fields, buttons, and a display area for the countdown.

### CSS (`style.css`)
- Styles the timer for a clean and minimalistic appearance.
- Responsive design to ensure usability on different devices.

### JavaScript (`script.js`)
- Handles the core functionality of the countdown timer:
  - Retrieves the user-input date and time.
  - Calculates the remaining time and updates the display in real time.
  - Stops the timer when the countdown reaches zero.
  - Resets the input and display when the **Reset** button is clicked.

#### Key Functions
- **`startCountdown()`**:
  - Validates the input date.
  - Calculates and updates the countdown every second.

- **`resetCountdown()`**:
  - Clears the input and stops the countdown.

## Example Output
When the countdown is running, the display shows:
```
10 Days, 5 Hours, 30 Minutes, 45 Seconds
```
When the countdown ends, the display shows:
```
Time is up!
```

## Live Demo
--This is a link of [Countdown Timer](https://mujaheedalikhan.github.io/BASIC-PROJECTS/COUNTDOWN-TIMER)

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

## Author
- Lavani Mujaheed Ali Khan
---

Enjoy building your countdown projects!
