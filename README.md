# Progress Steps

A clean, interactive progress indicator component built with vanilla JavaScript, HTML, and CSS.

## Description

This project demonstrates a multi-step progress indicator commonly used in forms, checkout processes, and onboarding flows. It features:
- Numbered step indicators
- A progress bar that fills based on the current step
- Previous and Next navigation buttons
- Smooth transitions between states

## Features

- Visual progress tracking with numbered circles
- Animated progress bar
- Responsive button states (disabled when reaching limits)
- Smooth CSS transitions
- Clean, modern UI design

## Technologies Used

- HTML5
- CSS3 (with CSS variables and transitions)
- JavaScript (ES6)
- Google Fonts (Roboto)

## How to Use

1. Clone or download the repository
2. Open `index.html` in your browser
3. Click the "Next" button to advance through the steps
4. Click the "Prev" button to go back to previous steps
5. Notice how the progress bar fills and the circles change state as you navigate

## Project Structure

- `index.html` - Basic HTML structure with the progress steps component
- `style.css` - All styling with CSS variables and transitions
- `script.js` - JavaScript for updating the progress state and handling button clicks

## JavaScript Functionality

The JavaScript code handles three main tasks:
1. Tracking the current active step
2. Updating the visual state of the circles (active/inactive)
3. Calculating and updating the progress bar width
4. Managing button states (enabling/disabling based on position)
