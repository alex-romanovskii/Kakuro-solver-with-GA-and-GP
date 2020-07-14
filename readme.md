# Kakuro

General

Kakuro is a kind of logic puzzle that is often referred to as a mathematical transliteration of
the crossword. Kakuro puzzles are regular features in many math-and-logic puzzle publications
across the world. The canonical Kakuro puzzle is played in a grid of filled and barred cells,
"black" and "white" respectively. Puzzle sizes vary widely. Apart from the top row and leftmost
column which are entirely black, the grid is divided into "entries" — lines of white cells — by
the black cells. The black cells contain a diagonal slash from upper-left to lower-right and a
number in one or both halves, such that each horizontal entry has a number in the black half-cell
to its immediate left and each vertical entry has a number in the black half-cell immediately
above it. These numbers, borrowing crossword terminology, are commonly called "clues".
The objective of the puzzle is to insert a digit from 1 to 9 inclusive into each white cell such that
the sum of the numbers in each entry matches the clue associated with it and that no digit is
duplicated in any entry. It is that lack of duplication that makes creating Kakuro puzzles with
unique solutions possible. Like Sudoku, solving a Kakuro puzzle involves investigating
combinations and permutations. There is an unwritten rule for making Kakuro puzzles that each
clue must have at least two numbers that add up to it, since including only one number is
mathematically trivial when solving Kakuro puzzles.

Description of the problem

Kakuro puzzles consist of an n × m grid containing black and white cells. All white cells are
initially empty and are organized into overlapping continuous runs that are exclusively either
horizontal or vertical. A run-total, usually given in black “clue” cell, is associated with each and
every run, and the puzzle is solved by entering values (typically from the range [1-9]) into the
white cells such that each run sums to the specified total and no digit is duplicated in any run.
Assuming only numbers in the range 1, . . . , 9 are used, a run can be between one and nine cells
in length with a corresponding run-total in the range 1, . . . , 45, although the majority of
published puzzles contain runs that are at least two cells in length. The figure below shows a
sample Kakuro puzzle consisting of a 5 × 5 grid

Most published puzzles are well-formed, meaning that only one unique solution exists. Such
puzzles are also called promise-problems (the promise being a unique solution).

Kakuro is very popular with jigsaw puzzles and often publishes in Israeli magazines and on the
last pages of weekly newspapers. At present, very little has been published specifically on
Kakuro and its related puzzles, however, their solution has been shown to be NP-Complete,
through demonstrating the relationship between the Hamiltonian Path Problem, 3SAT (the
restriction of the Boolean satisfiability problem) and Kakuro.

# Goal  
In this project, we tried to solve the problem of the Kakuro game using the genetic algorithm
and genetic programming and find out how much they will help us in cutting this problem.

Terminology

The size of the playing field (grid) - the number of rows and the number of columns.
White cells - cells of the playing field, which must be filled in with digits from 1 to 9.
Black cells - cells of the playing field which cannot be changed.
Clue cells - cells of the playing field that contain two numbers, the first number is the sum of
the elements of the group horizontally, the second number is the sum of the elements of the
group vertically.
Horizontal group - a continuous sequence of white cells horizontally.
Vertical group - a continuous sequence of white cells vertically.
Group sum - the sum of all elements of one group.
Duplicate values - elements that occur in the same group more than once.
GA light version algorithm with default parameters.
GA pro version - algorithm with optimal parameters obtained during the experiment.


