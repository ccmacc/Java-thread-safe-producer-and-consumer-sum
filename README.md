This program contains a Producer thread which initiates a variable too 100 and then sets a variable equal to the count of the loop numbe as it goes through a loop 5 times. The Consumer thread reads the varible from the Producer in a loop 5 times, sums the total, and writes the total to a file. Both the Producer and Consumer contain random sleeps in the for loops from 1 to 3 seconds. Sum is output to a file.

Purpose of the program is to demonstrate the non-predicatable order that threads will execute in Java
