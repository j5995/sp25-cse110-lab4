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
    - d) student["Favorite Teacher".name]
