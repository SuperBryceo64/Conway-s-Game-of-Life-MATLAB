# Conway's Game of Life MATLAB
## Introduction
Welcome! This project recreates Conway's Game of Life using MATLAB. What is Conway's Game of Life you ask? Simply put, it is an autonomous game that only requires an initial input to start. It consists of a rectangular grid of cells where each cell can only exist in one two states: dead or alive. Each generation, or discreet step in time, a set of rules are applied to each cell to determine whether it should live or die. Let the simulation play out and you may see a beautiful interpretation of life at the cellular level.
## The Rules
Whether a cell lives to the next generation or dies is determined by the number of adjacent cells (neighbors) that are alive:
- If a live cell has less than 2 live neighbors, it dies (due to underpopulation)
- If a live cell has 2 or 3 live neighbors, it lives
- If a live cell has more than 3 live neighbors, it dies (due to overpopulation)
- If a dead cell has exactly 3 live neighbors, it comes to life (due to reproduction)
