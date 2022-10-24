1. `3`, because there are 3 loops in total in the for loop,
   in the first loop i starts with 0, and i++ make i to 1,
   in the second loop, i starts with 1 an i++ make i to 2.
   in the third loop, i starts with 2 and i++ make it to 3, and since the i is `var` type, it has the scope even if out of the loop block, therefore we will have `3` as result

2. `150`, because `disountedPrice` is a `var` type variable, so it can reach the line 13. and `disountedPrice` value will be updated in every for loop and finally the answer is the value in the last loop which is
   > 300*(1-0.5) = 150

3. `150`, because the finalprice is a `var` type variable and it will be updated everytime. Thus, it stores the last loop value which is 
   >round(150*100)/100
   which is 150

4. it will return an array of `[50,100,150]`. Since it returns dis and in line 9, we push the half of input value into the dis array. Thus, 50,100,150 is what we return.

5. error, becauses the `let` locked the variable `i` within the loop, outside the loop the variable `i` is not defined.

6. error, becauses the `let` locked the variable `discountedPrice` within the loop, outside the loop the variable `discountedPrice` is not defined.

7.  `150`, even though the finalprice is `let` type, it still in the block, and can find the variable and print it.

8.  it will return an array of `[50,100,150]`. Since it returns dis and in line 9, we push the half of input value into the dis array. Thus, 50,100,150 is what we return.

9.  error, becauses the `let` locked the variable `i` within the loop, outside the loop the variable `i` is not defined.
    
10. `3`, length is the lengthh of input `prices`, and the `const` type allows it still reachable in the line 12

11. it will return an array of `[50,100,150]`. Since it returns dis and in line 9, we push the half of input value into the dis array. Thus, 50,100,150 is what we return.

12. -A `student.name`
    -B `student["Grad Year"]`
    -C `student.greeting()`
    -D `student["Favorite Teacher"].name`
    -E `student.courseLoad[0]`

13. -A `'32'` If we add a number and a string, the result will be a string
    -B `1` there is no minus in string, so it will be converted to strings
    -C `3` null will be converted to 0 
    -D `'3null'` string add will append two strings, and null will be converted to "null"
    -E `4` true will be converted into 1 
    -F `1` false is converted to 0 and true is conerted to 1, and thus under addition, it will be 1
    -G `'3undefined'` similar to D, undefined is converted to a string when add it to a string.
    -H `NaN` the minus is not applicable to strings, and it cannot be converted to numbeers.

14. -A true ,because when compare strings and numbers, we will convert strings into numbers and it will be true.
    -B true ,because when compare strings and strings, we will convert strings into numbers and it will be true.
    -C true ,because when compare strings and strings, we will convert strings into numbers and it will be true.
    -D false ,=== operator compares the values as well as the data types of the operands, and the data types are different.
    -E false, because true equals 1 in value not 2
    -F true, Boolean(2) is bool type and since 2 is not zero, the Boolean(2) is true and true === true is true.
15. the == operator does the type conversion of the operands before comparison, whereas the === operator compares the values as well as the data types of the operands.

16.  in another file

17. the result is `[ 2,4,6 ]`, because the input callback is doSomething function, and the function will double the current elements in the input array and push to the nenw array
    in the forloop, we extract the ith element in the array [1,2,3] and then put the ith element to doSomething  function to double it.
    
18. in another file

19. 1432