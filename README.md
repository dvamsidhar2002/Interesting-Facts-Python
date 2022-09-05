# Interesting-Facts-Python
A few interesting facts about python which will really impress you.

Interesting Facts about Python

Want to read a poem on Python by Time Peters? 
Then use the following commands - 

“import this” in the interpreter.
# Try to guess the result before you actually run it
import this


---------------------------------------------------
Want to find the index inside a for loop? Wrap an iterable with ‘enumerate’ and it will yield the item along with its index. See this code snippet.
# Know the index faster
vowels=['a','e','i','o','u']
for i, letter in enumerate(vowels):
	print (i, letter)


----------------------------------------------------
Comparison operators can be used in such a way that variable can store boolean values

# Chaining Comparison Operators
i = 5;

ans = 1 < i < 10
print(ans)

ans = 10 > i <= 9
print(ans)

ans = 5 == i
print(ans)

--------------------------------------------------
Instead of building a list with a loop, one can build it more concisely with a list comprehension. See this code for more understanding.

# Simple List Append
a = []
for x in range(0,10):
	a.append(x)
print(a)

# List Comprehension
print([x for x in a])




