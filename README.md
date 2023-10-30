# Conway's Game of Life MATLAB
## Introduction
Welcome! This project recreates Conway's Game of Life using MATLAB. What is Conway's Game of Life you ask? Simply put, it is an autonomous game that only requires an initial input to start. It consists of a rectangular grid of cells where each cell can only exist in one two states: dead or alive. Each generation, or discreet step in time, a set of rules are applied to each cell to determine whether it should live or die. Let the simulation play out and you may see a beautiful interpretation of life at the cellular level.
## The Rules
Whether a cell lives to the next generation or dies is determined by the number of adjacent cells (neighbors) that are alive:
- If a live cell has less than 2 live neighbors, it dies (due to underpopulation)
- If a live cell has 2 or 3 live neighbors, it lives
- If a live cell has more than 3 live neighbors, it dies (due to overpopulation)
- If a dead cell has exactly 3 live neighbors, it comes to life (due to reproduction)
## Getting Started
To get started, download the repository to your computer. You will need to have MATLAB to access the file. Visit https://www.mathworks.com/products/matlab.html for more info. 
## Playing the Simulation
Once you have MATLAB installed and **game_of_life.mlx** opened, you can change the simulation settings found in lines 1-7. To start the simulation, simply press the *Start* button on line 9. You do not need to edit any other part of the script. 
## Setting the Initial Value
You can set the initial value of the grid one of two ways: randomly and manually.
## Randomly:
To set the initial value to a random grid of cells, type `randBoard()`  into line 7 right after `initBoard =`. The number in between the parenthesis will determine the probability that a given cell in the grid is alive. For example, if line 7 is: `initBoard = randBoard(30);`, then the initial value will be a random distribution of cells where about 30% of the cells are alive.
#### Manually:
To set the initial value manually, type `loadBoard()` into line 7 right after `initBoard =`. Before starting the simulation, you will need to open **initial_board.xlsx**. There should be a 50 by 50 grid of all zeroes. To edit the spreadsheet, simply enter 0 *or* 1 into a cell in the grid. The cell should turn white if you enter a 0 or black if you enter a 1. If you enter an invalid number or go outside the 50 by 50 grid, the cell will turn red to indicate an error. Please fix the mistake to ensure your grid is properly imported into MATLAB. Once you are done editing the grid, save the spreadsheet and close it before running the simulation on MATLAB.
## Documentation
The full documentation to this project can be found by visiting this OneDrive link: https://1drv.ms/p/s!AkXvFCPcPiFjhuFaUVi0JSJTwQIghQ?e=rGTEth
