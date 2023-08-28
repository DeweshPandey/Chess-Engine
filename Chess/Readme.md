# ChessAI using Neural Networks
This is a chess AI that uses a neural network to evaluate the board state. The neural network is trained using a genetic algorithm. The AI is written in Python and the neural network is written in C++ using the Eigen library.

## Requirements
* Python 3
* C++ compiler
* Eigen library

## Usage
To run the AI, run the following command:
```
python main.py
```
To change the AI settings, edit the `settings.json` file.

## Settings
* `population_size`: The number of neural networks in each generation.
* `mutation_rate`: The probability that a weight in the neural network will be mutated.
* `mutation_range`: The range of the mutation.
* `crossover_rate`: The probability that two neural networks will be crossed over.
* `crossover_range`: The range of the crossover.
* `games_per_generation`: The number of games played by each neural network in each generation.
* `games_per_match`: The number of games played by each pair of neural networks in each generation.
* `games_per_thread`: The number of games played by each thread.
* `threads`: The number of threads used to play games.

## Neural Network
The neural network has 8 inputs and 1 output. The inputs are:
* `0`: The number of white pawns.
* `1`: The number of white knights.
* `2`: The number of white bishops.
* `3`: The number of white rooks.
* `4`: The number of white queens.
* `5`: The number of white kings.
* `6`: The number of black pawns.
* `7`: The number of black knights.
* `8`: The number of black bishops.
* `9`: The number of black rooks.
* `10`: The number of black queens.
* `11`: The number of black kings.

The output is a number between -1 and 1. A positive number means that the neural network thinks that white is winning and a negative number means that the neural network thinks that black is winning.

## Genetic Algorithm
The genetic algorithm works as follows:
1. Generate a population of neural networks.
2. Play games between all pairs of neural networks.
3. Sort the neural networks by their score.
4. Remove the worst neural networks.
5. Create new neural networks by crossing over the best neural networks.
6. Mutate the new neural networks.
7. Repeat from step 2 until the desired number of generations is reached.

## Example
Here is an example of a game played by the AI:
```
1. e4 e5
2. Nf3 Nc6
3. Bb5 a6
4. Ba4 Nf6
5. O-O Be7
6. Re1 b5
7. Bb3 d6
8. c3 O-O
9. h3 Na5
10. Bc2 c5
11. d4 Qc7
12. Nbd2 cxd4
13. cxd4 Nc6
14. Nb3 a5
15. Be3 a4
16. Nbd2 Bd7
17. Rc1 Qb7
18. Bb1 Rfc8
19. Nf1 Bd8
20. Ng3 Ba5
21. Re2 Bb6
22. Rd2 exd4
23. Nxd4 Nxd4
24. Rxc8+ Rxc8
25. Bxd4 Bxd4
26. Rxd4 Qc7
27. Ne2 Be6
28. Rxd6 Bc4
29. Ng3 Be6
30. Ne2 Bc4
31. Ng3 Be6
32. Ne2 Bc4

Draw by repetition
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
MIT License
ChessAI using Neural Networks

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute,
sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
```

## Acknowledgments
* [Chess](https://en.wikipedia.org/wiki/Chess)
* [Neural Network](https://en.wikipedia.org/wiki/Artificial_neural_network)
* [Genetic Algorithm](https://en.wikipedia.org/wiki/Genetic_algorithm)
* [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page)
* [Chess Programming Wiki](https://www.chessprogramming.org/Main_Page)
* [Chess Programming](https://www.chessprogramming.org/Main_Page)
* [Chess Programming Part I: Getting Started](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part II: Move Generation](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part III: Evaluation Functions](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part IV: Searching](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part V: Advanced Search](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part VI: Quiescence Search](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part VII: Alpha-Beta Pruning](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part VIII: Transposition Tables](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part IX: Move Ordering](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part X: Advanced Evaluation](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XI: Endgame Tables](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XII: Advanced Search](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XIII: Bitboards](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XIV: Bitboards Continued](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XV: Opening Books](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XVI: UCI Protocol](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XVII: Parallel Search](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XVIII: Conclusion](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XIX: Machine Learning](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XX: Reinforcement Learning](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XXI: Neural Networks](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XXII: Genetic Algorithms](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XXIII: Evolutionary Strategies](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)
* [Chess Programming Part XXIV: Conclusion](https://www.freecodecamp.org/news/simple-chess-ai-step-by-step-1d55a9266977/)

## Author
* **[Sergio Díaz-Rodríguez]()

## Contact
* **[Sergio Díaz-Rodríguez](https://www.linkedin.com/in/sergiodiazrodriguez/)**

## References
* **[Chess Programming Wiki](https://www.chessprogramming.org/Main_Page)**



