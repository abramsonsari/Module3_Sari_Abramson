
#Copied from PYZO


# MCON 141 — Homework 3
# Class 3 Concepts: if statements and Boolean logic
#
# Name: Sari Abramson
# Date: 9/16
#
# DIRECTIONS
# 1. Open this file in Pyzo and save it with your own name in the filename.
# 2. Type your solution directly below each exercise's comment block.
# 3. For every exercise that asks for user input, place the input/conversion
#    statements in a try / except ValueError block.
# 4. Test every solution. If you do not use a function, leave comments stating
#    the additional tests you ran, because only the final run is visible.
# 5. All code must run without errors.
#
# EXTRA CREDIT (up to 2 points)
# Write your solutions inside functions where appropriate. For example:
#
# def check_weather(temperature):
#     if temperature > 80:
#         return "It is hot outside."
#     elif temperature < 60:
#         return "It is cold outside."
#     else:
#         return "The weather is mild."
#
# print(check_weather(75))  # should print: The weather is mild.
# print(check_weather(85))  # should print: It is hot outside.
# print(check_weather(50))  # should print: It is cold outside.


# ================================================================
# Exercise 1: What is x relative to y?
#
# Two variables are named x and y. Set y to 10 and x to 20.
#
# Write an if / elif / else statement that compares x and y:
# - If x is less than y, print: "x is less than y"
# - If x is equal to y, print: "x is equal to y"
# - If x is greater than y, print: "x is greater than y"
#
# In a comment within your code, explain the result and why it occurs.
# Also test at least two other values of x and/or y, and document those tests.



# ================================================================
y = 10
x = 20
def compare_nums (x,y):
    if x < y:
        print ("x is less than y")
    elif x > y:
        print ("x is greater than y")
    else:
        print("x is equal to y")

compare_nums(x,y)
compare_nums(-23,4)
compare_nums(3,3)

#This code printed first "x is greater than y" , then "x is less than y"  , and then "x is equal to y".
#This was the expected code because in my first set of numbers, x was greater than y, in my second set of numbers, x was less than y, and in my third set of numbers, x is equal to y.






print ("NEXT EXERCISE")


# Exercise 2: Is x odd or even?
#
# Use x = 20 (or define x again so this exercise runs independently).
#
# If x is even, print: "x is even"
# Otherwise, print: "x is odd"
#
# In a comment within your code, explain the result and why it occurs.
# Test at least one odd value as well.

x = 20
def is_it_odd(x):
    if x % 2 == 0:
        print ("x is even!")
    else:
        print ("x is odd")

is_it_odd (x)
is_it_odd(3)
#Because x is an even number, it prints "x is even!" when 3 is inputted as x, the code prints, x is odd.



print ("NEXT EXERCISE")



# ================================================================
# Exercise 3: Polynomials
#
# Two factors, when multiplied together, can produce a binomial.
# Given (x + a) * (x + b), where a and b are integers:
#
#      x + a
#  *   x + b
# -------------
#        xb + ab
#   x^2 + xa
# -------------
#   x^2 + (xb + xa) + ab
#
# Write a program named polynomial that asks the user for integers a and b,
# then computes and prints the expanded binomial.
#
# Example: (x + 2) * (x + 3) = x^2 + 5x + 6
#
# Remember: x^2 means "x squared."
# Use try / except ValueError for user input.

def polynomial():
    int_a = input("give an integer: ")
    try:
        int_a = int(int_a)

        int_b = input("give another integer: ")
        try:

            int_b = int(int_b)
            digit_1 = str(int_a + int_b)
            digit_2 = str(int_a * int_b)
            print (" your polynomial is x^2 + " , digit_1, "x + ", digit_2 )


        except ValueError:
            print("thats not an integer!")
            print("couldnt print you a polynomial")

    except ValueError:
        print ("thats not an integer!")
        print("couldnt print you a polynomial")


polynomial()














print ("NEXT EXERCISE")










# ================================================================
# Exercise 4: Analyze the polynomial
#
# Given integers a and b, expand (x + a)(x + b) into:
# x^2 + (xb + xa) + ab
#
# Then determine whether:
# - the middle-term coefficient (a + b) is positive, negative, or zero; and
# - the constant (a * b) is positive, negative, or zero.
#
# You may reuse your values of a and b from Exercise 3, but make this exercise
# run independently if possible. Use try / except ValueError for user input.






def new_polynomial():
    int_a = input("give an integer: ")
    try:
        int_a = int(int_a)

        int_b = input("give another integer: ")
        try:

            int_b = int(int_b)
            digit_1 = str(int_a + int_b)
            digit_2 = str(int_a * int_b)
            print (" your polynomial is x^2 + " , digit_1, "x + ", digit_2 )
            digit_1 = int(digit_1)
            digit_2 = int(digit_2)
            if digit_1 < 0:
                print ("the middle coefficient is negative!")
            elif digit_1 == 0:
                print ("The middle coefficient is zero")
            else:
                print ("the middle coefficient is positive!")

            if digit_2 < 0:
                print ("the constant is negative!")
            elif digit_2 == 0:
                print ("The constant is zero")
            else:
                print ("the constant is positive!")




        except ValueError:
            print("thats not an integer!")
            print("couldnt evaluate your polynomial")

    except ValueError:
        print ("thats not an integer!")
        print("couldnt evaluate your polynomial")


new_polynomial()






print ("NEXT EXERCISE")
# ================================================================
# Exercise 5: Explore the and statement
#
# Ask the user to enter integers val1 and val2.
#
# - If both values are positive, print: "val1 and val2 are positive"
#   and print the values.
# - If both values are negative, print: "val1 and val2 are negative"
#   and print the values.
# - Otherwise, print: "The values are not both positive or both negative"
#   and print the values.
#
# Use try / except ValueError for user input.

