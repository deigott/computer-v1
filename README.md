# Computor v1 Math Project
Computer-v1 is a program that solves polynomial second or lower degree equations


<img src="https://wallpapercave.com/wp/wp2790127.jpg" width="1000">

## Introduction
Welcome to my Computor v1 math project repository! In this project, I've developed a Python program that solves polynomial equations of the second degree or lower. This project allowed me to explore mathematical problem-solving through programming and apply algebraic concepts practically.

## Project Summary
The Computor v1 project focuses on creating an equation-solving program to handle polynomial equations. The program calculates the reduced form of the equation, its degree, and the solutions. The project aims to reinforce mathematical skills and demonstrate their application in a programming context.

## Table of Contents
- [Introduction](#introduction)
- [Project Summary](#project-summary)
- [How to Run](#how-to-run)
- [Example Usage](#example-usage)
- [Folder Structure](#folder-structure)
- [Mandatory Part](#mandatory-part)
- [Bonus Part](#bonus-part)


## How to Run
1. Ensure you have Python 3 installed on your system.
2. Clone this repository to your local machine using:
```bash git clone <repository-url>```
3. Navigate to the repository's directory: ```cd computor-v1```
4. Run the Computor v1 program by providing an equation as a command-line argument.

## Example Usage
### Input

```bash
python computor.py "5 * X^0 + 4 * X^1 - 9.3 * X^2 = 1 * X^0"
```

### Output

```bash
Reduced form: 4.0 * X^0 + 4.0 * X^1 - 9.3 * X^2 = 0
Polynomial degree: 2
Discriminant is strictly positive, the two solutions are:
X1 = -4.7106
X2 = 0.9052
```
## Folder Structure
The repository's structure is organized as follows:

```
computor-v1/
├── computor  # Main Python script
└── README.md # Project README
```
## Mandatory Part
The program reads and parses the input equation, calculates its reduced form, determines the equation's degree, and solves it. It handles linear and quadratic equations, displaying solutions accordingly.

## Bonus Part
For the bonus section, I added features to manage entry mistakes, handle free-form entries, display solutions as irreducible fractions when possible, and show intermediate steps in the equation-solving process.
