# test-randomizer
A shiny app to create blocks of ids randomly assigned into two groups within each block without replacement.

For example, from a population of 1000 ids, we need to select 10 random ids without replacement in each block. These ids will be randomly assigned to 2 groups.
Then, for the 2nd block, we need to randomly select 10 ids from the (1000-10) = 990 ids and randomly assigned to 2 groups.


ids = 1:1000
block 1: 
g1: [1, 3, 44, 55, 34]
g2: [4, 2, 123, 11, 15]

block 2:
g1: [23, 45, 31, 90, 98]
g2: [333, 456, 675, 555, 10]

















