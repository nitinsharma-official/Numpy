# NumPy Practice

## About the Project
This repository contains my NumPy practice programs and hands-on exercises as part of my Python and Data Analysis learning journey.
The goal of this repository is to understand NumPy concepts and perform efficient numerical computations using Python.

## Technologies Used
* Python
* NumPy

## Topics Covered

### 1. NumPy Basics
* Introduction to NumPy
* Array creation using `np.array()`
* Array dimensions using `ndim`
* Array shape using `shape`
* Number of elements using `size`
* Data types using `dtype`

### 2. Array Indexing and Slicing
* Accessing array elements
* Selecting rows and columns
* Basic indexing
* Array slicing
* Extracting specific elements from arrays

### 3. Array Manipulation
* Adding rows using `np.vstack()`
* Adding columns using `np.hstack()`
* Combining arrays using `np.concatenate()`
* Deleting elements, rows, and columns using `np.delete()`
* Copying arrays using `copy()`

### 4. Mathematical Operations
* Addition, subtraction, multiplication, and division
* Calculating totals using `np.sum()`
* Calculating averages using `np.mean()`
* Finding maximum values using `np.max()`
* Finding minimum values using `np.min()`
* Standard deviation using `np.std()`

### 5. Sorting and Filtering
* Sorting arrays using `np.sort()`
* Sorting indices using `np.argsort()`
* Filtering elements using conditions
* Boolean indexing
* Using logical operators such as AND (`&`) and OR (`|`)

### 6. Missing Values Handling
* Detecting missing values using `np.isnan()`
* Finding missing value positions using `np.where()`
* Counting missing values
* Replacing missing values
* Creating cleaned copies of arrays

### 7. Practical Exercises
* Student marks analysis
* Total marks and percentage calculation
* Finding class toppers
* Sorting students by marks
* Sales data analysis
* Revenue calculation
* Filtering products based on ratings

## Installation
Install NumPy using pip:
pip install numpy

## Example
```python
import numpy as np
arr = np.array([10, 20, 30, 40, 50])
print("Array:", arr)
print("Shape:", arr.shape)
print("Size:", arr.size)
print("Dimensions:", arr.ndim)
print("Total:", np.sum(arr))
print("Average:", np.mean(arr))

## Learning Objectives
* Understand NumPy arrays and their properties.
* Perform numerical calculations efficiently.
* Learn array indexing, slicing, and manipulation.
* Apply sorting and filtering techniques.
* Handle missing values in datasets.
* Build a strong foundation for data analysis using Python.

## Repository Structure
:- text
NumPy-Practice/
│
├── numpy_basics.py
├── array_indexing_slicing.py
├── array_manipulation.py
├── mathematical_operations.py
├── sorting_filtering.py
├── missing_values.py
└── README.md

*Note: The file names above are suggested examples. Adjust the structure according to the actual files in your repository.*

## Future Improvements
* Practice more NumPy methods.
* Work with larger datasets.
* Explore advanced array operations.
* Use NumPy in real-world data analysis projects.

## Author
**Nitin Sharma**
This repository represents my learning journey in Python and NumPy, with a focus on building practical programming and data analysis skills.
If you find this repository useful, feel free to explore the code and practice the examples.
