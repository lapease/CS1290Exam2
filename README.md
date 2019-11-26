# CS1290Exam2

#Problem 3 - Palindromic Substrings
1 & 2 - This problem can be solved recursively because we can use the same algorithm for different substrings of the same string. We know that the amount of substrings is at least the amount of characters in the strinjg, so we don't necessarily need to handle the base cases of each character being its own palindromic string. We could store this data in a variable called sum, then we see if the current string is a palindrome. If it is, then add 1 to sum. If not, then we use the same algorithm for the same string, but alternating between removing the first and last characters, beginning with the first. After reaching the base case of only 1 character left in the string, we return sum.

3. - 
