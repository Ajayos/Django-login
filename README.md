# Django-login
Django login page


## 1

AIM:program to find the largest number among the three input numbers
Program:
```
	# change the values of num1, num2 and num3 
	# for a different result
	num1 = 10 num2 = 14 num3 = 12 
	# uncomment following lines to take three numbers from user 
	#num1 = float(input("Enter first number: ")) 
	#num2 = float(input("Enter second number: "))
	 #num3 = float(input("Enter third number: "))
	if (num1 >= num2) and (num1 >= num3): 
	largest = num1 elif (num2 >= num1) and (num2 >= num3): 
	largest = num2 else: largest = num3 print("The largest number between",num1,",",num2,"and",num3,"is",largest) 
```

Output : ``The largest number between 10 , 14 and 12 is 14``


##	2
Aim:Write a program to check whether givenstringispalindromeor not
			
Program 
```
		my_str = 'aIbohPhoBiA'
		# make it suitable for caseless comparison
		my_str = my_str.casefold()

		# reverse the string
		rev_str = reversed(my_str)

		# check if the string is equal to its reverse
		if list(my_str) == list(rev_str):
			print("The string is a palindrome.")
		else:
		print("The string is not a palindrome.")
```
``Output
	The string is not a palindrome``

## 3	

Aim: Python program for explaining  use of list, tuple, set and dictionary

Program
```
# Lists
l = []

# Adding Element into list
l.append(5)
l.append(10)
print("Adding 5 and 10 in list", l)

# Popping Elements from list
l.pop()
print("Popped one element from list", l)
print()

# Set
s = set()

# Adding element into set
s.add(5)
s.add(10)
print("Adding 5 and 10 in set", s)

# Removing element from set
s.remove(5)
print("Removing 5 from set", s)
print()

# Tuple
t = tuple(l)

# Tuples are immutable
print("Tuple", t)
print()


# Dictionary
d = {}

# Adding the key value pair
d[5] = "Five"
d[10] = "Ten"
print("Dictionary", d)

# Removing key-value pair
del d[10]
print("Dictionary", d)

Output
Adding 5 and 10 in list [5, 10]
Popped one element from list [5]

Adding 5 and 10 in set {10, 5}
Removing 5 from set {10}

Tuple (5,)

Dictionary {5: 'Five', 10: 'Ten'}
Dictionary {5: 'Five'}
```

##	4	

Aim:write a recursive function to find factorial of a number

Program
```
def factorial(x):
    if x == 1:
        return 1
    else:
        return (x * factorial(x-1))

num = 3
print("The factorial of", num, "is", factorial(num))
```

output:
the factorial of 3 is 6.


## 4

Aim:write a recursive function to find factorial of a number

Program
```
def factorial(x):
    if x == 1:
        return 1
    else:
        return (x * factorial(x-1))

num = 3
print("The factorial of", num, "is", factorial(num))
```

output:
```
the factorial of 3 is 6.
```


## 5

Aim:Write a python program to find area of room using class.

Program
```
# create a class
class Room:
    length = 0.0
    breadth = 0.0

    # method to calculate area
        defcalculate_area(self):
           print("Area of Room =", self.length * self.breadth)

# create object of Room class
study_room = Room()

# assign values to all the attributes 
study_room.length = 42.5
study_room.breadth = 30.8

# access method inside class
study_room.calculate_area()
```
ouput:
```Area of room=1309.0```
