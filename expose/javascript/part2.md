1. prints out prices.length because i still exists because it was called by var
2. prints out prices[prices.length] * (1-discount) since i still exists and discountedPrice gets replaced each iteration in the for loop until it ends, so discountedPrice keeps the value of what it was on the final iteration
3. prints discountedPrice rounded down to the nearest hundredth, where discountedPrice is the answer given in question1
4. returns an array containing all the finalPrices for each of the prices given in the original prices array, and it works properly since after each iteration in the for loop, the new calculated finalPrice is saved into the array discounted
5. code will return an error, since i doesn't exist outside the for loop
6. code will return an error, since discountedPrice doesn't exist outside the for loop
7. prints out what question2 prints out, since finalPrice is created outside the for loop, and the console.log is called within the same code block
8. returns what question4 prints out, since each item in the array is saved in the for loop, and the array is within the function code block, so it still exists
9. code will return an error, since i doesn't exist out the for loop, but also because discounted is a const and can't be changed
10. code will return an error since discounted is a const and can't be changed, but if you could bypass it, it prints prices.length
11. function will have an error since discounted is a const and can't be changed, but if you could bypass it, it prints the empty array []
12. - a) student.name
    - b) student["Grad Year"]
    - c) alert(student.greeting)
    - d) student["Favorite Teacher"][name]
    - e) student.courseLoad[0]
13. - a) output is 32 since javascript changes the integer to string
    - b) output is 1 since javascript changes the string to integer
    - c) 3, null is converted to 0
    - d) 3null, converts null to the string "null"
    - e) 4, converts true to 1
    - f) 0, false is converted to 0, null is converted to 0, since we use + operator
    - g) 3undefined, converts undefined to the string "undefined"
    - h) NaN, subtraction uses integers, and undefined becomes NaN
14. - a) true, javascript converts the string 2 to the integer 2
    - b) false, checks first char in each string, and 2 is lexicographically larger than 1, so the comparison is false
    - c) true, "2" is converted into 2
    - d) false, strict equality, both are not the same data type
    - e) false, true is converted to 1, and 1!=2
    - f) true, Boolean(2) is converted to true, and true is strictly equal to true
15. == operator will convert both data left hand and right hand to equivalent data types, then compare the converted results. === operator doesn't convert the data types and strictly compares if the left is equal to the right as well as the same data type

