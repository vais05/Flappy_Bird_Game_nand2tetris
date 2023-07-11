# Flappy_Bird_Game_nand2tetris

This project is an implementation of the popular Flappy Bird game using the Nand2Tetris framework. 
It provides a complete game experience with graphics and user interaction.

 Table of Contents
 
  -Introduction
  
  -Installation
  
  -Usage
  
  -Project Structure
  
  -Contributing
  
  -License


 Introduction
 
The Flappy Bird game in Nand2Tetris is a fun and challenging game where the player controls a bird trying to navigate through a series of pipes.
The objective is to avoid colliding with the pipes and achieve the highest score possible.

The game is implemented using the Nand2Tetris framework, which provides a set of virtual machine (VM) files and high-level Jack language files
to build a complete computer system from scratch.



Installation

To run the Flappy Bird game, you need to have the Nand2Tetris software suite installed on your computer. Follow these steps to set up the environment:

Download the Nand2Tetris software suite from the official website (http://www.nand2tetris.org/software/nand2tetris.zip).
Extract the contents of the downloaded ZIP file to a directory of your choice.
Navigate to the directory where you extracted the files.


Usage

To run the Flappy Bird game, follow these steps:

 1)Open the Nand2Tetris software suite and navigate to the project's root directory.
 
 2)Copy the provided VM files and Jack files for the Flappy Bird game into the project's directory.
 
 3)Open the Nand2Tetris Hardware Simulator.
 
 4)Load the provided .hdl files into the simulator to initialize the hardware components.
 
 5)Load the Flappy Bird VM files into the simulator.
 
 6)Click the "Load Program" button in the simulator and select the main VM file to load the game.
 
 7)Start the simulation by clicking the "Run" button.
 
 8)Enjoy playing the Flappy Bird game! Use the appropriate keys or controls specified in the game to control the bird.
 


Project Structure

The project structure is organized as follows:


 ├── FlappyBird.jack       # Main Jack file for the Flappy Bird game
 
 ├── Game.jack             # Game logic implementation
 
 ├── Bird.jack             # Bird class implementation
 
 ├── Pipe.jack             # Pipe class implementation
 
 ├── Assets                # Directory containing game assets (images, sounds, etc.)
 
 └── README.md             # Project README file

The project consists of the main Jack file FlappyBird.jack, along with several other files that implement the game logic, bird behavior, and pipe mechanics. 
The Assets directory contains any additional assets required by the game.



Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvement, please submit them as GitHub issues in this repository.
Feel free to fork the repository and submit pull requests with your changes.


License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.
