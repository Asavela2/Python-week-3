# Data Structure

## Methonds of list project

1.# Adding Elements:
append(): Adds an element to the end of the list.
```my_list.append(10)```
extend(): Appends elements from an iterable to the end of the list.
``my_list.extend([11, 12, 13])``
insert(): Inserts an element at a specified position.

``my_list.insert(2, 20)  # Inserts 20 at index 2``

2. Removing Elements:
remove(): Removes the first occurrence of a value from the list.
``my_list.remove(10)``

pop(): Removes and returns the element at a specified position (or the last element if no index is specified).

``popped_element = my_list.pop(3)  # Removes element at index 3``
clear(): Removes all elements from the list.
``my_list.clear()``
3. Accessing Elements:
Indexing: Access elements using square brackets [] and index numbers.

``element = my_list[2]  # Accesses the element at index 2``
Slicing: Access a portion of the list using slicing.

``sublist = my_list[2:5]  # Returns elements from index 2 to 4``
4. Information and Modification:
index(): Returns the index of the first occurrence of a value in the list.

index = my_list.index(20)
count(): Counts the number of occurrences of a value in the list.
``occurrences = my_list.count(10``
sort(): Sorts the list in place.

``my_list.sort()``
reverse(): Reverses the elements of the list in place.

``my_list.reverse()``
copy(): Creates a shallow copy of the list.


``new_list = my_list.copy()``
5. Utility:
len(): Returns the number of elements in the list.

``length = len(my_list)``
