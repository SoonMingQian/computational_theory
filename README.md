# Computational Theory

This repository provides practical implementations of fundamental computational theory concepts, showcasing how theoretical computer science principles translate into working code. Designed for students, educators, and researchers studying algorithmic foundations.

## Project Overview
Computational theory forms the mathematical backbone of computer science, addressing questions about what problems can be solved algorithmically and how efficiently. This repository bridges theory and practice by implementing key concepts including:

- Bitwise operations and binary manipulations
- Hash function design and analysis
- Cryptographic fundamentals (SHA-256)
- Prime number generation algorithms
- Turing machine simulations
- Algorithm complexity analysis

Each implementation includes detailed explanations, visualizations, and performance metrics to deepen understanding.

## Contents

This repository includes implementations of:

- **Binary Operations**: Bit rotation, choice functions, and majority voting
- **Hash Functions**: Simple hash implementations and collision analysis
- **SHA-256**: Padding scheme implementation with detailed explanations
- **Prime Numbers**: Trial division and Sieve of Eratosthenes algorithms
- **Binary Representations**: Calculation of square roots in binary
- **Proof of Work**: Finding optimal inputs for cryptographic puzzles
- **Turing Machines**: Simulation of binary addition on Turing machines
- **Algorithm Analysis**: Bubble sort with comprehensive complexity analysis

## Repository Structure

computational_theory/

- tasks.ipynb        # Main Jupyter notebook with all implementations
- requirements.txt   # Required packages
- README.md          # This documentation file
- words.txt          # Dictionary file for proof-of-work task

## Requirements

The following libraries are required to run the notebooks:
- matplotlib
- numpy
- hashlib (part of Python standard library)
- math (part of Python standard library)
- random (part of Python standard library)
- string (part of Python standard library)

## Setup and Installation

```bash
# Clone the repository
git clone [repository URL]
cd computational_theory

# Install required packages using requirements.txt
pip install -r requirements.txt
```

## Usage

### Running the Jupyter Notebook

```bash
# Start Jupyter Notebook
jupyter notebook

# Open tasks.ipynb in the browser interface
```

### Example: Binary Operations

```python
# Example of left rotation operation
x = 5
result = rotl(x)
print(format(result, '032b'))  # Output: 00000000000000000000000000001010
```

### Example: Finding Prime Numbers

```python
# Find the first 10 prime numbers using the Sieve of Eratosthenes
primes = sieve_of_eratosthenes(30)[:10]
print(primes)  # Output: [2, 3, 5, 7, 11, 13, 17, 19, 23, 29]
```

## Testing

Each implementation includes test cases and examples demonstrating correct functionality. The visualizations provide empirical validation for many of the algorithms.

## Learning Resources
- [FIPS 180-4 - Secure Hash Standard (SHS)](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)
- [The C Programming Language](https://en.wikipedia.org/wiki/The_C_Programming_Language) - Kernighan & Ritchie's classic text
- [On Computable Numbers](https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf) - Turing's original paper

## Requirements Verification

This repository satisfies the assessment requirements by:

- Implementing all 8 required tasks (Binary Operations, Hash Functions, etc.)
- Including detailed explanations of each algorithm
- Providing test cases and visualizations for verification
- Documenting code with comments and markdown explanations

## Author 
Ming Qian Soon
