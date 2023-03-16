# Python-For-Loops
A python for loop tutorial by ChatGPT-4 featured on my YouTube Channel.


Python for loops are used to iterate over a sequence (such as a list, tuple, or string) and execute a block of code for each item in the sequence. The basic syntax of a for loop in Python is as follows:

```python
for variable in sequence:
    # code to be executed for each item in the sequence
```
### Here's a step-by-step explanation of how a for loop works:

The for keyword starts the loop.
variable is a temporary name given to each item in the sequence as it is iterated over.
in is a keyword that signifies membership in the sequence.
sequence is the collection of items to be iterated over (e.g., a list, tuple, or string).
The colon : denotes the beginning of the loop's code block.
The indented code block contains the code to be executed for each item in the sequence.
Here's a simple example of a for loop that iterates over a list of numbers and prints each number:

```python
numbers = [1, 2, 3, 4, 5]

for num in numbers:
    print(num)
```

### This code would produce the following output:

```bash
1
2
3
4
5
```

### You can also use the range() function to generate a sequence of numbers to loop over:

```python
for i in range(5):
    print(i)
 ```
 
### This code would produce the following output:

```bash
0
1
2
3
4
```
Note that the range() function generates numbers starting from 0 by default and goes up to, but not including, the specified number.

For loops are versatile and can be used with various data structures, like lists, tuples, dictionaries, and strings. They are a fundamental concept in Python and are essential for performing repetitive tasks efficiently.
