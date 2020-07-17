## My Projects

### [Sketch to Color](./sketch-to-color) 

Sketch to Color Image generation is an image-to-image translation model using Conditional Generative Adversarial Networks as described in the original paper by Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros 2016, Image-to-Image Translation with Conditional Adversarial Networks.

The model was trained on the Anime Sketch-Colorization Pair Dataset available on Kaggle which contains 14.2k pairs of Sketch-Color Anime Images. The training of the model was done for 150 epochs which took approximately 23 hours on a single GeForce GTX 1060 6GB Graphic Card and 16 GB RAM.

### [Sudoku Solver](./sudoku-solver)

This is a project which takes an input of the sudoku puzzles as an 81 characters long string containing the digits from 0 to 9, where 0 represents an unfilled cell of the Sudoku Board. The objective of the algorithm is to replace all the zeros with valid digits such that the entire Sudoku Puzzle is solved. For doing this in a conventional way, the processor will require to try all 2*1077 possible combinations in a worst case scenario which is a huge number. So, to solve this problem in a comparatively less time, the Backtracking Algorithm is one of the best solutions to it.
