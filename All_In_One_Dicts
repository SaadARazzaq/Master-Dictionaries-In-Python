import os
import time as t

print("\t\t***Python Program starting shortly...***")
t.sleep(1.5)

# There are various dictionary methods in Python

# 1) clear(): This method removes all items from the dictionary.

print("\n<---------------1) clear() method---------------->\n")

dict_to_clear = {'name': 'John', 'age': 25, 'city': 'New York'}
print("Original dictionary: ", dict_to_clear)
dict_to_clear.clear()
print("Dictionary after clearing all items: ", dict_to_clear)

# 2) copy(): This method returns a shallow copy of the dictionary.

t.sleep(3)
print("\n<---------------2) copy() method---------------->\n")

dict_to_copy = {'name': 'John', 'age': 25, 'city': 'New York'}
copied_dict = dict_to_copy.copy()
print("Original dictionary: ", dict_to_copy)
print("Copied dictionary: ", copied_dict)

# 3) get(): This method returns the value for the specified key. If the key is not found, it returns a default value.

t.sleep(3)
print("\n<---------------3) get() method---------------->\n")

person_info = {'name': 'John', 'age': 25, 'city': 'New York'}
key_to_get = input("Enter a key to get its value: ")
value = person_info.get(key_to_get, "Key not found!")
print(f"Value for key '{key_to_get}': {value}")

# 4) items(): This method returns a view of the dictionary's key-value pairs.

t.sleep(3)
print("\n<---------------4) items() method---------------->\n")

car_info = {'brand': 'Toyota', 'model': 'Camry', 'year': 2022}
print("Original dictionary: ", car_info)
print("Dictionary items: ", car_info.items())

# 5) keys(): This method returns a view of the dictionary's keys.

t.sleep(3)
print("\n<---------------5) keys() method---------------->\n")

employee_info = {'name': 'Alice', 'position': 'Manager', 'salary': 60000}
print("Original dictionary: ", employee_info)
print("Dictionary keys: ", employee_info.keys())

# 6) values(): This method returns a view of the dictionary's values.

t.sleep(3)
print("\n<---------------6) values() method---------------->\n")

student_info = {'name': 'Bob', 'age': 20, 'grade': 'A'}
print("Original dictionary: ", student_info)
print("Dictionary values: ", student_info.values())

# 7) pop(): This method removes the item with the specified key and returns its value.

t.sleep(3)
print("\n<---------------7) pop() method---------------->\n")

fruit_stock = {'apple': 50, 'banana': 30, 'orange': 40}
print("Original dictionary: ", fruit_stock)
fruit_to_remove = input("Enter a fruit to remove: ")
removed_quantity = fruit_stock.pop(fruit_to_remove, "Fruit not found!")
print(f"Removed {removed_quantity} {fruit_to_remove}(s) from stock.")
print("Dictionary after removal: ", fruit_stock)

# 8) popitem(): This method removes and returns the last inserted key-value pair.

t.sleep(3)
print("\n<---------------8) popitem() method---------------->\n")

company_info = {'name': 'ABC Inc.', 'location': 'New York', 'employees': 100}
print("Original dictionary: ", company_info)
removed_item = company_info.popitem()
print(f"Removed item: {removed_item}")
print("Dictionary after removal: ", company_info)

# 9) setdefault(): This method returns the value of the specified key. If the key does not exist, it inserts the key with the specified value.

t.sleep(3)
print("\n<---------------9) setdefault() method---------------->\n")

book_info = {'title': 'Python Programming', 'author': 'John Smith'}
print("Original dictionary: ", book_info)
key_to_setdefault = input("Enter a key to setdefault: ")
default_value = input("Enter a default value: ")
value = book_info.setdefault(key_to_setdefault, default_value)
print(f"Value for key '{key_to_setdefault}': {value}")
print("Dictionary after setdefault: ", book_info)

# 10) update(): This method updates the dictionary with elements from another dictionary or from an iterable of key-value pairs.

t.sleep(3)
print("\n<---------------10) update() method---------------->\n")

