# Multithread_Producer-Consumer
Here I implemented a multithread system to create a simulation of the classic producer-consumer system for a cost calculator.
The file received must have this format:

###########

500

1 1 4

2 2 12

3 1 100

4 3 45

...

#########

The first row must say the number of rows to be used from the file
The next rows will be a <id> <type> <time> row, where the id is only de identification of the product, the type is the machine to be used (the cost will be different for the different machines).
  
  All this, using a Queue system.
