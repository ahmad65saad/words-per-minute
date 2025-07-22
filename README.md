# WPM Typing Speed Test (Python, Terminal)

This is a simple terminal-based typing speed test written in Python using the `curses` library.
It was created as a learning project to practice Python programming and working with terminal interfaces.

## Features

- Randomly selects a line from `text.txt` for you to type
- Real-time WPM (Words Per Minute) calculation
- Highlights correct (green) and incorrect (red) characters as you type
- Simple interface with instructions

## Requirements

- Python 3.x
- `curses` library (pre-installed on Linux/macOS; on Windows, install with `pip install windows-curses`)

## Setup

1. Clone or download this repository.
2. (Windows only) Install the curses library:
   ```
   pip install windows-curses
   ```
3. Make sure `text.txt` is in the same directory as `wpm.py`.

## Usage

Run the program from your terminal:

```
python wpm.py
```

Follow the on-screen instructions to start the typing test.

## File Structure

- `wpm.py` — Main application code
- `text.txt` — Source of typing text (one line per test)
- `README.md` — Project documentation

## License

MIT License

---

*This project was created for learning purposes and to practice Python programming skills.*# words-per-minute