customer_info = {'name': 'Mary', 'age': 30, 'city': 'London'}
print("Original dictionary: ", customer_info)
update_dict = {'age': 25, 'gender': 'Female'}
customer_info.update(update_dict)
print("Dictionary after update: ", customer_info)

# 11) in and not in: These operators allow you to check if a key is present in a dictionary.

t.sleep(3)
print("\n<---------------11) 'in' and 'not in' operators---------------->\n")

employee_roles = {'John': 'Developer', 'Alice': 'Manager', 'Bob': 'Tester'}
key_to_check = input("Enter a name to check in the dictionary: ")
print(f"{key_to_check} is {'in' if key_to_check in employee_roles else 'not in'} the dictionary.")

# 12) fromkeys(): This method returns a new dictionary with the specified keys and values.

t.sleep(3)
print("\n<---------------12) fromkeys() method---------------->\n")

keys_to_create = input("Enter keys (comma-separated): ").split(',')
default_value_for_keys = input("Enter a default value for keys: ")
new_dict = dict.fromkeys(keys_to_create, default_value_for_keys)
print("New dictionary created with fromkeys: ", new_dict)

# 13) len(): This function returns the number of items in a dictionary.

t.sleep(3)
print("\n<---------------13) len() function---------------->\n")

grocery_list = {'apple': 3, 'banana': 2, 'orange': 4}
print("Original dictionary: ", grocery_list)
print("Number of items in the dictionary: ", len(grocery_list))

# 14) clear() to empty a dictionary

t.sleep(3)
print("\n<---------------14) clear() to empty a dictionary---------------->\n")

my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}
print("Original dictionary: ", my_dict)
my_dict.clear()
print("Dictionary after using clear(): ", my_dict)

# 15) dict() constructor to create a dictionary

t.sleep(3)
print("\n<---------------15) dict() constructor to create a dictionary---------------->\n")

keys = ['name', 'age', 'city']
values = ['John', 25, 'New York']
constructed_dict = dict(zip(keys, values))
print("Constructed dictionary: ", constructed_dict)

# 16) Using dict() constructor with keyword arguments

t.sleep(3)
print("\n<---------------16) Using dict() constructor with keyword arguments---------------->\n")

keyword_dict = dict(name='Alice', age=30, city='London')
print("Dictionary created with keyword arguments: ", keyword_dict)

# 17) Deleting an item using del keyword

t.sleep(3)
print("\n<---------------17) Deleting an item using del keyword---------------->\n")

programming_languages = {'Python': 'High-level', 'C++': 'Mid-level', 'Java': 'High-level'}
print("Original dictionary: ", programming_languages)
key_to_delete = input("Enter a programming language to delete: ")
if key_to_delete in programming_languages:
    del programming_languages[key_to_delete]
    print(f"{key_to_delete} deleted from the dictionary.")
    print("Dictionary after deletion: ", programming_languages)
else:
    print(f"{key_to_delete} not found in the dictionary.")

# 18) Using dict() constructor with comprehension

t.sleep(3)
print("\n<---------------18) Using dict() constructor with comprehension---------------->\n")

keys = ['name', 'age', 'city']
values = ['John', 25, 'New York']
comprehension_dict = {keys[i]: values[i] for i in range(len(keys))}
print("Dictionary created with comprehension: ", comprehension_dict)

# 19) Sorting a dictionary by keys

t.sleep(3)
print("\n<---------------19) Sorting a dictionary by keys---------------->\n")

unsorted_dict = {'banana': 3, 'apple': 1, 'orange': 2}
sorted_dict_by_keys = {k: unsorted_dict[k] for k in sorted(unsorted_dict)}
print("Original unsorted dictionary: ", unsorted_dict)
print("Sorted dictionary by keys: ", sorted_dict_by_keys)

# 20) Sorting a dictionary by values

t.sleep(3)
print("\n<---------------20) Sorting a dictionary by values---------------->\n")

unsorted_dict = {'banana': 3, 'apple': 1, 'orange': 2}
sorted_dict_by_values = {k: v for k, v in sorted(unsorted_dict.items(), key=lambda item: item[1])}
print("Original unsorted dictionary: ", unsorted_dict)
print("Sorted dictionary by values: ", sorted_dict_by_values)
