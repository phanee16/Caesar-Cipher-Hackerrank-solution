# Caesar-Cipher-Hackerrank-solution

The Caesar Cipher problem is a classic encryption problem in which each letter in a given plaintext string is replaced by a letter some fixed number of positions down the alphabet. For example, with a shift of 3, A would be replaced by D, B would become E, and so on. The Caesar Cipher gets its name from Julius Caesar, who used it to communicate with his officials.

The problem requires the implementation of a function caesarCipher that takes three parameters: a string s to be encrypted, an integer k indicating the number of positions each letter is shifted, and a return string res containing the encrypted text.

The function should only encrypt alphabetic characters in s, leaving non-alphabetic characters unchanged. The encryption process should wrap around the end of the alphabet if a shift takes a letter beyond the letter 'z' (or 'Z' for capital letters). For example, with a shift of 3, the letter 'x' would become 'a'.

The task is to write an efficient function that encrypts the given plaintext string using the Caesar Cipher technique and returns the encrypted string.


The time complexity of the given code is O(n), where n is the length of the input string. This is because the code iterates over each character in the input string once, performs a constant amount of work on each character, and then returns the encrypted string.

The space complexity of the given code is also O(n). This is because the code creates a new string of the same length as the input string to store the encrypted string. The code also uses a constant amount of extra space for the variables n and k. Therefore, the total space required by the code is proportional to the length of the input string.
