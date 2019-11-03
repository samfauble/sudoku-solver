# sudoku-solver

## Overview
The Sudoku Solver takes an empty or partially-filled Sudoku board and produces a fully-finished, valid Sudoku board using a brute-force algorithm

## Technologies/Techniques used
- Racket
- Functional templating

## How the program was built
I started this project by doing an algorithmic analysis of how I could fill all the squares in a Sudoku puzzle with valid answers. Below is a summary of the steps that I took in the algorithm:

1. Determine whether the board was complete or not
2. If complete, then display the completed board
2. If not complete, then find the first empty square
3. Make a list of all boards with a valid answer for that square (that conform to the rules of Sudoku)
4. If there are no valid boards in the list, then produce false (meaning there is no possible solution)
5. If there are valid boards in the list, repeat the above steps for each of the boards in the list until either the boards are complete or there are no possible solutions

Given the nature of this project, I gained practice with the following:
- Doing domain analysis for algorithms
- arbitrary tree, iterative, and backtrack search data structures
- Unit testing

* This program was part of a class project I did on complex data structures, and I was given the Data Definition section seen at the top of the page

## How to run
It is only possible to run the tests for this project. However, if you wish to do so, you may:
1. Open the code in Dr.Racket
2. Press the "Run" button at the top of the page to run the tests
