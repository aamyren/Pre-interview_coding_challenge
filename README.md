# Pre-interview_coding_challenge
Pre-interview coding challenge

# Guidelines
Coding Challenge:
Using Python, construct a class without importing any modules given the following guidelines:

Given 2 inputs, data and shape, construct a tensor using nested lists.
A tensor a general term for n-dimension matrix. (order goes scalar, vector, matrix, tensor)
Data and shape inputs are given as lists of numbers. Data can be any number (int or float), but shape needs to be a list of positive integers.
Data and shape inputs can be lists of any length.
The constructed tensor can be saved as an instance variable, printed in standard output, or both.
If too many data numbers, cut it off after the tensor fills up. If not enough, pad the tensor w/ zeroes.
Output an empty list if the shape given is also an empty list ([])

# example 1
data0 =  [0, 1, 2, 3, 4, 5, 0.1, 0.2, -3]
shape0 = [2, 3, 2]
tensor0 = Tensor(data0, shape0)
# expected output: [[[0, 1],[2, 3],[4, 5]],[[0.1, 0.2],[-3, 0],[0, 0]]]
# example 1 output
Tensor.shape_data(tensor0)

# example 2
data1 = [0, 1, 2, 3, 4, 5, 0.1, 0.2, -3, -2, -1, 3, 2, 1]
shape1 = [5, 2]
tensor1 = Tensor(data1, shape1)
# expected output: [[0, 1], [2, 3], [4, 5], [0.1, 0.2], [-3, -2]]
# example 2 output
Tensor.shape_data(tensor1)
