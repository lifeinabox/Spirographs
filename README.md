# Spirographs

This project draws animated and static spirographs using Python's turtle graphics module.

## Features
- Draws random animated spirographs
- Draws custom spirographs with user-supplied parameters
- Save drawings as PNG images (press `s` while running)
- Toggle turtle cursor (press `t`)
- Restart animation (press `space`)

## Requirements
- Python 3.7+
- numpy
- Pillow
- tkinter (for turtle graphics)

## Usage

### Run with random animation
```sh
python3 spiro.py
```

### Run with custom parameters
```sh
python3 spiro.py --sparams R r l
```
Where:
- `R`: radius of outer circle
- `r`: radius of inner circle
- `l`: ratio of hole distance to r (0 < l < 1)

Example:
```sh
python3 spiro.py --sparams 220 65 0.8
```

## Notes
- Make sure you have all dependencies installed. On macOS, you may need to install `python-tk` via Homebrew for turtle graphics to work.
- If you encounter issues with numpy or turtle, check for conflicting files named `numbers.py` in your project directory.

## License
MIT
