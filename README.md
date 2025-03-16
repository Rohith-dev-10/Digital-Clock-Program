# Simple Digital Clock

## Overview
A simple digital clock that displays the current time in 12-hour format with AM/PM indicator. The clock features a clean, minimalist design with a blurred background effect.

> **Note:** This project was made in the learning stage for practice purposes.

## Features
- Real-time clock display (updates every 500ms)
- 12-hour time format with AM/PM indicator
- Responsive design
- Beautiful backdrop blur effect
- Full-screen background image

## Project Structure
- `index.html` - Main HTML structure
- `index.css` - Styling for the clock
- `index.js` - JavaScript functionality
- `image.png` - Background image (not included in repository)

## How It Works
The clock uses JavaScript's `Date` object to get the current time. The display updates every half-second using `setInterval`. The time is formatted to always show two digits for hours, minutes, and seconds.

## Usage
Simply open the `index.html` file in a web browser to run the clock.

```
$ open index.html
```

## Customization
- Change the background image by replacing `image.png` or updating the URL in `index.css`
- Adjust the font size, color, and blur effect in the CSS file
- Modify the update interval in `index.js` (currently set to 500ms)

## Learning Outcomes
This project demonstrates:
- Working with the JavaScript Date object
- DOM manipulation
- CSS styling techniques (flexbox, backdrop-filter)
- JavaScript time formatting
- Using setInterval for recurring functions

## License
[MIT](https://choosealicense.com/licenses/mit/)
