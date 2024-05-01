# Part 2
1. Line 12 prints “3”. This is the value of the variable i. The variable i was declared with var so there is no scope issue, and it retains its value from the end of the for loop.
2. Line 13 prints “150”. This is the value of discountedPrice. The variable discountedPrice was declared with var so there is no scope issue, and it retains the last value that the variable was set to within the for loop.
3. Line 14 prints “150”. This is the value of finalPrice. The variable finalPrice was declared with var so there is no scope issue, and it retains the last value that the variable was set to within the for loop.
4. This function returns the list [50, 100, 150]. This is a list that contains all the discounted prices for each corresponding price from the prices parameter. It returns this list as the discounted array. Every variable was declared using var so there will be no scope issue.
5. Line 12 has an error. The variable i cannot be accessed outside of the code block because it was declared with let.
6. Line 13 has an error. The variable discountedPrice cannot be accessed outside of the code block because it was declared with let.
7. Line 14 prints “150”. This is the value of the variable finalPrice. The variable finalprice was declared with let but we are only accessing it within the code block so there is no scope issue, and it retains the last value that the variable was set to within the for loop.
8. This function returns the list [50, 100, 150]. This is a list that contains all the discounted prices for each corresponding price from the prices parameter. It returns this list as the discounted array. The variables were declared with let, but we are only accessing them within the code block in which they were declared so there is no scope issue.
9. Line 11 has an error. This is because we declared the variable i with let, and we are trying to access it outside of the code block in which it was declared.
10. Line 12 prints “3”. This is the value of the variable length, which is set to the length of the array with 3 elements that is passed to the function. We declared length with const, but never tried to change its value nor access it outside of its block-scope, so there is no error.
11. This function returns the list [50, 100, 150]. This is a list that contains all the discounted prices for each corresponding price from the prices parameter. It returns the list as the discounted array. The variables were declared with const but there is no scope issue because all variables were only accessed within their block-scope, and even though we pushed values to discounted, we never reassigned the variable, so there is no error.
12.
   A. student.name
   B. student[‘Grad Year’]
   C. student.greeting()
   D. student[‘Favorite Teacher’].name
   E. student.courseLoad[0]
14.
   A. Output: ‘32’ – This is because the first value is a string so JS treats the addition as string concatenation.
   B. Output: 1 – This is because for subtraction, JS treats the values including the string as integers and performs the numerical operation.
   C. Output: 3 – This is because for integer arithmetic, JS treats null as a 0, and then performs the numerical operation.
   D. Output: 3null – This is because once again the first value is a string so JS treats this as string concatenation.
   E. Output: 4 – This is because for booleans false is treated as 0 and true is treated as 1, and the booleans can be used as integers in arithmetic operations.
   F. Output: 0 – Like stated in E, the boolean false is treated as 0, and like stated in C, null is also treated as 0. When adding them like integers we get 0 + 0, which is 0.
   G. Output: 3undefined. This is because once again the first value is a string so JS treats this as string concatentation.
   H. Output: NaN. This is because for subtraction, JS tries to treat the values like integers and tries to subtract undefined (which doesn’t have a numerical equivalent) from 3, which is not a valid operation.
16.
   A. Output: true – This is because for inequalities between a string and number, JS treats the values as integers if possible, and 2 is greater than 1
   B. Output: false – This is because for string comparisons, JS compares in order based on their corresponding characters. The first character of ‘2’ is not less than the first character of ‘12’.
   C. Output: true – This is because the ‘==’ operator applies type coercion to the comparison, so we can compare the value of a number with the value of a numerical string.
   D. Output: false – This is because the ‘===’ is the string equality operator which takes into account both type and value.
   E. Output: false – This is because even with the ‘==’ operator applying type coercion to the comparison, we are then checking for equality between 1 (true) and 2.
   F. Output: true – This is because Boolean(2) is true because 2 is considered truthy. We are then comparing true with true which satisfies the string equality operation because both the type and value match.
18. The ‘==’ and ‘===’ operators both check for equality but in different ways. The ‘==’ operator compares equality after coercing the compared values to the same type, but the ‘===’ operator only returns true for values that are both equal in type and value.
19. Answer in part2-question16.js
20. The result of the function is the list [2, 4, 6]. When we call modifyArray([1,2,3], callback), we create a new array, newArray, and then each iteration of the forLoop adds a new value to newArray, that is the iteration’s respective value from the parameter array after going through the callback function, which corresponds to doSomething() which doubles the value.
21. Answer in part2-question18.js
22. 1
    4
    3
    2

