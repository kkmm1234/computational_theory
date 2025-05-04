# Computational Theory
This repository contains implementations of some fundemental computational theory concepts. The project consists of eight tasks covering a range of topics from binary operations to Turing machines.

## Task Overview
1. Binary Representations: This task is a implementation of bit manipulation functions used in cryptographic algorithms
  - rotl(x, n=1): Rotates bits in a 32-bit unsigned integer left by n places
  - rotr(x, n=1): Rotates bits in a 32-bit unsigned integer right by n places
  - ch(x,y,z): Choose bits from y or z based on the corresponding bits in x
  - maj(x,y,z): Takes a majority vote of the bits in x, y, and z

2. Hash Functions - Implementation of a Kernighan and Ritche's string hasing function
  - Polynominal rolling hash function with 31 as base and 101 as modulus
  - Analysis of why these constants are effective

3. SHA-256 - Examining the padding mechanism in the SHA-256 hashing algorithm
  - Implementation of the standardised padding procedure as in FIPS180-4
  - Demonstration with example input "abc"

4. Prime Numbers - Two algorithms for calculating prime numbers
   - Sieve of Eratosthenes: Memory-efficient approach for finding n primes
   - Trial Division: Simple approach to finding n primes
   - Each used to retrieve the first 100 prime numbers

5. Square Root Fractional Parts - Calculating binary representations fo irrational numbers
   - Extracting the first 32 bits of the fractional part of square roots of the first 100 primes
   - Used on the first 100 prime numbers
   - Connection to cryptographic constants

6. Proof of Work - Finding the English words with the most leading zeros at the beginning of their SHA-256 hash digest
   - Demonstration of concepts behind cryptocurrency mining
  
7. Turing Machines - Implementation of a Turing Machine to add 1 to a binary number
   - Complete state transistion table for binary addition
   - Step by step simulation of the machines operation
   - Visual of tape changes during computation

8. Computational complexity - Analysis fo bubble sort algorithm
   - Implementation with comparison counting
   - Tested on all permutations of [1, 2, 3, 4, 5]

## Required files
In order to run this project you will need to add the following files:
- test.txt: this should contain the binary of the word you wish to input into the SHA-256 function for Task 3
- words.txt: this should contain a dictionary of words that will be used in the Proof of Work function for Task 6

## Cloning repo
Prerequisites
- Python 3.10 or higher
- All libraries used are Standard Libraries
- Clone repo: git clone https://github.com/kkmm1234/computational_theory
- Run: jupyter notebook tasks.ipynb
- Or execute through Visual Studio code using jupyter extensions selecting a kernal and running at the top of the workbook
