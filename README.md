**NumPy Analyzer**

A menu-driven Python program built using NumPy that allows users to create arrays and perform various mathematical, array manipulation, searching, sorting, filtering, and statistical operations.

**📌 Features**

The NumPy Analyzer provides the following features:

**1. Create a NumPy Array**
Create 1D arrays
Create 2D arrays
Create 3D arrays
Display the created array

**2. Mathematical Operations**

Perform different mathematical operations on arrays:

Addition
Subtraction
Multiplication
Division
Dot Product
Matrix Multiplication
3. Combine or Split Arrays
Combine arrays using stacking operations
Split arrays into smaller arrays
4. Search, Sort, or Filter Arrays
Search for a specific value
Sort array elements row-wise
Filter array values based on a condition

**5. Aggregates and Statistics**

Calculate different statistical values:

Sum
Mean
Median
Standard Deviation
Variance
Minimum
Maximum
Percentiles
Correlation Coefficient

**6. Exit**

Exit the program with a thank-you message.

**🛠️ Technologies Used**
**Python 3**
**NumPy**

**📂 Project Structure**
NumPy-Analyzer/
│
├── numpy_analyzer.py
└── README.md


numpy_analyzer.py contains the main program, while README.md contains the project documentation.

**⚙️ Requirements**

Make sure Python 3 is installed on your system.

You also need to install NumPy.

**Install NumPy**
pip install numpy


If you are using Python 3 and pip does not work, try:

pip3 install numpy

**▶️ How to Run**

Clone or download the project and open the project directory in the terminal.

Run the program using:

python numpy_analyzer.py


Or:

python3 numpy_analyzer.py

**🖥️ Main Menu**

When the program starts, the following menu is displayed:

==========================================
      WELCOME TO THE NUMPY ANALYZER
==========================================

Choose an option:
1. Create a Numpy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit


The user can select an option according to the required operation.

**📊 Example**
**Creating a 2D Array**

Input:

10 20 50
30 60 40


Output:

Array created successfully:
[[10 20 50]
 [30 60 40]]

**Slicing**

Example sliced array:

[[20 50]
 [60 40]]

**Addition**

Original Array:

[[10 20 50]
 [30 60 40]]


Second Array:

[[5 5 5]
 [5 5 5]]


Result:

[[15 25 55]
 [35 65 45]]

**Combining Arrays**

Original Array:

[[10 20 50]
 [30 60 40]]


Second Array:

[[1 2 3]
 [4 5 6]]


Combined Array:

[[10 20 50]
 [30 60 40]
 [ 1  2  3]
 [ 4  5  6]]

**Sorting**

Original Array:

[[10 20 50]
 [30 60 40]]


Sorted Array:

[[10 20 50]
 [30 40 60]]


Sorting is applied row-wise.

**Median**

For the array:

[[10 20 50]
 [30 60 40]]


The median is:

35.0

**🎯 Objective**

The main objective of this project is to provide a simple, interactive way to understand and practice NumPy array operations in Python.

This project demonstrates concepts such as:

Array creation
Indexing
Slicing
Arithmetic operations
Array stacking and splitting
Searching
Sorting
Filtering
Statistical calculations
**📚 NumPy Concepts Demonstrated**

This project makes use of common NumPy functions and concepts such as:

np.array()
np.add()
np.subtract()
np.multiply()
np.divide()
np.dot()
np.matmul()
np.vstack()
np.hsplit()
np.where()
np.sort()
np.sum()
np.mean()
np.median()
np.std()
np.var()
np.min()
np.max()
np.percentile()
np.corrcoef()

**🚀 Future Improvements**

The project can be extended with additional features such as:

User-friendly input validation
Support for custom array shapes
More mathematical operations
Transpose and inverse of matrices
Reshaping arrays
Unique value detection
Saving arrays to files
Loading arrays from files
Graphical User Interface (GUI)
Better error handling
**👨‍💻 Author**

Your Name

**📄 License**

This project is created for educational and learning purposes.# PR.-8-Analyzer
