# Tic Tac Toe Game

A simple Tic Tac Toe game implemented in C++ using the SFML library.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Gameplay](#gameplay)

## Introduction

This project is a basic implementation of the classic Tic Tac Toe game. It is built using C++ and the Simple and Fast Multimedia Library (SFML) for handling graphics and windowing.

## Features

- Two-player gameplay
- Simple graphical interface using SFML
- Reset functionality to start a new game
- Displays the winner or a draw

## Requirements

- C++ Compiler (GCC, Clang, MSVC, etc.)
- [SFML 2.5.1](https://www.sfml-dev.org/download.php) or higher

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Ali-Ch-001/Tic-Tac-Toe-sfml.git
    cd Tic-Tac-Toe-sfml
    ```

2. **Install SFML:**

    Follow the instructions on the [SFML download page](https://www.sfml-dev.org/download.php) to install SFML on your system.

3. **Build the project:**
   Create a make or compile manually

    ```bash
    mkdir build
    cd build
    cmake ..
    make
    ```

## Usage

After building the project, you can run the game executable:

```bash
./tic_tac_toe
 ```

## Gameplay

	•	The game is played on a 3x3 grid.
	•	Players take turns to place their marks (X or O) on the grid.
	•	The first player to get three of their marks in a row (vertically, horizontally, or diagonally) wins.
	•	If all 9 cells are filled and no player has three marks in a row, the game ends in a draw.
	•	Press the “R” key to reset the game and start a new round.

 ## Image 

![](https://github.com/Ali-Ch-001/Tic-Tac-Toe-sfml/assets/108975862/0ca7c555-206d-4bee-b2b5-9077949ec8dc)
