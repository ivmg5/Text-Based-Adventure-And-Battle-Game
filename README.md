# **Text-Based Adventure and Battle Game**
> *A dynamic text-based adventure game where players navigate worlds, encounter allies and enemies, and engage in battles.*

## **Introduction**
The Text-Based Adventure and Battle Game is a C++ project designed to offer an interactive story-driven experience. Players explore different worlds, interacting with various characters—some friendly, others combative—while managing health points and items to survive encounters. This project emphasizes object-oriented design, with a clear hierarchy of characters, items, and worlds that enhance gameplay.

## **Project Description**
- **Main functionality:** Engage in a text-based adventure where players interact with friendly characters and battle warriors in various worlds.
- **Technologies used:** 
  - C++ for core logic and object-oriented design.
  - Standard libraries for I/O and random number generation.
- **Challenges faced:** Managing complex character interactions, memory management for pointers, and ensuring game balance in health points and attack values.
- **Future improvements:** Expanding with more character types, adding special items, and developing more interactive game paths.

## **Table of Contents**
1. [Introduction](#introduction)
2. [Project Description](#project-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [License](#license)

## **Installation**
1. **Prerequisites**:
   - **g++** - [Installation page](https://gcc.gnu.org/install/)
   
2. **Clone the repository:**
   ```bash
   git clone https://github.com/ivmg5/Text-Based-Adventure-And-Battle-Game.git
   cd Text-Based-Adventure-And-Battle-Game
   ```

3. **Compile the program:**
   Use the `makefile` provided to compile all components.
   ```bash
   make
   ```

4. **Run the game:**
   Execute the compiled `exercise` file.
   ```bash
   ./exercise
   ```

### **Configuration Options**
- Customize item names, health points, and world names directly within the `.cpp` files or by extending classes as needed.

## **Usage**
To begin the game, execute the compiled binary and follow the on-screen instructions. Players are prompted to:
1. Choose a character name.
2. Start interactions in different worlds by typing `c` to continue or `s` to advance.

**Example usage:**
```cpp
Personaje* p1 = new Guerrero("Noe", "Warrior", 100, 100, 10);
p1->imprime();
```

## **License**
This project is licensed under the MIT License.

[![Build Status](https://img.shields.io/badge/status-active-brightgreen)](#)
[![Code Coverage](https://img.shields.io/badge/coverage-80%25-yellowgreen)](#)
