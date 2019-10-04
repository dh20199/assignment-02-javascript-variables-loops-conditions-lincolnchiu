# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`?

You would always use careful subtract because there's no reason not to sanitize your inputs whenever possible. blindly subtracting variables is going to cause unnecessary trouble when you may have accidentally defined a number as a string in earlier parts of the code or if while handling your number, a string is accidentally added to it. Making sure your function is getting the proper inputs first is also important so that it doesn't break the following code that uses the function's output and everything falls apart.

## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types.

Data types are the classifications assigned to every type of variable or object definable in code. This system of classifications is important because it informs the computer as to how exactly to execute your code, what to expect and how to handle certain situations. The most notable result of a robust data type structure to a coding language is the way it handles operators. If we attempt to add a number to a string, javascript can convert the number into a string and automatically concatenate them as opposed to doing nothing, or breaking, or returning an error. Javascript data types include numbers, strings, booleans, and arrays.

## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?

Arrays are preferable for an ordered list of items, and objects are generally used for a list of items that can be ordered in any way. Arrays are easier to use when filtering and grouping the data is required. Since arrays are an extension of the objects class, there are extra functions, that the object class doesn't have, that are built in that also make maintaining the array easier. These functions include push(), foreach(), indexof(), which make it desirable to use it for a list of objects that is intended to be searched through and organized often. Objects are usually used for lists that are unordered and wherein you already have some knowledge of what to look for. The values of an object list can be looked up by their property which can be simpler to handle when there are many lists of data you need to pull from. As a result, you could simply call for every value with a certain property of an object list.

## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?

Checking the contents of the objects before the function processes it with a function such as typeof(). Using if statements to assure that if you need to use a number, it fits within a minimum and maximum, whether it is a negative or positive number, or if it's a floating point integer. isNaN can be used to test whether a variable is a number or not as well. Before accessing the value in a object, the key could be verified to be what is expected.

It could be interesting to use the data to find the ruler who has ruled the longest, who the least, whomever has the longest name, how much more someone has ruled than another. 
