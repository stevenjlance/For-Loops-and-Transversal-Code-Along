# `for` LOOPS AND TRAVERSALS

Each for loop has a set structure. Let's look at an example:

```javascript
for(let i = 0; i<5; i++){
  //DO SOMETHING
}
```

Here's a more precise look at exactly how these three statements are implemented. This is generally not helpful for first-time students.

- The first statement is the starting value of the loop - it's run only once, before the loop begins. The loop above begins with the number 0, but could start anywhere.
- The second statement is run before each iteration in the loop. The code block is only executed when this second statement evaluates to `True`.
- The third statement is run after each iteration in the loop. much we want to increment by every time the loops runs. In the above example, i will increase by 1 (`i++` is shorthand for `i = i + 1` or `i += 1`), but you could just as easily skip-count by 3s or any other number with something like `i = i + 3`.


We can combine this knowledge of for loops to our previous knowledge of arrays. Suppose we have the following list:
```javascript
var myArray = ["I", "like", "to", "use", "arrays"]
```
We could use a `for` loop to iterate through this array and print out each value. This is known as a **traversal**
```javascript
for(var i = 0; i < myArray.length; i++){
	// i runs from 0 up to 1 less than the length of the array
	// We then use i to access the value as it can be the index value we pass in.
	console.log(myArray[i])
}
```

## Task Today

Open the `script.js` file and follow the directions for today's introduction to for loops and traversals!