def get_vals():
    val1 = input('enter an integer ')
    val2 = input ('enter an integer ')
    try:
        val1 = int(val1)
        val2 = int(val2)
        if val1 > 0 and val2 > 0:
            print("value 1 and value 2 are both positive")
        elif val1 <0 and val2 < 0:
            print ("val1 and val2 are both negative")
        else:
            print("val1 and val2 are not both positive or both negative")
        print(val1, val2)
    except ValueError:
        print("sorry, both values aren't integers"
        )

get_vals()









print ("NEXT EXERCISE")

# ================================================================
# Exercise 6: Explore the or statement
#
# Ask the user to enter integers val1 and val2.
#
# - If val1 or val2 is positive, print: "At least one value is positive"
#   and print the values.
# - If val1 or val2 is equal to zero, print: "At least one value is zero"
#   and print the values.
# - Otherwise, print: "At least one value is negative"
#
# Use try / except ValueError for user input.



def get_vals_or():
    val1 = input('enter an integer ')
    val2 = input ('enter an integer ')

    try:
        val1 = int(val1)
        val2 = int(val2)
        if val1 > 0 or val2 > 0:
            print("at least one value is positive")
        elif val1 == 0 or val2 == 0:
            print ("at least one value is 0 ")
        else:
            print("val1 and val2 are both negative")
        print(val1, val2)
    except ValueError:
        print("sorry, both values aren't integers"
        )


get_vals_or()


















print ("NEXT EXERCISE")

# ================================================================
# Exercise 7: Explore not
#
# Set the following variables:
# a = True
# b = True
# c = False
#
# Evaluate and print the results of these expressions:
# 1. not (a and b)
# 2. not a or not c
# 3. not ((a and c) and b)
#
# Include a comment explaining each result.



a = True
b = True
c= False
print( not a and not b)
print (not a or not c)
print (not (a and c) and b)
# The results are False, True, then True. this makes sense because: For #1, the True a and True b both switch to False with not. So, False and False evaluates to False. For #2, a is switched to false by the not and c evaluates to true after the not, so a or c is True. For #3, a and c is False, so the not of that is True and b is True, so it's True.









print ("NEXT EXERCISE")
# ================================================================
# Exercise 8: Voting Age and Citizenship
#
# Ask the user for their age and whether they are a citizen (yes or no).
#
# - If they are 18 or older AND a citizen, print:
#   "You are eligible to vote."
# - If they are under 18 OR not a citizen, print:
#   "You are not eligible to vote."
#
# Hint: use and for the eligibility requirements. Use try / except ValueError
# for the age input.

def voting ():
    age = input("how old are you?")
    cit = input("are you a citezin (yes or no)")
    try:
        age = int(age)
        if age >= 18:
            age = True
        else:
            age = False
    except ValueError:
        print("oof thats not a valid age")
        age = False
    if age == True and (cit == "yes" or cit == "yeah" or cit == "uh huh"):
        print("you can vote!")
    else:
        print("sorry you cant vote!")
voting()






















print ("NEXT EXERCISE")
# ================================================================
# Exercise 9: Number Classification
#
# Ask the user for an integer.
#
# - If it is positive and even, print: "Positive even number."
# - If it is positive and odd, print: "Positive odd number."
# - If it is negative or zero, print: "Not a positive number."
#
# Hint: combine and and or. Use try / except ValueError for user input.



def num_class():
    num = input("give an integer: ")
    try:
        num = int(num)
        if num > 0 and num % 2 == 0:
            print("its even and positive")
        elif num > 0 and num% 2 != 0:
            print ("its odd and positive")
        else:
            print("not a positive number")
    except ValueError:
        print ("not an integer...")




num_class()








print ("NEXT EXERCISE")
# ================================================================
# Exercise 10: Triangle Check
#
# Ask the user for three side lengths: a, b, and c.
#
# Print "Valid triangle." only if all sides are greater than 0 AND:
# - a + b > c
# - a + c > b
# - b + c > a
#
# Otherwise, print "Not a valid triangle."
#
# Hint: chain multiple and conditions. Use try / except ValueError for input.

def triangle_check(a,b,c):
    if (a > 0 and b > 0 and c > 0) and (a + b > c) and (a + c > b) and (c + b > a ):
        print ("valid triangle")
    else:
        print("not a valid triangle")




a = input("give a triangle side length ")
b = input("give another triangle side length ")
c = input("give another triangle side length ")
try:
    a = float(a)
    b = float(b)
    c = float(c)
    triangle_check(a,b,c)

except ValueError:
    print("sorry couldnt run program")


























print ("NEXT EXERCISE")
# ================================================================
# Exercise 11: Weekend Plan Decision Tree
#
# Ask the user two questions:
# - Is it the weekend? (yes or no)
# - Do you have homework? (yes or no)
#
# Build a decision tree that prints:
# - Weekend and no homework: "Go have fun!"
# - Weekend and homework: "Do your homework first, then relax."
# - Not weekend and homework: "Focus on schoolwork."
# - Not weekend and no homework: "It's a regular day, keep learning!"
#
# Consider converting responses to lowercase so Yes, YES, and yes all work.

def weekend():
    day = input("is it the weekend? ")
    hw = input("do you have hw?")
    if day == "yes" and hw == "no":
        print("Weekend and no homework: Go have fun!")
    elif day == "yes" and hw == "no":
        print("weekend and homework: do your hw first!")
    elif hw == "yes":
        print("focus on learning")
    else:
        print("its a regualr day, keep learning")
weekend()
























