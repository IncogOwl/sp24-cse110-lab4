## Part 2
1. It will print out **3** as it is the number of elements and the last value of i. Since i was declared within the function scope, it is able to print out the last value of i in line 12.

2. It will print out **150** as it is the discounted price for the last item in the list, 300. Since it was the last value stored in discountedPrice after the loop ended and since discountedPrice was declared with var within the function, it can still be used and thus would return the last value stored within it. 

3. It will print out **150** as it is the final price for the list item 300. Since it was the last value stored in finalPrice after the loop ended and since finalPrice was declared with var within the function, it can still be used and thus would return the last value stored within it. 

4. It will return a list of the discounted prices based on the discount list. After calculating each of the discounted prices and appending it to a list, it returns the result as expected. The output would be: **[ 50, 100, 150 ]**.

5. It will return an error, particularly a reference error because the use of i is no longer in the scope of the loop body when we use the return statment as it is defined with the let keyword. Thus we get a error saying that i is not defined as it is now out of scope.

6. It will return an error because we use discountedPrice outside of its scope of the loop body. Since we defined discountedPrice within the loop body with the keyword let, it can only be referenced within the loop body. Thus when we try to reference it in the function body, we get a reference error.

7. It will return **150** as it was defined with the let keyword in the function body thus its last value can be used in the console.log function. Thus it will print out the last value stored in it which is **150**. 

8. It will return  **[ 50, 100, 150 ]** as it was defined using the let keyword within the function and not in any other specific body, thus it will return the output as expected by calculating the discounted price of each item and appending them into a list. 

9. It will return an error, particularly a reference error because the use of i is no longer in the scope of the loop body when we use the console.log() function as it is defined with the let keyword. Thus we get a error saying that i is not defined as it is now out of scope.

10. It will return **3** as it is the length of the prices list that was declared and intialized at the beginning of the function as the length of the price list is 3. Its value will not change during the runtime of the function, thus it will print the value **3**.

11. It will return **[ 50, 100, 150 ]**. It will generate the new discounted price for every price list item, since the const discountedPrice gets reintialized at every iteration of the loop, it is not being reassigned thus there is no error that is returned. Thus the function would run as expected by calculating each of the discounted prices and appending it to the discounted list and returning the output.

12.
  A. student.name

  B. student['Grad Year']
  
  C. student.greeting()
  
  D. student['Favorite Teacher'].name
  
  E. student.courseLoad[0]

13. 

A. 32.   

It gave this output because it converted the integer 2 into the string '2' because it took the string '3' to be the defining type and concatenated the '2' to it. 

B. 1

It gave this output because it converted the string '3' to be the numeric 3 because you're only able to subtract 3 and 2 and no string operation is possible here with the minus thus it subtracted the two numbers and returned 1.

C. 3

It returned this output because it converted the null to the integer value 0 thus it did 3+0 to return the value 3. 

D. 3null

It returned this output because it converted the null value to the string value 'null' and appended it to the string value '3' and returned 3null.

E. 4

It returned 4 because it converted the boolean value true to be 1 and then added it to 3 to give us 4. 

F. 0

It returned 0 because it converted the boolean value of false to be 0 and the null value to be 0 to return 0 + 0 =0. Thus 0 is returned.

G. 3undefined

It returned 3undefined because it converted the undefined value into a string 'undefined' and appended it to the string value '3' and returned 3undefined. 

H. NaN

It returns NaN because this operation doesn't return a valid number as it converted '3' into the numeric 3 and when subtracted by undefined which gets converted to the numeric value of NaN, it would return NaN.

14. 

A. true

It returned true because it converted the '2' into the number 2 and compared it leading to the true result. 

B. false

It returned false because it compared the two values lexicographically instead of numerically thus returning false.

C. true

It returned true because it converted '2' to 2 and then compared the two values numerically thus leading to the true response. 

D. false

It returned false because it compared the two values both for value and type of value and since 2 is numeric and '2' is a string, it would return false.

E. false

It returned false because it converted the true value into its numeric value of 1 and checked for equality with 2 and thus returned false.

F. true 

It returned true because it converted the integer value of 2 into its boolean value and since 2>0, it automatically converted it to the boolean value of true. It then checked for equality of class and value between true and true thus it returned the value true.

15. The == operator checks only for equality after automatically converting the required operands into the same class while the === operator checks for equaltiy of class and value of both operands without any automatic conversion of either operands.

16. In the file titled part2-question16.js

17. It will return **[2, 4, 6]**. When it runs through the modifyArray function, it creates the newArr array and when it enters the loop, we see the callback function reference the doSomething function for each array element, thus each value in array gets doubled and then appended to the newArr list which is then returned as **[2, 4, 6]**.

18. It is stored in part2-question18.js
19. The output is presented in this format:

1
4
3
2

The output comes in this format due to the setTimeout function. It prints 1 first and then since there is a time out set to the numbers 2 and 3, it has to wait. Since there is no timeout for console.log(4) thus it gets printed first followed by 3 as its timeout period would have ended followed later by 2 when its timeout period ends. Thus you get the output as above.
