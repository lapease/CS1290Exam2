# CS1290Exam2

# Problem 6 - Maximum Length of Pair Chain

1 & 2 - This problem can be solved recursively by first selecting the smallest b value among the set of (a,b) pairs. Then, we can remove that pair from the set and look for the pair with the smallest difference between b and and any other a in the set. We could use a viariable called dif to keep track of the smallest difference found as we traverse each element of the set. Each time a minimum is found, we could ass that pair to another set of pairs, called ans. After we traverse every valid pair in the set, we return the size of ans as the output.

