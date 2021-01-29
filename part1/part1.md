1. The value of prices.length is returned because the for loop runs and increments i until it reaches the prices.length value. It is accessible at line 11 because it was declared using the var keyword.
2. The value of discountedPrice from the last for loop is printed because it is the last time that the variable was assigned a value. It is accessible at line 12 because it was declared using the var keyword.
3. Prints the finalPrice value from the last iteration of the for loop because it is the last time that the finalPrice variable was modified. If prices.length is 0, it will print 0.
4. Returns [50, 100, 150] because for each element of prices, a discounted price is calculated by multiplying the original price by (1-discount). The final price is the rounded version of the discounted price which is then pushed to the resulting array that is returned.
5. Error, no such variable because it is out of the scope of the for loop that declared it using the let keyword.
6. Error, no such variable because it is out of the scope of the for loop that declared it using the let keyword.
7. Prints the finalPrice value from the last iteration of the for loop because it is the last time that the finalPrice variable was modified. If prices.length is 0, it will print 0.
8. Returns [50, 100, 150] because for each element of prices, a discounted price is calculated by multiplying the original price by (1-discount). The final price is the rounded version of the discounted price which is then pushed to the resulting array that is returned.
9. Error, no such variable because it is out of the scope of the for loop that declared it using the let keyword.
10. Error, no such variable because it is out of the scope of the for loop that declared it using the const keyword.
11. 0 will be printed because it was declared using the const keyword so the changes from the for loop would cause an error but also would not change the finalPrice constant's value.
12. Returns [0, 0, 0] because finalPrice was declared using the const keyword so in each iteration of the for loop, line 7 does not update finalPrice's value and finalPrice is pushed in line 8 with its initial value of 0. So the array will fill with 0s and be returned.
13. 
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
14. 
    1.  '32' is outputted because JavaScript type casts 2 to a string to match '3' and performs string concatenation 
    2.  1 is outputted because a mathematical function was called so numeric conversion automatically happens to '3'.
    3.  3 because null has a 0 value after numeric conversion
    4.  '3null' beccause null has a value of 'null' after string conversion
    5.  4 because true has a 1 value after numeric conversion
    6.  0 because both false and null have 0 value after numeric conversion
    7.  3undefined because string conversion is applied through string concatenation
    8.  NaN because undefined has a NaN value after numeric conversion
15. 
    1.  true because string '2' becomes a number 2
    2.  false because the first character of '2' has a higher value than the first character of '12'
    3.  true because string '2' becomes a number 2
    4.  false because the === operator avoids type conversion
    5.  false because true has a numeric value of 1
    6.  true because Boolean(2) has a boolean value of true
16. === avoids type conversions while == applies type conversions
17. 'How are you?' is printed because 2 == true comes out to false and the boolean value of 2 is true so it enteres the else if statement and performs its code.
18. See part1-question18.js
19. [6, 8, 10] is returned. First newArr is declared, then the for loop is ran for the length of array. In each iteration, an element is pushed to newArr. This value is calculated by calling its callback function which in this case is doSomething() which adds 2 to num and calling callback once again which goes to the function defined in the for loop which multiplies the value by two. For example, the first element 1 is passed to doSomething which calles callback(1 + 2) which then multiplies it by 2 giving 6, the first element. At the end the resulting array is returned.
20. See part1-question20.js
21. 1
4
3
2
