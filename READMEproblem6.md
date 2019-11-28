# CS1290Exam2

# Problem 6 - Maximum Length of Pair Chain

1 & 2 - This problem can be solved recursively by first selecting the smallest b value among the set of (a,b) pairs. Then, we can remove that pair from the set and look for the pair with the smallest difference between b and and any other a in the set. We also need to consider the difference between a and b in each pair and take the minimum of those as well. We could use a viariable called diffa to keep track of the smallest difference found as we traverse each element of the set, and diffb to keep track of the smallest difference between a and b for each pair. Each time an optimal minimum is found, we could pass that pair to another set of pairs, called ans. After we traverse every valid pair in the set, we return the size of ans as the output.

3 - I used IDEAL by identifying the problem and considering what possible solutions could work for this problem in a general sense. I then refined these ideas using Duke's 7 steps. First, I made a random set of pairs with various values while keeping the constraints of the problem. Then, I noticed that I repeatedly analyzed the same pairs in the set while searching for the smallest difference. I then created larger arrays to test the general algorithm I created, and the outputs were what i expected them to be. Thus I concluded that my algorithm was working for this problem.
