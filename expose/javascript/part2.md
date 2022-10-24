1. The code will print the number '3' since that is the value of i at once the loop is finished.
2. '150' will be printed because that is the last value stored in discountedPrice once the for loop ends.
3. '150' is also printed because that's the last value saved in finalPrice.
4. The code will return an array that contains all of the discounted prices that were calculated with the function.
5. Line 12 throws an error because the let declarer means the scope of i is in the for loop so it isn't defined outside of it.
6. Line 13 also throws an error because discountedPrice is declared inside the for loop.
7. Line 14 will print will print '150' because finalPrice is declared in its block.
8. The function will return an array that contains the discounted prices based on the input array and discount ratio.
9. Line 11 will return an error because i is defined in the scope of the for loop so it is not defined outside of it.
10. Line 12 will return '3' because that is the length of the input array.
11. The function will return an array that contains the discounted prices based on the input array and given discount ratio.
12. Objects
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. Arithmetic
    1. '32' since the int is converted into a string then concatenated
    2. 1 since the string is converted to an int when subtracting
    3. 3 since null is mapped to 0 as an int
    4. '3null' since null is mapped to the string 'null' when concatenating
    5. 4 since true is mapped to 1 when converted to an int
    6. 0 since both false and null get converted to 0 for addition
    7. '3undefined' because undefined is mapped to the string 'undefined' when concatenating
    8. NaN because undefined is not mapped to an int when subtracting
14. Comparison
    1. true since '2' gets converted to the int 2 which is greater than 1
    2. false since '2' appears after '12' in the dictionary so the comparison becomes false.
    3. true since the int 2 is equal to the string '2' when converted to an int
    4. This is false because the === means strictly equal so since these are different data types they are not equal.
    5. false since true is mapped to the int 1 which is not equal to 2.
    6. This is true because Boolean(2) is equal to the boolean true which is strictly equal to true.
15. == performs data conversions to compare the values of the two pieces of data, while === performs a strictly equal operation which keeps in mind the data type when comparing.
16. See part2-question16.js
17. The result will be an array with all the numbers multiplied by 2. This is because the function modifyArray iterates through all elements of the input array while running the callback function and putting all of its results in a new array which is then returned.
18. See part2-question18.js
19. 1, 4, and 3 will be printed immediately in that order, then 2 will be printed after 1 second.