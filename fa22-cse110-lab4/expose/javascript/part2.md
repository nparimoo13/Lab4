1. 3, it prints out the value of i which is 3 after the loop has finished
2. 150, It's because the third element in the prices tuple is 300 and the last operation
   done to it is that it is multiplied by the discount (0.5) which is 150
3. 150, the final price is just the rounded version of the discounted price, which is just 150 again
   because it didn't need to be rounded.
4. Nothing was printed out into the console, because there was no messaged to be sent in the code via
   console.log
5. Error was given, this is because the variable i was defined with the word let, which binds its scope to the 
   for loop. It is put within a block scope
6. error, discountedPrices was defined with let, so it has block scope within
   the for loop and is not recognized outside of it.
7. returns the final price just like question 3 because it's still within the scope of the variable
8. A tuple of discounted final prices of the items, [50, 100, 150]
9. Error, gave an error because i was defined with let and is within the block scope of the for loop
10. 3, that's the length of prices
11. Returns the tuple of discounted prices, [50,100,150]
12. a. student.Name
    b. student.Grad Year
    c. student.greeting();
    d. student.Favorite Teacher.Thomas Powell
    e. student.courseLoad[0]
13. A. True, because of type conversion
    B. True, because of type conversion
    C. 3
    D. 3null
    E. 4, because the value of True is 1
    F. The value of false is 0 and the value is null no value
    G. 3undefined, they are both converted to string type
    H. Nan, Not A Number
14. A. True, 2 gets type converted to an integer and 2 > 1
    B. false, they get type converted to ints and 2 < 12
    C. True, because '2' gets type converted to an int
    D. False, It's strict equality so it doesn't type convert
    E. false, because 2 is an integer being compared to a boolean
    F. True, because the the value of true is 2

15. === is a strictly equal operation, == is a loose comparator
16. 
for (const [key, value] of statistic.entries(object)) {
  console.log(key, value);
}
17. It returns an array of [2,4,6] which is the array originally put in but just multiplied by 2

18. while(true)
{
    let d = new Date();
    let time = d.toLocaleTimeString();
    console.log(time);
}
19. 1
    4
    3
    2
