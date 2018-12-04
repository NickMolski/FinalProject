<h2>Random Number Generator!
<body>
This program is going to be slightly more difficult, but nothing you can't handle! In this tutorial, we are going to create a program that displays a random number 1-10.

Let's get started!

1) At the top of the Python Shell, click "File" and click on "New File". An untitled file should pop up. Before we do anything, we need to save the file. In the untitled file, go under "File", then "Save As...". Save the file wherever you would like and name it "RNG".

2) In the RNG file, we need to import the "random" module. To do this, type:
```
import random
```
Modules can be imported to be able to access code in other modules. In this case, we are importing the "random" module to gain access to the random function.

3) Once we have the random module imported, lets declare a variable. A variable is anything that can be called at anytime in the program. So, for instance, if x = 5, and you did x + 10, it would display 15. Let's begin by creating a variable for the random number we are generating.
```
import random
number =
```

4) Now this is where the random module comes into play. We are going to use this module to generate a random number by adding this to what you already have:
```
import random
number = random.randint
```

5) The added code above is going into the random module and grabbing randint to use in the program (randint = randominteger). If you tried running this, you probably got an error because we didn't put any paramters in! after the randint, we are going to add the parameters 1 and 10 (remember to put parenthesis!)
```
import random
number = random.randint(1,10)
```
The addition of (1,10) after randint is telling the random function to generate a random number 1 through 10. The first position (1) is the minimum number it generates, and the 2nd (10) is the maximum number it generates.

5) Now that we have a random number generated under the number variable, we have to print out that number. So, just like in the "Hello World" tutorial, we are going to use "print" but instead of using quotations, we are going to type in the variable name, in this case "number":
```
import random
number = random.randint(1,10)
print(number)
```

6) Now run the program! A random number 1-10 should pop up in the Python Shell!

Back to the README!
<br>
[README](README.md)
