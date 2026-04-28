# Sudoku Generator in HTML with JavaScript and CSS

## Usage
- Go to deployment page [https://cnordenb.github.io/html_sudoku_generator/](https://cnordenb.github.io/html_sudoku_generator/)
- Adjust difficulty using slider
- Click Reset to generate new Sudoku
- Click an empty cell to enter a value using your keyboard
- Click Validate to show correctness of numbers
- Click Reveal to show solution in separate grid

## Game Rules
1. A number may not repeat within its 3x3 block.
2. A number may not repeat within its row.
3. A number may not repeat within its column.

## Constraints
- The Sudoku only has one possible solution.
- The minimum amount of clues provided the constraint above is 17 (difficulty 64 empty cells), as mathematically proven by [McGuire et al](https://arxiv.org/abs/1201.0749).
- The maximum amount of clues in this implementation is arbitrarily limited to 80 (difficulty 1 empty cell).

## Warning
- These sudokus are computer-generated and are not handcrafted. Read Nobuhiko Kanamoto's [plea](https://www.nikoli.co.jp/en/puzzles/sudoku/why_hand_made/) as to why you should only play sudokus hand made by humans.
