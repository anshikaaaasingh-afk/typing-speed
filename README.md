# Typing Speed Tester

A terminal-based typing speed tester written in Python. It shows you a sentence, times how fast you can type it, and then reports your speed and accuracy.

## Features

- ⌨️ Displays a sentence to type
- ⏱️ Measures the time taken to type the sentence
- 🚀 Calculates Words Per Minute (WPM)
- 🎯 Calculates typing accuracy compared to the original sentence
- Simple, distraction-free terminal interface

## Demo

```
=== Typing Speed Tester ===
Type the following sentence exactly:
Artificial intelligence is changing the world.
Press Enter when you're ready...
Start typing:
Artificial intelligence is changing the world
===== Results =====
Time Taken: 10.97 seconds
Words Per Minute (WPM): 32.83
Accuracy: 97.83%
```

## Getting Started

### Prerequisites

- Python 3 installed on your system

### Installation

```bash
git clone https://github.com/anshikaaaasingh-afk/typing-speed-tester.git
cd typing-speed-tester
```

### Run

```bash
python3 speed_typing.py
```

## Usage

1. Run the program.
2. Read the sentence displayed on screen.
3. Press **Enter** when you're ready to start.
4. Type the sentence as accurately and quickly as you can, then press **Enter**.
5. View your results:
   - Time taken (seconds)
   - Words Per Minute (WPM)
   - Accuracy (%)

## How It Works

- **Time Taken** is measured from the moment you start typing to when you press Enter.
- **WPM** is calculated as `(number of words in the sentence / time taken in minutes)`.
- **Accuracy** compares your typed text to the original sentence to calculate a percentage match.

## Project Structure

```
typing-speed-tester/
├── speed_typing.py   # Main source file
└── README.md         # Project documentation
```

## Possible Improvements

- Add a pool of random sentences/paragraphs for variety
- Add difficulty levels (short/medium/long text)
- Track and display personal best scores over multiple runs
- Add colored terminal output to highlight typos
- Save results to a file for progress tracking over time

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Made by [Anshika](https://github.com/anshikaaaasingh-afk) as part of a growing Python/C/JavaScript portfolio.
