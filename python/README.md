# Practice Assessment Exam &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                   [50 Marks]

### **Question: 1**

> **_Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5,
> between 2000 and 3200 (both included).The numbers obtained should be printed in a comma-separated sequence on a single line._**
---
### **Question: 2**

> **_Write a program which can compute the factorial of a given numbers.The results should be printed in a comma-separated sequence on a single line.Suppose the following input is supplied to the program: 8
> Then, the output should be:40320_**

---

### **Question: 3**

> **_With a given integral number n, write a program to generate a dictionary that contains (i, i x i) such that is an integral number between 1 and n (both included). and then the program should print the dictionary.Suppose the following input is supplied to the program: 8_**

> **_Then, the output should be:_**

{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}

---

### **Question: 4**

> **_Write a program which accepts a sequence of comma-separated numbers from console and generate a list and a tuple which contains every number.Suppose the following input is supplied to the program:_**


34,67,55,33,12,98


> **_Then, the output should be:_**


['34', '67', '55', '33', '12', '98']
('34', '67', '55', '33', '12', '98')

---

### **Question: 5**

> **_Define a class which has at least two methods:_**
>
> - **_getString: to get a string from console input_**
> - **_printString: to print the string in upper case._**

> **_Also please include simple test function to test the class methods._**

### Hints:

> **_Use **init** method to construct some parameters_**

---

### **Question: 6**

> **_Write a program that calculates and prints the value according to the given formula:_**

> **_Q = Square root of [(2CD)/H]_**

> **_Following are the fixed values of C and H:_**

> **_C is 50. H is 30._**

> **_D is the variable whose values should be input to your program in a comma-separated sequence.For example
> Let us assume the following comma separated input sequence is given to the program:_**

100,150,180

> **_The output of the program should be:_**

18,22,24

---

### **Question: 7**

> **_Write a program which takes 2 digits, X,Y as input and generates a 2-dimensional array. The element value in the i-th row and j-th column of the array should be i _ j.\***

> **_Note: i=0,1.., X-1; j=0,1,¡­Y-1. Suppose the following inputs are given to the program: 3,5_**

> **_Then, the output of the program should be:_**


[[0, 0, 0, 0, 0], [0, 1, 2, 3, 4], [0, 2, 4, 6, 8]]

---

### **Question: 8**

> **_Write a program that accepts a comma separated sequence of words as input and prints the words in a comma-separated sequence after sorting them alphabetically._**

> **_Suppose the following input is supplied to the program:_**

without,hello,bag,world

> **_Then, the output should be:_**

bag,hello,without,world

---

### **Question: 9**

> **_Write a program that accepts sequence of lines as input and prints the lines after making all characters in the sentence capitalized._**

> **_Suppose the following input is supplied to the program:_**

Hello world

Practice makes perfect

> **_Then, the output should be:_**

HELLO WORLD

PRACTICE MAKES PERFECT

---

### **Question: 10**

> **_Write a program that accepts a sequence of whitespace separated words as input and prints the words after removing all duplicate words and sorting them alphanumerically._**

> **_Suppose the following input is supplied to the program:_**

hello world and practice makes perfect and hello world again

> **_Then, the output should be:_**

again and hello makes perfect practice world

---

### Hints:

> **_In case of input data being supplied to the question, it should be assumed to be a console input.We use set container to remove duplicated data automatically and then use sorted() to sort the data._**

---

### **Question: 11**

> **_Write a program which accepts a sequence of comma separated 4 digit binary numbers as its input and then check whether they are divisible by 5 or not. The numbers that are divisible by 5 are to be printed in a comma separated sequence._**

> **_Example:_**

0100,0011,1010,1001

> **_Then the output should be:_**

1010

> **_Notes: Assume the data is input by console._**

### Hints:

> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---


### **Question: 12**

> **_Write a program, which will find all such numbers between 1000 and 3000 (both included) such that each digit of the number is an even number.The numbers obtained should be printed in a comma-separated sequence on a single line._**

---

### **Question: 13**

> **_Write a program that accepts a sentence and calculate the number of letters and digits._**

> **_Suppose the following input is supplied to the program:_**

hello world! 123

> **_Then, the output should be:_**

