# Tetris Game

A classic Tetris game implementation in Python using Pygame.

## Features

- Classic Tetris gameplay with all 7 tetromino shapes (S, Z, I, O, J, L, T)
- 10x20 grid playing field
- Score tracking and level progression
- Next piece preview
- Smooth controls and rotation
- Game over detection

## Installation

### From GitHub

```bash
pip install git+https://github.com/lukaszplk/tetris.git
```

### From Release

```bash
pip install https://github.com/lukaszplk/tetris/releases/download/v1.0.0/tetris_game-1.0.0-py3-none-any.whl
```

### Local Development

```bash
git clone https://github.com/lukaszplk/tetris.git
cd tetris
pip install -e .
```

## Usage

After installation, run the game with:

```bash
tetris
```

Or run directly from source:

```bash
python tetris.py
```

## Controls

- **Left/Right Arrow** - Move piece horizontally
- **Down Arrow** - Soft drop (move piece down faster)
- **Up Arrow** - Rotate piece
- **Space** - Hard drop (instant drop)
- **P** - Pause game
- **ESC** - Quit game

## Requirements

- Python 3.7+
- Pygame

## Development

To set up for development:

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the game
python tetris.py
```

## Building

To build the package:

```bash
python -m build
```

## License

MIT License - feel free to use and modify!

## Credits

Classic Tetris gameplay mechanics by Alexey Pajitnov.
