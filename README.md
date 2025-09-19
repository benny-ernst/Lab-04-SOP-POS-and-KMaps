# Lab-04-SOP-POS-and-KMaps
# Group 46

# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

This week we applied what we learned about digital logic optimization and seeing a practical application of both sums of products and products of sums. We had some trouble with our logic, making a mistake on one of the lines, which in turn messed everything up and we had to look for it for 30 minutes. After that, everything went smoothly and we now understand the physical implementation of SOP and POS a lot better.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
K-Maps can be thought of like a cylinder where the wrap around once an "edge" is reached (both vertical and horizontal).

### Why are the names Sum of Products and Products of Sums?
Sum of Products takes the sum (OR) of all minterms (products, or AND) while Product of Sums takes the product (AND) of all maxterms (sums, or OR).

### Open the test.v file – how are we able to check that the signals match using XOR?
It checked whether the LED linked to naive and the LED linked to minterm/maxterm's values matched, and if they didn't, then it would output an error saying "Minterm/Maxterm output does not match".
