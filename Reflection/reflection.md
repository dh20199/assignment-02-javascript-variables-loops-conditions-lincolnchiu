# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`?

You would always use careful subtract because there's no reason not to sanitize your inputs whenever possible. blindly subtracting variables is going to cause unnecessary trouble when you may have accidentally passed a number as a string in earlier parts of the code or if while handling your number, a string is accidentally added to it. 

## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types.

## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?


## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?
