# CS1290Exam2

# Problem 2 - Minimum Falling Path Sum
  
  1 & 2 - This problem can be solved recursively by traversing all possible falling paths through a square array of integers. First, begin with array[0][0], then determine the possible "under neighbors" for that entry, in this case, array[1][0] and array[1][1]. An "under neighbor" for array[i][j] is array[i+1][j-1], array[i+1][j] and array[i+1][j+1], assuming indices are valid. We can recursively trace paths through all under neighbors for all array entries, then we can use a variable to keep track of the sum of the values being visited, called sum, and another variable to keep track of the smallest sum visited so far, called smallest. Once all valid paths have been exhausted, we return smallest.
  
  3. I used IDEAL by identifying the problem and considering what possible solutions could work for this problem in a general sense. I then refined these ideas using Duke's 7 steps.
  First, I made a random array that obeyed the constraints of the problem, then traced each path through the array and found the minimum sum among all the possible paths.
  Then, I noticed that I was essentially doing the same operation multiple times throughout the entire solution, that is, I was finding the under neighbors for every entry and adding up their values.
  I then created a couple more 2-D  test arrays to which i applied my algorithm and found that the outputs were what i expected them to be. Thus I concluded that my algorithm was working for this problem.
