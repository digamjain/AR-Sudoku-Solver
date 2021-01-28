# AR-Sudoku-Solver
My motive here is to create an Augmented Reality based sudoku solver.

## Progress
- I have used a backtracking based approach to solve the sudoku problem which can be seen in 'Sudoku_solver.ipynb' file which currently works on an hardcoded example.
- I created two ML models for digits detection first using Scikit libraries and second using Tensorflow libraries.
- 'digits.pkl' file is the training result of 'TrainingModel(scikit).ipynb' file and 't5_model.h5' file is the training result of 'TrainingModel(tf).ipynb'

## Current
Currently I'm working on extracting different cells of the sudoku problem to feed the images into to pretrained model which further can predict the number accurately. I'm using various different types of openCV transformation to get the best result possible and so as to make a more generalized program rather than an angle accurate one.

For test images I'm using  most different type of Images that can be captured in real time.
