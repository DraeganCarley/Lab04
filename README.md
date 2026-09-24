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

We learned how to program four switches to run our truth table to light LEDs. We programed our basic SOP in one file, minterms in one file and maxterms in another. This showed different ways to program our truth table to implement our design and get the same output.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
Because they represent a change in variable Like A or B which may be wrapped from one end to the other.

### Why are the names Sum of Products and Products of Sums?
Because it is determined by the wether we are using OR | (addition/sum) or AND & (multiplication/product) Sum of products is the OR of AND terms and Product of sums is the AND of OR terms.

### Open the test.v file – how are we able to check that the signals match using XOR?
By using opposite outputs than are expected.


