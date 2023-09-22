#Add Two Large Integers

Arithmetic instructions in all processors have a physical limit on the size and / or precision of the numbers that the operation can be performed against. Fortunately these limits can be overcome using software. Libraries for working with very large or very precise numbers exist for most languages, however, these libraries have not always been available.

Write a method or function to to add two large integers. The implementation should meet the following requirements:

1. Write the implementation in your language of choice, or in psuedocode
2. The implementation should be a method or function
3. The implementation should accept two large numbers as arguments, assume they are whatever data type you prefer.
4. The implementation should return the sum of the two integers passed as arguments
5. You may NOT use any libraries or native objects (for example, Java's BigInteger) that provide this functionality.

Validate your implementation using the following test scenarios:

| Input 1 | Input 2 | Result  |
| ------ | ------ | -----: |
|  4,294,967,295  |  4,294,967,295  |  8,589,934,590  |
|  5,392,139,375  |  12,429,147,123  |  17,821,286,498  |
|  20,125,744,073,782,551,120  |  89,739,241,051,127,892,191  |  109,864,985,124,910,443,311  |

**Trivia:**  
The physical limit on the size and / or precision of the numbers arithmetic instructions can operate on is typically the processor's word length.
