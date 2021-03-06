# Sudoku Solver

Solves Sudoku within seconds. The Sudoku can be given manually in the output screen or from a file. 

This package also contains [other functions](#other-useful-functions) on lists, that are useful to solve a Sudoku.

## Sudoku Format

Blank cells should be given as '-' and the number of characters should be 9. Press Enter after giving 9 characters, to enter the next row in Sudoku. If 9 characters are not given or the given characters are not unique, a warning will be given to re-enter the row.

Overall, the format of the Sudoku should be as follows:

        15-8--7-2
        -3--5----
        --72--5--
        -----1-9-
        -2--89---
        9-----18-
        36---2--4
        --4-6-9--
        -9-----61

## Functions

#### Main function:
- **solveSudoku** - Used to solve the Sudoku.
#### Other useful functions:
- **get_sudoku** - Imports Sudoku from a text file.
- **prompt_sudoku** - Prompts the Sudoku.
- **blocks_has_duplicates** - Checks if the Sudoku blocks have duplicates or not.
- **blockify** - Converts 9x9 Sudoku list into a list containing lists of values in the block of the given Sudoku.
- **vertically_has_duplicates** - Checks whether the given collection of lists have duplicate values at the same indexes or not.
- **list_difference** - Difference between two lists.
- **list_intersection** - Intersection between two lists.
- **combo_recursion** - Recursion function used to calculate all the combinations of a list.
- **all_combinations** - Uses the 'combo_recursion' function inside a loop, that iterates through the given list.
- **block_number** - Gives the block number in which the given row and column numbers intersects in a Sudoku.
- **value_inserts** - Inserts the given list of possible missing values inside the given original list, at the positions where the values are missing inside the original list.
- **insert_combos** - Tries all combinations of missing elements and inserts to a list and returns it.
- **vertical** - Transpose of a nx9 list.
- **list_duplicates_of** - Predicts the indexes of duplicate elements inside a list.


*Refer the Documentation for more info.* 

## Source Code and Documentation

- [Source Code](https://github.com/Raj-Srikar/solvesudoku/blob/master/src/solvesudoku/__init__.py)
- [Documentation](https://github.com/Raj-Srikar/solvesudoku/wiki#documentation)
