# Key Logger Web App

A simple yet professional Key Logger web application built with **HTML**, **CSS**, and **JavaScript** to demonstrate DOM manipulation. The app dynamically tracks keypress events and displays the key pressed along with its status in a clean and interactive user interface.

## Features

- **Real-time Key Logging**: Displays the last key pressed and its status (`Key Pressed` or `No Key Pressed`).
- **Start/Stop Controls**: Buttons to enable or disable key logging dynamically.
- **Responsive and Modern UI**: Clean design with internal styling for a professional look.
- **Educational Purpose**: Demonstrates JavaScript DOM manipulation and event handling.

## Technologies Used

- **HTML**: For the structure of the web application.
- **CSS**: For styling and enhancing the UI.
- **JavaScript**: For dynamic functionality and DOM interaction.

## How to Use

1. Clone or download the repository.
2. Open the `index.html` file in any modern web browser.
3. Use the following buttons:
   - **Start Logging**: Begins logging keypress events.
   - **Stop Logging**: Stops logging keypress events and resets the display.

## Code Structure

- **HTML**: Provides the structure for the key display and buttons.
- **CSS**: Contains internal styles for layout, buttons, and professional appearance.
- **JavaScript**: Implements event handling for key logging and button control.

## Usage Example

1. Click "Start Logging".
2. Press any key on your keyboard. The key will be displayed in the "Last Key Pressed" box.
3. The "Key Press Status" box updates to show whether a key is currently pressed or not.
4. Click "Stop Logging" to stop capturing key events and reset the display.

## Code Snippet

Here's a small example of the key logging functionality:

```javascript
function logKeyPress(event) {
  if (loggingActive) {
    keyDisplay.textContent = event.key;
    statusDisplay.textContent = "Key Pressed";
  }
}
```
