1. Bug is that num1 and num2 are both string type variables, so the result doesn't add them as integers.
2. I would fix it by wrapping Number() around num1 and num2 to force the addition to be integer addition
