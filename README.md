
# Console Ninja

Console Ninja is a lightweight JavaScript utility library designed to enhance console logging capabilities for developers.

## Features

- **Colorful Logging:** Easily add colors to your console logs for better readability.
- **Customizable Output:** Customize the format and style of your console logs to suit your preferences.
- **Logging Levels:** Support for different logging levels such as debug, info, warning, and error.
- **Additional Utilities:** Includes various utility functions to simplify common tasks during development.

## Installation

You can install Console Ninja via npm:

bashCopy code

`npm install console-ninja`

Or you can include it directly in your HTML file:

htmlCopy code

`<script src="path/to/console-ninja.js"></script>`

## Usage

### Basic Example

javascript

    `// Import Console Ninja
    const cn = require('console-ninja');
    
    // Log a simple message
    cn.log('Hello, Console Ninja!');` 
    
    ### Customizing Output

javascript

    `// Import Console Ninja
    const cn = require('console-ninja');
    
    // Customize log format and color
    cn.config({
      format: '[{level}] {message}',
      color: {
        debug: 'blue',
        info: 'green',
        warning: 'yellow',
        error: 'red'
      }
    });
    
    // Log messages with different levels
    cn.debug('Debug message');
    cn.info('Info message');
    cn.warn('Warning message');
    cn.error('Error message');` 

### Using Utility Functions

javascript

`// Import Console Ninja
const cn = require('console-ninja');

// Use utility functions
cn.clear(); // Clear console
cn.time('timer'); // Start timer
setTimeout(() => {
  cn.timeEnd('timer'); // End timer and log elapsed time
}, 1000);`

## Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](https://chat.openai.com/c/LICENSE) file for details.

## original : [wallabyjs/console-ninja.git](https://github.com/wallabyjs/console-ninja.git)
