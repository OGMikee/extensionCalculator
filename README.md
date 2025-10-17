# Simple Calculator Extension

A clean and functional calculator browser extension for Firefox with basic arithmetic operations.

## Features

- Basic arithmetic operations (+, -, ×, ÷)
- Decimal number support
- Delete and clear functions
- Modern, dark-themed interface
- Fast and lightweight
- No permissions required

## Installation

### From Firefox Add-ons (Coming Soon)
Search for "Simple Calculator" in Firefox Add-ons

### Manual Installation (Development)
1. Clone this repository
2. Open Firefox and navigate to `about:debugging`
3. Click "This Firefox"
4. Click "Load Temporary Add-on"
5. Select the `manifest.json` file from the extension directory

## Usage

1. Click the calculator icon in your Firefox toolbar
2. Use the number buttons and operators to perform calculations
3. Press `=` to see the result
4. Use `AC` to clear all, or `DEL` to delete the last digit

## Development

### Prerequisites
- Node.js (for development tools)
- npm or yarn

### Setup
```bash
npm install
```

### Testing
```bash
npm start
```

### Building
```bash
npx web-ext build
```

## Project Structure
```
calculator-extension/
├── assets/
│   ├── css/
│   │   └── popup.css
│   └── icons/
│       ├── icon-48.png
│       └── icon-96.png
├── src/
│   ├── app.js
│   ├── calculator.js
│   ├── display.js
│   └── utils.js
├── manifest.json
├── popup.html
└── README.md
```

## License

ISC

## Author

Mickaël Gatti