LETTERS 10

DIGITS 3

---

### **Question: 14**

> **_Write a program that accepts a sentence and calculate the number of upper case letters and lower case letters._**

> **_Suppose the following input is supplied to the program:_**


Hello world!


> **_Then, the output should be:_**


UPPER CASE 1

LOWER CASE 9

---

### **Question: 15**

> **_Write a program that computes the value of a+aa+aaa+aaaa with a given digit as the value of a._**

> **_Suppose the following input is supplied to the program:_**

9

> **_Then, the output should be:_**


11106

---

### **Question: 16**

> **_Use a list comprehension to square each odd number in a list. The list is input by a sequence of comma-separated numbers._** >**_Suppose the following input is supplied to the program:_**

1,2,3,4,5,6,7,8,9

> **_Then, the output should be:_**

1,9,25,49,81

---

### **Question: 17**

> **_Write a program that computes the net amount of a bank account based a transaction log from console input. The transaction log format is shown as following:_**

```
D 100
W 200
```

- D means deposit while W means withdrawal.

> **_Suppose the following input is supplied to the program:_**

```
D 300
D 300
W 200
D 100
```

> **_Then, the output should be:_**

```
500
```

---

### **Question: 18**

> **_A website requires the users to input username and password to register. Write a program to check the validity of password input by users._**

> **_Following are the criteria for checking the password:_**

