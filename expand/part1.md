# Part 1
Line 9 prints "values added: 20". We successfully print the sum of num1 and num2 by returning result. There is no scope issue because the variables are declared with var.
Line 13 prints “final result: 20”. We successfully print the sum of num1 and num2 again by returning result. There is no scope issue because the variables are declared with var.
Line 9 prints "values added: 20". We successfully print the sum of num1 and num2. We used the let keyword but we are within the code block’s scope so it is still successful.
Line 13 has an error. The variable result can’t be accessed outside of the code block because it was declared with let.
Line 9 has an error. The program tries to reassign the value of the variable result that was declared with const, which means its value cannot be changed.
Line 13 has an error. The program tries to reassign the value of the variable result that was declared with const, which means its value cannot be changed.

