# NumPy Built-in Functions

## Array Creation Functions
- **`np.array()`** – Use this to create a NumPy array from a list or tuple.
- **`np.zeros()`** – Creates an array filled with zeros.
- **`np.ones()`** – Creates an array filled with ones.
- **`np.arange()`** – Creates an array with a range of numbers (like a list of numbers from 0 to 10).
- **`np.linspace()`** – Creates an array with evenly spaced numbers over a specified interval.
- **`np.eye()`** – Creates an identity matrix (a square matrix with ones on the diagonal and zeros elsewhere).
- **`np.full()`** – Creates an array filled with a specific value you choose.

## Random Functions
- **`np.random.rand()`** – Generates random numbers between 0 and 1 in a given shape (e.g., a 3x3 array of random numbers).
- **`np.random.randn()`** – Generates random numbers that follow a normal distribution (like flipping a coin multiple times).
- **`np.random.randint()`** – Generates random integers within a specified range (e.g., random numbers between 1 and 10).
- **`np.random.choice()`** – Selects random elements from a given array or list.
- **`np.random.shuffle()`** – Shuffles the elements of an array (think of it like mixing a deck of cards).

## Array Manipulation Functions
- **`np.reshape()`** – Changes the shape of an array (like turning a row of 6 numbers into a 2x3 matrix).
- **`np.ravel()`** – Flattens a multi-dimensional array into a single row.
- **`np.transpose()`** – Switches the rows and columns of a matrix (like flipping a table of data).
- **`np.vstack()`** – Stacks multiple arrays vertically (one on top of the other).
- **`np.hstack()`** – Stacks multiple arrays horizontally (side by side).

## Mathematical Functions
- **`np.add()`** – Adds two arrays element by element (e.g., adding corresponding elements in two lists).
- **`np.subtract()`** – Subtracts one array from another, element by element.
- **`np.multiply()`** – Multiplies two arrays element by element.
- **`np.divide()`** – Divides one array by another, element by element.
- **`np.exp()`** – Returns the exponential (e^x) of each element in the array.
- **`np.sqrt()`** – Takes the square root of each element.
- **`np.log()`** – Computes the natural logarithm (log base e).
- **`np.sin(), np.cos(), np.tan()`** – These functions calculate the sine, cosine, and tangent of each element, respectively.

## Statistical Functions
- **`np.mean()`** – Calculates the average of the numbers in an array.
- **`np.median()`** – Finds the middle value of an array when the numbers are ordered.
- **`np.std()`** – Measures how spread out the numbers are in the array (standard deviation).
- **`np.var()`** – Measures how much variance (or difference) exists in the array.
- **`np.min()`** – Finds the smallest number in the array.
- **`np.max()`** – Finds the largest number in the array.

## Linear Algebra Functions
- **`np.dot()`** – Calculates the dot product (a mathematical operation) of two arrays.
- **`np.linalg.det()`** – Finds the determinant of a matrix (used in solving systems of linear equations).
- **`np.linalg.inv()`** – Finds the inverse of a matrix.
- **`np.linalg.eig()`** – Finds the eigenvalues and eigenvectors of a matrix (important in fields like physics and machine learning).
- **`np.linalg.norm()`** – Computes the norm (or length) of a matrix.
