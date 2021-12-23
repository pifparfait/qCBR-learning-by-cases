# qCBR-learning-by-cases
A supervised classifier can be interpreted as a program capable of predicting the output of input from the labelled data. From the input data and the label, with known examples, we will be able to, which will be the label given new input.  The main idea of quantum Case-Based Reasoning (qCBR) is to interpret the statement of the problem as an input and the solution to the problem as an output. Therefore, if we have a series of situations with their outcomes, we can train our classifier to determine its solution given a new problem.

The directory structure is as follows:
With this file: Brute_Force_Maxcut.ipynb, we generate a problem statement. If the user wanted to modify some parameters, he should execute the said file, and it would generate two files (qCBR_input.npy and qCBR_output.npy) that are the statements of our problem.
qCBR_input.npy is our input problem.
qCBR_output.npy is the solution to the known problem.
qCBR.ipynb is the notebook that implements the quantum Case-Based Reasoning algorithm.
