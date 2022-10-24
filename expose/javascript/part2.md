1. The code prints 3 because prices has a length of 3 and the for loop iterates for its length.
2. The code prints 150 because that is the result of the product of the last element in prices (300) and 1-discount (1-0.5) which occurs on line 7.
3. The code prints 150 because finalPrice is just discountedPrice rounded to the nearest two decimal places.
4. The function return the list discounted which has the elements: 50, 100, 150. These values are all the values in prices multiplied by 1-discount.
5. The code returns an error because i is only initialized in the scope of the for loop with let.
6. The code returns an error because discountedPrice is only initialized in the scope of the for loop with let.
7. The code prints 150 because finalPrice is initialized with let within the scope of the broader function.
8. The function returns the same list as question 4 because discounted is initialized with let in the scope of the function.
9. The code returns an error because i is still initialized with let so it is not in the scope of the broader function.
10. The code returns 3 because that is what length is initialized to, it is in the scope of the broader function, and it is not changed.
11. The function returns the same list as question 4 and 8 because discounted is initialized in the scope of the function and as a const variable does not change.
12. A. student.name 
    B. student['Grad Year'] 
    C. student.greeting() 
    D. student['Favorite Teacher'].name 
    E. student.courseLoad[0]
13. A. '32', '3' is a string so 2 is mapped to a string and concatenated to the end of it.
    B. 1, because it is subtraction the string is mapped to an int and regular subtraction occurs.
    C. 3, null maps to 0 as an int.
    D. '3null', '3' is a string and null maps to the string 'null'. The + operation concatenates null to the end of '3'.
    E. 4, true maps to a value of 1.
    F. 0, Both false and null map to values of 0.
    G. '3undefined', '3' is a string and undefined maps to the string 'undefined'.
    H. NaN, undefined does not map to an undefined int value so it cannot do a subtraction operation.
14. A. true, the strings of integers map to the same values as the integers.
    B. false, for strings the string is compared character by character and '2' < '1' is not true.
    C. true, == uses type conversion and strings of integers map to the same values as the integers.
    D. false, === does not use type conversion so it is false because they have different types.
    E. false, true maps to the integer value of 1.
    F. true, Boolean(2) type converts the value to true and thus it is equivalent and the same type as well.
15. == type converts the variables and if they are equivalent after the conversion, the expression will return true. With ===, there is no type conversion and the variables must be the same type to be equivalent.
16. part2-question16.js
17. The result will be a new array with the values [2,4,6]. This is because the function is used to double each element in the array.
18. part2-question18.js
19. 1
    4
    3
    2
    
