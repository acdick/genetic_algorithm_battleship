DATA STRUCTURES AND ALGORITHMS
# Understanding Genetic Algorithms
SOLVING A BATTLESHIP BOARD GAME AS AN OPTIMIZATION PROBLEM

A genetic algorithm is a prime example of technology imitating nature to solve complex problems, in this case, by adopting the concept of natural selection in an evolutionary algorithm. Genetic algorithms, introduced in 1960 by John Holland, extend Alan Turing’s concept of a “learning machine” and are best-suited for solving optimization problems such as the traveling salesman.

To intuitively understand the practical implementation and fundamental requirements for employing genetic algorithms, we can set up a toy problem and solve the board of the classic guessing game, Battleship, first released by Milton Bradley in 1967. But rather than calling a sequence of individual shots, let’s ask our genetic algorithm to make a series of guesses of the entire board.

[Continue reading the full story curated by Towards Data Science, a Medium publication](https://towardsdatascience.com/understanding-genetic-algorithms-cd556e9089cb?source=friends_link&sk=70e5b098ef167ff2d1132396ab441030)

## Repository Contents

* [Project Features](#project-features)
* [Source Code](#source-code)
* [Output Results](#output-results)
* [Collaboration](#collaboration)

## Project Features
MACHINE LEARNING | OPTIMIZATION

## Source Code
PYTHON

**[The Battleship Module](/src/battleship.py)**
* Random Battleship board generator
* Genetic representation of the board
* Fitness function evaluator of candidate solution

**[The Genetic Algorithm Module](/src/genetic_algorithm.py)**
* Generator for an initial random generation
* Assignment of elite parents
* Selection of elite parents
* Creation of mutant descendents
* Creation of splice pair descendents
* Filling of generation with random descendents
* Creation of descendent generation
* Evaluation of fitness of generation

## Output Results
SEABORN

**[Featured Notebook](/src/genetic_algorithm_battleship.ipynb)**

![01 Board Solution](/img/01_Battleship_Board_Solution.png)
![02 Random Guess](/img/02_Battleship_Random_Guess_51.png)
![03 Random Accuracy](/img/03_Random_Accuracy_53.png)
![04 Generation 001](/img/04_Generation_001.png)
![05 Generation 002](/img/05_Generation_002.png)
![06 Generation 003](/img/06_Generation_155.png)
![07 Statistics 010](/img/07_Stats_10.png)
![08 Statistics 155](/img/08_Stats_155.png)
![09 Convergence](/img/09_Convergence.png)
![10 Performance](/img/10_Performance.png)

## Collaboration

**Contact:** Adam C Dick
* [Email](mailto:adam.c.dick@gmail.com)
* [LinkedIn](https://www.linkedin.com/in/adamcdick/)
* [Medium](https://medium.com/@adam.c.dick)
* [Scholar](https://scholar.google.com/citations?user=eMO88ogAAAAJ&hl=en)

**License**
* [MIT License](https://github.com/acdick/understanding_genetic_algorithms/blob/master/LICENSE)
