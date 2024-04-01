# ![Python Data Structures Lab - Exercise](./assets/hero.png)

## Introduction

This lab provides an opportunity to practice working with different data structures in Python.

If you find yourself stuck during the lab, we encourage you to revisit the lesson materials first. They're designed to provide you with the information and examples that will help you complete the exercises. 

If you've revisited the materials and are still facing challenges, don't hesitate to collaborate with your classmates.

## Lab exercises

Copy and paste each of the following exercises into your `app.py` file. 

To check your work, you can run the following command in your terminal:

```bash
python3 app.py
```

### Exercise 1

```python
"""
Exercise 1
  - Create a list named students containing at least three student names (strings)
  - Assign the second student’s name to a variable named first_student
  - Assign the last student’s name to a variable named last_student
"""

# Your code here

print('Exercise 1:', first_student, last_student)
```

### Exercise 2

```python
"""
Exercise 2
  - Create a tuple named foods containing the same number of foods (strings) as there are names in the students list.
  - Create a variable named meal and assign an empty string to it
  - Use a for loop to iterate over the strings in foods and append each string to meal
  - Example: A foods tuple containg 'Taco' and 'Salad' would result in meal being equal to 'TacoSalad'
"""

# Your code here

print('Exercise 2:', meal)
```

### Exercise 3

```python
"""
Exercise 3
  - Using the slice operator, assign a new tuple containing only the last two food strings in the foods to a varaible named last_two_foods
"""

# Your code here

print('Exercise 3:', last_two_foods)

```

### Exercise 4

```python
"""
Exercise 4
  - Create a dictionary named home_town containing the keys of city, state and population.
  - Using the home_town dictionary, assign to a varialbe named home_town_message  a string with this format: “I was born in <city>, <state> - population of <population>”
  - Hint: Use an f-string!
"""

# Your code here

print('Exercise 4:', home_town_message)
```

### Exercise 5

```python
"""
Exercise 5
  - Define an empty list named home_town_items
  - Use a for loop to iterate over the key: value pairs in the home_town dictionary and append a string with the following format to home_town_items: "<key> = <value"
  - For example, home_town_items might look like: ['city = Arcadia', 'state = California', 'population = 58000']
  - Hint: Using the <dict>.items() method allows for unpacking the key, value
"""

# Your code here

print('Exercise 5:', home_town_items)
```

### Exercise 6

```python
"""
Exercise 6
  - Create an empty list named cohort.
  - Use a for loop to iterate over the students list.
  - Hint: Use the enumerate function to be able to access both the index & student
  - Within the for loop, append a dictionary to the cohort list that combines
    the student’s name and the food in the foods list at the same index.
    Each dictionary will have this shape:
      {
        'student': 'Tina',
        'fav_food': 'Cheeseburger'
      }
  - Hint: Once again, unpacking the tuples returned by the enumerate function will result in more readable code.
"""

# Your code here

print('Exercise 6:', cohort)
```

### Exercise 7

```python
"""
Exercise 7
  - Using the list of students and a list comprehension, assign to a variable named awesome_students a new list containing strings
  - For example: ["Tina is awesome!", "Fred is awesome!", "Wilma is awesome!"]
"""

# Your code here

print('Exercise 7:', awesome_students)
```

### Exercise 8

```python
"""
Exercise 8
  - Assign to a variable named foods_with_an_a the result of list comprehension that filters the foods tuple to only include food strings that contains the letter a
  - For example, if foods is a tuple of ('Taco', 'Burrito', 'Sandwich'), foods_with_an_a would be a list equal to ['Taco', 'Sandwich']
"""

# Your code here

print('Exercise 7:', foods_with_an_a)
```