# Python-Assignment
Ques 1: What is a dictionary in Python?

Ans:Python dictionary is one of the supported data types in Python. It is an unordered collection of elements. The elements in dictionaries are stored as key-value pairs. Dictionaries are indexed by keys.

For example, below we have a dictionary named ‘dict’. It contains two keys, Country and Capital, along with their corresponding values, India and New Delhi.

Ques2: What are functions in Python?

Ans:A function is a block of code which is executed only when a call is made to the function. def keyword is used to define a particular function as shown below:

def function():
print("Hi, Welcome to Intellipaat")
function(); # call to the function

Ques3: What are the common built-in data types in Python?

Ans:Python supports the below-mentioned built-in data types:

Immutable data types:

Number
String
Tuple
Mutable data types:

List
Dictionary
set

Ques4 : What is a map function in Python?

Ans:The map() function in Python has two parameters, function and iterable. The map() function takes a function as an argument and then applies that function to all the elements of an iterable, passed to it as another argument. It returns an object list of results.

Ques5:What are python iterators?

Ans: These are the certain objects that are easily traversed and iterated when needed.

Ques 6:Do we need to declare variables with data types in Python?

Ans: No. Python is a dynamically typed language, I.E., Python Interpreter automatically identifies the data type of a variable based on the type of value assigned to the variable.

Ques7:What are Dict and List comprehensions?

Ans: Python comprehensions are like decorators, that help to build altered and filtered lists, dictionaries, or sets from a given list, dictionary, or set. Comprehension saves a lot of time and code that might be considerably more complex and time-consuming.

Comprehensions are beneficial in the following scenarios:

Performing mathematical operations on the entire list
Performing conditional filtering operations on the entire list
Combining multiple lists into one
Flattening a multi-dimensional list

Ques8: What does *args and **kwargs mean?

Ans: .*args: It is used to pass multiple arguments in a function.
**kwargs: It is used to pass multiple keyworded arguments in a function in python.

Ques9: How will you remove duplicate elements from a list?

To remove duplicate elements from the list we use the set() function.

Ques10: What is the purpose of is, not and in operators?

Ans: Operators are referred to as special functions that take one or more values(operands) and produce a corresponding result.

is: returns the true value when both the operands are true  (Example: “x” is ‘x’)
not: returns the inverse of the boolean value based upon the operands (example:”1” returns “0” and vice-versa.
In: helps to check if the element is present in a given Sequence or not.

Ques11: How will you convert a string to all lowercase?

Ans: lower() function is  used to convert a string to lowercase.

For Example:

demo_string='ROSES'
print(demo_string.lower())

Ques12:What is the lambda function in Python?

Ans: A lambda function is an anonymous function (a function that does not have a name) in Python. To define anonymous functions, we use the ‘lambda’ keyword instead of the ‘def’ keyword, hence the name ‘lambda function’. Lambda functions can have any number of arguments but only one statement.

For example:

l = lambda x,y : x*y
print(a(5, 6))

Ques13: What is the difference between / and // operator in Python?

Ans: /: is a division operator and returns the Quotient value.
10/3
-> 3.33

// : is known as floor division operator and used to return only the value of quotient before decimal
10//3
-> 3

Ques14: What does immutable mean and what three types of Python core data types are considered immutable?

Ans: An immutable data type is a type of object which cannot be modified after its creation. Numbers, strings, and tuples in Python fall into this category. Although you cannot modify an immutable object in place, you can always create a new one by running an expression.

Ques15: What does mapping mean and what kind of data type is based on mapping?

Ans: The term mapping refers to an object that maps keys to associated values. The Python dictionary is the only type of mapping in the base typeset. Mappings do not maintain any left-to-right position order; they support access to stored data by key, as well as type-specific method calls.

Ques16: What are lists and tuples? What is the key difference between the two?

Ans: Lists and Tuples are both sequence data types that can store a collection of objects in Python. The objects stored in both sequences can have different data types. Lists are represented with square brackets ['sara', 6, 0.19], while tuples are represented with parantheses ('ansh', 5, 0.97).
But what is the real difference between the two? The key difference between the two is that while lists are mutable, tuples on the other hand are immutable objects. This means that lists can be modified, appended or sliced on the go but tuples remain constant and cannot be modified in any manner.

Ques17: What is pass in Python?

Ans: The pass keyword represents a null operation in Python. It is generally used for the purpose of filling up empty blocks of code which may execute during runtime but has yet to be written. Without the pass statement in the following code, we may run into some errors during code execution.

Ques18:  What are the three main conditional statements in Python?

Answer: if, elif, and else

Ques19: what is the difference between the continue and break statements in Python?

Ans: The break statement terminates the loop that contains it. The program immediately moves to the code section that is in the outer scope of the loop.
The continue statement skips the rest of the code of the current iteration and move to the next iteration.

Ques20:What is the difference between a for loop and a while loop?

Ans: A for loop is typically used when you know exactly how many times the loop needs to be repeated. A while loop is typically used when you don't know how many times the loop needs to be repeated.

A while loop repeats as long as its condition is true. For example, if a while loop says "while x == 5", then the line will execute as long as x equals five


























