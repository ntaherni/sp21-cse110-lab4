## Part 1a
var:
1. values added: 20
2. final result: 20
let: 
1. values added: 20
2. error, result is declared with a let inside the if block so it is only in the block-scope, here it is trying to access it outside of that if block.
const:
1. The code returns an error because result is declared as a const and we are trying to change it in line 7.
2. The code returns an error because result is declared as a const and we are trying to change it in line 7.

## Part 1b
1. It will return 3 because i is a var and it is 3 at the end of the for loop, the size of the array.
2. It will return 150 because discountedPrice is a var and the last price it was set to is 300 * 0.5, which is 150.
3. It will return 150 because finalPrice is a var and it was last set to be discountedPrice * 100 / 100 which is 150.
4. This function will return [50, 100, 150] in an array because it is the prices times a value of 0.5 which it calculates in the for loop.
5. It will give an error saying i is undefined because we declared i with a let declaration rather than a var declaration.
6. It will give an error because we define discountedPrice with let rather than with var so it is only accessable in the for loop.
7. It will return 150 because finalPrice is last set to 150 in the for loop.
8. This function will return [50, 100, 150] in an array because it is the prices times a value of 0.5 which it calculates in the for loop.
9. It will give an error saying i is undefined because we declared i with a let declaration rather than a var declaration.
10. It will return 3, the variable we defined as a constant, length, since the array we passed in is length 3.
11. It will return [50, 100, 150], because although the array is declared as const we can still push to it and the value for discountedPrice gets changed for every iteration of the for loop.
12. notations:
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting();
    4.  student["Favorite Teacher"].name
    5.  student.courseLoad[0]
13. Arithmetic:
    1.  ‘3’ + 2 = 32
    2.  ‘3’ - 2 = 1
    3.  3 + null = 3
    4.  '3’ + null = 3null
    5.  true + 3 = 4
    6.  false + null = 0
    7.  “3” + undefined = 3undefined
    8.  “3” - undefined = NaN
14. Comparison:
    1.  ‘2’ > 1 = true
    2.  ‘2’ < ‘12’ = false
    3.  2 == ‘2’ = true
    4.  2 === ‘2’ = false
    5.  true == 2 = false
    6.  true === Boolean(2) = true
15. == compares two variables without taking datatype into account, === also compares two variables but this one takes into account both value and datatype.
16. See file.
17. Line by line explanation:
    1.  Declaring function with parameters of an array and a function to perform calls with
    2.  Declaring a new array to push to
    3.  making a for loop for the size of the passed in array
    4.  pushing into the new array the value of the old array while passing it into the function that was passed in
    5.  bracket
    6.  returning the new array
    7.  bracket
    8.  break
    9.  declaring a function that takes in a number
    10. returns the number multiplied by 2
    11. bracket
    12. bracket
    13. calling the function with the multiplier function passed in and an array [1,2,3], this function will loop through the array, multiply each value by 2 using the doSomething function, then add it to the new array and return the new array. The array that it returns is [2,4,6].
18. See file.
19. 1
    4
    3
    2