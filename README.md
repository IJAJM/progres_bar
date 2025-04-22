# Hacker Progress Bar

This is a simple web page that simulates a "hacker-style" interface with:

- A green progress bar that animates from 0% to 100%
- A code output area where lines of code appear gradually
- Styling using Tailwind CSS for responsiveness and clean layout

## Features

- Dark terminal-like theme
- Animated green progress bar
- Code appears in sync with progress bar completion

## Technologies Used

- HTML
- Tailwind CSS
- JavaScript

## How It Works

- The page uses a predefined array of fake code lines
- A function `updateProgress()` adds a new line every 400ms
- The progress bar's width and percentage text update accordingly

## Usage

1. Open `index.html` in any modern browser.
2. Watch the progress bar fill up as the fake code appears.

## Customization

You can change the fake code inside the `fakeCodeLines` array in the script tag to suit your use case.

## License

MIT License

