# Learn Python

Read Allen Downey's [Think Python](http://www.greenteapress.com/thinkpython/) for getting up to speed with Python 2.7 and computer science topics. It's completely available online, or you can buy a physical copy if you would like.

<a href="http://www.greenteapress.com/thinkpython/"><img src="img/think_python.png" style="width: 100px;" target="_blank"></a>

For quick and easy interactive practice with Python, many people enjoy [Codecademy's Python track](http://www.codecademy.com/en/tracks/python). There's also [Learn Python The Hard Way](http://learnpythonthehardway.org/book/) and [The Python Tutorial](https://docs.python.org/2/tutorial/).

---

### Q1. Lists &amp; Tuples

How are Python lists and tuples similar and different? Which will work as keys in dictionaries? Why?

>> Both tuple and list are a sequence of values. The important difference is that tuples are immutable, while lists are multable. Tuples are also comparable and hashable so we can use tuples as key values in dictionaries.

---

### Q2. Lists &amp; Sets

How are Python lists and sets similar and different? Give examples of using both. How does performance compare between lists and sets for finding an element. Why?

>> Both are data structures, collection of elements. However, while lists have ordered elements that are accessed by indices, sets have unordered unique elements and doesn't allow indexing.

---

### Q3. Lambda Function

Describe Python's `lambda`. What is it, and what is it used for? Give at least one example, including an example of using a `lambda` in the `key` argument to `sorted`.

>> Lambda is an anonymous function is a function that is defined without a name. Lambda functions are mainly used in combination with the functions filter(), map() and reduce().

>> sorted() may have a key parameter to specify a function to be called on each list element prior to making comparisons. In the case bellow, lambda is an anonymous function for returning each element of the list in lower case.
>> sorted(['I', 'like', 'Metis', 'Bootcamp'], key=lambda word: word.lower())

---

### Q4. List Comprehension, Map &amp; Filter

Explain list comprehensions. Give examples and show equivalents with `map` and `filter`. How do their capabilities compare? Also demonstrate set comprehensions and dictionary comprehensions.

>> List comprehension is a way to define and create list in Python. It can substitute the lambda function as well as the functions map(), filter() and reduce().
>> if we already have a function defined, it is often reasonable to use map(), filter() and reduce(). For example:
>> "map(function, myLists)" seems cleaner than "[funtion(x) for x in myLists]". Otherwise, list comprehension might be easier for beggineers in python to read.

>> On top of list comprehensions, Python now supports dict comprehensions, which allow you to express the creation of dictionaries at runtime using a similarly concise syntax. A dictionary comprehension takes the form {key: value for (key, value) in iterable}.
>> Lastly, the syntax for set comprehensions is almost identical to that of list comprehensions, but it uses curly brackets instead of square brackets: {n**2 for n in range(10)}

---

### Complete the following problems by editing the files below:

### Q5. Datetime
Use Python to compute days between start and stop date.   
a.  

```
date_start = '01-02-2013'    
date_stop = '07-28-2015'
```

>> 937

b.  
```
date_start = '12312013'  
date_stop = '05282015'  
```

>> 513

c.  
```
date_start = '15-Jan-1994'      
date_stop = '14-Jul-2015'  
```

>> 7850

Place code in this file: [q5_datetime.py](python/q5_datetime.py)

---

### Q6. Strings
Edit the 7 functions in [q6_strings.py](python/q6_strings.py)

---

### Q7. Lists
Edit the 5 functions in [q7_lists.py](python/q7_lists.py)

---

### Q8. Parsing
Write a script as indicated (using the football data) in [q8_parsing.py](python/q8_parsing.py)





