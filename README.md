# Python Data Structures Examples

This repository contains Python examples covering **Lists**, **Tuples**, **Sets**, and **Dictionaries** with their basic methods and use cases.

---

## 📌 Lists
A **List** is an ordered, changeable collection that allows duplicate elements.

```python
# List Example
fruits = ["apple", "banana", "cherry"]
print(fruits[2])  # Output: cherry

# List Methods
fruits.append("orange")               # Add to end
fruits.insert(1, "orange")            # Insert at index
fruits.extend(["grape", "melon"])     # Add multiple items
fruits.remove("banana")               # Remove specific item
fruits.pop()                          # Remove last item
fruits.clear()                        # Clear list
print(fruits.count("apple"))          # Count occurrences

# Sorting and Reversing
numbers = [3, 6, 8, 10, 9]
numbers.sort()        # Ascending sort
numbers.reverse()     # Reverse order
print(len(numbers))   # Length of list
print(numbers)

# List Slicing
country = ["Bangladesh", "India", "Pakistan", "USA", "UK", "Canada", "Africa"]
print(country[0:3])   # First 3 items
print(country[:5])    # First 5 items
print(country[5:])    # Items from index 5
print(country[2:6])   # Items from index 2 to 5

# Loop through list
countryList = ["Bangladesh", "India", "Pakistan", "USA", "UK", "Canada", "Africa"]
for item in countryList:
    print(item)









# Tuple Example
fruits = ("apple", "banana", "cherry")
print(fruits[1])  # Output: banana

# Tuple to List
fruitsTuple = ("apple", "banana", "cherry")
fruitsList = list(fruitsTuple)  # Convert to list

# List to Tuple
fruitsTuple = tuple(fruitsList)
print(fruitsTuple)
