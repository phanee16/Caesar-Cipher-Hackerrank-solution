# Caesar-Cipher-Hackerrank-solution

The Caesar Cipher problem is a classic encryption problem in which each letter in a given plaintext string is replaced by a letter some fixed number of positions down the alphabet. For example, with a shift of 3, A would be replaced by D, B would become E, and so on. The Caesar Cipher gets its name from Julius Caesar, who used it to communicate with his officials.

The problem requires the implementation of a function caesarCipher that takes three parameters: a string s to be encrypted, an integer k indicating the number of positions each letter is shifted, and a return string res containing the encrypted text.

The function should only encrypt alphabetic characters in s, leaving non-alphabetic characters unchanged. The encryption process should wrap around the end of the alphabet if a shift takes a letter beyond the letter 'z' (or 'Z' for capital letters). For example, with a shift of 3, the letter 'x' would become 'a'.

The task is to write an efficient function that encrypts the given plaintext string using the Caesar Cipher technique and returns the encrypted string.