- **_At least 1 letter between [a-z]_**
- **_At least 1 number between [0-9]_**
- **_At least 1 letter between [A-Z]_**
- **_At least 1 character from [$#@]_**
- **_Minimum length of transaction password: 6_**
- **_Maximum length of transaction password: 12_**

> **_Your program should accept a sequence of comma separated passwords and will check them according to the above criteria. Passwords that match the criteria are to be printed, each separated by a comma._**

> **_Example_**

> **_If the following passwords are given as input to the program:_**


ABd1234@1,a F1#,2w3E*,2We3345


> **_Then, the output of the program should be:_**


ABd1234@1


---

### **Question: 19**

> **_You are required to write a program to sort the (name, age, score) tuples by ascending order where name is string, age and score are numbers. The tuples are input by console. The sort criteria is:_**

- **_1: Sort based on name_**
- **_2: Then sort based on age_**
- **_3: Then sort by score_**

> **_The priority is that name > age > score._**

> **_If the following tuples are given as input to the program:_**


Tom,19,80

John,20,90

Jony,17,91

Jony,17,93

Json,21,85


> **_Then, the output of the program should be:_**


[('John', '20', '90'), ('Jony', '17', '91'), ('Jony', '17', '93'), ('Json', '21', '85'), ('Tom', '19', '80')]


---

### **Question: 20**

> **_Define a class with a generator which can iterate the numbers, which are divisible by 7, between a given range 0 and n._**

---

### **Question: 21**

> **_A robot moves in a plane starting from the original point (0,0). The robot can move toward UP, DOWN, LEFT and RIGHT with a given steps. The trace of robot movement is shown as the following:_**

```
UP 5
DOWN 3
LEFT 3
RIGHT 2
```
> **_The numbers after the direction are steps. Please write a program to compute the distance from current position after a sequence of movement and original point. If the distance is a float, then just print the nearest integer._**
> **_Example:_**
> **_If the following tuples are given as input to the program:_**

```
UP 5
DOWN 3
LEFT 3
RIGHT 2
```

> **_Then, the output of the program should be:_**

```
2
```
---

### **Question: 22**

> **_Write a program to compute the frequency of the words from the input. The output should output after sorting the key alphanumerically._**

> **_Suppose the following input is supplied to the program:_**


New to Python or choosing between Python 2 and Python 3? Read Python 2 or Python 3.


> **_Then, the output should be:_**

```
2:2
3.:1
3?:1
New:1
Python:5
Read:1
and:1
between:1
choosing:1
or:2
to:1
```

---

### **Question: 23**

> **_Write a method which can calculate square value of number_**

---

### **Question: 24**

> **_Python has many built-in functions, and if you do not know how to use it, you can read document online or find some books. But Python has a built-in document function for every built-in functions._**

> **_Please write a program to print some Python built-in functions documents, such as abs(), int(), raw_input()_**

> **_And add document for your own function_**

### Hints: The built-in document method is __doc__


---

### **Question: 25**

> **_Define a class, which have a class parameter and have a same instance parameter._**

---

### Hints:
Define an instance parameter, need add it in __init__ method.You can init an object with construct parameter or set the value later

---

### **Question: 26**
> **_Define a function which can compute the sum of two numbers._**

### Hints:

> **_Define a function with two numbers as arguments. You can compute the sum in the function and return the value._**

---

### **Question: 27**

> **_Define a function that can convert a integer into a string and print it in console._**

---

### Hints:

> **_Use str() to convert a number to string._**

---
### **Question: 28**

> **_Define a function that can receive two integer numbers in string form and compute their sum and then print it in console._**

---

### Hints:

> **_Use int() to convert a string to integer._**

---

### **Question: 29**

> **_Define a function that can accept two strings as input and concatenate them and then print it in console._**

---

### Hints:

> **_Use + sign to concatenate the strings._**

---

### **Question: 30**

> **_Define a function that can accept two strings as input and print the string with maximum length in console. If two strings have the same length, then the function should print all strings line by line._**

---

### Hints:

> **_Use len() function to get the length of a string._**

---

### **Question: 31**

> **_Define a function which can print a dictionary where the keys are numbers between 1 and 20 (both included) and the values are square of keys._**

---

### Hints:


Use dict[key]=value pattern to put entry into a dictionary.Use ** operator to get power of a number.Use range() for loops.


---

### **Question: 32**

> **_Define a function which can generate a dictionary where the keys are numbers between 1 and 20 (both included) and the values are square of keys. The function should just print the keys only._**

---

### Hints:


Use dict[key]=value pattern to put entry into a dictionary.Use ** operator to get power of a number.Use range() for loops.Use keys() to iterate keys in the dictionary. Also we can use item() to get key/value pairs.


---

### **Question: 33**

> **_Define a function which can generate and print a list where the values are square of numbers between 1 and 20 (both included)._**

---

### Hints:


Use ** operator to get power of a number.Use range() for loops.Use list.append() to add values into a list.


---

### **Question: 34**

> **_Define a function which can generate a list where the values are square of numbers between 1 and 20 (both included). Then the function needs to print the first 5 elements in the list._**

---

### Hints:


Use ** operator to get power of a number.Use range() for loops.Use list.append() to add values into a list.Use [n1:n2] to slice a list


---

### **Question: 35**

> **_Define a function which can generate a list where the values are square of numbers between 1 and 20 (both included). Then the function needs to print the last 5 elements in the list._**

---

### Hints:


Use ** operator to get power of a number.Use range() for loops.Use list.append() to add values into a list.Use [n1:n2] to slice a list


---

### **Question: 36**

> **_Define a function which can generate a list where the values are square of numbers between 1 and 20 (both included). Then the function needs to print all values except the first 5 elements in the list._**

---


Hints: Use ** operator to get power of a number.Use range() for loops.Use list.append() to add values into a list.Use [n1:n2] to slice a list


---

### **Question: 37**

> **_Define a function which can generate and print a tuple where the value are square of numbers between 1 and 20 (both included)._**

---

### Hints:


Use ** operator to get power of a number.Use range() for loops.Use list.append() to add values into a list.Use tuple() to get a tuple from a list.


---

### **Question: 38**

> **_With a given tuple (1,2,3,4,5,6,7,8,9,10), write a program to print the first half values in one line and the last half values in one line._**

---

### Hints:

> **_Use [n1:n2] notation to get a slice from a tuple._**

---

### **Question: 39**

> **_Write a program to generate and print another tuple whose values are even numbers in the given tuple (1,2,3,4,5,6,7,8,9,10)._**

---

### Hints:

> **_Use "for" to iterate the tuple. Use tuple() to generate a tuple from a list._**

---

### **Question: 40**

> **_Write a program which accepts a string as input to print "Yes" if the string is "yes" or "YES" or "Yes", otherwise print "No"._**

---

### Hints:

> **_Use if statement to judge condition._**

---

### **Question: 41**

> **_Write a program which can map() to make a list whose elements are square of elements in [1,2,3,4,5,6,7,8,9,10]._**

---

### Hints:

> **_Use map() to generate a list.Use lambda to define anonymous functions._**

---

### **Question: 42**

> **_Write a program which can map() and filter() to make a list whose elements are square of even number in [1,2,3,4,5,6,7,8,9,10]._**

---

### Hints:

> **_Use map() to generate a list.Use filter() to filter elements of a list.Use lambda to define anonymous functions._**

---
### **Question: 43**

> **_Write a program which can filter() to make a list whose elements are even number between 1 and 20 (both included)._**

---

### Hints:

> **_Use filter() to filter elements of a list.Use lambda to define anonymous functions._**

---

### **Question: 44**

> **_Write a program which can map() to make a list whose elements are square of numbers between 1 and 20 (both included)._**

---

### Hints:

> **_Use map() to generate a list. Use lambda to define anonymous functions._**

---


### **Question: 45**

> **_Define a class named American which has a static method called printNationality._**

---

### Hints:

> **_Use @staticmethod decorator to define class static method.There are also two more methods.To know more, go to this [link](https://realpython.com/blog/python/instance-class-and-static-methods-demystified/)._**

---


### **Question: 46**

> **_Define a class named American and its subclass NewYorker._**

---

### Hints:

> **Use class Subclass(ParentClass) to define a subclass.\***

---

### **Question: 47**

> **_Define a class named Circle which can be constructed by a radius. The Circle class has a method which can compute the area._**

---

### Hints

> **_Use def methodName(self) to define a method._**

---

### **Question: 48**

> **_Define a class named Rectangle which can be constructed by a length and width. The Rectangle class has a method which can compute the area._**

---

### Hints

> **_Use def methodName(self) to define a method._**

---

### **Question: 49**

> **_Define a class named Shape and its subclass Square. The Square class has an init function which takes a length as argument. Both classes have a area function which can print the area of the shape where Shape's area is 0 by default._**

---

### Hints

> **_To override a method in super class, we can define a method with the same name in the super class._**

---

### **Question: 50**

> **_Please raise a RuntimeError exception._**

---

### Hints

> **_Use raise to raise an exception._**

---


### **Question: 51**

> **_Write a function to compute 5/0 and use try/except to catch the exceptions._**

---

### Hints

> **_Use try/except to catch exceptions._**

---


### **Question: 52**

> **_Define a custom exception class which takes a string message as attribute._**

---

### Hints

> **_To define a custom exception, we need to define a class inherited from Exception._**

---


### **Question: 53**

> **_Assuming that we have some email addresses in the "username@companyname.com" format, please write program to print the user name of a given email address. Both user names and company names are composed of letters only._**

> **_Example:
> If the following email address is given as input to the
> program:_**

> john@google.com

> **_Then, the output of the program should be:_**

> john

> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_Use \w to match letters._**

---


### **Question: 54**

> **_Assuming that we have some email addresses in the "username@companyname.com" format, please write program to print the company name of a given email address. Both user names and company names are composed of letters only._**

> **_Example:
> If the following email address is given as input to the program:_**


> john@google.com


> **_Then, the output of the program should be:_**


> google


> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_Use \w to match letters._**

---


### **Question: 55**

> **_Write a program which accepts a sequence of words separated by whitespace as input to print the words composed of digits only._**

> **_Example:
> If the following words is given as input to the program:_**


> 2 cats and 3 dogs.


> **_Then, the output of the program should be:_**


> ['2', '3']


> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_Use re.findall() to find all substring using regex._**

---


### **Question: 56**

> **_Print a unicode string "hello world"._**

---

### Hints

> **_Use u'strings' format to define unicode string._**

---


### **Question: 57**

> **_Write a program to read an ASCII string and to convert it to a unicode string encoded by utf-8._**

---

### Hints

> **_Use unicode()/encode() function to convert._**

---


### **Question: 58**

> **_Write a special comment to indicate a Python source code file is in unicode._**

---

### Hints

> **_Use unicode() function to convert._**

---


### **Question: 59**

> **_Write a program to compute 1/2+2/3+3/4+...+n/n+1 with a given n input by console (n>0)._**

> **_Example:
> If the following n is given as input to the program:_**


> 5


> **_Then, the output of the program should be:_**


> 3.55


> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_Use float() to convert an integer to a float.Even if not converted it wont cause a problem because python by default understands the data type of a value_**

---


### **Question: 60**

> **_Write a program to compute:_**


> $f(n)=f(n-1)+100$ when n>0

> and $f(0)=0$


> **_with a given n input by console (n>0)._**

> **_Example:
> If the following n is given as input to the program:_**


> 5


> **_Then, the output of the program should be:_**


> 500


> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_We can define recursive function in Python._**

---


### **Question: 61**

> **_The Fibonacci Sequence is computed based on the following formula:_**


> $f(n)=0$ if n=0

> $f(n)=1$ if n=1

> $f(n)=f(n-1)+f(n-2)$ if n>1


> **_Please write a program to compute the value of f(n) with a given n input by console._**

> **_Example:
> If the following n is given as input to the program:_**


> 7


> **_Then, the output of the program should be:_**


> 13


> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_We can define recursive function in Python._**

---


### **Question: 62**

> **_The Fibonacci Sequence is computed based on the following formula:_**


> $f(n)=0$ if n=0

> $f(n)=1$ if n=1

> $f(n)=f(n-1)+f(n-2)$ if n>1


> **_Please write a program to compute the value of f(n) with a given n input by console._**

> **_Example:
> If the following n is given as input to the program:_**

> 7

> **_Then, the output of the program should be:_**

> 0,1,1,2,3,5,8,13

> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_We can define recursive function in Python.
> Use list comprehension to generate a list from an existing list.
> Use string.join() to join a list of strings._**

---


### **Question: 63**

> **_Please write a program using generator to print the even numbers between 0 and n in comma separated form while n is input by console._**

> **_Example:
> If the following n is given as input to the program:_**

> 10

> **_Then, the output of the program should be:_**

> 0,2,4,6,8,10

> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_Use yield to produce the next value in generator._**

---


### **Question: 64**

> **_Please write a program using generator to print the numbers which can be divisible by 5 and 7 between 0 and n in comma separated form while n is input by console._**

> **_Example:
> If the following n is given as input to the program:_**

> 100

> **_Then, the output of the program should be:_**

> 0,35,70

> **_In case of input data being supplied to the question, it should be assumed to be a console input._**

---

### Hints

> **_Use yield to produce the next value in generator._**

---


### **Question: 65**

> **_Please write assert statements to verify that every number in the list [2,4,6,8] is even._**

---

### Hints

> **_Use "assert expression" to make assertion._**

---


### **Question: 66**

> **_Please write a program which accepts basic mathematic expression from console and print the evaluation result._**

> **_Example:
> If the following n is given as input to the program:_**


> 35 + 3


> **_Then, the output of the program should be:_**


> 38


---

### Hints

> **_Use eval() to evaluate an expression._**

---


### **Question: 67**

> **_Please write a binary search function which searches an item in a sorted list. The function should return the index of element to be searched in the list._**

---

### Hints

> **_Use if/elif to deal with conditions._**

---


### **Question: 68**

> **_Please generate a random float where the value is between 10 and 100 using Python module._**

---

### Hints

> **_Use random.random() to generate a random float in [0,1]._**

---


### **Question: 69**

> **_Please generate a random float where the value is between 5 and 95 using Python module._**

---

### Hints

> **_Use random.random() to generate a random float in [0,1]._**

---


### **Question: 70**

> **_Please write a program to output a random even number between 0 and 10 inclusive using random module and list comprehension._**

---

### Hints

> **_Use random.choice() to a random element from a list._**

---

### **Question: 71**

> **_Please write a program to output a random number, which is divisible by 5 and 7, between 10 and 150 inclusive using random module and list comprehension._**

---

### Hints

> **_Use random.choice() to a random element from a list._**

---


### **Question: 72**

> **_Please write a program to generate a list with 5 random numbers between 100 and 200 inclusive._**

---

### Hints

> **_Use random.sample() to generate a list of random values._**

---


### **Question: 73**

> **_Please write a program to randomly generate a list with 5 even numbers between 100 and 200 inclusive._**

---

### Hints

> **_Use random.sample() to generate a list of random values._**

---

### **Question: 74**

> **_Please write a program to randomly generate a list with 5 numbers, which are divisible by 5 and 7 , between 1 and 1000 inclusive._**

---

### Hints

> **_Use random.sample() to generate a list of random values._**

---


### **Question: 75**

> **_Please write a program to randomly print a integer number between 7 and 15 inclusive._**

---

### Hints

> **_Use random.randrange() to a random integer in a given range._**

---


### **Question: 76**

> **_Please write a program to compress and decompress the string "hello world!hello world!hello world!hello world!"._**

---

### Hints

> **_Use zlib.compress() and zlib.decompress() to compress and decompress a string._**

---

### **Question: 77**

> **_Please write a program to print the running time of execution of "1+1" for 100 times._**

---

### Hints

> **_Use timeit() function to measure the running time._**

---


### **Question: 78**

> **_Please write a program to shuffle and print the list [3,6,7,8]._**

---

### Hints

> **_Use shuffle() function to shuffle a list._**

---

### **Question: 79**

> **_Please write a program to generate all sentences where subject is in ["I", "You"] and verb is in ["Play", "Love"] and the object is in ["Hockey","Football"]._**

---

### Hints

> **_Use list[index] notation to get a element from a list._**

---


### **Question: 80**

> **_Please write a program to print the list after removing even numbers in [5,6,77,45,22,12,24]._**

---

### Hints

> **_Use list comprehension to delete a bunch of element from a list._**

---

### **Question: 81**

> **_By using list comprehension, please write a program to print the list after removing numbers which are divisible by 5 and 7 in [12,24,35,70,88,120,155]._**

---

### Hints

> **_Use list comprehension to delete a bunch of element from a list._**

---

### **Question: 82**

> **_By using list comprehension, please write a program to print the list after removing the 0th, 2nd, 4th,6th numbers in [12,24,35,70,88,120,155]._**

---

### Hints

> **_Use list comprehension to delete a bunch of element from a list.
> Use enumerate() to get (index, value) tuple._**

---

### **Question: 83**

> **_By using list comprehension, please write a program to print the list after removing the 2nd - 4th numbers in [12,24,35,70,88,120,155]._**

---

### Hints

> **_Use list comprehension to delete a bunch of element from a list.
> Use enumerate() to get (index, value) tuple._**

---

### **Question: 84**

> **_By using list comprehension, please write a program generate a 3\*5\*8 3D array whose each element is 0._**

---

### Hints

> **_Use list comprehension to make an array._**

---

### **Question: 85**

> **_By using list comprehension, please write a program to print the list after removing the 0th,4th,5th numbers in [12,24,35,70,88,120,155]._**

---

### Hints

> **_Use list comprehension to delete a bunch of element from a list.Use enumerate() to get (index, value) tuple._**

---


### **Question: 86**

> **_By using list comprehension, please write a program to print the list after removing the value 24 in [12,24,35,24,88,120,155]._**

---

### Hints

> **_Use list's remove method to delete a value._**

---

### **Question: 87**

> **_With two given lists [1,3,6,78,35,55] and [12,24,35,24,88,120,155], write a program to make a list whose elements are intersection of the above given lists._**

---

### Hints

> **_Use set() and "&=" to do set intersection operation._**

---


### **Question: 88**

> **_With a given list [12,24,35,24,88,120,155,88,120,155], write a program to print this list after removing all duplicate values with original order reserved._**

---

### Hints

> **_Use set() to store a number of values without duplicate._**

---

### **Question: 89**

> **_Define a class Person and its two child classes: Male and Female. All classes have a method "getGender" which can print "Male" for Male class and "Female" for Female class._**

---

### Hints

> **_Use Subclass(Parentclass) to define a child class._**

---


### **Question: 90**

> **_Please write a program which count and print the numbers of each character in a string input by console._**

> **_Example:
> If the following string is given as input to the program:_**

```
abcdefgabc
```

> **_Then, the output of the program should be:_**

```
a,2
c,2
b,2
e,1
d,1
g,1
f,1
```

### Hints

> **_Use dict to store key/value pairs.
> Use dict.get() method to lookup a key with default value._**

---


### **Question: 91**

> **_Please write a program which accepts a string from console and print it in reverse order._**

> **Example:
> If the following string is given as input to the program:\***


rise to vote sir


> **_Then, the output of the program should be:_**

ris etov ot esir

### Hints

> **_Use list[::-1] to iterate a list in a reverse order._**

---


### **Question: 92**

> **_Please write a program which accepts a string from console and print the characters that have even indexes._**

> **_Example:
> If the following string is given as input to the program:_**
```
H1e2l3l4o5w6o7r8l9d
```
> **_Then, the output of the program should be:_**
```
Helloworld
```
### Hints

> **_Use list[::2] to iterate a list by step 2._**

---


### **Question : 93**

> **_Please write a program which prints all permutations of [1,2,3]_**

---

### Hints

> **_Use itertools.permutations() to get permutations of list._**

---

### **Question: 94**

> **_Write a program to solve a classic ancient Chinese puzzle:
> We count 35 heads and 94 legs among the chickens and rabbits in a farm. How many rabbits and how many chickens do we have?_**

---

### Hints

> **_Use for loop to iterate all possible solutions._**

---


### **Question: 95**

> **_Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them in a list and find the score of the runner-up._**

> **_If the following string is given as input to the program:_**
>
> 5
> 2 3 6 6 5
>
> **_Then, the output of the program should be:_**
>
> 5

### Hints

> **_Make the scores unique and then find 2nd best number_**

---


### **Question: 96**

> **_You are given a string S and width W.
> Your task is to wrap the string into a paragraph of width._**

> **_If the following string is given as input to the program:_**
>
> ABCDEFGHIJKLIMNOQRSTUVWXYZ
> 4
>
> **_Then, the output of the program should be:_**
>
> ABCD
> EFGH
> IJKL
> IMNO
> QRST
> UVWX
> YZ

### Hints

> **_Use wrap function of textwrap module_**

---


### **Question: 97**

> **_You are given an integer, N. Your task is to print an alphabet rangoli of size N. (Rangoli is a form of Indian folk art based on creation of patterns.)_**

> **_Different sizes of alphabet rangoli are shown below:_**
>
> $size = 3$
>
> ----c----

> --c-b-c--

> c-b-a-b-c

> --c-b-c--

> ----c----
>
> $size = 5$
>
> --------e--------

> ------e-d-e------

> ----e-d-c-d-e----

> --e-d-c-b-c-d-e--

> e-d-c-b-a-b-c-d-e

> --e-d-c-b-c-d-e--

> ----e-d-c-d-e----

> ------e-d-e------

> --------e--------

### Hints

> **_First print the half of the Rangoli in the given way and save each line in a list. Then print the list in reverse order to get the rest._**

---


### **Question: 98**

> **_You are given a date. Your task is to find what the day is on that date._**

**Input**

> **_A single line of input containing the space separated month, day and year, respectively, in MM DD YYYY format._**
>
> 08 05 2015

**Output**

> **_Output the correct day in capital letters._**
>
> WEDNESDAY

---

### Hints

> **_Use weekday function of calender module_**

---


### **Question: 99**

> **_Given 2 sets of integers, M and N, print their symmetric difference in ascending order. The term symmetric difference indicates those values that exist in either M or N but do not exist in both._**

**Input**

> **_The first line of input contains an integer, M.The second line contains M space-separated integers.The third line contains an integer, N.The fourth line contains N space-separated integers._**
>
> 4
> 2 4 5 9
> 4
> 2 4 11 12

**Output**

> **_Output the symmetric difference integers in ascending order, one per line._**
>
> 5
> 9
> 11
> 12

---

### Hints

> **_Use \'^\' to make symmetric difference operation._**

---

### **Question: 100**

> **_You are given words. Some words may repeat. For each word, output its number of occurrences. The output order should correspond with the input order of appearance of the word. See the sample input/output for clarification._**

> **_If the following string is given as input to the program:_**
>
> 4
> bcdef
> abcdefg
> bcde
> bcdef
>
> **_Then, the output of the program should be:_**
>
> 3
> 2 1 1

### Hints

> **_Make a list to get the input order and a dictionary to count the word frequency_**

---

