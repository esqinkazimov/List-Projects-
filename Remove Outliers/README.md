When analysing data collected as part of a science experiment it may be desirable
to remove the most extreme values before performing other calculations. The
function takes a list of values and an non-negative integer, n, as its parameters.
The function creates a new copy of the list with the n largest elements and the
n smallest elements removed. Then it returns the new copy of the list as the
function’s only result. The order of the elements in the returned list does not
match the order of the elements in the original list.
The main program demonstrates function.The function reads
a list of numbers from the user and removes the two largest and two smallest values
from it. It displays the list with the outliers removed, followed by the original list. The
program generates an appropriate error message if the user enters less than 4
values.
