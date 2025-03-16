# Digital-Clock-Program

# Simple Clock

## Overview
A lightweight JavaScript clock that displays the current time. This simple clock provides an easy way to add a real-time clock display to any website.

## Installation
```bash
npm install simple-clock
# or
yarn add simple-clock
```

## Usage
```javascript
import { SimpleClock } from 'simple-clock';

// Create a new clock instance
const clock = new SimpleClock('#clock-container');

// Start the clock
clock.start();

// Stop the clock
// clock.stop();
```

HTML:
```html
<div id="clock-container"></div>
```

## Features
- Real-time display of hours, minutes, and seconds
- Customizable display format (12/24 hour)
- Low memory footprint
- No dependencies

## Customization
```javascript
// Create a clock with options
const clock = new SimpleClock('#clock-container', {
  format: '24h',        // '12h' or '24h'
  showSeconds: true,    // show or hide seconds
  updateInterval: 1000  // update interval in milliseconds
});
```

## Browser Support
- Chrome
- Firefox
- Safari
- Edge

## License
[MIT](https://choosealicense.com/licenses/mit/)