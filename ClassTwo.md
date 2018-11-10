# Class Two

## Basic Operators
Here i will go though the basic operators for doing math, when using operators for math purposes,
you can use both integers and float data types, However you cant use strings

> the `+` operator is for adding Numbers

> the `-` operator is for subtracting Numbers

> the `*` operator is for multiplying Numbers

> the `/` operatir is for dividing Numbers

> the `%` operator gives a remainder in an integer

> the `**` operator is for making a power relationship

```python
number = 1 + 2 * 3 / 4.0
print(number)

# this returns 2.5

number = 2 ** 4
print(number)

# this returns 16

number = 15 % 2
print(number)

# this returns 1
```

Now I will demenstate using operators on Strings

> you can use the `+` operator to add / glue strings together

> you can use the `*` operator to multiply / duplicate the strings

```python
helloworld = "hello" + " " + "world"
print(helloworld)

# this returns "hello world"

lotsofhellos = "hello" * 10
print(lotsofhellos)

# this returns "hellohellohellohellohellohellohellohellohellohello"
```
You can also use these operators on Lists

```python
even_numbers = [2,4,6,8]
odd_numbers = [1,3,5,7]
all_numbers = odd_numbers + even_numbers
print(all_numbers)

# this out puts [1, 3, 5, 7, 2, 4, 6, 8]

print([1,2,3] * 3)

# this outputs [1, 2, 3, 1, 2, 3, 1, 2, 3]
```

## String Operators and Methods

Here I will show some really important and handy Methods and functions
to help manage strings and Lists,

> the `len()` function returns the length of a string or list

> the `print()` function returns the output of what ever is put in it

```python
astring = "Hello world!"
print(len(astring))

# this will return 12
```

> the `.index()` gives the index inthe string or list of the item you enter in

> the `.count()` counts the amount of times and item appears in the string or list

> the `.upper()` coverts all the letters in a sting to upper case charactors

> the `.lower()` converts all the letters in a sting to lower case charactors

> the `.startswith()` returns true is the string starts with whatever is in the brackets

> the `.endswith()` returns true if the string ends with whatever is in the brackets

> the `.split()` splits strings by words or whatever is in the brackets and adds each to a list

> the `.append()` adds whatever is in the brackets to the end of a list or string

```python
astring = "Hello world!"
print(astring.index("o"))

# this returns 4

astring = "Hello world!"
print(astring.count("l"))

# this returns 3

astring = "Hello world!"
print(astring.upper())

## this returns HELLO WORLD!

print(astring.lower())

# this returns hello world!

astring = "Hello world!"
print(astring.startswith("Hello"))

# this returns True

print(astring.endswith("asdfasdfasdf"))

# this returns False

astring = "Hello world!"
afewwords = astring.split(" ")
print(afewwords)

# this returns ['Hello', 'world!']

```
