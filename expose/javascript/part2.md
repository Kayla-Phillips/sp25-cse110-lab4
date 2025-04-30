1. Line 12 will output 3 because that is the length of prices, when we would break out of the loop. Since i is declared using var, it has function scope and can be accessed outside of the loop.
2. Line 13 would output 150 since that is the discounted price in the last iteration of the loop. Since discountedPrice was declared using var, it can be accessed anywhere in the function.
3. Line 14 will output 150 because that was the last time the variable was updated.
4. The function will return [50, 100, 150] as that is the final list of discounted prices.
5. This line will cause an error because i is declared using let which means it has block scope and is not defined outside of the for loop.
6. This line will cause an error because discountedPrice is declared using let which means it has block scope and is not defined outside of the for loop.
7. Line 14 will output 150 because that was the last time the variable was updated. Since finalPrice was declared using let with function scope, we can access it inside and after the loop.
8. The function will return [50, 100, 150] as that is the final list of discounted prices and there shouldn't be any errors.
9. This line will cause an error because i is declared using let which means it has block scope and is not defined outside of the for loop.
10. Line 12 will output 3 as that is the length of prices. 
11. The function will return [50, 100, 150] as that is the final list of discounted prices and there shouldn't be any errors. A new discountedPrice is declared in each iteration and never being reassinged.
12. 
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. 
    A. '32' because the 2 will get converted into its equivalent string '2' and the two strings will get concatenated together. 
    B. 1 because the '3' will get converted into the integer 3 since minus is a numerical operation, so then subtract 2 from it to get 1. 
    C. 3 because null will get converted into 0 and 3 + 0 = 3.
    D. '3null' because null will get converted into ints string equivalent 'null' and then the strings will be concatenated together.
    E. 4 because true will get converted into its numerical value of 1 and they will get added  together to get 4.
    F. 0 becuase false and null both map to the numerical value of 0.
    G. '3undefined' because undefined will get converted to its string equivalent 'undefined' and the strings will get concatenated.
    H. NaN because minus is a numerical operation so '3' will get converted into 3 and undefined will get converted to NaN, which will give us NaN.
14. 
    A. true because '2' will be converted into the integer 2.
    B. false because they are both strings and 1 comes before 2 in lexographical order.
    C. true since '2' will get converted to the integer 2.
    D. false since there will be no type conversion and a string won't equal a number.
    E. false since true will get mapped to 1 and 1 doesn't equal 2.
    F. true since Boolean(2) will evaluate to true since 2 is non-zero.
15. With ==, type conversion will take place before comparing, whereas === is strict equality, so type conversion is not allowed.
16. Answer in part2-question16.js
17. The result will be [2,4,6]. IN the modifyArray function, we'll create a new array. Then for each element in the original list, we will call the callback function which will return the doubled number and that result will get pushed into the new array. Finally, the new array will get returned.
18.  Answer in part2-question18.js
19.  
    1
    4
    3
    2