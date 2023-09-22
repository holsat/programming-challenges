# Euclid's Algorithm

[Euclid's Algorithm](https://en.wikipedia.org/wiki/Euclidean_algorithm), also known as the Euclidean Algorithm, is an efficient method for computing the greatest common divisor (GCD) of two numbers (the largest number that divides both of them without leaving a remainder).

Write an implementation of Euclid's Algorithm meeting the following requirements:

1. Write the implementation in your language of choice, or in psuedocode
2. The implementation should be a method or function
3. The implementation should accept two integers greater than zero as arguments
4. The implementation should return an integer greater than or equal to zero as a solution
5. Implement the following algorithm:
  1. Subtract the smaller of the two inputs from the larger until the result is *less than the smaller of the two inputs* or *zero*
  2. If the result is zero, return the smaller of the two inputs as the greatest common divisor (GCD)
  3. If the result is less than the smaller of the (original) two inputs, repeat the process with the smaller of the (original) two inputs and the result as the new inputs

Validate your implementation using the following test scenarios:

| Input 1 | Input 2 | Result  |
| ------ | ------ | -----: |
|  1071  |  462  |   21  |
|  242879  |  157157  |   14287  |
|  7919  |  919  |   1  |
|  761862  |  123  |   123  |

**Trivia:**  
If the solution for any two numbers is one, then those numbers are said to be [coprime](https://en.wikipedia.org/wiki/Coprime_integers) (share no common factors).
