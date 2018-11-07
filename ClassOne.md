# Class One

## Data Types

There is meny data types in python, However I will only cover 4 of them.
* Strings

* integers

* Floating-Point Numbers (decimals)

* Boolean

You can test the type of some data using the `type()` function, below you can see
the output of doing this on diffrent data types.
```python
# strings
>>> type("I am a string.")
<class 'str'>


# intergers
>>> type(10)
<class 'int'>


# floats
>>> type(4.2)
<class 'float'>

# boolean
>>> type(True)
<class 'bool'>
```

If you want to convert data to a diffrent type you can use the following functions.
Becareful though, you cant convert a sting like 'hello world' to and interger However
you can convert an integer like 555 to '555' using `str(555)`.

```python
# this converts an item to a string
str()

# this converts an item to a integer
int()

# this converts an item to a float
float()
```

## Variables

Variables are nothing but reserved memory locations to store values. This means that when you create a variable you reserve some space in memory.

Basically it store what ever you assign it to.
In python, and programming in general the equal sign (=)
is used to assign data to variable.

```python
# for example:
variable = 'data'

# this prints what ever is inside the brackets
print(variable)
```
The above outputs the following:
```
data
```
Heres a few other examples

```python
# variables
hello = 'hello'
world = 'world'

# printing the two variables
print(hello, world)

# printing a string and adding in variables
print('I am printing ', hello, world, '!')

# or

# use placeholders
# this might look more complicated then it actually is
# but when strings get much bigger its much more simple
# then the above example, ill cover this in a future date
print('I am printing %s %s!' % (hello, world))

# variables using the integer data type
num = 2
extraNum = 6

# adding the two variables
ans = num + extraNum

# printing the answer
print(ans)

# reassigning this new calculation to the variable ans
ans = extraNum / num

# printing the new answer
print(ans)
```

## If statements

If statements are very important in programming, if statements allow you to program in decisions that the computer can make, depending on conditions that you state, heres an example of the pseudocode (made up language)
```
if condition is successful:
  do This
else:
  do this other thing instead
```
For example, this game will only play if you are older then 18
```python
age = 10

if age > 18:
  print('You are old enough to play')
else:
  print('You are not old enough to play')
```

## Lists and strings

Lists allow you to store a collection of data, it is indexed starting from 0 as the first item in the list or -1 from the last item in the list back, lists use square brakets ([]) to represent the list, it written and initialised as follows

```python
# lists are indexed as follows
#         0  1  2  3  4
#        -5 -4 -3 -2 -1
mylist = [1, 2, 3, 4, 5]

# if you wanted to print 3 you would have to do This
print(mylist[2])

# or

print(mylist[-3]) # not that if you add a new item this will output 4 etc

# you can ad an item to the list by using the append method
# this adds 6 to the end of the list
mylist.append(6)

# strings are also indexed the same way,
# strings work very simular to lists
#         01234
string = "12345"

# to prove that string and lists are similar
print(mylist[1])

# here we are converting the the string answer to an
# interger to give the same output as above
print(int(string[1]))
```
