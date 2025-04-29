# Modal Window Project

This project is a simple implementation of a modal window built using **JavaScript**, **HTML**, and **CSS**. The modal window can be opened and closed using various user interactions, such as button clicks, overlay clicks, and keyboard input. It demonstrates essential JavaScript concepts like DOM manipulation, event handling, and class-based styling.

## Features

- **Modal Window**: A pop-up modal that appears when triggered.
- **Overlay**: A semi-transparent background overlay that appears with the modal.
- **User Interactions**:
  - Open the modal by clicking on any "Show modal" button.
  - Close the modal by:
    - Clicking the close button (`×`).
    - Clicking outside the modal (on the overlay).
    - Pressing the `Escape` key.

## What Has Been Covered

### 1. **DOM Manipulation**

- Selecting elements using `document.querySelector` and `document.querySelectorAll`.
- Dynamically adding and removing CSS classes to show or hide elements.

### 2. **Event Handling**

- Adding event listeners for click events on buttons and the overlay.
- Handling keyboard events (e.g., `keydown` for the `Escape` key).

### 3. **Functions**

- Creating reusable functions like `openModal` and `closeModal` to manage modal behavior.

### 4. **CSS Class Manipulation**

- Using CSS classes to control the visibility of the modal and overlay.
- Toggling the `hidden` class to show or hide elements dynamically.

### 5. **Keyboard Interaction**

- Detecting and responding to specific key presses (e.g., `Escape`) to enhance user experience.

## How to Use

1. Open the `index.html` file in your browser.
2. Click on any "Show modal" button to open the modal.
3. Close the modal by:
   - Clicking the close button (`×`).
   - Clicking outside the modal (on the overlay).
   - Pressing the `Escape` key.

## Technologies Used

- **JavaScript**: Core logic for modal functionality and event handling.
- **HTML**: Structure of the modal, buttons, and overlay.
- **CSS**: Styling for the modal, overlay, and buttons.

## How to Run the Code

1. Clone the repository or download the project files.
2. Open the `index.html` file in a browser.
3. Interact with the modal by clicking buttons or using the keyboard.

## Future Improvements

- Add animations for opening and closing the modal.
- Implement accessibility features like focus trapping within the modal.
- Allow multiple modals to be opened and managed simultaneously.
- Add a confirmation dialog or additional content inside the modal.

Enjoy exploring the modal window functionality!
