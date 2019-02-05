# Selection-Sort
Selection sort in C#

This code starts by reading the length of the array. 
i = 0
The beginning of the sort, the computer divides the sorted and unsorted parts of the array by placing a marker before the first number. To sort, the computer will repeatedly search the unsorted section for the smallest number. Then swap this number with the one before it. 

To find the next smaller number in the unsorted section, the computer must make comparisons. For example: (num1 < num2) and (num1 > num3), (num3 > num4) and (num4 < num5). After these comparisons, the computer knows which is the smaller number. Swapping the smaller of the two places and left. The computer will move on to the next number. 

This is less efficient sorting method because the code has to go through each number in order to get to the end. 

