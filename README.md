# Sudoku Generator in HTML with JavaScript and CSS

## Usage
- Go to deployment page [https://cnordenb.github.io/html_sudoku_generator/](https://cnordenb.github.io/html_sudoku_generator/).
- Adjust difficulty using slider.
- Click Generate to generate new Sudoku.
- Click an empty cell under Progress to enter a value using your keyboard.
- Click Validate to show correctness of numbers.
- Click Reveal to show the solution.

## Game Rules
1. A number may not repeat within its 3x3 block.
2. A number may not repeat within its row.
3. A number may not repeat within its column.

## Constraints
- The Sudoku only has one possible solution.
- The minimum amount of clues provided the constraint above is 17, as mathematically proven by [McGuire et al](https://arxiv.org/abs/1201.0749).
- The maximum amount of clues in this implementation is arbitrarily limited to 80.

## Warning
- These sudokus are computer-generated and are not handcrafted. Read Nobuhiko Kanamoto's [plea](https://www.nikoli.co.jp/en/puzzles/sudoku/why_hand_made/) as to why you should only play sudokus hand made by humans.

## Acknowledgement
- Huge thanks to [Gordon Royle](https://research-repository.uwa.edu.au/en/persons/gordon-royle/) for his dataset of 49 151 unique solution 17-clue Sudokus. It is available in this repository as [sudoku17.txt](https://github.com/cnordenb/html_sudoku_generator/blob/main/sudoku17.txt).
