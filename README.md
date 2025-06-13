# Laser Dodger Game - Multi-Orb Edition

![Game Screenshot](./screenshot.png)

## Table of Contents
- [Description](#description)
- [Features](#features)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Controls](#controls)
- [Game Mechanics](#game-mechanics)
- [Development](#development)
- [Future Improvements](#future-improvements)

## Description

Laser Dodger is an exciting JavaFX-based arcade game where players control one or more orbs to dodge falling lasers. The multi-orb edition introduces the unique ability to spawn and control multiple orbs simultaneously, adding strategic depth to the classic dodging gameplay.

## Features

🎮 **Multiple Orb Control**: Spawn and control up to 5 orbs at once  
⚡ **Dynamic Laser System**: Randomly generated lasers falling at increasing speeds  
📊 **Score Tracking**: Earn points for each laser dodged  
❤️ **Life System**: Limited lives with game over condition  
📈 **Level Progression**: Difficulty increases as you progress  
🖥️ **Smooth JavaFX Animation**: Fluid 60FPS gameplay  
🔧 **Configurable Settings**: Easy to modify game parameters  

## How to Play

1. Launch the game
2. Use arrow keys to move all orbs left and right
3. Press 'A' to add new orbs (up to 5)
4. Dodge the falling lasers to earn points
5. Each hit removes one orb and reduces lives
6. Game ends when all orbs are destroyed or lives reach zero

## Installation

### Requirements
- Java 11 or higher
- Maven

### Steps
```bash
git clone https://github.com/yourusername/laser-dodger.git
cd laser-dodger
mvn clean package
java -jar target/laserdodger-1.0.jar
