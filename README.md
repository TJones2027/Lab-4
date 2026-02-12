# Lab 04 - SOP/POS and KMaps
Tyler and Fernando Team 8
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

We learned how to ultize kmaps to find SOP and POS. Then using that we can implement it into verilog to make our boards respond with it.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
the map is a visual representation of a circle but it just looks flat

### Why are the names Sum of Products and Products of Sums?
sop uses or gates to combine products that are anded, while pos uses and gates to combine sums that are combined using or together

### Open the test.v file – how are we able to check that the signals match using XOR?
in the test file we can see that using an xor gate it checks the output of the verilog files to check the output and make sure its the same as expected

