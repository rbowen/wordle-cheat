# wordle-cheat

An interactive Wordle helper that narrows down possible words based on your guess results.

## Usage

Run the script:

```bash
./wordle
```

Enter your guess results using this notation:
- `+letter` - correct letter in correct position (green)
- `-letter` - correct letter in wrong position (yellow)
- `letter` - letter not in the word (gray)

### Example

```
Guess result: ad+ie-u
```

This means:
- `a` is not in the word (gray)
- `d` is not in the word (gray)
- `i` is in position 3 (green)
- `e` is in the word but not in position 4 (yellow)
- `u` is not in the word (gray)

The script will show matching words and update constraints as you enter more guesses.

## Requirements

- Python 3
- `uv` (for script execution)
- `/usr/share/dict/words` (present on most Linux/macOS systems)

Yes, of course it's cheating.
