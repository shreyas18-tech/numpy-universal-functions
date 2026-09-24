# NumPy Vectors and Universal Functions

## Internship Project

This project completes the **Module 1 NumPy worksheet** focused on vectors, vector operations, matrix operations, inverse matrices, and NumPy universal functions (ufuncs).

## Objective

The worksheet demonstrates:

- Creating NumPy arrays
- Vector addition and subtraction
- Scalar multiplication
- Element-wise multiplication
- Vector/matrix multiplication using `np.dot()`
- Transpose operations
- Matrix inverse using `np.linalg.inv()`
- Performing three NumPy universal functions on `v1`

## Universal Functions Demonstrated

The final task uses three NumPy ufuncs on the 3×3 matrix `v1`:

### 1. `np.square(v1)`
Calculates the square of every element in `v1`.

### 2. `np.sqrt(v1)`
Calculates the square root of every element in `v1`.

### 3. `np.log(v1)`
Calculates the natural logarithm of every element in `v1`.

These functions operate element-by-element and demonstrate NumPy's vectorized numerical computation.

## Requirements

- Python 3.x
- NumPy
- Jupyter Notebook

## Installation

```bash
pip install -r requirements.txt
```

## Run the Project

Open the notebook using Jupyter:

```bash
jupyter notebook Module_1_worksheet_solved.ipynb
```

Then run the cells from top to bottom.

## Example `v1`

```python
v1 = np.array([1, 3, 5, 7, 11, 13, 17, 19, 23])
v1 = v1.reshape(3, 3)
```

## Technologies

- Python
- NumPy
- Jupyter Notebook

## Author

**Shreyas S Bhat**

B.E. Artificial Intelligence & Machine Learning  
Shri Madhwa Vadiraja Institute of Technology and Management (SMVITM)
